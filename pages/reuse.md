---
layout: page
title: Reuse the Collection
permalink: /reuse/
collection: polish
---

All materials presented in the collection are accessible online in public domain, thanks to digitization efforts of[Jagiellonian Library in Kraków](https://jbc.bj.uj.edu.pl) and [Polona, digital section of National Library in Warsaw](polona.pl).

Wax is inspired by [FAIR data principles](https://journal.code4lib.org/articles/13427), and as such strives to make its collections findable, accessible, interoperable and reusable.

The demo site comes with a specific `_include` called `interactive_metadata_table` to help you make pages like this one complete with interactive [DataTables](https://datatables.net/) and downloadable CSVs of collection metadata.

{% include interactive_metadata_table.html collection=page.collection %}
