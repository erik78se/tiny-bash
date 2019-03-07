# Overview

A tiny bash (non reactive) charm that demonstrates the "hook" concept for Juju.

This charm runs on pretty much any linux distro.

## What it does

 * Acts on the hooks in the hooks directory as part of the juju event cycle.

This charm is for practice and study only. Its really not very useful for other that this.

# Usage

```
charm pull cs:~erik-lonroth/tiny-bash  && juju deploy ./tiny-bash
```

# Configuration

None


# Contact Information

Erik Lönroth <erik.lonroth@gmail.com>
