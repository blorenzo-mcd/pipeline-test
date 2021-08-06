# Workaround for quality pipeline email report

Create a public repository outside of restaurant-technology-org and commit at least one file, like this readme for example. 

Try to access this url:
https://api.github.com/users/[your github user name]/events/public. 

Check if at least one object inside the json has this path:

### payload > commits > author > email

If not works, try a second commit. Like the one I'm doing right now.
