<h1>Reverse Engineering:</h1><br>
Books: https://repo.zenk-security.com/Reversing%20.%20cracking/Practical%20Reverse%20Engineering.pdf
<br><br>
<b>Books on C:</b>
http://www2.cs.uregina.ca/~hilder/cs833/Other%20Reference%20Materials/The%20C%20Programming%20Language.pdf<br>
<br>
While tracing malicious links, Try using urlscan.io<br>
<br>
<h2>Basic Inspection:</h2><br>
<b>strings (filepath)</b>    -     Very basic file inspection. Often gives you a lot of info.<br>
<br>
<b>hexdump -d (filepath)</b> -     Dumps the contents of the binary file.
<br>
<b>binwalk (filepath)</b>    -     Very basic information related to the binary itself. Worth a read.
<h3>Basic trick:</h3> Try decompressing the file simply using 7-zip. Works sometimes kek.<br>
<h1>Dealing with Python binaries:</h1><br>
Try: https://github.com/extremecoders-re/pyinstxtractor to decompile the code.<br>
Use uncompyle6 to decompile the main pyc file. The main pyc file is usually the file with the same name as the exe.
