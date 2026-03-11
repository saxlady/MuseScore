# MuseScore Repository Setup

## What is this?

MuseScore is an open-source music notation program. The official project lives on GitHub at
`musescore/MuseScore`. We've forked (made our own copy of) it so we can make personal changes
and keep them backed up online.

## GitHub Details

- **Your fork**: https://github.com/saxlady/MuseScore
- **Official repo**: https://github.com/musescore/MuseScore
- **Local folder**: ~/Projects/MuseScore

## How the remotes work

The local repo has two "remotes" (links to GitHub):

| Name       | Points to                          | What it's for                        |
|------------|-------------------------------------|--------------------------------------|
| `origin`   | git@github.com:saxlady/MuseScore   | Your personal fork — push changes here |
| `upstream` | musescore/MuseScore                 | The official project — pull updates from here |

- When you make changes, they get pushed to **origin** (your fork).
- When the official MuseScore project gets updated, you can pull from **upstream** to stay up to date.

## Folder structure

| Folder     | What's in it                                      |
|------------|---------------------------------------------------|
| `dev/`     | Development settings, config, and notes (like this file) |
| `plugins/` | Your personal custom MuseScore plugins            |
| `music/`   | Your MuseScore music files and scores             |

Everything else in the repo is the standard MuseScore source code.

## Outstanding local changes

These exist on your computer but haven't been committed yet:

- **Modified**: `src/framework/cmake/MuseCreateModule.cmake`
- **New plugins**: `share/plugins/mirror_layout/` and `share/plugins/mirror_markings/`
