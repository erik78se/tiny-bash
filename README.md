# Overview

A tiny charm.

It uses "hooks only" to deploy.

See: https://docs.jujucharms.com/2.5/en/reference-charm-hooks

## What it does

 * Executes the hooks in the hooks directory as part of the juju event cycle.

Check out the 'hooks' directory to learn.

# Usage

```
charm pull cs:~erik-lonroth/tiny-bash  && juju deploy ./tiny-bash
```

# Configuration

None

# Contact Information

Erik Lönroth <erik.lonroth@gmail.com>
