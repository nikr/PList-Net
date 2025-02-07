﻿# Change log

## 3.0
 - fixed a number of binary PList parsing bugs
 - fixed writing of unicode strings in XML format
 - converted to netstandard1.0

## 2.0.5
 - project cleanup (removed unused file)

## 2.0.4
 - fixed handling of empty arrays

## 2.0.3
 - fixed issue where invalid PList XML files were generated

## 2.0.2
 - switched NuGet package to Release bits

## 2.0.1
 - corrected bug in XML writer that resulted in written file missing the root "plist" element

## 1.x - 2.0
 - root namespace changed from `CE.iPhone.x` to `PListNet`
 - moved all nodes to the `PListNet.Nodes` namespace
 - renamed nodes from PListXXX to XXXNode (e.g. `PListArray` => `ArrayNode`)
 - dramatically reduced public API surface -- things meant to be internal now are
