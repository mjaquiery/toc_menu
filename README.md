# toc_menu

Crawl an Rmd HTML page and insert a bootstrap-themed navigation menu.

Includes a minimum-length example .Rmd file and the corresponding .html output.

Usage:

Include toc_menu.html in your project folder and include it in the html output as shown below.

```yaml
---
title: "Your Title"
author: "Your Name"
date: "13 December 2018"
output: 
  html_document:
    includes:
      after_body: toc_menu.html
---
```

Produces:

A fixed navigation menu at the top of the output HTML page as shown [in the demo](https://mjaquiery.github.io/toc_menu/demo).
