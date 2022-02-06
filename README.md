# Overview

The tiny-bash charm that use "hooks only" to deploy. Since its super small and only uses hooks, it deploys very fast.

## What it does

This charm just logs the hooks it runs. But doesn't do anything. Check out the logs with:

    juju debug-log 
	
## Deploy from charmhub

    juju deploy tiny-bash

## Deploy from  development host

Hook-only charms doesn't need to be built, so you can deploy straight from the directory:

    git clone git@github.com:erik78se/tiny-bash.git
    juju deploy ./tiny-bash

## Build  the charm

You can build the charm if you like with charmcraft:

    git clone git@github.com:erik78se/tiny-bash.git
	charmcraft build
    juju deploy ./tiny-bash.charm

# Contact Information

Erik Lönroth <erik.lonroth@gmail.com>

