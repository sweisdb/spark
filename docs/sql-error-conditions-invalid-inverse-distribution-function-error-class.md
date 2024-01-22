---
layout: global
title: INVALID_INVERSE_DISTRIBUTION_FUNCTION error class
displayTitle: INVALID_INVERSE_DISTRIBUTION_FUNCTION error class
license: |
  Licensed to the Apache Software Foundation (ASF) under one or more
  contributor license agreements.  See the NOTICE file distributed with
  this work for additional information regarding copyright ownership.
  The ASF licenses this file to You under the Apache License, Version 2.0
  (the "License"); you may not use this file except in compliance with
  the License.  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
---

[SQLSTATE: 42K0K](sql-error-conditions-sqlstates.html#class-42-syntax-error-or-access-rule-violation)

Invalid inverse distribution function `<funcName>`.

This error class has the following derived error classes:

## DISTINCT_UNSUPPORTED

Cannot use DISTINCT with WITHIN GROUP.

## WITHIN_GROUP_MISSING

WITHIN GROUP is required for inverse distribution function.

## WRONG_NUM_ORDERINGS

Requires `<expectedNum>` orderings in WITHIN GROUP but got `<actualNum>`.

