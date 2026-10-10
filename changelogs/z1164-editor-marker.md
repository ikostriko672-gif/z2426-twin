---
title: Z1164 editor marker
author: sadas asdas
hidden: true
published_at: '2026-10-10T19:35:21.566Z'
type: added
---
Z1164 editor-authored marker.

Env: {typeof window === "undefined" ? "SSR-ONLY" : "CLIENT-" + window.location.host}

export const z1164e = (typeof window === "undefined") ? "EXP-SERVER" : (function(){ try { document.documentElement.setAttribute("data-z1164", "EDITOR-EXPR-RAN"); } catch(e){} return "EXP-CLIENT"; })();

Export: {z1164e}

End.