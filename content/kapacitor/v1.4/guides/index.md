---
title: Guides
aliases:
    - kapacitor/v1.4/examples/
menu:
  kapacitor_1_4:
    name: Guides
    identifier: guides
    weight: 4
---

The following is a list of examples in no particular order that demonstrate some of the features of Kapacitor.
These guides assume your are familiar with the basics of defining, recording, replaying and enabling tasks within Kapacitor.
See the [getting started](/kapacitor/v1.4/introduction/getting_started/) guide if you need a refresher.

### [Calculate Rates across joined series + Backfill](/kapacitor/v1.4/guides/join_backfill/)

Learn how to join two series and calculate a combined results, plus how to perform that operation on historical data.

### [Live Leaderboard of game scores](/kapacitor/v1.4/guides/live_leaderboard/)

See how you can use Kapacitor to create a live updating leaderboard for a game.

### [Load Directory](/kapacitor/v1.4/guides/load_directory/)

Put TICKscripts, TICKscript templates and handler definitions in a directory,
from where they will be loaded when the Kapcitor daemon boots.

### [Custom Anomaly Detection](/kapacitor/v1.4/guides/anomaly_detection/)

Integrate your custom anomaly detection algorithm with Kapacitor.

### [Continuous Queries](/kapacitor/v1.4/guides/continuous_queries/)

See how to use Kapacitor as a continuous query engine.

### [Socket based UDF](/kapacitor/v1.4/guides/socket_udf/)

Learn how to write a simple socket based UDF.

### [Template Tasks](/kapacitor/v1.4/guides/template_tasks/)

Use task templates to reduce the amount of TICKscripts you need to write.

### [Reference TICKscripts](/kapacitor/v1.4/guides/reference_scripts/)

Some examples of TICKscripts built against common Telegraf plugin data.
