# Changelog

## 2026-10-30 — Split comments half/half on Reels + more transparent tab bar (bundle 0.17.4)
- New experimental patch (98 total): "Split the screen half and half when comments open on Reels" — the in-place split screen's ratio is capped at a half where its controller clamps and keeps it, so the comments sheet rests over the bottom half of the screen and the top half keeps showing the reel. The sheet can still be dragged up to full height or down out of the way. On by default in this trial build; switch in Hushfacebook settings > Comments.
- New switch (no new patch; it rides the tab bar patch like the see-through bars switch): "Make the tab bar background more transparent" — while the tab bar is showing, its background fills keep about half of Facebook's own alpha (128/255), so the content behind the bar reads through it. Icons, size, position and the hide/show behaviour are untouched, and it works whether or not See-through bars is on. On by default in this trial build; switch in Hushfacebook settings > Appearance.
- All 97 patches from the previous build are otherwise unchanged.

## 2026-10-30 — Push the video to the top when comments open (bundle 0.17.3)
- New experimental patch (97 total): with the comments open under a video (feed/Watch split screen), the video rests at the top of the space above the sheet instead of in its middle, so there is no black band above it. On by default in this trial build; switch in Hushfacebook settings > Comments.
- All 96 patches from the previous build are otherwise unchanged.

## 2026-10-29 — Reels tab bar: space back + returns on a touch (bundle 0.17.2)
- Fix: hiding the tab bar on the Reels/Video tab now gives the bar's space back. Facebook pins the bar block's height in pixels — onto the bar's container and the frame above it — so a hidden bar left a blank strip as tall as the bar at the bottom of the screen and reels stopped above it. Those pinned heights are collapsed while the bar is hidden and restored when it shows, including heights Facebook pins again in between.
- New: a tap or a swipe on the Reels surface brings the tab bar back for three seconds, then it hides itself again. Before, nothing on the surface could bring it back short of leaving the tab. "Always keep the tab bar" still wins.
- All 96 patches otherwise unchanged.

## 2026-10-29 — Reels tab bar fix (bundle 0.17.1)
- Fix: the hidden tab bar on the Reels/Video tab is now kept hidden even when a surface attaching after the tab pick settles the bar back to showing (the pick's answer is re-applied at the tab bar container's own layout). Still on by default; "Always keep the tab bar" still wins.
- The setting is now labelled in Vietnamese ("Ẩn thanh tab khi ở trang Reel"), with its description translated too.
- All 96 patches otherwise unchanged.

## 2026-10-29 — Hide the tab bar on the Reels tab (bundle 0.17.0)
- New patch (96 total): the bottom tab bar hides while the Reels/Video tab is open and comes back on every other tab. On by default; "Always keep the tab bar" still wins if that is on.
- All 95 patches from the previous build are otherwise unchanged.

## 2026-10-25 — Save photos by default (bundle 0.17.0)
- "Download any photo" now starts enabled: saving a photo straight from a post's menu works out of the box, no settings trip needed.
- All 95 patches from the previous build are otherwise unchanged.

## 2026-10-24 — Following feed by default (bundle 0.17.0)
- Home opens on the Following (most recent) feed from the first launch.
- Full Vietnamese settings.
- Quiet preset included.

## 2026-10-24 — First release (bundle 0.17.0)
- HushFacebook patches for Facebook 584: clean feed, no ads or suggested clutter, downloads, quiet defaults (95 patches).
