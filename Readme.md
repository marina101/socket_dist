# Intro

This is my attempt to implement Joe Armstrong's irc-like Erlang client and server while working through his "Programming Erlang" book. In the future I'll try to expand on it by re-writing it using OTP, and maybe trying to integrate it to work with the actual irc protocol, but this was a really great exercise to experiment with how this stuff works under the hood.

# Running the program

Install Erlang/OTP v. 17.5

Run ```make```. Then in one terminal window run ```make chat_server``` and in another run ```make chat_client```. This will make the client windows pop-up where you can send message to others in the group, who are all authenticated with the same password.