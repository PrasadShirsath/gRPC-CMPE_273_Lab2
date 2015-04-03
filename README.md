grpc Moderator-Polls Examples
==============================================

In order to run the examples simply execute one of the gradle tasks

For example, say you want to play around with the Polls examples. First you want to start
the server and then have the client connect to it and let the good times roll.

Assuming you are in the grpc-java root folder you would first start the route guide server
by running

```
$ ./gradlew :grpc-examples:PollsServer
```

and in a different terminal window then run the route guide client by typing

```
$ ./gradlew :grpc-examples:PollsClient
```

That's it!

Please refer to [Getting Started Guide for Java] (https://github.com/grpc/grpc-common/blob/master/java/javatutorial.md) for more information.
