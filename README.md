Responding to Text Messages - Twilio Python Server
--------------------------------------------------


**Description**

A python flask server that responses to text messages.


**How it works**

The flask server listens to request that are funneled through a secure tunnel - [ngrok](https://ngrok.com/). It sends responses to depended on what was texted. 

Step-by-step guide on how the set up the server, ngrok and connect it to Twilio by [chatasweetie](https://chatasweetie.com/) on the post:[Twilio - 2 Ways of Sending Text Message](http://chatasweetie.com/2016/12/19/twilio-2-ways-of-sending-text-message)


### Technology Stack

Python, Flask, & ngrok


### How to run Script locally

Create a virtual environment 

```
$ virtualenv env
$ source env/bin/activate
```

Install the dependencies

```
$ pip install -r requirements.txt
```

Download [ngrok](https://ngrok.com/)

Run ngrok
```
$ ./ngrok http 5000
```

In another terminal, run script
```
$ python server.py
```

Note: The messaging functionality requires that you have a [Twilio](https://www.twilio.com/) account and connecting ngrok to Twilio.

### About the Developer    
Jessica Dene Earley    
[Bio](https://chatasweetie.com/about-me/)   
[Linkedin](https://www.linkedin.com/in/jessicaearley)    
[Blog](https://chatasweetie.com/)    
