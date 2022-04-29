<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [toast](./bitburner.ns.toast.md)

## NS.toast() method

Queue a toast (bottom-right notification).

<b>Signature:</b>

```typescript
toast(msg: any, variant?: string, duration?: number | null): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  msg | any | Message in the toast. |
|  variant | string | Type of toast, must be one of success, info, warning, error. Defaults to success. |
|  duration | number \| null | Duration of toast in ms. Can also be <code>null</code> to create a persistent toast. Defaults to 2000 |

<b>Returns:</b>

void
