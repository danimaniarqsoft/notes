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
- how to create a backup #backup
	- ```sh
	  tar -zcvf archive-name.tar.gz source-directory-name
	  rsync -ravzp --partial /from/folder /to/destiny/
	  ```
- how to test DNS Name resolution #dns
	- ```sh
	  # forward lookup
	  nslookup google.com
	  host google.com
	  
	  # reverse lookup
	  nslookup [IP ADDRESS]
	  host [IP ADDRESS]
	  ```