# Headerscript
Pulls Request Headers from Origin Server vs Through Cloudflare
headerscript.sh compares the request headers of kpatullo.com through it's origin server on Digital Ocean and through it's default configuration through cloudflare.  After the script is run 2 text files are created in the same directory as headerscript.sh, one is named cloudflare.txt and shows the headers directly through Cloudflare and the second is originserver.txt where the request is sent directly to the IP of the origin server for resolution.
