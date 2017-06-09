title: "New Hyper.sh Features: June 2017"
date: 2017-06-09 17:00:00 +0800
author: Hyper Crew
tags:
    - Docker
    - Local Load
    - Invoicing
    - Hyper
preview: Two new heavily requested features are out today!

---

# Two heavily requested features released

## hyper "load local image"

A lot of users have been asking about how they can 'load' images from their local machine directly to Hyper.sh.

To solve this issue we have extended the functionality of ```hyper load``` so you can now load from STDIN, a local tar or a local image.

**Load image from STDIN: (similiar with push, only upload the diff)**

```$ cat helloworld.tar | hyper load```


**Load image from local tar archive file: (similiar with push, only upload the diff)**


```$ hyper load -i helloworld.tar```

**Load a local image: (similiar with push, only upload the diff)**

```$ hyper load -l helloworld:latest```


Check the full docs here: [https://docs.hyper.sh/Reference/CLI/load.html](https://docs.hyper.sh/Reference/CLI/load.html)

## Print view for invoices

Slightly less spectacular but still very important, many users wanted a specific print view for invoices, so we made one. :-)

Check it out in the console: [https://console.hyper.sh/](https://console.hyper.sh/)

As always, Happy Hacking!

The Hyper Crew
