# **Windows Il2Cpp Dumper**

A powerful tool designed to dump games utilize the il2cpp export name `"il2cpp_domain_get_assemblies"`—even when it’s protected.

## **Features**

- **Dumping of Constant Fields**  
  Extracts constant fields such as strings, booleans, and numeric types.

- **Numeric Field Extraction**  
  Dumps various numeric field types, including:
  - `int16`, `int32`, `uint16`, `float`, `double`, etc.

- **Supports Generic Types**  
  Includes the ability to dump:
  - `Dictionary<TKey, TValue>`
  - `List<T>`
  - `KeyValuePair<TKey, TValue>`
  - And more...

## **Credits**

- **Sxitxma** – Developer of the improved dumper.
- **Nullbit** – Contributor to the `GetProtectedExportName` function.
- **Perfare** – Original creator of the dumper.
