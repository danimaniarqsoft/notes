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
- find
	- ```sh
	  find . -name "*logo*.svg"
	  ```
- tar
	- for backup #backup
		- ```sh
		  tar -zcvf archive-name.tar.gz source-directory-name
		  ```
- rsync
	- ```sh
	  rsync -ravz --partial /from/folder /to/destiny/
	  ```