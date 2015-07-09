## Introduction ##
**HELP WANTED: This project may be neatly separated into two, and if it's not too late I would appreciate a partner with which to share the work (and profit)**

_NOTE: This project will actually consist of two parts: the backpack application service and a user-facing application. The entire stack is currently referred to as simply 'backpack' for now._

jim wishes to send a file to alice. This is difficult because:

  * alice does not have an easy way to receive data, mainly due to being behind a NAT.
  * jim does not have an explicit method for transmitting data to alice. His options are currently limited to:
    * email (no larger than 50MB, and inefficient)
    * sms (no)
    * a file sharing site (a pain)
    * a public dropbox (easy, except now we have to share a dropbox and requires an internet connection).
    * physical media (come on, it's 2011)

What backpack will provide is a simple and intuitive way of sharing files and information with friends and strangers. For example, to share a photo you just took on your Android phone:

  1. click 'share', then 'backpack'
  1. choose a stream to share with (this may be a single user)
  1. wait.

Everyone subscribed to a certain stream will store and forward the contained data to other interested peers. This means a user A does not necessarily need a direct link to share stuff with user B, C, D, or X. Moreover, this is all handled automatically, and the user simply receives a notification when more data is available in one of her subscribed streams. A multi-hop topology emerges.

### Use Cases ###

300 people at a party. Everyone wants the pictures being taken, but there is no
easy way to assemble this collage. Luckily backpack supports automatic uploading to the party's stream. Everyone gets their pictures, and noone's data plan is adversely affected.

Passive aggressive blogging. Share links with strangers. Local tweeting.
"streams" are the new BBS.  Subscribe to people around you. It's like tumblr
without internet.

After a meeting, everyone's todo list is automatically updated.

Disseminate news through your family automatically.


### Client Application Ideas ###
  * file sharing
  * community newsfeed
  * distributed file system

### Similar Apps ###

  * bump (although it requires an internet connection)
  * aerofs comes close, but you only sync with yourself
  * frostwire, a bittorrent client which has similar ideas

### References ###

Frostwire: http://frostwire.wordpress.com/

Netty: http://www.jboss.org/netty

Vuze:

zeromq: https://github.com/zeromq/zeromq2-1