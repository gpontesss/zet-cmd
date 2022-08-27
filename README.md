# zet

A minimalist script to manage a Zettelkasten repository. It's a basic wrapper
around a git repository that makes it easier to create notes and search through
text contained in notes. It also provides a tagging system for notes that can be
used for searching and indexing.

## Installation

To install it:

```shell
git clone https://github.com/gpontesss/zet-cmd.git
cd zet-cmd/
sudo ./zet install
```

After that, it should be available in your global `PATH`.

## Usage

```shell
# Creates a repository to store 
zet init

# Configure your personal git remote to upload your zettels
zet remote add origin <URL>

# Creates a new zettel and prompts its editting
zet new

# Opens buffer to add notes to be latter incorporated in real zettels
zet buff

# Syncs unstaged changes with remote (main remote is 'origin')
zet sync
```

## Planned

+ I mainly use vim. I want to create a plugin that it's easy to integrate with
    the environment managed by the script;
+ Implement tag filtering;
+ Implement fuzzy search.
