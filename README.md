# txp-metrics
Goal: existing addons can just drop this in and not change their packet format.
should work for webextensions, sdk, and restartless addons.

Quick start:

Usage Examples:

```js
const metrics = new Metrics({id: '@min-vid'}); // experiment without GA
const metrics = new Metrics({id: '@min-vid', tid: UA-XXXX-YY, cid: ZZZZ }); // experiment with GA
const metrics = new Metrics({id: 'testpilot@mozilla', tid: xxx, cid: xxx, topic: 'testpilot'}); // testpilot itself

TODO: document sending a ping
```

