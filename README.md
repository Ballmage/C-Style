# C# at Me Style Guide
This style guide is for C# code developed by me.

Rule summary:

Code

- Names of classes, methods, enumerations, public fields, public properties, namespaces: `PascalCase`.
- Names of local variables, parameters: `camelCase`.
- Names of private, protected, internal and protected internal fields and properties: `_camelCase`.
- Naming convention is unaffected by modifiers such as const, static, readonly, etc.
- For casing, a “word” is anything written without internal spaces, including acronyms. For example, `MyRpc` instead of MyRPC.
- Names of interfaces start with `I`, e.g. `IInterface`.

Files

- Filenames and directory names are `PascalCase`, e.g. `MyFile.cs`.
- Where possible the file name should be the same as the name of the main class in the file, e.g. `MyClass.cs`.
- In general, prefer one core class per file.
