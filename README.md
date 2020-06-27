# NickelBlock Internship
All the code for the NickelBlock internship.

Temperature Maps
==
To generate temperature maps for week 2, use the following command:

```
python [Map File] -t [hours]
```

Where the `Map File` is the script to run, `-t` is the flag for time, and `hours` is how many hours from the time of 
running the script you want to generate a temperature map.

Example that generates local temperature map 12 hours from now:

```
python Map_Local_Temperature.py -t 12
```