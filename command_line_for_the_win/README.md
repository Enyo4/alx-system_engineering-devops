This repo contains screenshots taken from task completed in the command line challenge.
They were uploaded using the SFTP command-line tool which means Secure File Transfer Protocol.
sftp is a file transfer program, similar to ftp, which performs all operations over an encrypted ssh transport. It may also use many features of ssh, such as public key authentication and compression.

The steps used to upload the screenshot:
	1. Open a terminal or command prompt on your local machine.
	2. Use the SFTP command-line tool to establish a connection to the sandbox environment. You will need the hostname, username, and password provided to you for the sandbox environment. eg.(sftp ssh username@your_server_ip_or_remote_hostname)
	3. Once connected, navigate to the directory where you want to upload the screenshots.
	4. Use the SFTP put command to upload the screenshots from your local machine to the sandbox environment.
	5. Confirm that the screenshots have been successfully transferred by checking the sandbox directory.
	6. Once the screenshots are transferred, you can proceed to push the screenshots to GitHub as mentioned in the initial requirements.
