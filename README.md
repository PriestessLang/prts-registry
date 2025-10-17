# PRTS Registry

This is the official Git-based registry for the Priestess programming language.
Packages are listed under `/index/` and can be browsed manually or via the `priest` package manager.

To add a new package:
1. Publish the `.tar.gz` source to [prts-packages](https://github.com/<PriestessLang>/prts-packages/releases).
2. Append a new line to the appropriate file in `index/<letter>/<packagename>` with version metadata.
