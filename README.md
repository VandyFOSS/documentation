See other files for getting started documentation. Current projects:

## Nix
* Typo: on or the other -> one or the other https://github.com/NixOS/nixpkgs/blob/master/pkgs/tools/virtualization/nixos-container/nixos-container.pl
* Make bashInteractive default per https://github.com/NixOS/nix/issues/2965 and https://github.com/NixOS/nix/pull/3107

## Ghidra
* Reword last sentence of README.md so that it's understandable

## Alacritty
* [#3304](https://github.com/alacritty/alacritty/issues/3304) Fix end of line errors while copying in block 
* [#3290](https://github.com/alacritty/alacritty/issues/3290) Clear search buffers on mode toggle
* [#3232](https://github.com/alacritty/alacritty/issues/3232) Scrollback doesn't work when the output is ongoing

## Urho3D
* Links:
  * <https://urho3d.github.io/>
  * <https://github.com/urho3d/Urho3D>
  * [Video review](https://youtu.be/p8A4OTtegIc)
* Todos:
  * Try out this game engine, learn how its scripting works and how it interfaces with the engine, then make a basic Minecraft clone to learn how the engine holds up and what it needs improvement on. Then we can fix some issues.
  * Ideas for improvements to the engine so far:
    * Needs better artist tools - will check after using the engine
    * Better ECS performance, i.e. [here](https://github.com/urho3d/Urho3D/blob/master/Source/Urho3D/Scene/LogicComponent.h), more data-oriented etc. 
  * Potentially, after learning how Lua works under the hood: mod Lua for the engine so it runs as compiled code essentially as a conversion to C++, to allow for optimized code, and then also support hot reload using LuaJIT which is already integrated into Urho3D. There are already comments on adding this feature: 
    * <https://discourse.urho3d.io/t/recompile-scriptfile-at-runtime/1961>
    * <https://discourse.urho3d.io/t/runtime-compiled-c-in-urho3d-aka-scripting-in-c/318>
    * <https://github.com/urho3d/Urho3D/issues/2488>
    * <https://github.com/urho3d/Urho3D/issues/1291>
* Side projects/goals:
  * Later: Implement a Haskell/Lisp scripting frontend for Urho3D?
  * Compare Urho3D to [Apecs](https://github.com/jonascarpay/apecs), a Haskell game engine
    * [A basic tutorial for Apecs](https://steemit.com/blog/@aas-sh/an-introduction-to-developing-games-in-haskell-with-apecs)

## Rust
* Significantly decrease the number of lints when running cargo clippy. We are attempting to change how unicode number codes are represented.
* Todo: Figure out what the code is doing and change the way numbers are outputed.

## Miscellaneous - feel free to add other projects or issues!
* [GatsbyJS](https://www.gatsbyjs.org)
  * [#14228](https://github.com/gatsbyjs/gatsby/issues/14228) Gatsby docs need to be updated. This [page](https://www.gatsbyjs.org/docs/html-generation/) requires replacing mentions of `data.json` with `page-data.json`.

## Merged PRs :tada:
* https://github.com/NixOS/nix/pull/3173
* https://github.com/NixOS/nix/pull/3190
* https://github.com/NixOS/nix/pull/3191
* https://github.com/rust-lang/rust/pull/64326
* https://github.com/rust-lang/rust/pull/64721
