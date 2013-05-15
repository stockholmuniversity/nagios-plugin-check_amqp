nagios-plugin-check_amqp
========================

Nagios NRPE check for checking the AMQP connection to a server (like check aliveness does).
It supports AMQP as well as SSLed AMQP connections.

It's written in Python because, AFAIK, the Perl AMQP libs doesn't do SSL and I
couldn't get Ruby AMQP/Bunny to work on Ubuntu = S

Our primary use for check_amqp is to use it as a healthcheck for our
loadbalancers.

Installation
------------

$ pip install -r requirements.txt
