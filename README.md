# notebook_startup
Startup script for Linux-based systems for running jupyter notebook when rebooting using an /etc/init.d script.

###Testing###

Test that it all works:

    /etc/init.d/jupyter-notebook start
    /etc/init.d/jupyter-notebook status
    /etc/init.d/jupyter-notebook restart
    /etc/init.d/jupyter-notebook stop

Add **jupyter-notebook** to the default runlevels:

    update-rc.d jupyter-notebook defaults
