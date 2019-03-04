# Pyhton Is a Superpower
#### https://medium.com/progate/python-is-a-superpower-6d818777137c
To stream music from youtube
https://ascolta.ml/ 
Youtube API Heads up!

The world of geolocation
https://geopy.readthedocs.io/en/stable/

There is always a way to implement an idea in python.  What questions can you now
ask?


# Simple Web Automation
#### https://towardsdatascience.com/controlling-the-web-with-python-6fceb22c5f08
Selinium
driver.find_element_by_id()
driver.find_element_by_link_text()
driver.find_element_by_name()
then
.click()
or
.send_keys()
Hehe


# Learning a Programming Language, Hard or No?
#### https://towardsdatascience.com/master-python-through-building-real-world-applications-part-1-b040b2b7faad
He is creating his dictionary but words is this way
>...if the user has made a typo while entering a word, our program will suggest the closest word saying ‘did you mean this instead?’, and if the word has more than one definition, retrieve all of them
I suppose the key to app development is structuring the language used to explain how an app works similar to how the code for that app would be structured.  I am very seribral, I need to spend more time working and communicating in this way.  Thus the blog eh?
Json:  Thinking about things this way makes app developent not trivial but non-mystical

data = json.load(open("data.json"))

def retrive_definition(word):
    return data[word]
    
Very Simple. Done.
When it comes to comparing stings, to find the closes word there is the difflib lybary -libruary I mean library
import difflib
from difflib import SequenceMatcher

Dictionary of english words 
https://github.com/Dhrumilcse/Interactive-Dictionary-in-Python/blob/master/dictionary.json
https://www.kaggle.com/borrkk/dictionary


# Pyhton and Graph Theory a Must
#### https://becominghuman.ai/to-all-data-scientists-the-one-graph-algorithm-you-need-to-know-59178dbb1ec2
Graph Analytics Big data course https://www.coursera.org/learn/big-data-graph-analytics?ranMID=40328&ranEAID=lVarvwc5BD0&ranSiteID=lVarvwc5BD0-uD3tAFL0mCUdzcfwDd6FTQ&siteID=lVarvwc5BD0-uD3tAFL0mCUdzcfwDd6FTQ&utm_content=2&utm_medium=partners&utm_source=linkshare&utm_campaign=lVarvwc5BD0
Python Graph Class Implementation https://www.python-course.eu/graphs_python.php
PySpark https://ai.google/research/pubs/pub43122
GraphFrames in PySpark http://go.databricks.com/hubfs/notebooks/3-GraphFrames-User-Guide-python.html


