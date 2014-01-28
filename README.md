robotgame
=========

Codes for robotgame.net

Running the code
================

'''
$ sudo pip install -U rgkit #only once
$ rgrun yourcode.py yourothercode.py #once in the folder with both .py files. They can also be the same
'''

run.py also takes optional parameters. Some common ones are:
-m, --map <map>: specifies a map file
-H, --headless: runs without the UI (e.g. for A/B testing, etc.)
-c, --count <number>: specifies a number of games to run concurrently
