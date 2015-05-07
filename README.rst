AutoSlack
============

AutoSlack is a simple module designed to automate some tasks for http://slack.com.
Currently it includes an invite method for automatically inviting persons
to a Slack community.

Usage
---------
::

    import autoslack
    autoslack.invite(group="pythonjam",token="XXXXXXXX",
                    clientid="XXXXXXXX",
                    secret="XXXXXXX",
                    firstname="XXXXXXXX",
                    lastname="XXXXXXX",
                    emailaddress="XXXXXXX",
                    channels=['XXXXX','XXXXX'])
