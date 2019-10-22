# Blocklist and filters for Pi-hole

This is a compilation of filters made by me, the list will get longer as time goes on.

You can import my blocklist by pasting this link: https://raw.githubusercontent.com/s0m3guy2004/pihole-filters/master/blocklist.txt
## Regex
```
^([A-Za-z.-]*\.)?trafficjunky(.[a-z]*)
^([A-Za-z.-]*\.)?moatads\.com/
^(api[4-6]*\.)([A-Za-z0-9.-]*)
platform?[0-9]*[-_.]
yoads(.[a-z]*)
```
## Wildcards
```
(^|\.)amazon-adsystem\.com$
(^|\.)adskeeper\.co\.uk$
(^|\.)addthis\.com$
(^|\.)bebi.com$
(^|\.)bemobtrk\.com$
(^|\.)cpmstar\.com$
(^|\.)exdynsrv\.com$
(^|\.)fastfreeredics[0-9]\.life$
(^|\.)mgid\.com$
(^|\.)steepto\.com$
(^|\.)treasuredata\.com$
```
