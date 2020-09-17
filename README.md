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


See other files for getting started documentation. Current projects:

## Nix
* Typo: https://github.com/NixOS/nix/blob/6f3244ce4517cc51ef3ffd39025152aa7046ef69/src/libfetchers/registry.cc#L193
* Typo: https://github.com/NixOS/nix/blob/master/src/libexpr/flake/flake.cc#L369
* https://github.com/NixOS/nix/issues/3533
* Fixme: https://github.com/NixOS/nix/blob/master/src/libexpr/flake/flake.cc#L22
* ask @mkenigs for help and other good issues

## Nixpkgs
* New packages
  * [mozwire](https://github.com/NixOS/nixpkgs/pull/95754),
    [knightos-kcc](https://github.com/NixOS/nixpkgs/pull/95891),
    [kimg](https://github.com/NixOS/nixpkgs/pull/95890),
    [scas](https://github.com/NixOS/nixpkgs/pull/94165),
    [mkrom](https://github.com/NixOS/nixpkgs/pull/95842),
    [kpack](https://github.com/NixOS/nixpkgs/pull/95846),
    [knightos-mkrom](https://github.com/NixOS/nixpkgs/pull/97545)
* Enforce lower case names for executables (eg https://github.com/NixOS/nixpkgs/blob/1937fd3f1906e2c0909e889ddd31f2e77cbd8bfc/pkgs/applications/networking/instant-messengers/discord/default.nix#L8) and package names (eg https://github.com/NixOS/nixpkgs/blob/5897bf1f60dd488ee9513d4c9df42d8b5f48e63a/pkgs/misc/vscode-extensions/default.nix#L29)

## VSCode
* [#105935](https://github.com/microsoft/vscode/issues/105935): Interactive playground eats arrow keys 
* [#105730](https://github.com/microsoft/vscode/issues/105730): "Select all occurrences of find match" selects weirdly when word wrapping
* [#106123](https://github.com/microsoft/vscode/issues/106123): activeTerminal undefined for first terminal even when visible
* [#106746](https://github.com/microsoft/vscode/issues/106746): Notebook metadata - undefined means false

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
* https://github.com/NixOS/nixpkgs/pull/79783
* https://github.com/rust-lang/rust/pull/64326
* https://github.com/rust-lang/rust/pull/64721
* https://github.com/microsoft/vscode/pull/91050
* https://github.com/NixOS/nixpkgs/pull/95754
* https://github.com/NixOS/nixpkgs/pull/95891
* https://github.com/NixOS/nixpkgs/pull/95890
* https://github.com/NixOS/nixpkgs/pull/94165
* https://github.com/NixOS/nixpkgs/pull/95842
* https://github.com/NixOS/nixpkgs/pull/95846
* https://github.com/NixOS/nixpkgs/pull/97545
