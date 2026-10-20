# bookmarker

Keep the bookmarks of every browser profile on every Linux machine in agreement with one plain-text file in a git repository, whose history is the history of your bookmarks.

- One file in your dotfiles repository holds every bookmark and folder, one line each, so `git log` and `git diff` show what changed and when.
- `sync` merges a browser profile with that file, shows real conflicts in bookmark terms, and writes the result back into the browser.
- No browser extension and no browser account: the tool reads and writes Chromium-based (`Bookmarks`) and Firefox (`places.sqlite`) profiles directly, with a verified backup before every write.

## Status

Design phase. There is no usable release yet.

## License

MIT
