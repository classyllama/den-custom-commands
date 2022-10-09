# Classy Llama Den Custom Commands

Custom commands that can be used on a per-environment basis to aid in
setup, installation, and synchronization of live or stage environments
to your local dev environment.

## Quick Installation

Just copy the contents of the .warden directory to your local project
environment root. The simplest way to do that is to run the following 
command from your project's root directory:

```
git archive --format=tar --remote=git@github.com:classyllama/den-custom-commands.git main .warden | tar -x
```
