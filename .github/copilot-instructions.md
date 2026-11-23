# Copilot instructions: JS-SEZ website
 
## Goal
A one-page static website that introduces the Johor-Singapore
Special Economic Zone (JS-SEZ) to Singapore manufacturers, with
an AI advisor chat that opens from a button at the bottom right.
 
## Content
- Use ONLY facts from the SMF JS-SEZ Playbook. Never invent
  rates, dates, names or statistics.
- Sections: hero, the nine zones, the SETUP framework,
  incentives and tax watch-outs, passes for staff,
  "Ask the advisor", footer.
- Footer: "C334 class exercise. Not affiliated with SMF,
  Enterprise Singapore or MIDA."
- Plain English, UK spelling, short sentences.
 
## Chat widget
- Use n8n's widget @n8n/chat version 1.46.5 from jsDelivr:
  style.css and chat.bundle.es.js.
- Call createChat with mode 'window' (round button, bottom right).
- webhookUrl: https://agenticflows.tokencraze.org/webhook/fc8a7c18-1af2-4868-9498-7656dd82e712/chat
- Chat title "JS-SEZ advisor"; two short initial messages.
- loadPreviousSession: false.
 
## Technical rules
- Plain HTML, CSS and JavaScript only: index.html, styles.css,
  chat.js. No framework, no build step, no npm.
- Works at 360 px wide with no sideways scrolling.
- Visible keyboard focus and good colour contrast.
- The site is published with GitHub Pages from main, root folder.
 
## Done when
- The chat button opens the window and a JS-SEZ question gets
  an answer that names a playbook page.
- Every fact on the page can be found in the playbook.

