#SeznamMap

Display markers on Google (API v3) map based on addresses.

![Mapa](http://vojtechvymetal.cz/seznam/map.png)

##How to use map

Into source code you must plug the addresses in this format: "Street,street number,postcode,city".

After that you need to open script in your browser and wait for load map. Map is loaded after conversion adresses into coordinate. Conversion process you can see in console in your browser (typically in chrome F12 -> console)

![Counting](http://vojtechvymetal.cz/seznam/count.png)

##Changelog

* Version 0.9: Increase number of attempts for load map (up to 2500 - maximum limit given by Google Maps APIv3)
* Version 1.0: Changed input of address points
* Version 1.0.1: Updated bugs at long addresses
