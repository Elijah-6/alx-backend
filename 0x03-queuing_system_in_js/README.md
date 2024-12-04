# Queuing System in JavaScript

This repository contains various scripts demonstrating the use of queuing systems and Redis in JavaScript. Below is a brief overview of each script and its functionality.

## 0-REDIS_CLIENT.JS

This script demonstrates how to create a Redis client and handle connection events.

## 1-REDIS_OP.JS

This script shows basic Redis operations such as setting and getting values.

## 2-REDIS_OP_ASYNC.JS

This script demonstrates asynchronous Redis operations using `promisify` from the `util` module.

## 4-REDIS_ADVANCED_OP.JS

This script demonstrates advanced Redis operations, including updating and printing hash values.

## 5-PUBLISHER.JS

This script demonstrates how to publish messages to a Redis channel.

## 5-SUBSCRIBER.JS

This script demonstrates how to subscribe to a Redis channel and handle incoming messages.

## 6-JOB_CREATOR.JS

This script demonstrates how to create a job in a Kue queue.

## 6-JOB_PROCESSOR.JS

This script demonstrates how to process jobs from a Kue queue.

## 7-JOB_CREATOR.JS

This script creates multiple jobs in a Kue queue with different job data.

## 7-JOB_PROCESSOR.JS

This script processes jobs from a Kue queue and handles blacklisted phone numbers.

## 8-JOB.JS

This script contains a function to create push notification jobs from an array of job information.

## 8-JOB.TEST.JS

This script contains tests for the `createPushNotificationsJobs` function using Mocha and Sinon.

## 9-STOCK.JS

This script demonstrates a simple stock management system using Redis and Express.

## 100-SEAT.JS

This script demonstrates a seat reservation system using Redis, Kue, and Express.
