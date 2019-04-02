# Todo list

## Misc

* ~~Implement Bangs like in DuckDuckGo~~ Done, try d! for DuckDuckGo, g! for Google, w! for Wikipedia
  or wde! for German Wikipedia
* Admin page
    * Tools for updating data from [[@github(urbandwin, stuff)]]
      (kind of done via refresh page)
    * admin-only content
* Accounts / login
    * for personalized content (favorite stations, lists of things, bookmarks, etc.)
* compare data sources from osm vs other source (vegan maps)
* ~~special search for OSM tags~~ [done](/openstreetmap/search)

## Things along

* Make distance configurable
* Add more object categories (Imbiss, Restaurant)
* Add bus and tram routes
* Flat street view with things along it
* Show geographical lines with things along on map
* Show food stuff that is open now
* Show piece of map from each POI (beim Mauszeiger drüberhalten)
* Bezeichnungen der Geldautomaten korrigieren
* "show all" bei click auf Station
* ~~nicht Node als Überschrift der Kartenübersicht, sondern Kategoriename oder Objektname~~
  Jetzt wird der Objektname angezeigt

## OpenStreetMap

### Misc

* There's a Metro in Berlin with shop=wholesale
* Add link to this somewhere:
  [https://wiki.openstreetmap.org/wiki/DE:Unternehmensketten](https://wiki.openstreetmap.org/wiki/DE:Unternehmensketten)
* Add links to [amenity=doctors](/openstreetmap/tag/amenity/doctors),
  [amenity=dentist](/openstreetmap/tag/amenity/dentist) and [office=lawyer](/openstreetmap/tag/office/lawyer)
  and assess data coverage using a different source of information.

### Search

* Street search
* Key-Histogram and Tag-Histogram based on search results

### Things / Categories

* Einkaufsmöglichkeiten / Einzelhandel
* Fashion chains: H&M's, C&A's etc.
* Schwimmbäder / Badestellen / Freibäder
* Eisbahnen

#### Done

[Supermärkte](/things/supermarkets),
[Drogerien](/things/drogerien),
[Geldautomaten](/things/atms) / [Banken](/things/banks),
[Bibliotheken](/things/libraries),
[Museen](/things/museums),
[Baumärkte](/things/baumärkte),
[Apotheken](/things/pharmacies),
[Bäckereien](/things/bakeries)

### Restaurants / Fast food

* Make discoverable using certain filters
    * Using [cuisine](/openstreetmap/key/cuisine)
    * Using quarters als filters
    * Within distance of something else

## Other data sources

* Alles vom
  [VBB](https://www.vbb.de/unsere-themen/vbbdigital/api-entwicklerinfos),
  insbesondere auch Fahrstuhlinfo
* Station nicknames from
  [derhuerst/vbb-common-places](https://github.com/derhuerst/vbb-common-places)
* Other additional data listed here:
  [derhuerst/vbb-modules](https://github.com/derhuerst/vbb-modules),
  escpecially station photos, tile patterns, change-positions
* Concert info. Songkick, Eventim, Ticketmaster?

## Other stuff to integrate

* Flats. Immobilienscout, Immoscout
* Flatshares. wg-gesucht, wgcompany
* Jobs. StackOverflow Jobs
* Short term accomodation. Airbnb, Wimdu etc, Booking.com, HRS, etc.
* Data from
  [luftdaten.info](http://maps.luftdaten.info/#11/52.5227/13.4102)
* Search for books in VOEBB, possibly using
  [opacapp/opacclient](https://github.com/opacapp/opacclient)
