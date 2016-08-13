##Additions by RASP.US
This is the repository for the version of the map currently hosted

Feel free to contribute via issues and pull requests

# PokemonGo Map ![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/PoGoMapDev) [![Build Status](https://travis-ci.org/PokemonGoMap/PokemonGo-Map.svg?branch=develop)](https://travis-ci.org/PokemonGoMap/PokemonGo-Map)


#[Twitter] (https://twitter.com/PokemapDevRE), [Website] (https://pokemongomap.github.io/PoGoMapWebsite/)#

For general support, join [PokemonGoMap discord server](https://discord.gg/uAmEkcu).

For feature requests go to, [PokemonGoMap feathub page](http://feathub.com/PokemonGoMap/PokemonGo-Map).

Live visualization of all the pokemon (with option to show gyms and pokestops) in your area. This is a proof of concept that we can load all the pokemon visible nearby given a location. Currently runs on a Flask server displaying Google Maps with markers on it.

Features: 

* Shows Pokemon, Pokestops, and gyms with a clean GUI.
* Notifications 
* Lure information
* Multithreaded mode
* Filters
* Independent worker threads (many can be used simulatenously to quickly generate a livemap of a huge geographical area)
* Localization (en, fr, pt_br, de, ru, ja, zh_tw, zh_cn, zh_hk)
* DB storage (sqlite or mysql) of all found pokemon
* Incredibly fast, efficient searching algorithm (compared to everything else available)

Building off [tejado's python pgoapi](https://github.com/tejado/pgoapi), [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s API, [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps). Current version relies primarily on the pgoapi and Google Maps JS API.
