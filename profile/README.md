[Latimer](https://www.latimer-lang.org) is a statically-typed interpreted programming language built for speed, safety, and clarity.

Latimer is designed from the ground up as a modern interpreted language that prioritizes clarity, safety, and developer experience. While it draws inspiration from statically typed and scripting languages, it is not bound by compatibility with any existing language like Python or C++. This freedom allows Latimer to introduce a strict type system, explicit semantics, and predictable execution behavior, without legacy compromises.

The current version of Latimer’s interpreter is a tree-walk interpreter, implemented in C++ and closely following C++’s runtime semantics. In the future, the goal is to build a dedicated virtual machine from scratch, decoupling Latimer’s execution model from its implementation language.

Unlike many scripting languages, Latimer enforces rules like explicit variable declarations and compile-time type checking, which help eliminate entire categories of bugs common in dynamic environments. It currently ships with no standard library, but the language is built to scale as a safe and expressive general-purpose tool.

Our main [latimer repository](https://github.com/latimer-lang/latimer) hosts source code for the language implementation and associated tooling. It includes binary releases and welcomes [contributions](https://github.com/latimer-lang/latimer/blob/main/CONTRIBUTING.md). It should also be used for [questions or discussions](https://github.com/latimer-lang/latimer/discussions) or for [filing bug reports](https://github.com/latimer-lang/latimer/issues).

We also have other repositories:
- [site repository](https://github.com/latimer-lang/site) hosts documentation for the language and is available at https://latimer-lang.org/. Pull requests improving documentation are always welcome!
