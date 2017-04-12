GumTree merge driver for Git
============================

## Setup

1. Download GumTree with Merge Client from https://github.com/Mikulas/gumtree/releases/tag/2.1.0-merge
2. Extract the archive and note the path to `gumtree` binary
3. In your Git repository, update your `.git/config` according to the example above. Replace "path-to-gumtree" with the real path.
4. Copy the merge driver into `.git/gumtree-driver` (also in your git repository)
5. Finally, apply `.gitattributes` changes to enable the new merge driver.

## Usage

After the initial setup, merging is completely transparent. Git will automatically invoke the GumTree merge driver when attempting a merge of two php files.
