# Affinity Login Gateway

Scripts hosted on Github, served via jsDelivr 

## Cache
Once scripts are updated on Github they will not be reflected immediately: scripts are cached on jsDelivr. 
In order to purge the cache a GET request needs to be issued via the jsDelivr API. 
To do this, simply replace the 'cdn' with 'purge' in the script URL. For example, to purge cache for app.js, visit the following link in your browser:
https://purge.jsdelivr.net/gh/aff-allen/aff/Scripts/app.js

(Original script URL was https://cdn.jsdelivr.net/gh/aff-allen/aff/Scripts/app.js)
