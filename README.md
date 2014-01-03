# Resolve-Cli

Resolve path in command line.

## Installation

```
npm install -g resolve-cli
```

## Usage

Once the plugin has been installed, use it in command line:

```
resolve .
# /home/xxx/yyy/zzz/
```

```
resolve /tmp/abc/a.js
# /tmp/abc/a.js
```

```
resolve /tmp/abc ../ooo
# /tmp/ooo/
```