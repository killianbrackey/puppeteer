<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Target](./puppeteer.protocol.target.md) &gt; [CreateTargetRequest](./puppeteer.protocol.target.createtargetrequest.md)

## Protocol.Target.CreateTargetRequest interface

<b>Signature:</b>

```typescript
export interface CreateTargetRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [background](./puppeteer.protocol.target.createtargetrequest.background.md) | boolean | Whether to create the target in background or foreground (chrome-only, false by default). |
|  [browserContextId](./puppeteer.protocol.target.createtargetrequest.browsercontextid.md) | [Browser.BrowserContextID](./puppeteer.protocol.browser.browsercontextid.md) | The browser context to create the page in. |
|  [enableBeginFrameControl](./puppeteer.protocol.target.createtargetrequest.enablebeginframecontrol.md) | boolean | Whether BeginFrames for this target will be controlled via DevTools (headless chrome only, not supported on MacOS yet, false by default). |
|  [height](./puppeteer.protocol.target.createtargetrequest.height.md) | [integer](./puppeteer.protocol.integer.md) | Frame height in DIP (headless chrome only). |
|  [newWindow](./puppeteer.protocol.target.createtargetrequest.newwindow.md) | boolean | Whether to create a new Window or Tab (chrome-only, false by default). |
|  [url](./puppeteer.protocol.target.createtargetrequest.url.md) | string | The initial URL the page will be navigated to. |
|  [width](./puppeteer.protocol.target.createtargetrequest.width.md) | [integer](./puppeteer.protocol.integer.md) | Frame width in DIP (headless chrome only). |
