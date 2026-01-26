# FileTug

Modern CLI file browser/picker with neat UI (open source: go/tview)

## Why FileTug and not MC/ranger/etc.?

> Other file managers show what files exist. Users want to know what those files are.

### Key Differentiators:

- It is fast!
    - Non-blocking progressive UI (_that pulls data in the background_).
    - Predictive pre-fetching
    - Caching of data for network resources (_with in-background refresh_)
- Smart summarizer that provides a concise overview of directory contents
- Smart previewers showing summary and key info for a file
- Quick selection of files and directories by mask with a collection of named patterns
- Quick navigation to favorite, frequently used, and recent directories
- Build-in git client that provides git status and allows to stage/commit/rollback/etc.
- Log viewer with milestones

## Installation

```shell
brew tap filetug/filetug
brew install filetug 
```

## Usage

To start in the current directory:

```shell
ft
```

To start at the specific directory or file:

```shell
ft <PATH_TO_DIRECTORY_OR_FILE>
```

## Repositories:

- https://github.com/filetug/filetug
