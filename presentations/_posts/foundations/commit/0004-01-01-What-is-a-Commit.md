---
chapter: Commit
layout: slide
tags: ['commit']
---

<img class="diagram" src="assets/diagrams/git-commit-structure.png">

{% capture notes %}
* Git folder is a directory "database" of snapshots for every commit
* `.git` folder contains files, directories
* `.git` is the _entire_ repository
* `/objects` contains all commits, blob, trees
{% endcapture %}
{% include hydeslides/core/notes %}
