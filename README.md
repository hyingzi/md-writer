# Markdown-Writer for Atom

Adds tons of features to make [Atom](https://atom.io/) a even better Markdown editor!

Works great with static blogging as well. Try it with [Jekyll](http://jekyllrb.com/), [Octopress](http://octopress.org/), [Hexo](http://hexo.io/) and any of your favorite static blog engines.

![Insert Image](http://i.imgur.com/s9ekMns.gif)

More GIFs Here: [Create New Post](http://i.imgur.com/BwntxhB.gif), [Insert Reference Link](http://i.imgur.com/L67TqyF.gif), [Remove Reference Link](http://i.imgur.com/TglzeJV.gif).

## Notice

> From version `1.5.0`, the invasive key maps that come with package are removed.
>
> You can execute command `Markdown Writer: Create Default keymaps` to append the list of default keymaps to your keymap config file, then modify them based on your needs. Refer to [wiki][31ebd53f].

  [31ebd53f]: https://github.com/zhuochun/md-writer/wiki/Settings-for-Keymaps "Settings for Keymaps"

## Features

### Blogging

- **Create new post** with front matters ([setup required][ca8870d7]).
- **Create new draft** with front matters ([setup required][ca8870d7]).
- **Publish draft** moves a draft to post's directory with front matters (`date`, `published`) updated.
- **Manage tags and categories in front matters** ([setup required][9be76601]).
- **Site specific settings** ([view setup][1561ed4c]).

### General

- **Continue lists** when you press `enter`.
- **Insert link** (`shift-cmd-k`) and **automatically link to the text next time**.
  - Insert inline link.
  - Insert reference link with title. _Use `-` in title field to create an empty title reference link._
  - Remove link (and its reference) after URL is deleted.
  - Search published posts by title in your blog.
- **Insert image** (`shift-cmd-i`), auto-detect images' heights and widths, and optionally copy images to your site's images directory.
- **Insert table** (`markdown-writer:insert-table`), and a shortcut to **jump to next table cell** (`cmd-j cmd-t`).
- **Format table** (`markdown-writer:format-table`).
- **Toggle headings**: `ctrl-alt-[1-5]` to switch among `H1` to `H5`.
- **Toggle text styles**:
  - `code` (`cmd-'`)
  - **bold** (`cmd-b`)
  - _italic_ (`cmd-i`)
  - ~~strikethrough~~ (`cmd-h`)
  - `'''code block'''` (`shift-cmd-"`)
  - `<kbd>key</kbd>` (`cmd + k`)
  - `- unordered list` (`shift-cmd-U`)
  - `0. ordered list` (`shift-cmd-O`)
  - `> blockquote` (`shift-cmd->`)
  - `- [ ] task list` (`markdown-writer:toggle-task`)
- **Jumping commands**:
  - Jump to previous heading (`cmd-j cmd-p`)
  - Jump to next heading (`cmd-j cmd-n`)
  - Jump to next table cell (`cmd-j cmd-t`)
  - Jump to reference marker/definition (`cmd-j cmd-d`)
- **Markdown cheat sheet** (`markdown-writer:open-cheat-sheet`).
- **Correct order list numbers** (`markdown-writer:correct-order-list-numbers`).

  [ca8870d7]: https://github.com/zhuochun/md-writer/wiki/Quick-Start "Markdown-Writer Setup Guide"
  [9be76601]: https://github.com/zhuochun/md-writer/wiki/Settings-for-Front-Matters "Setup Tags/Categories/Posts"
  [1561ed4c]: https://github.com/zhuochun/md-writer/wiki/Settings#project-specific-settings "Project Specific Settings"

You can find and trigger all features in:

- Open Command Palette (`shift-cmd-P`), enter `Markdown Writer`
- Or, go to menubar `Packages -> Markdown Writer`.

## Installation

- In Atom, go to Settings (`cmd-,`) -> Install -> Search `Markdown Writer`.
- Or, run `apm install markdown-writer`.

## Setup

Go to Settings (`cmd-,`) -> Packages -> `markdown-writer` -> Settings.

> If you do not see any settings (due to a [Atom's bug][3ecd2daa]), please activate Markdown-Writer using command (e.g. `Open Cheat Sheet`). Close and reopen the Settings page.

[View setting explanations][7ddaeaf4] if you have any doubts.

[3ecd2daa]: https://github.com/atom/settings-view/issues/356 "Viewing a package's settings should activate it"
[7ddaeaf4]: https://github.com/zhuochun/md-writer/wiki/Settings "Settings"

To **manage tags/categories in front matter**, please [follow this setup](https://github.com/zhuochun/md-writer/wiki/Settings-for-Front-Matters).

## Project

- View [CHANGELOG][e45121fa] :notebook_with_decorative_cover:
- Bugs, suggestions & feature requests, [open an issue][e6ad7ed1] :octocat:
- Contributes to project, [view guide][ed53c4bd] :sparkles:
- License in [MIT][6a9a3773] :unlock:
- Shipped by [Zhuochun][41ae693b] :sunny: and [contributes][f303810e] :clap:

[e45121fa]: https://github.com/zhuochun/md-writer/blob/master/CHANGELOG.md
[e6ad7ed1]: https://github.com/zhuochun/md-writer/issues
[6a9a3773]: https://github.com/zhuochun/md-writer/blob/master/LICENSE.md
[41ae693b]: https://github.com/zhuochun
[ed53c4bd]: https://github.com/zhuochun/md-writer/wiki/Contribute
[f303810e]: https://github.com/zhuochun/md-writer/graphs/contributors
