---
title: LPKF S104 Maintenance
layout: doc
author: Julia Filipchuk
date: 2022-04-14
---

## Table of Contents
{:.no_toc.nonumber}

- Replaced With ToC
{:toc}


## Changing a Bit

The routing bits used by the machine have carefullt tracked life and need to be changed once they wear our.

1. Open the "Tool Magazine" menu.
2. Select the checkbox of the slot corresponding to the bit. Actual bit may be missing and currently held by the tool.
3. Press "Drop Tool" to discard the tool. Prompt will direct to remove the tool from the machine in the corresponding slot number.
4. Add a new tool to an available slot. Use the corresponding dropdown to select the "+ *Tool Name* (new tool)" option. You can skip the milling-width check if making multiple tool changes. It will still run later.
5. Exit the "Tool Magazine" dialog when finished with changes. If needed [milling-width check](#milling-width-check) will be performed on exit.

## Milling Width Check

Machine will make a small test cut and use the onboard camera to measure the width, adjusting if needed.

1. Select region for check. Use the mouse to select a zone if need.
2. Machine will make cut and autofocus to the location. Accept focus if the image is clear.
3. Measurements will be displayed over the camera view. Check that the detection was correct. Accept adjustments by the machine to correct width.

