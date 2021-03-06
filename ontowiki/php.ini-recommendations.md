---
title: Setting in php.ini
tags: [ontowiki, install]
sidebar: ontowiki_sidebar
permalink: /php.html
editme_path: ontowiki/php.ini-recommendations.md
---

You should set up your PHP environment with the following settings in php.ini:

  * `max_execution_time = 120`
  * `memory_limit = 128M`
  * `upload_max_filesize = 16M ; depending on the size of knowledge bases you plan to use`
  * `post_max_size = 16M`
  * `short_open_tag = Off`; if you have this turned on, some features will not work (especially `<?xml` will cause trouble)

To get rid of strict warnings, set the default timezone for your server, e.g.

  * `date.timezone=Europe/Berlin`
