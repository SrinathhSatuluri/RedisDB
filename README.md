# RedisDB Clone

A simple Redis clone implemented in C++. This project is part of a Codecrafters.io challenge to build a basic version of the Redis key-value store from scratch.

## Features

- Simple key-value storage system
- Support for basic Redis commands
- Implemented in C++

## Prerequisites

- C++ Compiler (e.g., g++)
- CMake (for building)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/SrinathhSatuluri/RedisDB.git
    cd RedisDB
    ```

2. Build the project using CMake:

    ```bash
    mkdir build
    cd build
    cmake ..
    make
    ```

3. Run the application:

    ```bash
    ./redisdb
    ```

## Usage

After running the application, you can use basic Redis commands like:

- `SET key value` – Set a key-value pair
- `GET key` – Retrieve the value for a key
- `DEL key` – Delete a key

## Contributing

Feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).

