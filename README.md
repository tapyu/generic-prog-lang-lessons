### Compiled programming languages

A compiled programming language is a type of programming language in which the source code is translated into machine code or an intermediate code by a compiler before execution. The compilation process typically involves several stages, including lexical analysis, syntax analysis, optimization, and code generation. Here's a brief overview of the key concepts:

- **Source Code**: This is the human-readable code written by the programmer in a "high"-level programming language (e.g., C, C++, Java).
- **Preprocessing** (optional): In languages that use a preprocessor, the source code is processed before actual compilation begins. The preprocessor handles tasks such as macro substitution, file inclusion, and conditional compilation. It generates an intermediate human-readable code (the translation units), which is then passed to the compiler for further processing. Common tasks include including header files, macro substitution, and conditional compilation. Not all compiled programming languages have a preprocessor. It is a feature commonly found in languages like `C` and `C++`. Languages like Java or `C#` do not have a separate preprocessor stage as seen in `C` or `C++`. Instead, they rely on other mechanisms, like annotations in Java or attributes in `C#`, to achieve similar effects without a dedicated preprocessing step.
- **Compiler**: A compiler is a software tool that translates the entire source code of a program into either assembly language (human readable) or machine code (non-human readable). Some compilers directly generate machine code from the preprocessed code, skipping the generation of human-readable assembly code. In contrast, other compilers may generate intermediate code or assembly code before producing the final machine code. Anyway, the compiler performs various tasks, such as lexical analysis (breaking code into tokens), syntax analysis (parsing the structure of the code), optimization (improving the efficiency of the code), and code generation (producing machine code or assembly code).
- **Assembly** (optional): The generated assembly code is assembled into machine code or assembly code. This is typically done by an assembler.
- **Linking** (optional): In some compiled languages, the compiled code may need to be linked with other compiled code or libraries. Linking is the process of combining multiple compiled files into a single executable program.
- **Execution**: The compiled code is executed by the computer's hardware.

Key aspects of compiled programming languages:

- **Standalone Executables**: The output of compilation is often a standalone executable file, which can be run independently of the source code and the compiler. Therefore, we can share only the compiled executable, instead of sharing the source code. This enables source privacy, which may be desirable for some proprietary softwares. Although compiled executables may still depend on certain system libraries on the target machine, these dependencies are typically well-managed and often come bundled with the operating system or are distributed along with the application.
- **Efficiency**: Compiled programs are generally more efficient in terms of runtime performance compared to interpreted programs. Since the translation to machine code is done beforehand, there is less overhead during execution.
- **Ahead-of-Time (AOT) Compilation**: A classic compiled programming language is based on the Ahead-of-Time (AOT) Compilation, where compilation is a separate step that converts the source code into an executable machine code before the program runs.
- **Static typing**: Many compiled languages are statically typed, meaning that variable types are checked at compile time rather than runtime. This can catch certain types of errors before the program is run.
- **Reduced Portability**: Compiled programs often result in platform-specific executables. While this may reduce portability, it can lead to better performance optimizations tailored to the target platform.

Common examples of AOT compiled programming language are `C`, `C++`, `Rust`, `Fortran`, and `Go`.


### Interpreted programming languages

In interpreted programming languages, the source code is typically translated into an intermediate representation known as bytecode. The bytecode is a lower-level, platform-independent representation of the source code. This bytecode is then interpreted by a runtime environment or virtual machine, which executes the program.

- **Source Code**: The programmer writes source code in a high-level programming language.
- **Bytecode generation**: The source code is translated into an intermediate bytecode by a compiler or interpreter. Interpreted programming languages may have a compiler, but it plays a different role: this compiler is responsible for translating the high-level source code into an intermediate representation (bytecode), which is not specific to any particular machine architecture, whereas a compiler usually converts the source code into machine code in AOT-compiled programming languages.
- **Execution**: The bytecode is interpreted and executed by a runtime environment or virtual machine. The interpreter reads and executes the instructions in the bytecode line-by-line.

Key aspects of interpreted programming languages

- **Portability**: Since the interpreter runs on the host machine, code can be more portable across different platforms without the need for recompilation. We usually share the source code so that the other users' computer interpret it and execute the program.
- **Ease of Development**: Interpreted languages often provide a shorter feedback loop for developers. You can run your code immediately after writing it, without waiting for a lengthy compilation process.
- **Dynamic Typing**: Interpreted languages often use dynamic typing, allowing variables to change types during runtime.
- **Platform Independence**: Interpreted languages are often more platform-independent. As long as there is an interpreter for a particular platform, the same source code can run on different systems.

Examples: Python, Ruby, JavaScript, and PHP.

### Just-in-time (JIT) compiled programming language

Generaly, there are two categories of compilation:

- **Ahead-of-Time (AOT) Compilation**: The entire program is translated into machine code before execution. This is common in languages like C, C++, and Fortran.
- **Just-In-Time (JIT) Compilation** (also known as dynamic translation or runtime compilation): The source code is initially translated into an intermediate representation, often bytecode. This intermediate code is then executed by a virtual machine or runtime environment. However, rather than interpreting the bytecode directly, a Just-In-Time compiler translates parts of (or all) the bytecode into machine code on-the-fly, just before they are executed. This process is known as dynamic compilation. A system implementing a JIT compiler typically continuously analyses the code being executed and identifies parts of the code where the speedup gained from compilation or recompilation would outweigh the overhead of compiling that code.

The line between compiled and interpreted languages can sometimes blur, and many modern languages use a combination of compilation and interpretation techniques (e.g., Just-In-Time compilation). For instance, Matlab is primarily interpreted, as it executes scripts and commands directly without a separate compilation step. However, The MATLAB execution engine, introduced in R2015a, uses JIT compilation to accelerate some parts of the MATLAB code. JIT compilation generates native machine level code that is optimized for your MATLAB code and for specific hardware.

Sources:

- [learncpp][1]

[1]: https://www.learncpp.com/cpp-tutorial/introduction-to-programming-languages/