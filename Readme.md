

ws-ping
-------

Console utility developed in Node.js, that checks the status of web services.

![Execution screenshot](https://github.com/aleiglesias/ws-ping/blob/master/ws-ping-01.png)

**ws-ping** scan the directories from the root for files containing web services requests:

![Requests directories](https://github.com/aleiglesias/ws-ping/blob/master/ws-ping-02.png)

Root directory is obtained from the config.js file:

    config.root = "./requests";

Web service requests file must have the same format obtained from Fiddler:

![Request format](https://github.com/aleiglesias/ws-ping/blob/master/ws-ping-03.png)

## Command-line arguments flags ##

-s \<subdirectory\>: It defines the subdirectory where looking

-n \<file name\>: Filter by complete file name

-f : Set Fiddler proxy to monitor the request
