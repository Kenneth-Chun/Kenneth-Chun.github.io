---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Mobile Game Private Server Restoration"
date: 2026
published: true
labels:
  - Reverse Engineering
  - Network Protocols
  - Lua
summary: "Revived an abandoned open-source private server for a live-service mobile game by reverse-engineering network protocols to resolve client hang states."
---

<div class="text-center p-4">
  <img width="200px" src="../img/project/andriodplay.png" class="img-thumbnail" >
  <img width="200px" src="../img/project/applegames.png" class="img-thumbnail" >
</div>

<hr>

<pre>

This project involved reviving an abandoned open-source private server for a live-service mobile game. The original repository had stopped working because official client updates had deprecated the server's network protocols.

While the server could still establish a base connection with the game client, the request and response cycles were broken. Because the client wasn't receiving the correct data, it would hang indefinitely, such as freezing on the loading screen. 

To fix this, I utilized publicly available Lua scripts to identify the data structures the updated client was expecting. I monitored network traffic and analyzed multiple requests and responses to write new server-side handlers. Although I was able to map out the structure of the responses, my knowledge of the game's internal logic was limited, and I couldn't determine the exact values needed to make some responses completely valid. 

To get the game into a usable state, I implemented server-side handlers that sent back placeholder and mock data matching the known structures. This iterative process of capturing traffic, building new handlers, and mocking values was just enough to satisfy the client's parsing expectations, allowing it to bypass the login screen and achieve basic functionality.

</pre>

<hr>

