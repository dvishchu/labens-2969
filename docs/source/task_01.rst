TASK 01: Prepare network devices for automation
===============================================

In this task, we will prepare our environment and devices for automation via ansible. This means that we will activate our virtual environment for python which have already preinstalled all necessary libraries and we will verify connectivity towards network devices.

First, we will start with activation of our virtual environment for python. This can be accomplished via command below.

.. code-block:: console
    
    ansible@iol-ansible:~$ source ansible/bin/activate
    (ansible) ansible@iol-ansible:~$

As you can see, after activation of virtual environment, prompt suffix will change to (ansible) indicating that virtual environment was activated. Now, lets start our lab devices and verify, that they are reachable.  For this, please login to [lab manager] and select lab number 1 -> “01”.