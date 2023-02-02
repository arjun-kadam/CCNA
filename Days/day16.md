# FTP (File Transfer Protocol)
- FTP is used to transfer files or resources between server and client.
- It is also used for downloading the files to computer from other server.
- Popular FTP clients are FileZilla, WinSCP, Cyberduck...etc.
- To trasnfer a file, 2 TCP connections are used by FTP in parallel i.e Control Connection and Data Connection.
<img src="Images/FTP.png?raw=true" alt="FTP">



1. **Control Connection:** 
- For sending control information like user identification, password commands to change remote directory, commands to retrive & store files...etc.
- It active throghout the session.
- It uses TCP port 21.

2. **Data Connection:**
- For sending the actual file or data, FTP make use of Data Connection.
- It uses port 20.

### FTP data structure
1. File Structure.
2. Record Structure.
3. Page Structure.

### Transmission Modes
1. Stream Mode.
2. Block Mode.
3. Compressed Mode.

## Common FTP Commands
`GET` : Get file from remote server.

`PUT` : Send one file (Folder)

`SEND` : To send single file only.

`USER` : To send user authentication to server.

`OPEN` : Open Address (Public) Of FTP server.

`PASS` or `PWD` : User password for particular user.

`CLOSE` : Disconnect from FTP but does not terminate session.

`QUIT` : Disconnect from remote host and terminate session.

## SFTP (Secure FTP)
- Data is encrypted.
- It uses port 22.
- SFTP uses SSH/SSL/TLS.
- SFTP was designed by IEIF as an extended version of SSH 2.0, allowing file trasnfer over SSH and with transport layer security (TLS) and VPN application.
- SFTP is Slower.

## TFTP (Trivial FTP)
- Mainly used for transferring files within a LAN.
- It uses UDP, therefore it's unreliable.
- It uses port 69.
- Not used to transfer files over the internet.
- It is good for simple file transfer such as during boot time.

This is about FTP. Next  [Day 17](day17.md) we will see about HTTP/S.