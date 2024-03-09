# Arduino-Lessons

This repository is intended to serve as a tool for the Arduino lessons.

During each lesson, an issue will be assigned to each student (collaborator) with it's primary and secondary objectives.

Every pull request needs to be aproved before merging and the 'develop' branch is set to be protected.

With this methodology, the progress will be carefully tracked and well documented.

### How to configure .gitmessage.txt

The message of every commit is a default template and the students may complete it as clearly as possible.

To set this template, each user only have to run the following line just once: `git config --global commit.template .gitmessage.txt`

Then, when commiting changes, the user have to run the line `git commit` and a new window will appear with the template to fill.

**Caution**: Take into account that the editor is not the same on Windows as in Linux. On Windows the editor is VIM and in Linux is Nano. Make sure you know the basic commands before commiting.

The fields for the commit message are explained as follows:

- **Commit title**: In few words describe the commit. Try to aswer the question *What is this commit about?*
- **Username**: No need to explain anything. This answers the *Who?* question.
- **Date**: Write the date with the format DD/MM/YYYY. Of course, this answers the *When?* question.
- **Commit changes**: Give a more detailed information about the changes. You can write for example a bullet list. This field answers the *What happened?* question.
- **Related collaborator/s**: In this field write the username of the collaborators who have something to do with this commit. They can be a revisor, coworker, etc. Answer the *Who else?* question.
- **Related issue/s**: In this field write the number of the issue in which this commit is done. The format is "#\<number\>". For example, for one related issue can be "#7, if there are two "#7, #10".

### Files to ignore with .gitignore

Let's keep it simple. If you have files you want to keep out of track, just locate them in a directory with the name **ignore**.