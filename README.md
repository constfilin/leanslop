<p align="center">
  <img src="logo.svg" alt="LeanSlop" width="500"/>
</p>

<p align="center">
  <em>slop slop slop slop slop</em>
</p>

---

# LeanSlop: 
LeanSlop is a fork of [leanslop](https://github.com/kiranandcode/leanslop) by @kiranandcode except that
instead of calling a standalone curl binary, it uses [leancurl](https://github.com/bergmannjg/leanCurl) 
to talk to LLMs.

Please read [leanslop README](https://github.com/kiranandcode/leanslop/blob/main/README.md) to learn how
to setup leanslop. 

## Building

With [elan](https://github.com/leanprover/elan) installed, `lake build` should suffice.

## Adding LeanSlop to Your Project
To use LeanSlop in a Lean 4 project, first add this package as a
dependency. Add the following require in your `lakefile.toml`:
```toml
[[require]]
name = "leanslop"
git = "https://github.com/constfilin/leanslop"
```
You can see a complete example of in [HelloSlop](https://github.com/constfilin/helloslop)
The rest of the setup and configuration instrucations are the same as in the original 
[leanslop](https://github.com/kiranandcode/leanslop/blob/main/README.md)

Here's an example of leanslop in action:
<img width="1176" height="644" alt="image" src="https://github.com/user-attachments/assets/4e916198-3d6e-49e0-9dc4-914f8fc31f3d" />
