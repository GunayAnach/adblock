# adblock domain servers

I've been using multiple adblock servers, but realise that most of them are not monitored or contains loads of expired webpages which bloats and slows the adblocking server.

So I've created this project from which my pihole can pull and fill blacklisted domains.
Also I've noticed that updating the blacklist straight in /etc/pihole/blacklist.txt slows down the pihole too, while pulling them and parsing them seems to be faster.
