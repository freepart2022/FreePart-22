
# **FreePart Source Code**
This folder contains the code of static analysis tool, kernel module and run-time support.

## **Static API Analysis Tool**
This part of code is related to the `static analysis` part.

We use the `ast` module of Python to analyze the target application's source code. 

`typed-ast` is used to extract API metadata from `.pyi` files in the framework libraries.

Detailed code are shown in [`static_analysis`](static_analysis).

## **FreePart_lib**
This folder contains the source code of FreePart's runtime support and instrumented frameworks part in the above figure. We instrument the frameworks instead of the target application to partition the programs into 4 different phases because it can reduce the complexity of program analysis and provide effective protections.

## **Kernel Module**
In section 2.1.2, we mentioned that FreePart uses a kernel module to block unintended syscalls. 

This folder contains the source code of a configurable kernel module.

Details are in [`kernel_module`](kernel_module).
