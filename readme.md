## A bare metal HTTP server in C that handles promitive requests

Currently, only __GET__ is implemented in files as well as output from __CGIs__

Build everything with __make all__

Run the server either in the backround or in another terminal window (__./server &__)

Run the client (__./client__)

To kill the server, bring it back to the foreground by first __interrupting the client__ (ctrl +c) and then bring the server back in the foreground (__fg__) and interrupt it also