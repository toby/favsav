# favsav

`favsav` is a quick and dirty bash script that downloads your Twitter favorites/likes.

## Prerequisites

1. `egrep`
2. `wget`
3. An authorized `t` client: https://github.com/sferik/t

If you are having trouble authorizing t, see [this comment](https://github.com/sferik/twitter/issues/878#issuecomment-401299182).
It worked for me.

## Usage

`./favsav`

If `t` is properly authorized, it should start to download many things. In the end you'll have a few artifacts:

* `favs.txt` - All of your favorites in text format
* `links.txt` - Extracted links
* `media.txt` - Twitter image links
* `./media/*` - Downloaded Twitter images
* `./links/*` - Downloaded links
