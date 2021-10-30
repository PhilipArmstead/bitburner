<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Singularity](./bitburner.singularity.md) &gt; [donateToFaction](./bitburner.singularity.donatetofaction.md)

## Singularity.donateToFaction() method

If you are not in BitNode-4, then you must have Level 3 of Source-File 4 in order to use this function and the RAM cost is doubled.

Attempts to donate money to the specified faction in exchange for reputation. Returns true if you successfully donate the money, and false otherwise.

<b>Signature:</b>

```typescript
donateToFaction(faction: FactionName, amount: number): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  faction | [FactionName](./bitburner.factionname.md) | Name of faction to donate to. |
|  amount | number | Amount of money to donate. |

<b>Returns:</b>

boolean

True if the money was donated, and false otherwise.

## Remarks

Singularity - Level 3
