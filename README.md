[![Build Status](https://secure.travis-ci.org/iffy/agentforhire.png)](http://travis-ci.org/iffy/agentforhire)

Goal
====

I want something to test Twisted web Resources.  Ideally, the thing made should
be good enough to be included in Twisted.


What to do
==========

1. Fork this repo.
2. Modify one of the implementations in `forhire/` (or make a new one; see 
   `forhire/mixin.py`)
3. Make `trial forhire.THETHING` pass (or `./testall.sh`)


Can I change the tests?
=======================

Yes.  If there's something not tested that you think should be, add it.
