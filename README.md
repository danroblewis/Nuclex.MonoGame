# Nuclex.MonoGame

The GUI (`Nuclex.UserInterface`), input (`Nuclex.Input`) and support
(`Nuclex.Support`) libraries of the Nuclex Framework (Markus Ewald,
nuclex.org, revision 1404 for XNA 4.0) ported to MonoGame 3.8 DesktopGL,
merged into one assembly.

* Namespaces, types and members keep their original names, so XNA-era code
  using Nuclex compiles unchanged.
* DirectInput/SlimDX, window-message input, Xbox/Zune paths and the test code
  are removed; keyboard, mouse and text input come from MonoGame
  (`Keyboard.GetState`, `Mouse.GetState`, `GameWindow.TextInput`).
* The "Suave" skin, its XSD and fonts are embedded as before.
* Every change to the library is listed in `NUCLEX-PORT-NOTES.md`.

License: IBM Common Public License 1.0 (`LICENSE-CPL.txt`), as the original.

```
dotnet add package Nuclex.MonoGame
```

Built for the [Vexillum](https://github.com/buildist/Vexillum) port.
