# Playground
This Playground is meant to mess around and apply the skills I've learned throughout the course. I will add to this README as I make changes to the project and practice new things.  

9/7 01:00AM:  Created an index.html file.  Added a bunch of random lines to it to see what each HTML tag did...  had some fun with it.  I'm sure we can add to it later.  Also added two .jpg files, one of Cleopatra and one of Achilles.  Hit a little snag when trying to push the changes to GitHub...  the steps are as follows:
1. git add -A
2. git commit -m "message"
3. git push "SSH key copied from repo"

9/7 01:15AM:  I wanted more practice with pushing changes to the repo so I figured I'd run it back.  I also added changes to the README to keep track of the progress I'm making :)

9/8 02:10PM:  Just wanted another run at pulling and pushing with GitBash and GitHub.  SSH key is linked to GitHub, but the URL in HTTPS works as well.  In GitLab I'll just be pulling using the URL each time unless the instructors want something else...

9/8 02:25PM:  Wanted to test pulling from GitLab using the URL.  Ran into an error "fatal: not a git repository (or any of the parent directories) .git".  Snooped Google and found that the folder I was trying to pull into hadn't been initialized.  Easy fix, navigate to the directory you want to pull to:
1. ls -la
2. look for a .git/ folder.  If no such folder exists, it needs to be initialized.
3. git init
Folder should be ready to pull to :)