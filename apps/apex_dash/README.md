# Apex Dash

Redraws the instrument cluster through cluster-render. Four dashes:

- **Apex** (new): big gear and speed across the top, cards for rpm, oil and water on the left, boost, shift point and clock on the right, a rev bar and the last shift's grade below.
- **Circuit** (new): a rev ring and a speed ring at the sides, the gear big in the middle, oil, water and boost cells under it.
- **M** and **Sport**: the two other dashes from Cluster Themes, unchanged.

Shift lights, shift scoring, cold-engine rev guard and the drive-mode switching work as in Cluster Themes.

## Placement

Apex and Circuit keep clear of what BMW paints over the cluster: the black box over the middle (nothing big between y 300 and 420 there), the warning strip at the bottom centre (nothing below y 585 between x 570 and 1150), and the hood over the top corners. BMW's own warning lights stay visible; the app never hides them.

## Install

Use one cluster app at a time: cluster-render has a single screen slot. Set **Cluster Themes** to Off (or remove it) before using Apex Dash. Needs **cluster-render** from the `robertnisipeanu/idrive-apps` Store source.

Settings are on the center screen (open Apex Dash from the apps menu): theme, drive-mode switching, units (km/h, °C, bar by default), clock (24-hour by default), redline, shift point, boost, demo data.

Built on bimmer-lab/apps (MIT) and the MGU App Kit (MIT). See NOTICE.
