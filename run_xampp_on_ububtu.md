### How to run XAMPP from command line on Ubuntu
***
**Open the terminal and run the following commands**<br>
``sudo su``<br>
**Enter your password**<br>
``cd /opt/lampp``<br>
``./xampp``<br>
**Then you will get an action command list like in the following**<br>

    Usage: xampp <action>
    
        start         Start XAMPP (Apache, MySQL and eventually others)
        startapache   Start only Apache
        startmysql    Start only MySQL
        startftp      Start only ProFTPD

        stop          Stop XAMPP (Apache, MySQL and eventually others)
        stopapache    Stop only Apache
        stopmysql     Stop only MySQL
        stopftp       Stop only ProFTPD

        reload        Reload XAMPP (Apache, MySQL and eventually others)
        reloadapache  Reload only Apache
        reloadmysql   Reload only MySQL
        reloadftp     Reload only ProFTPD

        restart       Stop and start XAMPP
        security      Check XAMPP's security

        enablessl     Enable SSL support for Apache
        disablessl    Disable SSL support for Apache

        backup        Make backup file of your XAMPP config, log and data files

        oci8          Enable the oci8 extenssion

        panel         Starts graphical XAMPP control panel

**To run Apache, MySQL**<br>
``./xampp start``
