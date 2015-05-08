AutoSlack
============

AutoSlack is a simple module designed to automate some tasks for http://slack.com.
Currently it includes an invite method for automatically inviting persons
to a Slack community.

Installation
--------------
::

  pip install autoslack

(you could also simply add autoslack to your requirements.txt, setup.py or buildout file)

Usage
---------
To use this you will need to generate a token by visiting https://api.slack.com/web#authentication, the token is passed to the autoslack.invite() method.

.. image:: https://github.com/PythonJamaica/autoslack/raw/master/slacktoken.png
 
::

    import autoslack
    autoslack.invite(group="SLACKCOMMUNITYNAME",
                    token="XXXXXXX",
                    firstname="XXXXXXXX",
                    lastname="XXXXXXX",
                    emailaddress="XXXXXXX",
                    channels=['XXXXX','XXXXX']
                    )
