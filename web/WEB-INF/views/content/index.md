**Micro**, for short: **(μ)** or **[Mu](http://en.wikipedia.org/wiki/Mu_\(letter\))**, is a modular Model View Controller framework ([MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)) for web development, and it was designed with simplicity in mind. Compared with other Java web frameworks, Micro is not forcing you to use the Java language for creating dynamic content, nor pigmenting your code with Java [syntactic metadata](http://en.wikipedia.org/wiki/Java_annotation) or anything like that. With Micro you can start developing your web application right away even if the only content your site has is plain text or [Markdown](http://daringfireball.net/projects/markdown/) documents, and you don't need Java for that. Micro is using Java under the hood providing you the support that is specific to the web development: localization, template languages, scripting support for more advanced use, and a modular way to extend your dynamic content with controllers written in Java or using scripting, such as: [Beanshell](http://www.beanshell.org/), server side [Javascript(Rhino)](http://www.mozilla.org/rhino/), [JRuby](http://jruby.org/) and [more](http://commons.apache.org/bsf/).

We hope Micro will help you develop web applications while increasing the fun quotient of programming as well. Inspired from [Sinatra](http://www.sinatrarb.com/), Micro will help you creating web application in Java with very little effort. Before going forward please check the few **[prerequisites](/misc/check_java.md)** and follow the simple steps there to prepare your environment for running Micro. 

#### Installing Micro
Micro can be downloaded from Github and you will need just a few commands to make it available to your console.

    $ ...

#### Creating a new Micro web application
Create a new micro web application and start Micro with the embedded [web server](http://docs.codehaus.org/display/JETTY/About+Jetty):

    $ micro new hellow_world

A new directory `web_app` will be created and you can start using Micro right away:
    
    $ cd hellow_world
    $ ./bin start

You will see something like this:
    
    -  _ __ ___ ( ) ___ _ __ ___ 
    - | '_ ` _ \| |/ __| '__/ _ \ 
    - | | | | | | | (__| | | (_) |
    - |_| |_| |_|_|\___|_|  \___/  (v0.1)
    - = a modular micro MVC Java framework
    .... 
    - Started SelectChannelConnector@127.0.0.1:8080 

You can visit your web application by pointing your browser to: [http://localhost:8080](http://localhost:8080)

We hope you'll enjoy writing web applications with **Micro**.

Thank you!    

### Special thanks
  - to my [wife](http://twitter.com/simonuta), for understanding my endless passion for programming.
  - [JPublish.org](http://jpublish.org/) - a rusty but trusty framework. There are core concepts in Micro designed as continuations of the ideas developed for JPublish; Templates and Repositories, for example.
  - Many thanks to [Anthony Eden](https://github.com/aeden) for being an inspiring developer and a model for many of us.
  - Many thanks to [Frank Carver](https://github.com/efficacy) for contributing ideas to the [JRack](https://github.com/florinpatrascu/jrack), many of these being ported back into JRack and used by Micro.
  - [Spring framework](http://www.springsource.org/) - the localization support in Micro was extracted from selected classes originally developed for the early Spring framework.
  - [Apache Wink](http://en.wikipedia.org/wiki/Apache_Wink) - used as a future support for [JSR-311](http://www.jcp.org/en/jsr/detail?id=311).
  - to all our **contributors** and **supporters**. Cheers!
  
### License

    Copyright (c) 2012-2013 Florin T.Pătraşcu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    