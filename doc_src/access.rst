.. _access:

.. include:: global.txt

Getting access to the EMDR network
==================================

In order to get access to the EMDR network, you will merely need to connect
to a relay. For your convenience, we have listed the relays below that have
available capacity. If you'd like to verify the health of a relay before
using it, check out our `EMDR monitor`_.

==========================================  ==================  ==============  ==================  ====================================================================
URI                                         ISP                 Location        Access              Notes
==========================================  ==================  ==============  ==================  ====================================================================
tcp://relay-us-west-1.eve-emdr.com:8050     Cogent              Sacramento, CA  Open                West coast US realy. Volunteered by Yann of EVE Central.
tcp://relay-us-central-1.eve-emdr.com:8050  Ubuquity Hosting    Chicago, IL     Open                Central US relay. Volunteered by udsaxman.
tcp://relay-eu-germany-1.eve-emdr.com:8050  Hetzner             Germany         Open                German relay. Volunteered by FuzzySteve.
tcp://relay-eu-germany-2.eve-emdr.com:8050  Hetzner             Germany         Open                German relay. Volunteered by Agedon Group, Inc.
tcp://relay-eu-germany-3.eve-emdr.com:8050  Intergenia          Germany         Open                German relay. Volunteered by EVE-HQ.com.
tcp://relay-eu-germany-4.eve-emdr.com:8050  Hetzner             Germany         Open                German relay. Volunteered by Karbowiak.
tcp://relay-eu-denmark-1.eve-emdr.com:8050  ComX                Denmark         Open                Volunteered by Karbowiak.
==========================================  ==================  ==============  ==================  ====================================================================

Once you have chosen a relay, simply adapt the sample in
:doc:`using` to use the hostname/port of the relay of your choice.

.. tip:: If reliability is a concern, you'll want to connect to multiple
    relays and handle the duplicate messages. This will keep you running even
    if one of the relays you're using dies.

.. note:: Some relays, marked as *Restricted*, require that you request
    access to use them. You will need to get in touch with the relay via the
    contact info listed to work it out with the admin.
