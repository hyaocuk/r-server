#R-Server
----------------

easy server

###How-to:

1. install [Racket](http://racket-lang.org/).
2. `git clone https://github.com/hyaocuk/r-server.git`.
3. `$ racket`
4. `> (enter! serve.rkt)`.
5. Start the server by `> (define stop (serve port-no))`.
6. Stop the server by `> (stop)`.

###What you get

1. Launch browser and go to `localhost:port-no`.
2. `localhost:port-no` will display wrong page.
3. `localhost:port-no/hello` will display `hello world`.
4. `localhost:port-no/many` will ask you input how many `hello` to be displayed and then reply from the server.
