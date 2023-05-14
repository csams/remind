# What is this?

Create simple reminders from the CLI.

## Examples

Durations default to seconds:
```bash
remind 3 do the thing
```

The duration is passed to [sleep][sleep], so use units it accepts. E.g. minutes are like this:
```bash
remind 30m stop reading
```

# Install

Copy `src/*` into a directory in your `$PATH`.

# Prerequisites

- autorandr
- xcowsay


[sleep]: https://www.man7.org/linux/man-pages/man1/sleep.1.html
