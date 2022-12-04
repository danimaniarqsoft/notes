- how to test DNS Name resolution #dns #network #troubleshooting
  id:: 63684caf-e366-45d3-81e1-2df4745748a9
	- [Testing DNS Name Resolution](https://wiki.samba.org/index.php/Testing_the_DNS_Name_Resolution#:~:text=To%20verify%20that%20your%20DNS,available%20on%20Linux%20and%20Windows.) 
	  ```sh
	  # forward lookup
	  nslookup google.com
	  host google.com
	  
	  # reverse lookup
	  nslookup [IP ADDRESS]
	  host [IP ADDRESS]
	  ```