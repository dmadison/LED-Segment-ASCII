# Segmented LED Display - ASCII Library

![Header Image](../master/Images/LED-ASCII-Library.png)

## Synopsis

This repository contains integer literals for displaying ASCII characters on 7 segment, 14 segment, and 16 segment LED displays.

I needed a set of 16 segment and 7 segment ASCII characters for a project, but I couldn't find a readily-available library. I'm sharing my own character patterns so others won't have this problem.

Each character set covers all visible ASCII characters, starting at 32 ('space') and ending at 127 ('del'). Segments are ordered sequentially.

## 16 Segment

![All Sixteen-Segment Characters](../master/Images/All%20Characters/16-Segment-ASCII-All.png "Sixteen-segment display characters")

Sixteen-segment characters require 17 bits each (16 segments + the decimal point). I've also included a "No Decimal Point" (NDP) set which only requires 16 bits per character. The only other character difference is for '.' which has the display point moved to segment 'R'.

## 14 Segment

![All Fourteen-Segment Characters](../master/Images/All%20Characters/14-Segment-ASCII-All.png "Fourteen-segment display characters")

Fourteen-segment characters require 15 bits each (14 segments + the decimal point). Many of these are 1:1 with their 16-segment counterparts, with changes only where a single horizontal edge segment was used.

## 7 Segment

![All Seven-Segment Characters](../master/Images/All%20Characters/7-Segment-ASCII-All.png "Seven-segment display characters")

Seven-segment characters require 8 bits each (7 segments + the decimal point). It's more difficult to display certain characters with the limited segments - some require context and a bit of imagination.

## Segment Order

![LED Segment Legend](../master/Images/Segment-Labels.png "LED segment legend. Left to right: sixteen, fourteen, and seven-segment displays.")

For each set the segments are ordered sequentially. Bit '0' corresponds to segment 'A', bit '1' corresponds to segment 'B', and so-on. Here are the ordered segments for each display:

* 16 Segment: DP-U-T-S-R-P-N-M-K-H-G-F-E-D-C-B-A
* 14 Segment: DP-L-M-N-K-J-H-G2-G1-F-E-D-C-B-A
* 7 Segment: DP-G-F-E-D-C-B-A

Use the above image as reference for the segment names and positions.

## Issues / Contributions

If you have a suggestion on how to improve a character or if you see a mistake in the repository, please create an issue.

## License

The segmented character representations and their associated integer literals are licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT).

All included reference images are licensed under the [Creative Commons - Attribution license](https://creativecommons.org/licenses/by/4.0/).
