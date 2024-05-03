GIt CAPSTONE PROJECT 
Project objectives 
1. Practice cloning a repository and working with branches in Git. 
2. Gaining experience in staging, committing and pushing changes from both developers.
3. Create pull requests and merge them after resolving any potential conflicts.

TASK
1. I logged into my GitHub account and proceeded to create a new repository. I named it greenwood-library-website. While doing so, I initialized the README.md file
2. On my local computer via VScode, I opened the folder that was created i.e. greenwood-library-website.
3. I then switched from master to main using the command git branch -m main
4. I created four files for each of the web pages. The files created were home.html, about_us.html, events.html and contact_us.html.
5. I proceeded to add content to these files and save each of them.
6. I staged all the files using the command git add . This changed the state of the file from U to A. This was confirmed through git status.
7. I then committed all the files using the command git commit -m “All webpages require review and updates”. The change made was also confirmed through git status. The message below followed.
8. [main 008f92d] All webpages requires review and updates

 8. 4 files changed, 0 insertions(+), 0 deletions(-)      
 create mode 100644 about_us.html
 create mode 100644 contact_us.html
 create mode 100644 events.html
 create mode 100644 home.html

10. I then pushed the files to my remote repository using the command git push -u origin main. The message below followed.

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 322 bytes | 107.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Emmanuel-Ohaba/greenwood-library-website.git
   11f5ec5..008f92d  main -> main
branch 'main' set up to track 'origin/main'.

11. This indicates that the files were successfully pushed to the remote repository.

MORGAN’S WORK
I.  created a branch for morgan and switched to it. I used the command git checkout -b add-book-reviews. Add-book-reviews being the name of the new branch for morgan.
2. I added a new file named book-reviews.html. I added content to the file and then saved the file, stage, commit and push to the remote repository. The push was successful.
3. I then went to my GitHub, raised a pull request for Morgan, and proceeded to merge Morgan’s work with the main branch.

JAMIE’S WORK
1. I created and switched to a new branch called update-events using git chechout -b update-event.
2. I then created a pull request using the command git pull origin main. This ensure that Jamie has an updated file that contains Morgan’s work.
3. I then added more content to the events.html file and saved it.
4. I staged using git add . I committed the file using the command git commit -m “updated events”. I pushed the file to GitHub using git push -u origin update-events.
5. I then went to GitHub to create a pull request and merge these changes to the main branch.
6. This signified the end of the project.