# millMap
## Background Information
### What is This?
millMap is a simplified timer and data accumulator to quickly display recorded spawn sightings for a particular set of static spawn points in the mobile game Pokemon Go.
### How does the Map Work?
The map is a static image constructed using [My Google Maps](https://www.google.com/mymaps). Each star on this map represents a particular item in Pokemon Go. Purple stars indicate Pokestops, Orange stars indicate Gyms, and Blue stars indicate spawn points.
### How did you determine Spawn Times?
The spawn time for each particular spawn point may be observed and calculated over a few spawn cycles. Furthermore, each spawn point has a set duration of either 30 minutes or 60 minutes. You calculate the spawn time, simply watch a particular Pokemon in the wild and wait for it to despawn. Record the time the Pokemon despawns. If another Pokemon immediately spawns, then this is a 60 minute spawn point, which will spawn once every hour at the time you recorded. If a pokemon does not immediately spawn, then this is a 30 minute spawn point; subtract 30 minutes from the time you recorded to identify the exact spawn time.
### How do you record Spawn Data?
All spawn data is observed and manually entered into a Google Spreadsheet. The spreadsheet consists of multiple columns, one for each spawn point. From here, millMap queries the spreadsheet for specific sets of data mapped to the respective spawn point data column and a Javascript library handles parsing and displaying the data in a graphical format.
### What is the purpose of all this?
Well, some of us would like to have a better understanding of the spawning behavior and distribution of species amongst different biomes in Pokemon Go. This is a tool purely for data analysis and calculation of particular Pokemon appearance frequency.
## Creating your Own Map
### Coming Soon!