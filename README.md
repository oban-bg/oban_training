# Oban Training

The Oban Training curriculum is extracted from our in-person training from ElixirConf 2023. It's
designed to teach everything you need to know to get started with Oban, a background job system
for Elixir.

Training is open source and built with Livebook.

## Prerequisites

* Install [Livebook](https://github.com/livebook-dev/livebook) (0.12+ recommended)
* Install [Postgres](https://www.postgresql.org/download/) (15+ recommended)

This course is intended to be approachable to developers with minimal Elixir background.

## Getting Started

Clone this repository to your local computer. Then open the `start.livemd` file to see all lessons
and exercises.

## Training Outline

See `start.livemd` for a full breakdown of our lessons and exercises.

### 📓 Why Oban?

* Where we convince you that using Oban is a good idea
* Not really. It's where we'll give a high level overview of the architecture
* Terminology, how things work

### 📓 Up and Running

* Installing Oban into an application
* Running migrations
* Configuring for tests
* Verifying Oban is running and configured properly

### 📓 Signing Up

* Creating worker modules
* Enqueueing jobs
* Scheduling jobs to run in the future
* Asserting jobs are enqueued in tests

### 📓 Placing an Order

* Controlling worker behaviour with return values
* Testing worker functionality
* Managing retry backoff
* Providing execution timeouts

### 📓 Refunding an Order

* Ensuring uniqueness
* Cancelling and retrying jobs
* Replacing fields on unique conflicts
* Draining queues for integration testing

### 📓 Delivering a Daily Digest

* Running jobs on a schedule
* Managing multiple queues and concurrency
* Pausing and resuming queues
* Validating configuration changes

### 📓 Backfilling Reviews

* Deprioritizing jobs
* Inserting multiple jobs at once
* Recursively enqueuing jobs
* Asserting the content of all enqueued jobs

### 📓 Ready for Production

* Pruning older jobs
* Rescuing unexpectedly stopped jobs
* Logging and instrumenting with Telemetry
* Reporting errors
