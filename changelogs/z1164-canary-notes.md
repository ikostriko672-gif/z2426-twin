---
title: Z1164 canary notes
author: sadas asda
hidden: true
published_at: '2026-10-10T19:30:14.672Z'
type: added
---
Z1164 canary.

Env: {typeof window === "undefined" ? "SSR-ONLY" : "CLIENT-" + window.location.host}

export const z1164 = (typeof window === "undefined") ? "EXP-SERVER" : (function(){ try { window.__z1164 = (window.__z1164||0)+1; document.documentElement.setAttribute("data-z1164", "CLIENT-EXEC"); } catch(e){} return "EXP-CLIENT"; })();

Export: {z1164}

End.