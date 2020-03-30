# Go training

## Environment

For the "Go by Example" exercises, I used a Docker container.

For the "Black Hat Go" exercises, I used my laptop (Windows 10). I used chocolatey to install the other required programs from the book.   

### Get the image

```
docker pull go-lang 
```

### Run the image

```
docker run -ti go-lang
```

This will create a Debian 10 container with GO already on it. 

### Get text editor

Vim is my text editor of choice. 

```
apt-get update
apt-get install vim
```

## Credit
Following [Go by Example](https://gobyexample.com/). The website provided all of the GO code.
This work is copyright Mark McGranaghan and licensed under a
[Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/)

"Black Hat Go Go Programming for Hackers and Pentesters" by Tom Steele, Chris Patten, and Dan Kottmann. February 2020.
