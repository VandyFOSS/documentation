See other files for getting started documentation. Current projects:

## Nix
* Typo: on or the other -> one or the other https://github.com/NixOS/nixpkgs/blob/master/pkgs/tools/virtualization/nixos-container/nixos-container.pl
* Make bashInteractive default per https://github.com/NixOS/nix/issues/2965 and https://github.com/NixOS/nix/pull/3107

## Ghidra
* Reword last sentence of README.md so that it's understandable

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

## Add your own!
Feel free to add projects or other issues here too.

## Merged PRs :tada:
* https://github.com/NixOS/nix/pull/3173
* https://github.com/NixOS/nix/pull/3190
* https://github.com/NixOS/nix/pull/3191
