# trending-api-64

about commit names that are sometimes wrong here:

When i was writing messages for commits i hadnt yet thought that all the files would be captioned as "..with unsolved bugs" etc.
The real case is it is alive and kicking and bugs are rare (crashes after a 5 hrs doesnt count)

# about bugs

1: When you search by name it sometimes failes to find some letters in particular names, it looks like it has something to do with github API and its responds to this kind of requests.

2: Fsync from CLI makes console hang and you need to Ctrl+C when you recieved the response (which is refreshed database)

# DOCUMENTATION:

# how to run this API:

You need to get the contents of the repo cloned or downloaded and then invoke the terminal inside the folder to call "npm install" (initiates the node package manager settings)
then the app will notify you that the server has started and it will be hosted on a port of 4000, which value is set in "app.js" file at a 47th line

1. Graphical interface:
   To use the graphical interface you need to run "npm run dev" from the file of downloaded/cloned repository, and then go to page of localhost:4000 in your browser and then it wont be that hard to go on

2. Command Line Interface
   In order to use CLI you need to invoke the file commands.js with node by calling node commands.js in terminal while located in file "trending-repos-cli".
