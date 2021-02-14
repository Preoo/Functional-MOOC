# What is this?

This repo contains files created and used while author tries/tried to learn some Haskell

GHC and other dev tooling are contained in Docker image created by Dockerfile,
located in this dir, and are to be used with VS Code Dev Container extension.

Usage and workflow:

    Start Docker in HyperV and make sure to whitelist this directory in

        Settings > Resources > File-sharing

    Use "Open this folder in container" feature to connect and happy hacking!

Source files are stored in host's filesystem and copied over. Same goes for git-repo.

## MOOC

Files for MOOC.git course material are cloned into haskell-mooc directory.
To work on this material, goto haskell-mooc/exercises directory and follow instructions
from course page and other material. 
