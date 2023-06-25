# Picoser

A minimalistic and streamlined serialization and deserialization library.

## Learning Rust and systems programming by implementing tiny programs that work

**Picoser** is a minimalistic and streamlined serialization and deserialization library. It's a nano Serde-like library.

When creating a nano Serde-like library, there are three key concepts in Rust that should be researched and adequately understood :

_Rust's **trait** system_: Traits are a fundamental concept in Rust that allow us to define shared behavior for types. In the context of serialization and deserialization, I'll need to explore how traits can be used to define the core serialization and deserialization functionality, such as Serialize and Deserialize. Through _Picoser_ I'll research how traits work, how to implement them for custom types, and how to leverage them for generic programming.

_Rust's **reflection** capabilities_: Reflection refers to the ability of a programming language to examine and manipulate its own structures, such as types and properties, at runtime. While Rust doesn't have built-in reflection like some other languages, I should be able to achieve similar functionality using libraries like **syn** and **quote**. I'll research how to use these libraries to perform code generation and manipulation based on Rust's syntax and types.

_Rust's **macros** system_: Macros in Rust allow us to write code that generates code, enabling powerful meta-programming capabilities. Understanding how to define and use macros is essential for creating a mini Serde-like library. I'll research the different types of macros in Rust, including declarative macros (macro_rules!) and procedural macros (#[derive] and custom attribute macros), and explore how they can be used to automatically derive serialization and deserialization implementations.
