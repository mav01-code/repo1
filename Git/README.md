### GIT BASICS

There are 4 stages
1. Working Directory
2. Staging Area
3. Local Repository 
4. Remote Repository

- Working directory is where you work, modify files, make changes
- Staging area is where you add files and they remain in processing stage
- You can access local repo when you commit your files
- There is no need for Internet access till this stage
- Once we decide to push to remote repo, we need Internet

#### Commands
1. git init 
2. git remote add origin "Your github repo link"
3. git branch -M main
4. git add * (or file name)
5. git commit -m "Message"
6. git push -u origin main

Note:
If you are prompted to login and the terminal asks for your password, give "Personal Access Token"

#### Steps to create a Personal Access Token (PAT)
1. Go to your github profile (on browser - github.com)
2. Click on profile and go to settings
3. Scroll down, on the left side panel you can see "Developer Settings"
4. Click on Personal Access Tokens
5. Create one - Tokens (Classic)
6. Give it any name in "Note" and select all checkboxes
7. Generate new token
8. Copy it and store it somewhere safe