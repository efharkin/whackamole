# How to play Whack-A-Mole with `git`

## Instructions

1. Clone this repository.
2. Attempt to get a clean working tree in `git status`.
3. Enjoy playing Whack-A-Mole!

## Explanation

This repo was created on a Linux server. Linux OSs usually use case-sensitive
file systems, so having a pair of files named `Mole` and `mole` is perfectly
legal. Windows file systems are not case-sensitive, and the current Apple file
system (APFS) is case-insensitive by default (although this can be changed by
reformatting), causing strange things to happen to the pair of files in this
repo.

## Solution

Add `-f`/`--force` flag to `git rm`, `git add`, or `git mv` commands to resolve
the conflict.

