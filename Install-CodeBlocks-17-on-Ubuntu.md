
**Step 1:** Install gcc and g++
Open terminal `Ctrl` + `Alt` + `T`

    sudo apt-get install gcc g++

**Step 2:** Download CodeBlocks
[Download Link](http://www.codeblocks.org/downloads/26)
![enter image description here](download.png)

**Step 3:** Go to the folder that contains the `codeblocks_17.12-1_amd64_stable.tar.xz` file and open the terminal by right clicking from the folder.

**Step 4:** Extract the files and install codeblocks

    tar -xf codeblocks_17.12-1_amd64_stable.tar.xz

    sudo dpkg -i *17.12*.deb

**Step 5:** Install the missing dependencies

    sudo apt-get install -f
