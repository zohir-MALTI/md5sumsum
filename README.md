`md5sumsum`
===========

This repo contains a dumb script `md5sumsum` which compute the `md5sum`
of the concatenation of all `md5sum` of all files of a folder hierarchy
with paths sorted in alphabetical order.

This script is useless (you would for sure prefer do that with `tar` and
have in bonus the file metadata) and have no other purpose than to be an
exercise to learn what commonly makes a software slow and how to speed
up it.

That's why we have here an automated test suite (thanks to [Travis
CI](http://travis-ci.com)) that measures the speed of execution of
submitted PRs!
