---
title: sequentiediagram
draft: true
tags:
  - mermaid
description: desc
date: 2024-01-01
aliases: 
difficulty: 1
---

er kunnen ook sequantie-diagrammen gemaakt worden. door een code block als type "mermaid" te zetten kunnen hier diagrammen in gemaakt worden.

stappen:
1. maak een code block met "mermaid" als type
2. geef binnen het blok het type diagram aan: "sequenceDiagram"
3. ==Alice->>+John: Hello John, how are you?==

```mermaid 
sequenceDiagram 
	Alice->>+John: Hello John, how are you? 
	Alice->>+John: John, can you hear me? 
	John-->>-Alice: Hi Alice, I can hear you! 
	John-->>-Alice: I feel great! 
```
- "You can create [internal links](https://help.obsidian.md/Linking+notes+and+files/Internal+links) in your diagrams by attaching the `internal-link` [class](https://mermaid.js.org/syntax/flowchart.html#classes) to your nodes."
-  A[Alice] B[John] + A ->> B