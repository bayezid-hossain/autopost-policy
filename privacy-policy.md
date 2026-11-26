---
title: autopost - Privacy Policy
---
# Privacy Policy: autopost

_Last updated: 2026-11-26_

autopost is a private tool that uploads videos from a Google Drive folder to one YouTube channel, with the channel owner's permission. It is not offered to the public.

## Data it uses
- **Google account access (OAuth):** permission to upload videos to YouTube (`youtube.upload`) and read-only access to Google Drive (`drive.readonly`) to read the video folder. The OAuth refresh token and client credentials are stored only as encrypted GitHub Actions secrets in a private repository.
- **Video files:** downloaded from Drive to a temporary GitHub Actions runner, uploaded to YouTube, then deleted from the runner when the run ends.
- **File names:** sent to the Google Gemini API to draft video titles and descriptions.
- **Upload log:** Drive file IDs and YouTube video IDs are kept in a private repository to prevent duplicate uploads.

## What it does not do
- It does not collect data from anyone other than the channel owner.
- It does not sell, share or transfer data to third parties.
- It does not use YouTube or Drive data for advertising or analytics.

## YouTube API Services
autopost uses YouTube API Services. By using it you agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms). See also the [Google Privacy Policy](https://policies.google.com/privacy).

Access can be revoked at any time at [Google account permissions](https://myaccount.google.com/permissions).

## Contact
[github.com/bayezid-hossain](https://github.com/bayezid-hossain)
