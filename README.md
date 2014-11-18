richelieu
=========
Named after Cardinal Richelieu: https://en.wikipedia.org/wiki/Cardinal_Richelieu

Usage
-----
1. Run getwp with the URL of a wordpress blog, redirecting the output to file.  
e.g.  
./getwp http://wpblog.example.com/ > wpblog.data

2. Run find_terrorist on a data file to try to frame them. Note that at the moment it just finds sentences containing keywords.  
e.g.  
./find_terrorist --source wpblog.data

To-do
-----
It is intended to provide more 'get' types (e.g. twitter, livejournal).

It is also intended to improve the find_terrorist program to:
1. Accept input from stdin if a source is not specified (allowing direct piping from a 'get' program).

2. Do some better processing on the data to try to pick out, e.g. two sentences that when placed together make the person sound suspect, or to cut sentences with ellipses to aid in framing. This needs further investigation.
