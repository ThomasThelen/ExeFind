# File5
Finds and stores all exe files in a vector container.


##Background

Certain malware modify existing windows executeable files in malacious ways. One result of doing such is that the file's MD5 signature changes. These signatures generated by malacious code have been and continue to be documented.
<br>

## This Program
First, This program scans the filesystem and fills a data structure with a list of all .exe files.
<br>
Next, OpenSSL is implimented to generate MD5 signatures of the files. The signature along with the file path is included in a text file. The malware researcher can then use the file to search against malicious signatures in a database. 