vis
===

A better inbox
------------------------------
The goal of this project is to create a better web-based email system.
For me, gmail has gotten slow and bloated, and its lack of integration
with systems like Facebook and Twitter has gone on for too long.

I like the efforts of projects like Sparrow, but I'd like to see something
that lives within the browser.

Email should be fast
 - It should use HTML 5 features like local storage and indexDB to store as much of your email locally as possible.
   Loading should be instantaneous.  Think the Offline Gmail app, but an actual full-featured product.
 - Search should be implemented on the client using IndexDB so that little to no server operations are required.

Email should be integrated
 - I'm tired of having separate, disparate services running around the net that refuse to talk to each other.
 - It should be extremely easy to send/read email, Facebook messages, Text messages, etc from a single inbox.
   * The system should deal with de-duplication - in the case that the user is getting notifications via email
     about Facebook messages.


A note about third-party code
------------------------------
I realize that the way I currently am using third party code is awful.  It is definitely incorrect
to simply re-check-in all these libraries.  BUT, I couldn't find an easy way to coordinate a bunch
of git and svn repositories, although there must be a way to do it.

I will rectify this situation in the future....
