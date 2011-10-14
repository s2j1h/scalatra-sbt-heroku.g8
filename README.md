# Scalatra project

[g8](http://github.com/n8han/giter8) template to get a Scalatra web service up and running quickly on [heroku](http://www.heroku.com). The template generates a project that uses SBT 0.11.

## Usage

Install giter8 (g8) - [readme](http://github.com/n8han/giter8#readme) for more information.

Install SBT 0.11.x - [Setup](https://github.com/harrah/xsbt/wiki/Setup) for more information.

In a shell, run the following:

    g8 scalatra/scalatra-sbt-heroku
    cd <name-of-app>
    sbt
    > update
    > jetty-run
    
You should be able to browse to a [test resource](http://localhost:8080/)

