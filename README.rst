docker-python-2.7.13-jessie-nodejs
----------------------------------
Debian Jessie with:python 2.7.13, NodeJS, NVM, git, python-pip, Firefox 47 preinstalled

Used for Plone/Django test runners in Gitlab CI.

Usage
=====

To pull:

.. code-block:: sh

	docker pull gw20e/jessie-py2.7.13-nodejs:latest

To push:

.. code-block:: sh

    docker build -t gw20e/jessie-py2.7.13-nodejs:latest .
	docker push gw20e/jessie-py2.7.13-nodejs:latest

To run:

.. code-block:: sh

	docker run gw20e/jessie-py2.7.13-nodejs

Gitlab CI
=========

In your `gitlab-ci.yml` file add the image statement to use this image:

.. code-block:: text

    image: gw20e/jessie-py2.7.13-nodejs:latest
