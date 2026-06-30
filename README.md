# 💬 Client Feedback Generator

Why wait for clients to give feedback about their button sizes? Cut out the middleman! This satirical **Figma plugin** scans what you are working on and attaches brutally honest (but totally… familiar) “client feedback” to your canvas in the form of sticky notes. Use it to enjoy a good laugh or to stress-test your designs before showing them to a real client!

## What it does

**Really evaluates your design** - will find logos and tell you to increase their size, locate buttons and lament about their hue, that type of thing. The comments, no matter how random the original comment appears to be, are based on what is actually present within the design.
**Severity Levels**, as not every comment will produce a similar level of panic: ⚪ Nitpick, 🟡 Change Request, 🔴 PANIC.
 **Lets you manage the chaos** — mark notes as Addressed or Dismissed, or just nuke them all with the bulk action buttons.
- **Draws connector lines** from each sticky note back to the exact element it's roasting, so you know who to blame.
- **Runs entirely locally** — no internet required, no data leaving your machine.

## How to install/try it

1. Clone or download this repository
2. Open a terminal in the project folder and install dependencies:
   ```bash
   npm install
   ```
3. Build the plugin:
   ```bash
   npm run build
   ```
   This compiles `code.ts` → `dist/code.js` using the TypeScript compiler.
4. Open the **Figma desktop app**, go to **Plugins → Development → Import plugin from manifest**, and point it at the `manifest.json` file.
5. Select part of your design, hit **Generate Feedback**, and brace yourself.