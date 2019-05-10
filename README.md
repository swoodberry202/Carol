How to run:
1) in terminal navigate to the InstaBot file followed by the instapy-quickstart-master file
2) type python quickstart.py
How to post:
1) in terminal navigate to the InstaBot file followed by the instapy-quickstart-master file
2) type python myPost.py
NOTE: if you want to change the images the bot choses from for posting you can access those in the post file

libraries used
-instapy
-os
-zipfile
-datetime
-threading
-random 
-time
-threading
-random
-markovify
-nltk
-urllib2 
all of these should be able to be installed easily by typing "pip install (myLibrary)" 

File breakdown
capLibrary.txt
	this file is used to generate captions off of for posting. it contains the html from a specific tag page
moreTags.java
	this is used to properly format tags for posts
cleanCaption.txt
	this is the isolated captions that were sifted through by formatter.java
cleanPostTags
	these are the properly formatted tags for the post captions
follow.py
	this is the python file that manages following. If you only want to follow and not perform the other actions that are performed in quickstart.py then just write "python follow.py" in terminal
formatter.java
	this file isolates the captions from a certain tag and stores them in capLibrary.txt for myPost.py to generate off of
hideMe.py
	this file allows the user to not get blocked by instagram by using a rotating IP
like.py
	this file manages liking.If you only want to likw and not perform the other actions that are performed in quickstart.py then just write "python like.py" in terminal
myPost.py
	this uses a markovian chain to generate instagram captions based on 2 specific tags. change tag1 and tag2 to decide which tag you want a caption to be generated from.
quickstart.py
	this file runs like.py,follow.py, and unfollow.py at the same time.
unfollow.py
	this file unfollows the users that are not following you back. If you only want to unfollow and not perform the other actions that are performed in quickstart.py then just write "python unfollow.py" in terminal
myPost.py
	this generates a random caption off of the tags in tags.txt and picks a random photos from the posts folder
tags.txt
	this is a list of tags that the bot will use for posts as well as liking 


