---
title: "From dict to DashTable: How Dragonfly cuts memory overhead by 40%"
url: "https://www.dragonflydb.io/blogfrom-dict-to-dashtable-how-dragonfly-cuts-memory-overhead-by-40"
date: "2026-07-30"
feed_url: "https://www.dragonflydb.io/feed.xml"
---
Redis doubles its hash table in memory before moving a single key. Dragonfly's DashTable grows one segment at a time and cuts memory overhead by 40%.
