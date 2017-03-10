docker-python-2.7.13-jessie-nodejs
----------------------------------
Debian Jessie with python 2.7.13, NodeJS, NVM, git, python-pip preinstalled

Used for Plone/Django test runners in Gitlab CI.

To use::

$ docker pull gw20e/jessie-py2.7.13-nodejs
    
    
Gitlab CI
=========

In your `gitlab-ci.yml` file add the image statement to use this image::

    image: gw20e/jessie-py2.7.13-nodejs
