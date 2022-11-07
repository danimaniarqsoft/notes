- how to update/upgrade ubuntu? #update
	- ```sh
	  sudo apt update
	  sudo apt upgrade
	  ```
- how to copy entire folder? #copy
	- ```sh 
	  cp -r copy/folder/ in/folder/
	  ```
- locate
	- ```sh
	  locate wordToFind
	  ```
- how to find files #find
	- ```sh
	  find . -name "*logo*.svg"
	  ```
- how to create a backup #backup #rsync #tar
	- ```sh
	  #compress
	  tar -zcvf archive-name.tar.gz source-directory-name
	  #uncompress
	  tar -xvzf archive-name.tar.gz
	  
	  # with rsync
	  rsync -ravzp --partial /from/folder /to/destiny/
	  ```
- how to test DNS Name resolution #dns
	- [Testing DNS Name Resolution](https://wiki.samba.org/index.php/Testing_the_DNS_Name_Resolution#:~:text=To%20verify%20that%20your%20DNS,available%20on%20Linux%20and%20Windows.) 
	  ```sh
	  # forward lookup
	  nslookup google.com
	  host google.com
	  
	  # reverse lookup
	  nslookup [IP ADDRESS]
	  host [IP ADDRESS]
	  ```
- how to test if port is open #port-test
	- `telnet [IP ADDRESS | DOMAIN NAME] [PORT]`
- how to display connected devices #nmap
	- `sudo nmap -sn 123.23.4.0/24`
- how to delete files in a secured way #shred #delete-files
	- `shred -vzu -n5 [[FILE-NAME]]`
- how to see trace route #tracerouce #tracepath #mtr
	- `traceroute`
	  `mtr`
	- > times over 150 ms into the united state
- how to test the network speed #speedtest-cli
	- `speedtest-cli`