# xmlrpc_bf

![alt tag](https://github.com/c0dejump/xmlrpc_bf/blob/master/static/exemple.png)

bruteforce login with xmlrpc.php in wordpress website

# Features
- [x] Check automaticly if method is allowed and admin webpage
- [x] Search automatlicaly users in the website with different techniques

# Usage:

>

    usage: xmlrpc_bf.py [-h] [-u URL] [-w WORDLIST] [-s TIME_SLEEP] [--user USER] [-a USER_AGENT] [-rs]

    optional arguments:
    -h, --help     show this help message and exit   
    -u URL         URL to scan [required]    
    -w WORDLIST    Wordlist used for URL Fuzzing [required]    
    -s TIME_SLEEP  timesleep if it's must fast   
    --user USER    if you know the user   
    -a USER_AGENT  Choice user-agent  
     -rs            read source   
>

# Exemples

>

    //Basic
    python xmlrpc_bf.py -u https://url.com/
    
    //Know user
    python xmlrpc_bf.py -u https://url.com/ -w passwd.txt --user admin
    
>
