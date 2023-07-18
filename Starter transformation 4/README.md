# Starter transformation

[This project](https://github.com/quixio/quix-samples/tree/main/csharp/transformations/empty-template) covers the most basic and essential "hello world" transformation sample. 

It gives an example on how to connect to Kafka and detect the arrival of a new stream.
It also shows you where to place your data processing code.

## How to run

Create a [Quix](https://portal.platform.quix.ai/self-sign-up?xlink=github) account or log-in and visit the Samples to use this project.

Clicking `Edit code` on the Sample, forks the project to your own Git repo so you can customize it before deploying.

## Environment variables

The code sample uses the following environment variables:

- **input**: This is the input topic.
- **output**: This is the output topic.

## Content of the sample
- HelloWorldModel.sln: The solution file describing what projects to include
- HelloWorldModel/Program.cs: contains logic necessary to connect to Kafka topic and consume a stream, process the data and publish it back to Kafka in different topic.
- HelloWorldModel/HelloWorldModel.csproj: the project file which holds together the project and describes some build related details

## Contribute

Submit forked projects to the Quix [GitHub](https://github.com/quixio/quix-samples) repo. Any new project that we accept will be attributed to you and you'll receive $200 in Quix credit.

## Open source

This project is open source under the Apache 2.0 license and available in our [GitHub](https://github.com/quixio/quix-samples) repo.

Please star us and mention us on social to show your appreciation.
