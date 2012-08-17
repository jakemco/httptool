# HTTP Tool

HTTP Tool is a Mac application that makes HTTP requests for testing RESTful APIs without having to muck around with curl on the command line.

## Description

HTTP Tool is build using the [RestKit](https://github.com/RestKit/RestKit) framework in order to make GET, POST, PUT, and DELETE requests easily. You can specify a base URL, http or https, set whether or not you want to follow redirects, ignore or respect certificates, and apply parameters to the request.

## How To Use

There is not yet a pre-built app binary, as httptool isn't ready for 1.0 yet, but if you want to play with it, simply copy down the source and build using Xcode. I'm running Xcode 4.4.1 on OS X Mountain Lion. Haven't tested it on any other system.