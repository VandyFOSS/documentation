````
-----------------------------          _______  _______  _______  _______ ------------------------------
-----------------------------|\     /|(  ____ \(  ___  )(  ____ \(  ____ \------------------------------
-----------------------------| )   ( || (    \/| (   ) || (    \/| (    \/------------------------------
-----------------------------| |   | || (__    | |   | || (_____ | (_____ ------------------------------
-----------------------------( (   ) )|  __)   | |   | |(_____  )(_____  )------------------------------
----------------------------- \ \_/ / | (      | |   | |      ) |      ) |------------------------------
-----------------------------  \   /  | )      | (___) |/\____) |/\____) |------------------------------
-----------------------------   \_/   |/       (_______)\_______)\_______)------------------------------
                                   Vanderbilt Free & Open Source Society
````                                             

<p align="center"><strong>Welcome to VFOSS</strong></p>

## Getting Started

If you're new, read our [Guide for New Members](NEW_MEMBER_GUIDE.md).

If you're not, continue below to our Projects List.

# Projects List

Listed here are the open source issues that you can work on. Click here to [claim an issue](#claim-an-issue) or [add an issue](#add-an-issue).


| Technology | Title | Brief Description | Link   | Member     | Difficulty |
| ---        | ---   | ---               | ---    | ---        | ---        |
| Python | urljoin| urljoin does not follow Internet Standard when resolving relative path in edge case | [link](https://bugs.python.org/issue37235) | [Viet Than](https://github.com/VietThan) | 2 star |
| Nix | Typo | Typo: on or the other -> one or the other | [link](https://github.com/NixOS/nixpkgs/blob/master/pkgs/tools/virtualization/nixos-container/nixos-container.pl) |  | 1 star |
| Nix | bashInteractive | Make bashInteractive default | [link](https://github.com/NixOS/nix/issues/2965) [link](https://github.com/NixOS/nix/pull/3107) |  | 1 star |
| Ghidra | documentation | Reword last sentence of README.md so that it's understandable | [link](https://github.com/NationalSecurityAgency/ghidra) |  | 0 star |
| Alacritty | UX fix | Clear search buffers on mode toggle | [link](https://github.com/alacritty/alacritty/issues/3290) |  | 1 star |
| Alacritty | Scrollback | Scrollback doesn't work when the output is ongoing | [link](https://github.com/alacritty/alacritty/issues/3290) |  | 1 star |
| Rust | Scrollback | Significantly decrease the number of lints when running cargo clippy. We are attempting to change how unicode number codes are represented. Figure out what the code is doing and change the way numbers are outputed.|  |  | >2 star |
| GatsbyJS | Documentation | Gatsby docs need to be updated.change how unicode number codes are represented. requires replacing mentions of `data.json` with `page-data.json`. | [link](https://www.gatsbyjs.org/docs/html-generation/) |  | >2 star |



## :tada: Merged PRs :tada:

| Technology | Title | Brief Description | Link   | Member     | Difficulty |
| ---        | ---   | ---               | ---    | ---        | ---        |
| NixOS | typo | fix typo | [link](https://github.com/NixOS/nix/pull/3173) | [Matt K](https://github.com/mkenigs) | 1 star |
| NixOS | syntax | change deprecated attribute syntax in run examples | [link](https://github.com/NixOS/nix/pull/3190) | [Matt K](https://github.com/mkenigs) | 1 star |
| NixOS | arguments | environment fixes in run | [link](https://github.com/NixOS/nix/pull/3191) | [Matt K](https://github.com/mkenigs) | 3 star |
| Rust | documentation | Fixed documentation within c_str::from_ptr | [link](https://github.com/rust-lang/rust/pull/64326) | [Hunter](https://github.com/hman523) | 2 star |
| Rust | Optimization | (1) we do not have to worry about a possible negative number. (2) max from the children isn't updated correctly | [link](https://github.com/rust-lang/rust/pull/64326) | [Hunter](https://github.com/hman523) | 3 star |
| VS Code | Optimization | Removes redundant flags from tsconfig.base.json | [link](https://github.com/microsoft/vscode/pull/91050) | [Hunter](https://github.com/hman523) | 3 star |




# TO BE AMENDED

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
