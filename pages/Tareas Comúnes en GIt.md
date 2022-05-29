- [Git stash](https://www.atlassian.com/git/tutorials/saving-changes/git-stash) 
  ![image.png](../assets/image_1644800480829_0.png)
	- guardar en el **stash**
	  ```sh 
	  git stash
	  ```
	- guardar en el **stash untracked** files
	  ``` sh
	  git stash -u
	  ```
	- guardar en el **stash ignore** files
	  ``` sh
	  git stash -a
	  ```
	- sacar del **stash** los archivos
	  ```sh
	  git stash pop
	  ```
- Git branch
	- create new branch
	  ```sh
	  git checkout -b <branch-name>
	  ```
	- create new branch from commit
	  ```sh
	  git checkout -b <branch-name> <commit-sha>
	  ```