# Tor Project Website

This is the repository of Tor Project website. The current online version of this portal can be found at [https://torproject.org](https://torproject.org) or [Tor Project Onion Service](http://2gzyxa5ihm7nsggfxnu52rck2vv4rvmdlkiu3zzui5du4xyclen53wid.onion/).

To clone the code use either of

```git clone https://git.torproject.org/project/web/tpo.git/```

```torify git clone http://xtlfhaspqtkeeqxk6umggfbr3gyfznvf4jhrge2fujz53433i2fcs3id.onion/project/web/tpo.git/```

or browse it [online](http://gitweb.torproject.org/project/web/tpo.git).

## How to report bugs or feedback

First, check if the bug is already known. You can search and read all the issues at https://gitlab.torproject.org/. To create a new issue, please [request a new account](https://gitlab.onionize.space/) to access Tor Project's GitLab instance and [find the right repository](https://gitlab.torproject.org/tpo) to report your issue. Issues related to our websites should be filed under the [Web issue tracker](https://gitlab.torproject.org/groups/tpo/web/-/issues).

## What is Lektor

[Lektor](https://www.getlektor.com/) is a framework to generate and serve websites from Markdown files.

Its code can be found at [GitHub](https://github.com/lektor/lektor).

## How to contribute

### (Easy) Edit this page button

You can click ```Edit this page``` and submit your content changes in a [Pull Request in GitHub](https://github.com/torproject/community/pulls).

### (Advanced) Compiling a local version of the website

1. Download and install Lektor: https://www.getlektor.com/downloads/

2. Install the lektor-i18n plugin and its [dependencies](https://github.com/numericube/lektor-i18n-plugin#prerequisites).

3. Clone the repository:

```git clone https://git.torproject.org/project/web/tpo.git```

4. Init the building blocks submodule:

```$ cd lego && git submodule update --init --recursive```

5. Translations for the website are imported by Jenkins when bulding the page, but if you want to test them, download the correct branch of the translations repo to the ./i18n/ folder.

6. Finally

To run a local continuous builder: ```$ lektor server```

To just build the website once: ```$ lektor build -O <folder>```

#### How to develop on the website

Check our [wiki pages](https://gitlab.torproject.org/web/community/wikis/How-to-develop-on-the-website).

### Translations

To help us to translate, please join the Tor Project team in [Transifex](https://www.transifex.com/).


### Getting help

If you want to contribute to the Tor Project website, we will be happy to help you. Join us at #tor-www in [irc.oftc.net](https://www.oftc.net).
