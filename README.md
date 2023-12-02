# Redis 

A simplified Redis-like in-memory data structure store, capable of supporting basic data structures such as strings, hashes, lists, sets, and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Features

- **In-memory Storage:** Store data directly in memory for quick access.
- **Basic Data Structures:** Support for strings, lists, hashes, and sets.
- **Command Parser:** Interpret and execute commands similar to native Redis commands.
- **Persistence:** (Optional) Save and load data from disk to retain data across sessions.

## Installation

### Prerequisites
- [Go](https://golang.org/dl/) (or replace with your language's prerequisites)

Clone the repository:

    git clone https://github.com/yourusername/build-your-own-redis.git

Navigate to the project directory:

    cd build-your-own-redis

Build the project (if applicable):

    make build

## Usage

Start the BYOR server:

    ./byor-server

Connect to the server using BYOR client:

    ./byor-client

Once connected, you can use commands similar to Redis:

    > SET hello "world"
    OK

    > GET hello
    "world"

## Contribution

Interested in contributing to BYOR? Great! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Push your changes to your forked repo.
4. Create a pull request from your branch to the main BYOR repository.
5. After review, if everything looks good, your changes will be merged.

## Acknowledgments

- This project was inspired by and based on the ["Build your own Redis"](original-link-to-the-tutorial) tutorial. All credits to the original author for the idea and foundational knowledge.

