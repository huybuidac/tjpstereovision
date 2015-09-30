# t/m Monday 7th June #
Iedereen heeft opencv 2.1 werkend op zijn laptop.
Team Rectify heeft voor elkaar om de beide webcams aan te spreken zowel in linux als in opencv.

Team Rectify heeft de camera stereo calibratie aan de praat gekregen in opencv. We kunnen nu een schaakbord voor de beide webcams houden zodat dat hij de coordinaten van alle hoekpunten vindt. Dit kan hij zelfs real time tekenen op het video beeld! **_Augmented Reality here we come!_**

Team Stereo heeft het voorbeeld dieptemap plaatje op de wiki van opencv kunnen herproduceren. Er is gebruikt gemaakt van GraphCut en de tsukuba (lamp) dataset.
Ook is een blokmatching algoritme werkend gekregen, alleen deze resultaten hebben we nog niet kunnen controleren.

# Tuesday 8th June #
Team Rectify heeft de camera stereo calibratie nu ook in opencv in C++ aan de praat gekregen, maar dat bleek niet sneller. Daarnaast kan de fundumental matrix nu genereerd worden.

Team Stereo kan nu c functies in python gebruiken, dit is nodig omdat een algoritme wat we willen gebruiken (Sub Global Block Matching) alleen beschikbaar is in de C++ opencv Api. Daarnaast zijn de eerste opencv applicaties in C++ ook in dit team werkend gekregen.

# Vragen voor Rein #
Kan je een beetje uitleggen over Block Matching, met name wat het resultaat precies voorstelt.