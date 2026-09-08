# Glide 1.0 Privacy Notes

Glide is a Windows browser built on Microsoft WebView2.

## Local browser data

Glide's browser profile and application state are stored locally on the Windows PC, primarily under:

`%LOCALAPPDATA%\Glide`

This can include browser/session state such as cookies, WebView2 profile data, history, settings and other local application state.

## Crash logs

Glide writes crash/debug logs locally under:

`%LOCALAPPDATA%\Glide\Logs`

These logs are not automatically submitted by this tester pack. If you choose to share a log in a GitHub issue, review it first for information you do not want to post publicly.

## Browsing-data controls

Glide includes controls for clearing:

- history
- cookies/site data
- cache
- broader browsing data
- site permissions

## Web content

Web pages are rendered through Microsoft WebView2. Websites and services you visit may collect data according to their own privacy policies, cookies and account settings.

## Feedback

If you report a bug publicly, only include screenshots, logs or URLs that you are comfortable sharing.
