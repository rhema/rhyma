rhyma
=====
### Live demo: http://infovisu.com/sand/rhyma-master/sandbox/rhyme/example.html


Rhyma is an effort to create a client side javascript rhyming library. Instead of communicating with a remote database, Rhyma loads two dictionaries on the client: the cmu pronunciation dictionary http://www.speech.cs.cmu.edu/cgi-bin/cmudict and a term dictionary (home brewed from Google's n-gram data http://storage.googleapis.com/books/ngrams/books/datasetsv2.html).


Note:
To run the example in a browser it must be served via HTTP.
For development, I use:
python -m SimpleHTTPServer
