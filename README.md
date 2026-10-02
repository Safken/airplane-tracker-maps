# Airplane tracker regional maps

Public-domain regional basemap data for the standalone CrowPanel airplane tracker.

The Reno / Tahoe / Carson pack contains coarse roads, water outlines, selected rivers
and airport runways derived from USGS The National Map. Credit: USGS TNM, Census
TIGER/Line, USFS and FAA-origin runway data. See the pack credits and source manifest.
This is a general reference basemap, not navigation or survey data.

Download: [region.atmap](reno-tahoe-carson-2026-10-01/region.atmap).
Size: 130,188 bytes. SHA-256:
`42225ef742d44995ad4b9d16cd92a5affb95404f67e9dfcc2abf7324ff72b56d`.

Coverage: 121.0 W to 118.5 W, 38.0 N to 40.8 N. The full 50 x 50 mile display
footprint must fit inside coverage; the device checks this after installation.
Manual installation path: `/airplane-tracker/region.atmap` on a FAT32 microSD card.
Firmware can download this fixed version over HTTPS and verify its pinned checksum.

USGS data policy: https://www.usgs.gov/information-policies-and-instructions/copyrights-and-credits
This repository contains map assets and provenance only. Firmware is maintained separately.
