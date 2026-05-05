---
title: "Memory-Aware Rebalancing Is Now Automatic in Dragonfly Cloud"
url: "https://www.dragonflydb.io/blogmemory-aware-rebalancing-is-now-automatic-in-dragonfly-cloud"
date: "Tue, 28 Apr 2026 21:52:45 GMT"
author: ""
feed_url: "https://www.dragonflydb.io/feed.xml"
---
Most cluster rebalancing tools spread hash slots evenly by count, not by memory — which does nothing for a shard overloaded with large values. Dragonfly Cloud's shard memory balancing tracks utilization at the individual slot level and automatically redistributes slot ranges to eliminate memory hotspots.
