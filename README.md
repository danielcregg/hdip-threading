# HDip Threading

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A collection of Java multithreading examples designed for the Higher Diploma in Software Development program at ATU (Atlantic Technological University). These examples demonstrate core threading concepts from basic thread creation to inter-thread communication.

## Overview

This repository contains a set of progressively structured Java examples that illustrate how to work with threads in Java. It covers both the `Thread` class extension and `Runnable` interface approaches, along with practical demonstrations of thread lifecycle management, sleep/interrupt handling, and concurrent execution patterns.

## Features

- **Thread Class Extension** -- Creating threads by extending the `Thread` class (`ThreadDemo`, `GuessANumber`, `Worker`)
- **Runnable Interface** -- Implementing the `Runnable` interface for thread creation (`RunnableDemo`, `Jabber`, `ThreadMaker`)
- **Thread Lifecycle** -- Starting, sleeping, joining, and interrupting threads
- **Concurrent Execution** -- Running multiple threads simultaneously with `PrintChar` and `PrintNum`
- **Thread Communication** -- Demonstrating how threads interleave output and share execution time
- **Practical Examples** -- Includes a number guessing game, countdown timer, and character/number printing demos

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- A Java IDE (e.g., IntelliJ IDEA, Eclipse, VS Code) or command-line tools

## Getting Started

### Installation

```bash
git clone https://github.com/danielcregg/hdip-threading.git
cd hdip-threading
```

### Usage

Each example is organized in its own package under `threadspackage/`. To compile and run an example:

```bash
# Compile a specific example
javac threadspackage/firstThread/firstThread/MyFirstThread.java threadspackage/firstThread/firstThread/Worker.java

# Run the example
java ie.atu.threadspackage.firstThread.firstThread.MyFirstThread
```

**Available Examples:**

| Package | Driver Class | Description |
|---------|-------------|-------------|
| `firstThread/firstThread` | `MyFirstThread` | Basic thread creation with a worker thread |
| `firstThread/charNum` | `TestThreads` | Concurrent character and number printing |
| `ThreadDemo` | `ThreadDemoDriver` | Thread class extension with countdown |
| `RunnableDemo` | `RunnableDemoDriver` | Runnable interface implementation |
| `Jabber` | `JabberDriver` | Concurrent string output with sleep |
| `GuessName` | `ThreadClassDemo` | Multi-threaded number guessing game with join |
| `ThreadMaker` | `ThreadMakerDriver` | Sequential output using thread sleep |

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Java | Core programming language |
| Java Threads API | Multithreading and concurrency |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
