![Newman](http://i.imgur.com/92bZB.jpg)

Newman is a microframework which aims to do for email-based 
applications what Rack and Sinatra have done for web programming. It is
currently in its very early experimental stages, and is not safe for use in
production. 

That said, it is already capable of doing a number of interesting things:

* A simple polling server can be started up which provides a basic interface for
  reading email from a single inbox and then building up a response email.

* Filters can be defined for processing messages based on their TO or
  SUBJECT fields, or for arbitrary conditions based on the mail gem's 
  `Mail::Message` object
 

### For a demonstration of how Newman is used:

Check out [Jester](http://github.com/mendicant-university/jester) as well as some of the
simple examples in this repository.

### For general discussion, questions, and ideas about newman:

Find seacreature in the #newman channel on Freenode or send an email to newman@librelist.org
