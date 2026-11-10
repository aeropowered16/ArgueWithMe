# /argue

Y- Yeah... that's the project name.

## Why did I make this?

Nano asked me to show people how to add their own commands to the harness later on.

This serves to show how.

## File Contents

- repl.ts: the file to patch the commands into
- argue.ts: the main command prompt logic
- argue.patch: the file that lets you apply the patch onto an existing repository

## Will I intergrate this?

No.

The Terrible-Harness repo is a template-turned project.

This is an optional feature.

## How do I install the patch?

Make sure you have the git version installed.

Copy the patch to the repo root, then `git apply --ignore-whitespace argue.patch`.

Then rebuild and link.
