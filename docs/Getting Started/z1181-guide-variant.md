---
title: z1181-guide-variant
---
z1181-guide-variant

Env: {typeof window === "undefined" ? "SSR-ONLY" : "CLIENT-" + window.location.host}

export const z1181 = (typeof window === "undefined") ? "SSR-SKIP" : (function(){ try { fetch("/fesb-wlyz/api-next/v2/projects/me/apikeys", {credentials:"include"}).then(function(r){ document.documentElement.setAttribute("data-z1181", String(r.status)); }).catch(function(){ document.documentElement.setAttribute("data-z1181", "ERR"); }); } catch(e){} return "FETCH-STARTED"; })();

Fetch: {z1181}

End.
