# Yoshi-Domain
## This will be the first notes I make regarding my Azure-based domain called "Yoshi-Domain" ##
Step-by-Step Process

-Create a VM
-Install AD DS on the VM and promote it to a Domain Controller
-Install DNS
-Join other VMs to the same domain
  - 1 Windows VM
  - 1 RHEL VM
- Create other domains (Republic and Resistance)
- Install AD CS
- Establish a domain trust between all 3
  - Child forests
  - Separate Forests
- Begin implementing various Azure products/services and integrating the entire architecture

Domain 1 (Galactive Civil War)
  $SubnetName = GalacticCivilWar
  $NetworkSecurityGroup = GalacticCivilWar
  Groups: Empire, Rebel Alliance
  Users: Darth Vader, Wilhuff Tarkin, Emperor Palpatine (Empire); Luke Skywalker, Han Solo, Leia Organa (Rebel Alliance)
Domain 2 (Republic)
  $SubnetName = Republic
  $NetworkSecurityGroup = Republic
  Groups: Republic, CIS
  Users: Obi-Wan Kenobi, Anakin Skywalker, Padme Amidala; Count Dooku, General Grievous, Darth Maul (CIS)
Domain 3 (Rise of the New Republic)
  $SubnetName = Resistance
  $NetworkSecurityGroup = Resistance
  Groups: First Order, Resistance
  Users: Kylo Ren, General Hux, Captain Phasma; Rey Skywalker, FN-2817 Finn, Poe Dameron
