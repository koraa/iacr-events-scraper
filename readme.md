# IACR Events Scraper

This scrapes https://iacr.org/events/ and exports it as a calendar file.

I host a version of this for myself under https://arrrr.cupdev.net/iacr-events/iacr-events.ics
(No warranty for accuracy or availability).

IACR now offers calendar on the [event site](https://iacr.org/events/). You might still
want to use this as this scraper produces submission and notification dates in the event description
and uses shorthand names for conferences, providing long names in the description.

The IACR calendar also gives some weird year long events (e.g. IFIP Summer School starting in 2020 ending in 2021)
which are clearly artifacts.

# Usage

Install [pipenv](https://pipenv.pypa.io) – the python dependency manager, use python three
and then execute the following:

```sh
pipenv install
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
