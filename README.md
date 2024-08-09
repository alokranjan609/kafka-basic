# Kafka App with Node.js

This repository contains a simple Kafka application built using Node.js. The application includes a producer that sends messages to a Kafka topic and a consumer that reads messages from the Kafka topic.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Producer](#producer)
  - [Consumer](#consumer)

## Prerequisites

Before running this application, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/) (version 12 or later)
- [Apache Kafka](https://kafka.apache.org/) (version 2.7.0 or later)

Ensure Kafka is set up and running locally or on your server.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/kafka-app.git
   cd kafka-app
2.Install the dependencies:

   ```bash
   npm install
  ```


### Usage
**Producer**
The producer sends messages to a Kafka topic using the command-line interface.

To start the producer, run:
   ```bash
   node producer.js
  ```

You can then enter messages via the CLI, and they will be sent to the configured Kafka topic.

**Consumer**
The consumer reads messages from a Kafka topic.

To start the consumer, run:
   ```bash
   node consumer.js
  ```

