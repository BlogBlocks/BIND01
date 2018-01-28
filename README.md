# BIND01
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/BlogBlocks/BIND01/master?filepath=Palett_Swap_ARRAY_STUFF.ipynb)
.. image:: https://mybinder.org/badge.svg :target: https://mybinder.org/v2/gh/BlogBlocks/BIND01/master?filepath=Palett_Swap_ARRAY_STUFF.ipynb
</div>

The post to twitter will work if a proper key.py file is created.
(notice) lowercase Example is upper case K

Write this in the notebook with proper keys and it will create the key file.

%%writefile key.py
def twiter():
    CONSUMER_KEY = 'xxxxxxxxxxxxxxxxxxxxxxxxxx'
    CONSUMER_SECRET = 'xxxxxxxxxxxxxxxxxxxxxxxxxxx'
    ACCESS_KEY = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxx'
    ACCESS_SECRET = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
    twitter = (CONSUMER_KEY, CONSUMER_SECRET, ACCESS_KEY, ACCESS_SECRET)
    return twitter

