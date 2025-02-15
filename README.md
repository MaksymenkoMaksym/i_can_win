# i_can_win

1. Install git and generate a pair of ssh keys.
   Authorize the public key on github.com.
   # ssh-keygen -t rsa –C “[mail-or-other-info]"
2. Specify your user.name and user.email in git.

   # git config --global user.name="[user-name]"

   # git config --global user.mail="[user-mail]"

3. Create a new repository on github.com and
   clone it locally to your computer.

4. Create a file called song.txt and
   put there half the text of your favorite song.

   # touch [name-of-file]

5. Make a commit called "add first half of my favorite song"
   and send it to~ the server.

   # git add . -> added all files to staging

   # git add [name-of-file] -> added specific files to staging

   # git commit -a -m "[comments]" -> adding all files to staging, commit with comments mentioned inside " "

   # git commit -m "[comments]" -> commit with comments mentioned inside " "

6. Make sure github has a song.txt file with the lyrics.

7. Using the github's web interface,
   add the second half of the lyrics and
   make a commit with the name "finish my song".

8. Make a pull in the local repository and
   make sure that the commit you created on github
   is pulled up and you have all the lyrics.
   #git pull

   ====== PART 2 ========================
   Bring It On

9. This task is performed immediately after the previous one (I Can Win).

10. Add a .gitignore file to the project and
    configure it to hide files with the extension
    .db, .log and directories with the names target or bin.

    # touch .gitignore

    # inside _.db _.log /target /bin

11. Create a feature branch and add two commits to it

    # git branch [branch-name] -> create new [branch-name]

    # git checkout [branch-name] -> switched to [branch-name]

12. Merge the feature branch in master

13. Return to feature and create the arrows.txt file with the following contents:

The ship glides gently on the waves
As day turns into night

Make a commit.

5. Go to master. Create the arrows.txt file there and add the following text:

One thousand burning arrows

Fill the starlit sky

Make a commit.

6. Merge feature in master resolving the conflict: save all 4 lines in arrows.txt file in the order they were added in steps 4 and 5.
