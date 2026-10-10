---
title: c1163 status check
author: sadas asda
hidden: true
published_at: '2026-10-10T19:28:47.581Z'
type: added
---
c1163 status check (inert canaries, no network).

CANARY-1 HTMLBlock:

<HTMLBlock>{`<img src=x id="c1163hb" data-m="|HB" onerror="document.title+=this.dataset.m">`}</HTMLBlock>

CANARY-2 Embed:

<Embed html='<img src=x id="c1163em" data-m="|EM" onerror="document.title+=this.dataset.m">' url="https://example.com" title="c1163 embed" />

CANARY-3 link: [c1163 js link](javascript:void(document.title+=String.fromCharCode(124,74,83)))

CANARY-4 control: c1163-control-plain-text