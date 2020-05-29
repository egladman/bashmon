# bashmon

Watch for file changes in a static site (or web app) and automatically trigger a command.

### Dependencies

- Bash 4.4+
- Coreutils

### Example

Watch for changes in files that have the following extensions: `.html`, and `.conf`. Runs `<command>` if a change is found.
```
bashmon "html conf" "<command>"
```

### Install

```
git clone https://github.com/egladman/bashmon.git
cp bashmon/bashmon /usr/local/bin/bashmon
```
