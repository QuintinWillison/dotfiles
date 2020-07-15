# My dotfiles

This is a subset of the configuration files I have in place for day to day work on my macOS based work station.

## Structure

There's plenty of mechanisms out there for managing and maintaining repositories of dotfiles. Some are more opinionated than others and most infer a fair bit of structural overhead.

I've taken the approach of keeping things very simple, for now at least, opting to go down the manual route when it comes to migrating files or folders from my `$HOME` folder to this repository. I do this when the whim takes me or I explicitly want to share some part of my configuration with others.

## Adding dotfiles

Broadly speaking:

1. Move file or folder from `$HOME` to the root of this repository
2. Add installation step to the [`make-links`](make-links) script
3. Run the script at least two times
4. Git: `add`, `commit` then `push` to publish

Running the script twice is important, in particular when the dotfiles being added are a folder.
