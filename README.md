# csgo-protobufs

---

# Info

The current Protobufs for Counter-Strike: Global Offensive.

The latest from
[SteamDatabase/GameTracking](https://github.com/SteamDatabase/GameTracking).

---

# How to make a sparse checkout of SteamDatabase/GameTracking just for the
CSGO Protobuf files

- git init game-tracking
- cd game-tracking
- git remote add origin https://github.com/SteamDatabase/GameTracking.git
- git config core.sparseCheckout true
- echo Protobufs/csgo/ >> .git/info/sparse-checkout
- git pull --depth=1 origin master

