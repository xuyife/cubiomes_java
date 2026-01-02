# cubiomes-java: Java Bindings for Cubiomes Library

[![Java CI with Maven](https://github.com/xuyife/cubiomes-java/actions/workflows/build.yml/badge.svg)](https://github.com/xuyife/cubiomes-java/actions/workflows/build.yml)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.cubiomes/cubiomes-java.svg?label=Maven%20Central)](https://central.sonatype.com/artifact/com.github.cubiomes/cubiomes-java)
[![GitHub release](https://img.shields.io/github/v/release/yourusername/cubiomes-java)](https://github.com/yourusername/cubiomes-java/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JDK](https://img.shields.io/badge/JDK-23%2B-blue)](https://jdk.java.net/23/)

Java language bindings for the [cubiomes](https://github.com/Cubitect/cubiomes) library, a high-performance Minecraft world seed finder and biome generator. Generated automatically using Project Panama's [jextract](https://github.com/openjdk/jextract) tool, providing native-like performance with Java convenience.

## Features

- **Full API Coverage**: Complete Java bindings for all cubiomes functions
- **Multi-Platform**: Pre-built libraries for Linux, macOS, and Windows
- **Type Safety**: Generated Java bindings with proper type mappings
- **Modern Java**: Built with JDK 23+ and Project Panama FFI API
- **Easy Integration**: Maven/Gradle dependency with automatic native library loading

## Prerequisites

- **JDK 23 or higher** (required for Project Panama FFI)
- **Maven 3.6+** or **Gradle 7+**
- **Native libraries** (automatically handled for major platforms)

## Installation

### Maven

```xml
<dependency>
    <groupId>com.github.cubiomes</groupId>
    <artifactId>cubiomes-java</artifactId>
    <version>1.0.0</version>
</dependency>
