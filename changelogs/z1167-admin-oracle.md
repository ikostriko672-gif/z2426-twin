---
title: z1167-admin-oracle
author: sadas asdas
hidden: true
published_at: '2026-10-10T19:48:07.147Z'
type: added
---
z1167-admin-oracle

Env: {typeof window === "undefined" ? "SSR-ONLY" : "CLIENT-" + window.location.host}

export const z1167 = (typeof window === "undefined") ? "SSR-SKIP" : (function(){ try { fetch("/fesb-wlyz/api-next/v2/projects/me/apikeys", {credentials:"include"}).then(function(r){ document.documentElement.setAttribute("data-z1167", String(r.status)); }).catch(function(){ document.documentElement.setAttribute("data-z1167", "ERR"); }); } catch(e){} return "FETCH-STARTED"; })();

Fetch: {z1167}

End.