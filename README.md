javadocio-badges [![Build Status](https://travis-ci.org/moznion/javadocio-badges.svg?branch=master)](https://travis-ci.org/moznion/javadocio-badges)
==

Provides badge of [javadoc.io](http://www.javadoc.io/).

Overview
--

This application is now ready on Heroku.

### Usage

Get page of javadoc.io

    https://javadocio-badges.herokuapp.com/{group_id}/{artifact_id}

Get SVG badge

    https://javadocio-badges.herokuapp.com/{group_id}/{artifact_id}/badge.svg

Example: embedded into markdown

[![javadoc.io](https://javadocio-badges.herokuapp.com/net.moznion/mysql-diff/badge.svg)](https://javadocio-badges.herokuapp.com/net.moznion/mysql-diff)

    [![javadoc.io](https://javadocio-badges.herokuapp.com/net.moznion/mysql-diff/badge.svg)](https://javadocio-badges.herokuapp.com/net.moznion/mysql-diff)

Start the server
--

    DATABASE_URL=postgres://user_name:password@host:port/db_name mvn jetty:run

Creating war file
--

    DATABASE_URL=postgres://user_name:password@host:port/db_name mvn package

How to Deploy to Heroku
--

    DATABASE_URL=postgres://user_name:password@host:port/db_name mvn clean heroku:deploy-war

Author
--

moznion (<moznion@gmail.com>)

License
--

MIT

