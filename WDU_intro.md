# What is Watson Document Understanding?

Watson Document Understanding is a standard embeddable library designed to be the primary delivery method for state-of-the-art document conversion in IBM products. It is an inner source library built on top of the best AI OSS enhanced with input from Research, Watson Discovery, Automation and GBS. Watson Document Understanding is a component of Watson Core, and it is developed under Watson Core’s inner source model.

Watson Document Understanding was initially announced in 2019.

## Components
WDU consists of many components:

### ADR

ADR (Architecture Decision Records) captures key decisions having to do with anything architectural in a way that promotes better communication than simple word-of-mouth.

### GTE

GTE (Global table extractor) is a framework for joint table identification and cell structure recognition using visual context

### IOCR
IOCR is the component in WDU which produces the OCR result in JSON format.

## Basic Configuration

There are several options in running WDU.

1. Run the WDU Library directly. This requires a Python 3.11 setup, and a full install of WDU and all it's dependent libraries. This allows direct interaction with the module interfaces and data objects.

2. Run WDU as a server, and interact with it's REST or gRPC api.

3. Run WDU as a developer in an IDE, with cloned github repositories, and debugging capabilities.
 - Run in PyCharm
 - Run in VSCode


