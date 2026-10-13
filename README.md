# BioPerformance feedback

Public bug reports and feature requests for the BioPerformance mobile and web apps.

## Where these issues come from

Most issues here are created automatically. When someone uses **Send feedback** in the app and
agrees to publish it, the BioPerformance server turns the report into one issue in this
repository.

**Everything here is public.** That includes every issue, comment and screenshot.

## What is published

The app adds nothing about you: no name, email or account id. An issue contains only:

- the description you typed, exactly as you typed it;
- any screenshots you attached, up to three;
- whether it is a bug or a feature request, and whether you sent it from the mobile or web app.

Your description and screenshots are published exactly as you send them. Leave out anything
personal, such as health readings, names or contact details, and crop it out of your screenshots.

Screenshots are re-encoded before they are published, so their metadata is removed. That covers
location, device details, embedded text and colour profiles.

## Labels

| Label | Meaning |
|---|---|
| `bug` | Something in the app is broken or wrong |
| `feature` | A request for something new or different |
| `mobile` | Sent from, or about, the mobile app |
| `web` | Sent from, or about, the web app |

Every issue the app creates carries one of `bug`/`feature` and one of `mobile`/`web`.

## Screenshots

Screenshots are stored on the [`screenshots`](https://github.com/rejuve-bio/bioperformance-feedback/tree/screenshots) branch, one folder per report
under `reports/<report-id>/`, and are shown in the issue as images. That branch is written only by
the feedback publisher and is never merged into `main`.

## Sending feedback

Open the BioPerformance app and use **Send feedback**. You need a verified email address to send
it.

Please don't report security vulnerabilities as issues or through in-app feedback, because both
are public. Report them privately instead, with **Report a vulnerability** on this repository's
[Security tab](https://github.com/rejuve-bio/bioperformance-feedback/security).
