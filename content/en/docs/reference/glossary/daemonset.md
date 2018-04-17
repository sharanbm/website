---
title: DaemonSet
id: daemonset
date: 2018-04-12
full-link: /docs/concepts/workloads/controllers/daemonset
tags:
- fundamental
- core-object
- workload 
---
 Ensures a copy of a {{< glossary_tooltip text="Pod" term_id="pod" >}} is running across a set of nodes in a {{< glossary_tooltip text="cluster" term_id="cluster" >}}.

<!--more--> 

Used to deploy system daemons such as log collectors and monitoring agents that typically must run on every {{< glossary_tooltip term_id="node" >}}.
