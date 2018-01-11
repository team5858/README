# How do I move my local Eclipse project to GIT?

I have tried various options through the Eclipse UI. But Eclipses seems to want a "myProject/myProject" directory structure instead of a plain "myProject" one. Frustrating. So here is what I do:

  - Use the file explorer to copy the Eclipse project directory to another location.
  - Delete the local project from Eclipse.
  - Use the GIT web interface to create a new project with the EXACT same name as the directory you just copied.
  - Be sure to click the box to initialize the project with a README.
  - Clone the project from GIT (see below).
  - Copy the contents of the saved directory to the new project directory.
  - Restart Eclipse.
  - Push the new files to the repository.

# How do I pull an existing GIT project into Eclipse?

  - Use the GIT web interface to "Clone or download" your project.
  - Click the button to the right of the URL to copy the URL to the clipboard.
  - Open the GIT perspective in Eclipse.
  - Click on "Clone a git repository and add to this view"
  - The information from the clipboard will fill out the form. 
  - Add your username/password.
  - Right click on the repo in the GIT perspective.
  - Click "Import projects ..." and "Finish".
  - Switch back to the Java perspective. The new project is in the tree on the left.
