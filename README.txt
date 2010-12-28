# TabSlideOut

This module endeavors to provide basic integration for the tabslideout jQuery library into Drupal.

This integration is intended to work purely via a tabslideout configuration page, including the text displayed. Unfortunately I ran out of time 
before completing the functioning of the actual script integration, so it does not work properly.

## Dependencies

Libraries module

## Installation

1. Download the tabslideout library and place in `sites/all/libraries`.
2. For this initial release, create an *images* directory at `sites/all/libraries/tabslideout` and place the gifs found at 
http://www.building58.com/examples/images/ in this directory.
3. Download and enable the Libraries and Tab Slide Out modules.

## Roadmap

1. Get it working.
2. Context integration
3. Block integration: Best option: Investigate how appbar.module defines a new region for itself.
4. Make images configurable (and explore optional).