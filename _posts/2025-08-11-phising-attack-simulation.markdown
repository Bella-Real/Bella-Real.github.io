---
layout: post
title:  "Phishing Attack Simulation"
date:   2025-08-11 16:45:01 -0700
categories: welcome
image: /assets/images/image.png
---

For this project, I will be using the Gophish framework and I will be following [this](https://alphasec.io/phishing-attack-simulation-with-gophish/) tutorial from alphasec.

The first thing I did was sign into [Railway](https://railway.com/) using my GitHub account. After agreeing to the terms and conditions, I used the Gophish [one click starter template](https://railway.com/new/template/gEmUp6?referralCode=alphasec&ref=alphasec.io) to deploy the Docker image of Gophish. 

All of this sounds super complicated but trust me when I say it's a lot more straightforward and intuitive than it sounds. I don't have any experience with Railway or Gophish, and I have very little experience with Docker but you don't need to set any of this up yourself so don't stress too much! With the one click template everything is already configured for you!

Once you have the Docker image up and running, if you look at the deploy logs, you can find the default username and password you will use to sign into Gophish with. It will be something like:


`username: admin`

`password: somecombinationoflettersandnumbers`

After signing in and changing the default password, now is where you get to the fun part. From here you need to:

1. Select the Users/Groups to be phished
2. Sett the Email Template for the user to receive
3. Configure SMTP relay details or "Sending Profiles" to send emails from
4. Set up a Landing Page that the user will go to after clicking on the phishing link

Soooooooo I had an issue with choosing the proper URL for the landing page. I looked into it and wasn't able to figure it out using Railway so I'm going to try hosting it locally instead just to get it functioning and once I get that resolved, I might try and host it on a RaspberryPi for fun?

I've been in the process of moving so this project has gotten extremely delayed! I am determined to return to it once I'm more settled and less frustrated with the issue I ran into hehe in the meantime, I'm going to work on something else. To be continued...