remote: Total 83990 (delta 14473), reused 14390 (delta 14301), pack-reused 69134 (from
Receiving objects: 100% (83990/83990), 82.16 MiB | 3.58 MiB/s, done.
Resolving deltas: 100% (66634/66634), done.
$ cd sqlmap
$ chmod tx sqlmap.py
chmod: invalid mode: 'tx'
Try 'chmod --help' for more information.
~/sqlmap $ chmod +x sqlmap.py
~/sqlmap $ python2 sqlmap.py https://hbh.sh/home

    ___
   __H__
 ___ ___[.]_____ ___ ___ {1.8.9.1#dev}
 |_ -| . ['] | .'| . |
 |___|_ [,]_|_|_|__,| _|
       |_|V... |_| https://sqlmap.org

[!] legal disclaimer: Usage of sqlmap for attacking targets without prior mutual consent
is illegal. It is the end user's responsibility to obey all applicable local, state, and federal
laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program

[*] starting at 21:13:36 /2024-10-02/

[21:13:39] [WARNING] you've provided target URL without any GET parameters (e.g. 'http:.
    /article.php?id=1') and without providing any POST parameters through option '-data'
[21:13:47] [INFO] testing connection to the target URL
...
[21:14:16] [INFO] testing MySQL 5.1 AND time-based blind
...
[21:14:41] [CRITICAL] considerable lagging has been detected in connection response(s)
[21:15:03] [INFO] testing Oracle AND time-based blind
...
[21:16:16] [WARNING] HTTP error codes detected during run: 404 (Not Found) - 73 times
[*] ending at 21:16:16 /2024-10-02/

~/sqlmap $
