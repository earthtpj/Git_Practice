* **create a new repository on the command line**

      * echo "# source" >> README.md
      * git init
      * git status
      * git add README.md
      * git commit -m "first commit"
      * git branch -M main
      * git remote add origin https://github.com/aaaaa/aaa.git
      * git push -u origin main

*  **push an existing repository from the command line**

      * git remote add origin https://github.com/aaaaa/aaa.git
      * git branch -M main
      * git push -u origin main

* **create a new repository on the command line**

   * by using GitBash :

    **1. Create a directory** 
  
          mkdir folder1

    **2. Change directory**

          cd folder1

 * if repository created in github then clone the path 
    git remote add origin https://github.com/______.git

   **3. Create a README.md file**
 
    echo "# practice" >> README.md

   **4. Check for any changes**

    git status
    git add README.md
    or ( for multiple files)
    git add -A 

**5. Commit Changes**

     git commit -m "first commit"

  **6. Push to remote repository** 

       * git branch -M main
       * git remote add origin https://github.com/test/practice.git
            or
       * git push -u origin main

 **push an existing repository from the command line**

       * git remote add origin https://github.com/test/practice.git
             or
       * git branch -M main
       * git push -u origin main

**Merge from Main to feature branch**

     * git checkout feature
     * git merge main
	 
	 
**How to remove git repository

    rm -fr .git