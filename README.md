# shitter :shit:

A little Bash library for Twitter (WIP).

## What's possible right now?

Almost nothing. You can get the current trend list and write tweets.

## Example

```bash
#!/bin/bash

source shitter.sh

trends=`get_trends`
compose_tweet "Hi from over here!"
```
