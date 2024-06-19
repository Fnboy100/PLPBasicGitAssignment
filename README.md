# PLPBasicGitAssignment
Hands-On Assignment: Basic Git And GitHub Workflow

### Here are the step-by-step instructions for performing the tasks you outlined:

1. **Create a GitHub repository:**
   - Go to GitHub and log in to your account.
   - Click on the "New" button to create a new repository.
   - Name the repository "PLPBasicGitAssignment".
   - Add a README file during the repository creation.
   - Create the repository.

2. **Create a new folder on your local machine:**
   - Open your terminal or command prompt.
   - Navigate to the folder where you want to create the new folder.
   - Create a new folder named "PLPBasicGitAssignment":
     
     mkdir PLPBasicGitAssignment
     cd PLPBasicGitAssignment
     

3. **Initialize a new Git repository in the local folder:**
   - Run the following command:
     
     git init
     

4. **Connect the local repository to the GitHub repository:**
   - Add the remote repository URL to your local repository:
     
     git remote add origin https://github.com/Fnboy100/PLPBasicGitAssignment.git
     

5. **Creating a new file inside the local folder:**
   - Create a new file named hello.txt:
     
     echo "Hello, Git!" > hello.txt
     

6. **Stage, commit, and push the changes:**
   - Stage the changes:
     
     git add hello.txt
     
   - Commit the changes with the message:
     
     git commit -m "Add hello.txt with a greeting"
     
   - Push the committed changes to the GitHub repository:
     
     git push -u origin main
     
   This command pushes the changes to the GitHub repository.
