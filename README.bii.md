json11
-------

json11 is a tiny JSON library for C++11, providing JSON parsing and serialization.

The biicode block "https://www.biicode.com/lasote/json11" has been generated from the forked github repo: "https://github.com/lasote/json11".

It includes slight modifications added to the original repository (https://github.com/dropbox/json11) in order to work properly with biicode.

How to use it?
--------------

New with biicode? Check the [getting started guide](http://docs.biicode.com/c++/gettingstarted.html).

Create new biicode project and create an empty block:

    > bii init myproject
    > bii new myuser/myblock


Include the header you need from this block in your source code:

    #include "lasote/json11/json11.hpp"


You can also keep your **#includes** as *"json11.hpp"* using include mapping:

    [includes]
    json11.hpp: lasote/json11


Open **biicode.conf** file and put a requirement to this block:

    [requirements]
    lasote/json11: 4 # Check last version in website (http://www.biicode.com/lasote/lasote/json11/master)


Program your code and build it:

    > bii cpp:build # This command will build your project and json11 dependency


You can check an [the example](http://www.biicode.com/examples/examples/json11/master/0/test.cpp) with some examples using Json11 with biicode.
