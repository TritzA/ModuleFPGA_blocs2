# UniteArithmetiqueLogique2

Diviseur ou convertisseur ou encrypteur choisi grace à un multiplexeur.

Laboratoire : 3/5

Cours : INF1500 Logique des systèmes numériques

Partenaire : James Brutus


## Objectifs

Modéliser un diviseur entier par 4 avec reste ou convertisseur code binaire en code Gray ou encrypteur choisi grace à un multiplexeur, le tout sur 4 bits.

## Utilisations
Logiciel de moélisation : [Vivado 2020.1](https://www.xilinx.com/support/download.html)

École : [Polytechnique Montréal](https://www.polymtl.ca)


## Représentation

### Circuits

UAL final.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique2/blob/main/images/modele.PNG)


Diviseur 4 bits.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique2/blob/main/images/DIVISION.PNG)


Convertisseur 4 bits.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique2/blob/main/images/BIN_VERS_GRAY(%20antonin).PNG)


Encrypteur 4 bits.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique2/blob/main/images/CRYPTO_4Bantonin.png)


Multiplexeur 4 bits.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique2/blob/main/images/MUX_1_3_4B.png)


### Tests

Test exhaustif de l'UAL.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique2/blob/main/images/labo3.PN)


### Implémentation phyisque sur une carte FPGA

Fichier de contraintes en *.txt avant sa modification en *.xdc.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/contraintes.png)

Carte FPGA.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/Nexys4.jpg)

Circuit de la carte FPGA.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/Mapping_Nexys4.png)
