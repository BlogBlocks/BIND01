# BIND01
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/BlogBlocks/BIND01/master?filepath=Palett_Swap_ARRAY_STUFF.ipynb)
.. image:: https://mybinder.org/badge.svg :target: https://mybinder.org/v2/gh/BlogBlocks/BIND01/master?filepath=Palett_Swap_ARRAY_STUFF.ipynb
</div><br /><br />

The post to twitter will work if a proper key.py file is created.<br />
(notice) lowercase Example is upper case K<br /><br />

Write this in the notebook with proper keys and it will create the key file.<br /><br />

%%writefile key.py<br />
def twiter():<br />
    CONSUMER_KEY = 'xxxxxxxxxxxxxxxxxxxxxxxxxx'<br />
    CONSUMER_SECRET = 'xxxxxxxxxxxxxxxxxxxxxxxxxxx'<br />
    ACCESS_KEY = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxx'<br />
    ACCESS_SECRET = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'<br />
    twitter = (CONSUMER_KEY, CONSUMER_SECRET, ACCESS_KEY, ACCESS_SECRET)<br />
    return twitter<br />

