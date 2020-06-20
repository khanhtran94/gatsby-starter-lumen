---
title: Copy data from table to table other schema
date: "2020-06-21T22:40:32.169Z"
template: "post"
draft: false
slug: "orace-tranform-table-schema"
category: "Oracle"
tags:
  - "oracle"
  - "sql"
  - "tranform"
  - "data"
description: "Tranform data 2 table other schema."
socialImage: ""
---

```sql
  insert into BCCS_CST.AREA(AREA_CODE, PARENT_CODE, AREA_GROUP, PROVINCE, DISTRICT, PRECINCT, STREET_BLOCK, NAME,
                          FULL_NAME, CENTER, PSTN_CODE, PROVINCE_CODE, STATUS, CREATE_USER, UPDATE_USER,
                          CREATE_DATETIME, UPDATE_DATETIME)
  select *
  from INPUT_EINVOICE.AREA ie;

```
