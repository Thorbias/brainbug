# Immich Photo Library on Synology
A year ago I tried to switch from google photos to MS one drive due to the fact that I had 1 TB cloud storage bundled with my office 365 subscription. Turns out that this was not as easy as I thought of.
Google just wouldn't easily give me my photos back and only with the help of a custom script (I'll add the link later) I was able to get all my photos back. That was the day when I decided to host my photos on my own and ordered a Synology DS224+.
It seemed very appealing at first glance and does in fact come with a nice UI and a lot of managed services. 

reminder: create an article about the synology-localbackup-cloudsync setup

After a while I was pretty much annoyed by the Synology Photos App and so I looked for better altenatives and came across immich. And since immich has now a stable relese I gave it a try.

ToDo: describe installation and set up.

Having immich running on my NAS was nice but it also lacked accessiblity which kind of came for free with Synology Photos. So I started to confiugre my NAS so that my immich which is running as docker service would be accessible via HTTPS.

ToDo: descibe the whole setup

In the end I decided to go with the "manual" set up with certificates and Port Forwarding at my router instead of going with tailscale. The main reason was that I didn't want to rely on another service and app and therefore sacrifise maybe a little bit of security.

ToDo: test tailscale :)
