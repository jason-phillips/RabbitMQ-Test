# Rabbit MQ Example Notes
This is a quick implementation of the RabbitMQ Examples. The examples tutorials can be found here:
[RabbitMQ Getting Started](https://www.rabbitmq.com/getstarted.html)

This folder contains the visual studio project for the following example:
Topics

## Setup

You must install the RabbitMQ.client plugin for C#. This can be easily done via Nuget in Visual Studio.
[RabbitMQ.Client Nuget](https://www.nuget.org/packages/RabbitMQ.Client)

To run the examples you must also install the RabbitMQ server and it's dependency Erlang.

Rerecorded to grab the RabbitMQ binary install for windows:
[RabbitMQ Windows Install Instructions](https://www.rabbitmq.com/install-windows.html)

The installer will also ask you to download and install Erlang. It can be found here:
[Erlang(https://www.erlang.org/downloads)


## Running the example

The example is split into two separate solutions. One named Send and the other Receive. As expected, the Receive will consumerism a message and the send will publish a message. 
