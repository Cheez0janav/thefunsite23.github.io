<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [getGrowTime](./bitburner.ns.getgrowtime.md)

## NS.getGrowTime() method

Get the execution time of a grow() call.

<b>Signature:</b>

```typescript
getGrowTime(host: string): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  host | string | Host of target server. |

<b>Returns:</b>

number

Returns the amount of time in milliseconds it takes to execute the grow Netscript function. Returns Infinity if called on a Hacknet Server.

## Remarks

RAM cost: 0.05 GB

Returns the amount of time in milliseconds it takes to execute the grow Netscript function on the target server. The function takes in an optional hackLvl parameter that can be specified to see what the grow time would be at different hacking levels. The required time is increased by the security level of the target server and decreased by the player's hacking level.
