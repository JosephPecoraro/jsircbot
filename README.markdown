### jsircbot

Simple IRC bot for [##javascript](irc://irc.freenode.net/##javascript).
You can catch me on IRC as JoePeck.


### Features

  - Quick Google Search (```g`` or ``lucky`)
  - Admin Interface for Adding / Removing Commands and URI Search Commands (`admin)
  - JavaScript interpreter support for (jsc, rhino, v8, and spidermonkey)


### Dependencies

The [json](http://json.rubyforge.org/) gem.  Installation is simple:

    shell> sudo gem install json

The [htmlentities](http://htmlentities.rubyforge.org/) gem. Installation is simple:

    shell> sudo gem install htmlentities

The [open4](http://www.ruby-forum.com/topic/54593) gem. Installation is simple:

    shell> sudo gem install open4


### Setup Your Bot

1. Change the admin password. Just edit the `.password` file.
2. Setup Interpreters in the `interpreters.yaml` file. Just point them
   to the interpreters on your machine.
3. The rest are command line arguments. Just look at the usage:

        usage: jsircbot server port nick channels...
        example: jsircbot irc.freenode.net 6667 JoePeckBotTest #JoePeck ##javascript

           Channels must be prefixed with their hash symbol. You may need to
           escape them in your shell, for example: \#\#javascript


### Contact Info

Name: Joseph Pecoraro  
Blog: [http://blog.bogojoker.com][1]  
Email: [joepeck02@gmail.com][2]  

[1]: http://blog.bogojoker.com "Joseph Pecoraro's Blog"
[2]: mailto:joepeck02@gmail.com "Joseph Pecoraro's Email"
