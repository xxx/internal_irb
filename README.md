Wut?
====

Just a small chunk of code taken from a blog post at http://jameskilton.com/2009/04/02/embedding-irb-into-your-ruby-application/ (which itself was taken from the ruby-debug gem) to drop into an irb session at any point in a ruby program.

How?
====

0. `require` this file somewhere in your app.
1. `IRB.start_session(binding)` in your code will drop into irb immediately.


Huh?
====

It works on my machine. ¯\(°_o)/¯
