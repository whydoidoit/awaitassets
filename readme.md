### Introduction

Promisifies the loading of an asset in PlayCanvas.

### Installation

```language-shell
npm install --save playcanvas-awaitassets
```

### Usage

```language-javascript
import awaitAsset from 'playcanvas-awaitassets';

...

await awaitAsset(someAssetId);

awaitAsset(someAssedId).then(function() { ... }); 

```

### Requirements

Requires PlayCanvas Engine to be running on the page.  Uses ES6/Babel/PlayCanvas template.
