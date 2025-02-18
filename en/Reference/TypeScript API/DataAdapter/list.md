---
aliases: "obsidian.DataAdapter.list.md"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`DataAdapter`](obsidian.DataAdapter.md) › [`list`](obsidian.DataAdapter.list.md)

## DataAdapter.list() method

Retrieve a list of all files and folders inside the given folder, non-recursive.

**Signature:**

```typescript
list(normalizedPath: string): Promise<ListedFiles>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>normalizedPath</code> | <code>string</code> | path to folder, use [normalizePath()](obsidian.normalizePath.md) to normalize beforehand. |

**Returns:**

`Promise``<`[`ListedFiles`](obsidian.ListedFiles.md)`>`

