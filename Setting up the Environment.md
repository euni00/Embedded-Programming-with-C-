# Setting up the Environment

### Cross-compilation

Build system - Ubuntu linux in docker

Host system - QEMU running Raspbian Linux

### Using gdbserver for remote debugging 

An embedded application is launched on the target system using gdbserver.

Developers run GDB on a build system and connect to gdbserver over the network.

### Using CMake as a build system

Containing multiple source files, depend on other libraries, and be split into independent projects.

Cmake allow developers to define high-level rules and translate them into a lower-level build system, such as Unix make.

Cmake ( build system ) 

### Working with Different Architectures

**Attention!**

1. Using high-level programming languages that hide these complexities at the cost fo performance.

2. Their code runs on the x86 architecture

We should understand how to organize date in memory to get the most efficient use out of the CPU cache and operating system paging mechanisms.

#### 1. Exploring fixed-width integer types

#### 2. Working with the size_t type

#### 3. Detecting the endianness of the platform'

#### 4. Converting the endianness

#### 5. Working with data alignment

#### 6. Working with packed structures

#### 7. Aligning data with cache lines

### Technical requirements

Learning how to debug embedded applications int the ARM platform emulator.

Ubuntu Linux in a Docker container ( Build system ) 

Debian Linux in a QEMU ARM emulator ( Target system ) 

const : 변수를 상수값으로 초기화하고, 멤버 함수에서 객체의 멤버 변수를 변경하지 않기 위한 목적으로 사용되기 때문이다. / 중복 선언을 못하게 한다. 







