# IACR Events Scraper

This scrapes https://iacr.org/events/ and exports it as a calendar file.

I host a version of this for myself under https://arrrr.cupdev.net/iacr-events/iacr-events.ics
(No warranty for accuracy or availability).

# Usage

Install [pipenv](https://pipenv.pypa.io) – the python dependency manager, use python three
and then execute the following:

```sh
pipenv run scrape
```

Use shell redirection to mask debug output or write to a file.

```sh
pipenv run scrape > iacr-events.ics 2>/dev/null
```

# Copying

![](./cc0-8x31.png)

Copyright (C) 2021 by Karolin Varner. Licensed under [CC0 V1.0](http://creativecommons.org/publicdomain/zero/1.0/).
You may copy and use in any way but entirely on your own risk.
