# FileTug - Modern CLI file browser/picker with neat UI

**Open source repository**: https://github.com/filetug/filetug

## Why FileTug and not MC/ranger/etc.?

> Other file managers show what files exist. Users want to know what those files are.

### Key Differentiators
<table>
    <tr>
        <td width="25%">
            <img src="https://github.com/filetug/filetug/blob/main/docs/filetug-avatar1.png?raw=true" lt="FileTug avatar"/>
        </td>
        <td>
            <ul>
                <li>
                    - It is fast!
                    <ul>
                        <li>- Non-blocking progressive UI (_that pulls data in the background_).</li>
                        <li>Predictive pre-fetching</li>
                        <li>Caching of data for network resources (_with in-background refresh_)
                    </ul>
                </li>
                <li>Smart summarizer that provides a concise overview of directory contents</li>
                <li>Smart previewers showing summary and key info for a file</li>
                <li>Quick selection of files and directories by mask with a collection of named patterns</li>
                <li>Quick navigation to favorite, frequently used, and recent directories</li>
                <li>Build-in git client that provides git status and allows to stage/commit/rollback/etc.</li>
                <li>Log viewer with milestones</li>
            </ul>
        </td>
    </tr>
</table>

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
