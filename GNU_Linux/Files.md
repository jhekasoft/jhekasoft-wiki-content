# Files #

## Delete .svn files ##

    find . -name ".svn" -exec rm -rf {} \;

## Recursively change permissions ##

    find . -type d | xargs chmod a+wx

