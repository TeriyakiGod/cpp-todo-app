# C++ Todo API

This is a simple Todo API written in C++. It allows you to manage your tasks easily. Can be connected to a todo app client.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

## Prerequisites

- cmake
- g++
- doxygen

### How to run
Clone the Repository
```bash
git clone https://github.com/teriyakigod/cpp-todo-api.git
cd cpp-todo-api
```

Initialize and Update vcpkg Submodule
```bash
git submodule update --init --recursive
```

Build the Project
```bash
mkdir build
cd build
cmake ..
make
```
Building the project should get all the vcpkg dependencies, generate documentation and of course build the app.
Run the app after building.
```bash
./cpp-todo-api
```
The documentation should be available at the root (localhost:8080/)
