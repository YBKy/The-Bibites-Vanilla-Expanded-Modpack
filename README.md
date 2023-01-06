# The-Bibites-Vanilla-Expanded-Modpack
A Modpack for the Bibites containing Mods which could be resonably added to the base game. 

Activating/deactivating mods and changing their settings can be done in the config.txt file in the games Mods folder

## Instalation Guide
1) make a backup save of your Bibites folder somehwere
2) download the zip file and unzip it somewhere
3) drag the "The Bibites_Data" folder of the right version into your Bibites folder. If it asks you, if you want to replace files, you confirm that. 

## Mods Included
in the newest version 0.5.0 there are:


### Neurons Plus: 
This mod adds 4 new activation functions for neurons, most notably the highly suggested multiplication neuron:
1) Mult: Multiplies all inputs together
2) Div: Divides 1 by the sum of inputs
3) Ln: Takes the natural logarithm of the sum of inputs
4) Exp: Exponentiates Euler’s number e by the sum of inputs 

### Senses Plus: 
This mod adds 6 new input neurons generally related to sensing:
1) Rotation Speed: Lets the Bibite sense its rotation speed
2) Bibite Heading Angle: Lets the BIbite see the direction Bibites in view are moving towards.
3) Target Diet: Lets the Bibite see the diet gene of the closes Bibite.
4) Target Speed: Lets the BIbite see the speed the closes Bibite is moving at.
5) Target Size: : Lets the BIbite see the size of the closes Bibite.
6) Own Red, Green and Blue letting the Bibite sense the red, green and blue components of its own color .

### YBKs Vision Rework Mod:
This mod implements the Vision Rework suggested by YBK and Leo’s addition to it. It adds 3 output neurons controlling the vison of the Bibite:
1) Field Of View: A multiplier by which the View Angle Gene is multiplied to determine the real View Angle
2) Panning: The amount by which the Vision Cone is angled to the left/right of center
3) Range Of View: A multiplier by which the View Range Gene is multiplied to determine the real View Range

This Mod has one further configuration. If DefaultMultiplyerIsOne is true (which it is by default) Field of View and Range of View will be 1 if there are no inputs going into it. If it is false, the multipliers will be 0.5 if there are no inputs. 

### Simpified Templates:
This mod changes the defult templates to be simpler, to have no unnessesary synapses or neurons, while retaining all previous functionality

### Better Initial Connections:
This mod adds a Bibite that is similar to the Deafult Bibite, but with additional helpful connections and a number of random connections. 

You can configure the number of random connections, the probability, that the connections will go through pheromones or a neuron, and and option to give the random connections to all Bibites, rather than just the Better Inital Connections Bibite. 

### Soft Bibite Cap:
This mod changes the functionality of the Bibite Cap. Instead of disallowing Bibites to lay eggs, while there are more Bibites than the cap allows, with this mod there is a probability of egg laying not working, with the energy still being consumed. This probability increases with every percent the number of Bibites is over the cap. Eggs also cost more, per percent over cap



