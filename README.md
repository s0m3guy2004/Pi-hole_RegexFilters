# Blocklist and filters for Pi-hole

This is a compilation of filters made by me, the list will get longer as time goes on.

You can import my blocklist by pasting this link: https://raw.githubusercontent.com/s0m3guy2004/pihole-filters/master/blocklist.txt
## Regex
```
^([A-Za-z.-]*\.)?trafficjunky(.[a-z]*)
^([A-Za-z.-]*\.)?moatads\.com/
yoads(.[a-z]*)
```
## Wildcards
```
(^|\.)amazon-adsystem\.com$
(^|\.)cpmstar\.com$
(^|\.)fastfreeredics[0-9]\.life$
(^|\.)treasuredata\.com$
```
