# this README file contains the things that I learned during my journey of backend.
## web fundamentals

## INTERNET
Internet is the biggest network
It is the network of networks.
Internet != World Wide Web
www is a service that is provided and based on internet.
like truck service is provided to us by roads.

Internet evolved from 4 computer in 1969 to 5.6billion computers as of now.

Internet is managed by many organisations, and not by a single entity.

# Packets 
data is divided into numbered little chunks that choose their own routes and then are reassembled once they reach destination.

# servers
servers are the computers that are always on to take request and give response.

# http
hyper text transfer protocol, it is like an open envelope, that everyone can read.

# https 
it is the secured protocol, not everyone can read, thus improving the security.

# port
IP adress defines a machine, and port describes what service is running on the machine.

# DNS - DOMAIN NAME SYSTEM
when we right something in our browser to search, like a domain name,
example - google.com
our browser don't know what is google.com here, what our browser know is the IP address mapped to it.
DNS helps getting that IP adress.
# how dns works?
browser -> you wrote something like google.com
search in cache -> browser will first search in the cache memory, is there any recent knwoledge about this domain.
if the domain is not found in the cache -> it will go to the OS host files
if not there, then in users ISP DNS resolvers (like jio dns)
if not there, then it will be searched in the routes nameserver (globally only 13)
then TDL server will get the IP from google namespace.
then the IP is returned to browser.

# what is a record in DNS? 
    it is the table maintained for domain name and the IP address associated to it.
# TXT record?
    it makes the google and github checks if you own a domain or not.
# CNAME?
    it is the alias to domain name, like www.google.com -> google.com


# IP ADRESS
it is the local address for your system, to let internet locate it.
## IPV4 
    it is the combination of 4 groups of number (0-255) seperated by .
    around 4.3 billion possibilities available, we've almost ran out.
## IPV6
    it is 8 group of hex numbers, it is much longer.
    340 undecilion possible addresses.
# three most famous IP addresses.
170.0.0.1 -> localhost
192.168.x.x -> private/local IP
0.0.0.0 -> it means it can listen from anywhere, it accepts connection from everywhere.

# client server architecture
whole web server is based on this client server architecture.
clients sends the request to server
and then the server send the respond to client.