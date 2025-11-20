This is very simple and not at all properly formatted, but here's a simple description of how to get the most recent version of the file and how to add changes to the repo.

1) Pulling repo for the first time:
    (Make sure to remember where the directory is stored)

     **Commands:**
   
       git clone "https://github.com/empckec03/math-3430-final-project.git"
       cd math-3430-final-project

   Now you should have access to the shared file
   
3) Any future pulls (used to get most recent version of file before adding changes to it):
  **Commands:**

  If still in the same directory:
      
      git pull

  If in the wrong directory:
       
       cd *path to directory here*

  Then:

       git pull
   
5) Adding new file changes to the repo:
   (Make sure you are still in the correct directory)

   **Commands:**

       git add .  (This is used to add all changed files)

   or

       git add *file name here*

  Then:
   
     git commit -m "*Message containing description of changes to the file*"
     git push origin

For the sake of this class, I don't think we should worry about using branches at all since they will not be very helpful.
