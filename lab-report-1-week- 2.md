#Report 1
Dani Rahman
## Installing VScode:
<p>
Go to [VScode](https://code.visualstudio.com/) and use the download and instructions for ur computer.<br>
At the end you should have something like this:
</p>
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/Installing%20Vscode.png)
## Remotely Connecting
First go make sure that you create a password for your remote server acc. at this [Link](https://sdacs.ucsd.edu/~icc/index.php)<br>
Then type in ssh cs15l22???@ieng.ucsd.edu
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/RemoteConnecting.png)
## Typing Some Commands
Google some helpful commands such as cd and ls that you can use in the bash
For exmample I used ls here after connecting to the host which shows all the non-hidden items in my current dir
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/Typing%20Some%20Commands.png)
## Moving Files with scp
Using the cmd scp we can type the dir of a local file and transfer that to a dir on the server using the following format:
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/Moving%20Files%20with%20scp.png)
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/Moving%20Files%20with%20scp2.png)
## SSH Key
In cmd type ssh-keygen and name the file id_rsa.pub and give it no password, saved in your users' folder.
Then ssh to the remote dir and create a .ssh folder using mkdir
Then copy the pub key you made over to a folder authorized_keys inside .ssh on the remote server
At the end should be able to log into ssh without password:
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/ssh%20key.png)
## Optimizing Remote Running
Type the following commands inorder to copy compile and run a file on the remote server. Once typed use the up arrow key to reuse.
![Image](https://github.com/drahmanucsd/cse15l-lav-reports/blob/main/Images/Optimizing.png)

