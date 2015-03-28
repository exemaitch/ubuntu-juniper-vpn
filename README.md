Role Name
=========

Role to install requirements for Juniper VPN in Ubuntu.

Requirements
------------

We need to install a 32 bit Oracle JDK on the Ubuntu system before you can actually run the Juniper vpn from the 
website or from the jvpn script.

Before running jvpn for the first time, you have to navigate to the VPN website and install nvsc.  
In other words, try to log into the Juniper VPN server from the provided webpage.  That will install nvsc.  
From there, edit the jvpn.ini file to  reflect the correct realm and server ip.


Role Variables
--------------

None.

Dependencies
------------

ubuntu-base-desktop role

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ubuntu-base-desktop }
         - { role: ubuntu-juniper-vpn }

License
-------

BSD

Author Information
------------------

Xuan Mai Ho
