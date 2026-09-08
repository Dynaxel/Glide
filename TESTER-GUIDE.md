# Glide 1.0 Tester Guide

Thanks for helping test Glide.

The most useful testing is ordinary daily use, especially while gaming or streaming.

## Quick smoke test

1. Launch Glide.
2. Open several websites in separate tabs.
3. Close and reopen Glide and check session restore.
4. Add, edit and remove a bookmark.
5. Open History.
6. Download a small file and open Downloads.
7. Open Privacy controls.
8. Open Streamer Controls.
9. Toggle mute and play/pause media.
10. Try Panic Silence.
11. Open Settings and change theme/accent.
12. Confirm the performance bar is hidden by default.
13. Turn the performance bar on and off.
14. Change Maximum live tabs to 2 or more and keep multiple Twitch/YouTube pages active.
15. Minimize Glide and restore it.
16. If you use OBS Studio or Meld Studio, launch it and check Stream Mode behaviour.
17. If Glide is your default browser, click a web link in another application and confirm it opens as a new tab in the existing Glide window.

## Performance testing

If you want to help with performance testing:

- note how many tabs are open
- note Maximum live tabs
- note whether Stream Mode is on
- optionally enable the performance bar
- record APP / WV2 / TOTAL / PROC values
- describe what media is playing
- mention what game or streaming software is running

Raw numbers are useful, but perceived impact matters too. Tell us if a game stutters, media pauses unexpectedly, tab switching feels slow, or memory rises and never settles.

## Twitch testing

Useful Twitch cases:

- one stream active
- multiple live streams
- raid from one channel into another
- raid while the Twitch tab is in the background
- switching between Twitch tabs
- mute/unmute all Glide audio
- Panic Silence

## External-link test

With Glide already open:

1. Click an `https://` link from another application.
2. Confirm a second Glide window does **not** appear.
3. Confirm the link opens in a new tab in the existing Glide window.
4. Minimize Glide and repeat; Glide should restore and open the new tab.

## Downloads test

Try:

- a normal completed download
- cancelling an in-progress download
- Open File
- Open Folder
- clearing completed download history

## Privacy test

Try:

- clearing history
- clearing cookies/site data
- clearing cache
- clearing browsing data
- site permission prompts
- resetting permissions
- popup behaviour

## Please do not share private data

Before posting screenshots or logs, check them for:

- email addresses
- account names
- private URLs
- download paths
- tokens or login information
- anything else you do not want public
