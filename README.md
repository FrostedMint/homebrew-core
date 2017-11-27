# homebrew-mpv 🌺

This tap contains formulae for building mpv using ffmpeg-mpv.

To quickly resolve merge conflicts for deleted files when merging
homebrew-core, use:

```sh
$ git status --porcelain | awk '{if ($1=="DU") print $2}' | xargs git rm
```
