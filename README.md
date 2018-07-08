# MMC5277-Assignment 8

# Resources

The only resource I used besides our lecture notes and videos was the GitHub forum.

## link
[GitHub Blog](https://blog.github.com/2015-06-08-how-to-undo-almost-anything-with-git/)

# Comments

I had issues with committing the image.
I was unsure of how to add the image into the folder so I just manually did a drag and drop into the images folder, but then somehow managed to do a git add . for the file into both master branch and new-section. It then gave me a merge conflict and I had to resolve the duplicate commit by resetting to the previous commit. I had to remove the file from the staging area (git reset Head <file>) and the delete the file (git clean -d -x -i) and then selected the 1st option.
