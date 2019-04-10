
# Hello World Jaeger Instrumentation

This repository initially contains a hello world program to show how tracing works with jaeger backend.
Further I look contribute to Jaeger by making tutorial for Jaeger-cpp-client. 

## Building


jaeger-client-cpp is built using CMake. It will automatically download
needed dependencies using [Hunter](https://docs.hunter.sh/en/latest/).

To build:

```bash
    mkdir build
    cd build
    cmake ..
    make
```

After building, the [example](./examples/App.cpp) program can be run
with:

```bash
    ./app ../examples/config.yml Bryan!
```

To run tests:

```bash
    make test
```

To install the library:

```bash
    make install
```

### Screenshots

![command-line-input](https://github.com/dexter816/jaeger-hello-world/blob/master/Screenshots/Screenshot%20from%202019-04-03%2003-15-00.png)
![Jaeger-UI](https://github.com/dexter816/jaeger-hello-world/blob/master/Screenshots/Screenshot%20from%202019-04-03%2003-15-30.png)
