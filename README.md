README
======

It's Simple
-----------

`mkdir -p path/to/dir`

`git clone https://github.com/andrew-werdna/DockerMeanSetup.git path/to/dir/docker`

`cd path/to/dir/docker`

`docker-compose up --build -d`

The path/to/dir is a convenient container for your whole setup.
The path/to/dir/docker is where this repo will live.
When you up the containers, your mount folders will be created inside
path/to/dir (or path/to/dir/application on your local)

What's inside
-------------

Node/MongoDB/Express-Generator

Starting out
------------

When you exec into the running nodeapp container, you will land in your mount folder.
Just run `express [options] .` and [express-generator](https://expressjs.com/en/starter/generator.html)
will output the scaffolding for an easy start
