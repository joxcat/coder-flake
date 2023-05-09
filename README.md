# coder-flake
NOTE: You need `/bin/stty` as it's hardlinked, in the future it could be a good idea to wrap everything using [buildFHSUserEnv](https://nixos.org/manual/nixpkgs/stable/index.html#sec-fhs-environments)
Quickfix for NixOS: `sudo ln -s /run/current-system/sw/bin/stty /bin/stty`

[Coder](https://github.com/coder/coder), packaged as a Nix flake.

## Outputs
 - One binary corresponding to each supported platform and each licensing variant.
 - One container (Non-AGPL, linux-x86_64)
## TODO
 - Add support for cross-compiled containers
