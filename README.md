
# TensorFlow Lite Micro Library for Arduino mbed_nano

## Overview

This is a port of the TensorFlow Lite Micro Library to the Arduino mbed_nano platform, aimed at enabling Tiny Machine Learning (TinyML) experiments on Arduino Nano 33 BLE boards.

## Compatibility

- **Supported Boards**: Arduino Nano 33 BLE
- **Other Boards**: Compatibility with other Arduino boards is not guaranteed and may require additional adaptations.

## Resources

The Arduino Nano 33 BLE boards have sufficient resources to host TensorFlow Lite (TFLite) models.

## Experimental Nature

Please note that this library is experimental and has some differences from the typical Arduino library style.
It is similar to older and outdated Arduino_TensorFlowLite Micro example library, published in 2019 and referred by Arduino tutorials, but It has been regenerated from main TFLite Micro Library and is updated.

## Features

- **TensorFlow Lite Interpreter**: Allows instantiation of a TensorFlow Lite interpreter.
- **Memory Allocation**: Allocates space for the Tensor Arena and for input and output tensors.
- **Inference Operations**: Enables the execution of inference operations.

## Getting Started

For more details on how to use this library, refer to the `hello_world` example included in the repository.


