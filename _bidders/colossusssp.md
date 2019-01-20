---
layout: bidder
title: Colossus
description: Prebid Colossus Bidder Adaptor
top_nav_section: dev_docs
nav_section: reference
hide: true
biddercode: colossusssp
biddercode_longer_than_12: false
prebid_1_0_supported : true
---

### bid params

{: .table .table-bordered .table-striped }
| Name           | Scope    | Description                                              | Example    | Type      |
|----------------|----------|----------------------------------------------------------|------------|-----------|
| `placement_id` | required | Placement Id will be generated on Colossus SSP Platform. | `0`        | `integer` |
| `traffic`      | optional | Type traffic                                             | `'banner'` | `string`  |