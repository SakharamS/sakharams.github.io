---
layout: post
title: Az CLI Commands - CheatSheet
categories: [cloud, azure, az cli]
tags: [cloud, azure, az cli, cheatsheet]
---

# Shell
1. Get a single column from an array:
```
az ad app list --query "[].displayName"
```

2. Get multiple columns from an array
```
az ad app list --query "[].{Name:displayName, Created:createdDateTime}"
```
