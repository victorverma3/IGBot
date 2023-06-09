# FakeFriends

# Inspiration
Instagram, like most social media, is full of "fake friends", which I define as any account that is not both following the user and followed by the user. I created this program so that users can identify their "fake friends" on Instagram and take action to follow/unfollow them if desired. Naturally, there will accounts (e.g. sports pages) that will not follow the user back, but this is left for the user to categorize. 

# Overview
Fakes are defined as accounts that the user follows, but don't follow the user back. Fans are defined as accounts that follow the user, but the user doesn't follow back. This program will read the user's following and follower JSON data and create a CSV with two columns. The first column lists the fakes, and the second column lists the fans.

# Setup
First, open the desired Instagram account and navigate to Your activity --> 
Download your information --> Request a download --> Select accounts and profiles --> Select types of information --> Followers and following --> "JSON" Format and "All time" Date range. At this screen, request the user data to be 
downloaded as JSON files. Download the data from your email when it is completed. Finally, unzip the data and move the files followers_1.json and 
following.json into a folder called {user}, where user is the name of the 
person whose data is being used. Then move this folder into the same 
local directory as igbot.py.

The json and pandas libraries must be installed in Python for this program to run (see other tutorials online to install these).

Once the setup is complete, run the file igbot.py and follow the 
instructions that are provided.

