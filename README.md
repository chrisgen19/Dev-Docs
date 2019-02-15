# Dev-Docs

### Dev Bookmarks

DevDocs combines multiple API documentations in a fast, organized, and searchable interface. Here's what you should know before you start:
- [devdocs.io](https://devdocs.io)

I'd love any ideas/feedback/thoughts, please open [an issue](https://github.com/TomAnthony/itermocil/issues) or create a [fork](https://github.com/TomAnthony/itermocil/fork) and send a pull request, like these wonderful people:

- [onthestairs](https://github.com/onthestairs)
- [jefftriplett](https://github.com/jefftriplett)
- [febLey](https://github.com/febLey)
- [rebeling](https://github.com/rebeling)
- [adityavarma1234](https://github.com/adityavarma1234)
- [chris838](https://github.com/chris838)
- [mattmartini](https://github.com/mattmartini)
- [glasnoster](https://github.com/glasnoster)
- [bitsapien](https://github.com/bitsapien)
- [galaxyutii](https://github.com/galaxyutii)
- [mbollemeijer](https://github.com/mbollemeijer)
- [mcky](https://github.com/mcky)

### Dev Rules

| Key        | Description
|------------|----------------------------
| `name`     | All iTerm panes in this window will be given this name.
| `root`     | The path where all panes in the window will be started
| `layout`   | The layout format that iTermocil will use (see below)
| `panes`    | An `Array` of panes
| `command`  | A command to run in the current window. Ignored if `panes` is present
| `commands` | An array of commands for run in the current window. Ignored if either `panes` or `command `is present
| `focus`    | This is currently unsupported in iTermocil