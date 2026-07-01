# 💬 Client Feedback Generator

Dont't waste time waiting for your client to tell you how big button is. This **Figma plugin**, it scans yours design and provied honest review in the form of sticky notes that get attached to canvas. Use is for laugh or use it as a way to stress test your design .

## What it does

The plugin truly **review your design**. It will examine logos and point out id they are too small. It can also identify buttons and comment on their color. All feedback are provided no matter how much unrelated it is.

The plugin has **Severity Levels** to ensure you don’t panic over every comment: ⚪ Nitpick, 🟡 Change Request, 🔴 PANIC. 

The plugin gives you some chasos created by client. You can mark comments as Addressed or Dismissed.

Each sticky note has Connector Line drawn back to element it review, so you will know where to focus

## How to install/try it

1. Download this repo, then run `npm install` and `npm build` in project folder terminal
2. In figma desktop: **Plugins -> Development -> Import plugin from manifest**, then select `manifest.json`.
3.Select part of your design and click on **Generate Feedback**