# Deque-Using-Stacks


Here is the kind of output I get before fixing the move method.

    4000     0.4   3.1
    8000     1.5   4.1
    16000     4.9   3.2
    32000    21.6   4.4

Here is the kind of output I get after fixing the move method.
You can see that it is much faster, but not very consistent.
This is due to garbage collection and other system effects.

    4000     0.0   0.7
    8000     0.0   1.2
    16000     0.0   2.2
    32000     0.0   0.2
    64000     0.0   1.5
    128000     0.0   5.7
    256000     0.1   5.3
    512000     0.2   2.1
    1024000     0.4   1.9
    2048000     0.7   2.0
    4096000     2.5   3.6
 
 TODO: Fix this method so that the overall performance is not so bad!
