+++
title = 'Bsd Sockets p1 - Basic TCP server'
date = 2026-02-23T18:31:04-06:00
draft = true
+++

I want to preface this by saying that if you are interested in learning about Berkley Sockets, I highly recomend you buy 'Beej's Guide to Network Programming'. It is where I got most of my knoweledge from and I highly recomend it.

In this post I am going to introduce Berkley sockets and show how I wrote a simple tcp server in C.

Berkley sockets are an abstraction that allows us to send and recieve data via tcp/udp between processes and computers over the network. Our tcp server will be able to send and recieve data across a network. For our tcp client I will be using netcat(1). To learn how to write a tcp client, check out my next blog post.

Lets start the server with the neccessary #include statements:
