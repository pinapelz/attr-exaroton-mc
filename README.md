# attr-exaroton-mc

Limit the playtime of users on an Exaroton hosted Minecraft server. Makes use of the Exaroton REST + Websocket API.

**This code was made for a specific use-case and may or may not be useful:**
- Limited playtime on weekdays. A constant amount of playtime is allocated each day, all unused time gets rolled over to the next day.
- Unlimited playtime on weekends
- When players run out of playtime, they get banned until the next day. 
- Fun features to gamble playtime

Why? To prevent any given player from progressing too much on their own.
