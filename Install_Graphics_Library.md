## How to Install graphics.h in Ubuntu

Download ``libgraph``. **[Download Link](http://download.savannah.gnu.org/releases/libgraph/libgraph-1.0.2.tar.gz)**

Open Terminal and run the following commands.
 
``sudo add-apt-repository universe``<br>
``sudo apt-get update``
    
After that

      sudo apt install libsdl-image1.2 libsdl-image1.2-dev guile-2.0 guile-2.0-dev libsdl1.2debian libart-2.0-dev libaudiofile-dev pulseaudio-esound-compat libdirectfb-dev libdirectfb-extra libfreetype6-dev libxext-dev x11proto-xext-dev libfreetype6 libaa1 libaa1-dev libslang2-dev libasound2 libasound2-dev

Move ``libgraph-1.0.2`` to your home directory. (Extract the files first)

``cd libgraph-1.0.2``

Finally

``./configure``<br>
``make``<br>
``sudo make install``<br>
``sudo cp /usr/local/lib/libgraph.* /usr/lib``<br>

Now you can use ``grapics.h`` header file. 
Thank you.

