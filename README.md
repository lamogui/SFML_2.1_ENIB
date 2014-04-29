SFML_2.1_ENIB
=============

SFML 2.1 Compatible ENIB


Ce dépot propose une version 2.1 de la SFML modifié pour compiler sur les 
vieilles versions de linux à l'ENIB (et aussi parce les paquets SFML sont 
toujours à la version 1.6 sur la plupart des distributions)

Il s'agit d'une version statique de la SFML donc il y aura jamais de problème de 
compilation générés par ces _merveilles_ de .so jamais compatibles.

Si comme à l'ENIB glew n'est pas installé j'ai ausi inclus les sources de GLEW
histoire que vous n'ayez pas à chercher

Tout le code de la SFML est écrit par Laurent Gomilla https://github.com/LaurentGomila
Je n'ai fais qu'enlevé la dépendence à la libraire freetype et fournir un makfile 
permettant de compiler en statique la lib sous linux. 

Notez que le module Network et module Son ne sont pas fournis et ni d'ailleurs le 
support de sf::Text.

La SFML officielle est disponible ici http://www.sfml-dev.org/index-fr.php




