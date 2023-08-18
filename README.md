# BPM-Templates

A collection of Templates i use when downloading from BPM

This repo should give an idea about how templates can be created but also give an idea about how you can make your own centralized repo like this one to keep a track of all of your templates and to maintain them in a single repo.

# IMPORTANT

currently moving files is problmatic as the last set file into every possible location.
Most likely an issue with BPM so the recommended way of downloading templates from here is to use the manual usage.

Should now be fixed with bpm => v1.1.3

# Usage

1. Clone this repo

> for automatic usage

2. place `BPM-Templates` in `$HOME/.local/share/BPM/repos/`

3. run `bpm -d BPM-Templates`

> for manual usage

2. place the wanted templates in `$HOME/.local/share/BPM/repos/`

3. run `bpm -d <template in $HOME/.local/share/BPM/repos/>`

# Updating

if BPM-Templates requires updating run `bpm -U BPM-Templates` before updating any other packages, if it doesn't need an update you can update as usal with `bpm -u` or `bpm -U <package name>`
