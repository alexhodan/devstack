# devstack
DevStack local.conf file


Enabled Services

1. Controller
2. Nova
3. Neutron
4. Swift
5. Glance
6. Cinder
7. Heat
8. Trove
9. Sahara
10. Horizon

#Starting DevStack
Run ./stack.sh from devstack directory. Make sure that user is a sudo user(gid 27).
Once all the componets are started, You will get the Dashboard(Horizon) URL.

#Stopping DevStack
Run ./unstack.sh. This will stop all the processes started by stack.sh and terminates the screen.

#Clean up
Run ./clean.sh to remove all the installed OS packages installed when stack.sh was run.

Set RECLONE to False to minimize the startup time. 

