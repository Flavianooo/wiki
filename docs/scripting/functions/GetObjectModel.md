---
id: GetObjectModel
title: GetObjectModel
description: Get the model ID of an object (CreateObject).
tags: []
---

:::warning

This function was added in SA-MP 0.3.7 and will not work in earlier versions!

:::

## Description

Get the model ID of an object (CreateObject).

| Name     | Description                              |
| -------- | ---------------------------------------- |
| objectid | The ID of the object to get the model of |

## Returns

The model ID of the object. -1 if object does not exist.

## Examples

```c
new objectid = CreateObject(1234, 0, 0, 0, 0, 0, 0);
new modelid = GetObjectModel(objectid);
```

## Related Functions

- [GetPlayerObjectModel](GetPlayerObjectModel): Get the model ID of a player-object.
