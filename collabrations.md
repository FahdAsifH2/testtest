# GitHub Collaboration Workflow

1. **Create Main Folder and Initial Files**  
   One person sets up the project folder and adds the initial files.

2. **Push to GitHub**  
   The same person pushes the folder and files to a new GitHub repository.

3. **Add Collaborators**  
   The repository owner adds collaborators to the repository so others can contribute.

4. **Clone the Repository**  
   Each collaborator clones the repository locally using the `git clone` command.

5. **Create a Branch** _(Very Important)_  
   Each collaborator creates their own branch before making any changes:
   ```bash
   git checkout -b your-branch-name
