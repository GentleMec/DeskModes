# Launch log

Launch access and outreach checked on 2026-10-07; release/package evidence below is from October 4.
This records evidence and actions still needed, not a claim of
universal hardware support. Start with [the launch plan](https://github.com/GentleMec/DeskModes/blob/main/docs/public-launch.md).

## Current evidence

| Item | Result | Evidence and limit |
| --- | --- | --- |
| Public release | Verified | [1.0.2](https://github.com/GentleMec/DeskModes/releases/tag/v1.0.2), normal public release from f07232136200a4650ef4b355a399f31e6a878edf. [Tag workflow succeeded](https://github.com/GentleMec/DeskModes/actions/runs/37158627145). Downloaded ZIP hash matches attached checksum and GitHub digest. All 25 files match the clean local build. |
| Released startup commands | Verified on this PC | Fresh isolated extraction: status and diagnostics exit 0 under Windows PowerShell 5.1. Diagnostics contains schema, version, windows, powershell and displays. No real switch was invoked. |
| Source quality | Verified | Release commit f07232136200a4650ef4b355a399f31e6a878edf: [Windows CI success](https://github.com/GentleMec/DeskModes/actions/runs/37158437316), including required analyzer. Local tools/check.ps1 passed 2,849 assertions on October 4; local analyzer unavailable. Tag workflow ran all gates again successfully. |
| GitHub presentation | Prepared and published | Short README, Modes/desk screenshots, release download link, useful About description and repository website. Release description shortened with full changelog linked separately. |
| Bug and idea forms | Verified in a signed-in browser | Required fields block empty submissions. A suggestion with optional fields empty created [#3](https://github.com/GentleMec/DeskModes/issues/3) with enhancement; a bug without logs created [#4](https://github.com/GentleMec/DeskModes/issues/4) with bug. Both harmless tests were closed. |
| Private security route | Enabled | Repository API returns private vulnerability reporting enabled. |
| Maintainer notifications | Subscription saved; delivery pending | Watch → Custom → Issues was saved and confirmed checked after reload on October 4. A report from another account and actual notification delivery remain unverified. |
| Donation links | Published in app and on GitHub | README, FUNDING.yml and the 1.0.2 About Support button point to https://ko-fi.com/gentlemec. Payment acceptance remains a separate owner check. |
| App release | 1.0.2 published | Support and canonical-link patch; no display-engine, rules, settings or diagnostics change. Isolated downloaded status/diagnostics exit 0 and report DeskModes 1.0.2. No real display switch was invoked. |
| Ko-fi profile | Text verified; approved cover awaits upload | Signed-in Chrome access restored October 6. English About and GitHub link remain visible. Approved monochrome cover is local; automated upload failed because the extension's file-URL permission is disabled. Thank-you field was empty after the earlier reload and is not saved. |
| Ko-fi payments | Owner checks remain | Payment Settings shows both providers connected and outstanding verification requirements. Signed-out checkout and receipt unverified. Private account follow-up is kept outside this public log. |
| Outreach | X and two Reddit comments visible signed in; SideProject filtered | [Weekly Discovery](https://www.reddit.com/r/software/comments/1wvquoc/comment/peb50n7/), [X](https://x.com/Il0CP8LOdcSDHVV/status/2107593394583200003) and [simracing reply](https://www.reddit.com/r/simracing/comments/1wz5kq9/comment/peb9nj8/) checked at their permanent URLs. SideProject review and Windows11 moderator reply are pending. Anonymous visibility could not be verified by the web fetch. |
| Content formatting | Earlier rendering verified; current Markdown inspected | GitHub Markdown API rendered the earlier plan, posts, content checklist, journal and release notes; tables and code blocks are retained. About screenshot rendered from current WPF source and visually inspected. |
| October 3 profile follow-up checks | Historical failure resolved October 4 | Tall-menu fixture assumed 1,200 pixels would fit 40 rows; at 150% DPI the menu needs 1,204. Larger fake screen now uses the natural menu height. Original regression failed 1 of 5; fixed check passes 5 of 5 and full tools/check.ps1 passes 2,849 assertions. No production menu change. |
| Demo | Script ready; recording pending | A 20–25 second physical-desk recording is optional for the first screenshot post. No real-hardware video was fabricated or recorded. |

Published ZIP SHA256:

```text
cdcc7ea4807f1ed3d4e47eff067547802882c67eb52781cb20787e876943ac7e
```

The 1.0.1 asset count was 1 before its earlier verification download. Treat
maintainer downloads as part of the count, not new users. Refresh the baseline immediately
before outreach using [release assets](https://github.com/GentleMec/DeskModes/releases/tag/v1.0.2)
and the private [traffic view](https://github.com/GentleMec/DeskModes/graphs/traffic).

An ignored local `DeskModes-1.0.1.zip` in the checkout predates publication and is a
historical candidate. Use the public attached ZIP and verified hash above for the launch.

## Historical 1.0.2 candidate verification

Candidate ZIP SHA256:

```text
ca39bf94179eef1357fd219b4acd4435e420fe6b7f2607ab75e961b58a0b7b12
```

The ZIP, matching hash and candidate notes are saved under
`../DeskModes-launch/prepared-1.0.2-36ee7e4`. The same files are saved in the
[maintainer-only preservation draft](https://github.com/GentleMec/DeskModes/releases/tag/untagged-5e2a2933156f305e801c),
including validation.txt and the UI preview. All five uploaded asset digests matched
the local files. The draft's own body records hosted CI confirmation. At that candidate stage no v1.0.2 tag
was pushed. The final dated release above supersedes it; the preservation draft stays unpublished.

Local tools/check.ps1 passed 2,849 assertions after the version bump; local analyzer
was unavailable. Extracted status and diagnostics report DeskModes 1.0.2. The About
window shows the same version, Support is visible/enabled, and raising its click event
passes https://ko-fi.com/gentlemec to a locally captured Open-UiTarget call. This verifies
the packaged action's target, not browser navigation or payment checkout.

The [Support preview](https://raw.githubusercontent.com/GentleMec/DeskModes/main/docs/images/settings-support.png)
was rendered offscreen from the candidate and visually inspected. No real display
switch or user installation update was performed. The original hardware limits apply.

## Owner checks: record the actual result

| Check | How | Result |
| --- | --- | --- |
| Suggestion form | Browser submission and required-field validation; optional workaround left empty. | Passed; #3 closed |
| Bug form | Browser submission and required-field validation; diagnostics and logs left empty. | Passed; #4 closed |
| Notifications | Watch → Custom → Issues is saved. Have another account create a harmless issue and check arrival. | Subscription verified; delivery pending |
| Ko-fi page | [Profile text](https://github.com/GentleMec/DeskModes/blob/main/docs/kofi-page.md) is saved; finish cover upload, reload-check thank-you and inspect signed-out checkout. | Text verified; remaining checks pending |
| Receipt | Check any outstanding PayPal/Stripe account requirements and confirm receipt after a genuine supporter payment. | Pending; no agent payment attempted |
| Outreach | Weekly Discovery and contextual simracing comments plus X announcement opened at their permanent URLs. | Visible in signed-in Chrome; SideProject filtered, moderator review pending |

For future app releases, keep the existing tag workflow. Bump the source version and
move applicable Unreleased notes to that version; run the required gates, build an isolated
candidate, verify affected behavior and exact-commit CI, then date and tag that commit.
Do not reuse v1.0.1 or overwrite its assets to add the new Support button.

## Publication and feedback journal

The first community publication is recorded below.

### October 6: first community comment

The owner approved the monochrome cover and authorized starting community publication.
The first planned post is the short r/software Weekly Discovery comment. The thread's
current fetched text allows relevant side projects with transparent authorship, and
prohibits link spam and AI-generated content dumps. The SideProject front page was also
rechecked; verify its submission rules before a standalone post.

The initial in-app attempt required a CAPTCHA and Ko-fi login. The owner then connected
signed-in Chrome tabs. No CAPTCHA was solved and no payment was attempted.

The approved cover is `../DeskModes-launch/kofi-cover-monochrome.png`, with its brief
beside it. Chrome upload failed immediately because the extension's local-file permission
is disabled. The owner was asked for separate permission or a manual upload.

- Posted: 2026-10-06 at 21:49:42 UTC (23:49:42 Europe/Paris), from Pristine_Ad_4378.
- Destination: [r/software Weekly Discovery](https://www.reddit.com/r/software/comments/1wvquoc/weekly_discovery_thread_october_02_2026/).
- Result: [comment permalink](https://www.reddit.com/r/software/comments/1wvquoc/comment/peb50n7/).
  Full body remains visible after opening the permalink in signed-in Chrome. No removal
  notice was visible. A separate anonymous web fetch failed; broader visibility is unverified.
- Material: short introduction covering display modes, hotkeys and automatic rules,
  with authorship disclosed, the GitHub link and a practical improvement question. No image
  attached; the repository links the current v1.0.2 release and screenshots.
- Baseline: v1.0.2 ZIP download count was 2 before posting, including maintainer checks.
- Screenshot: saved in the local delivery folder as `reddit-first-comment-2026-10-06.png`.
- Next at that point: review initial replies before expanding. The owner's October 7
  request to broaden outreach superseded that timing recommendation.
  No automatic monitoring or later scheduled publication was configured.

The owner confirmed on 2026-10-03 that the task is to prepare the posting plan. No community
post or moderator message was sent. First options: the current r/software Weekly Discovery Thread or r/SideProject.
At that planning stage no community post had been sent. The October 6 entry supersedes
that pending status.

### October 7: testing request and broader outreach

The owner requested more suitable communities and contextual monitor replies,
explicitly asked for a testing/bug/improvement invitation, and signed in to X.

- Weekly Discovery: edited the existing comment to ask users to test restoring their
  layout, report bugs or confusing setup steps, and suggest improvements. The saved
  edit remains visible after reload. Proof: `reddit-feedback-request-2026-10-07.png`.
- X: [announcement](https://x.com/Il0CP8LOdcSDHVV/status/2107593394583200003),
  published at 00:06 Europe/Paris from the owner's account. Modes, hotkeys and app/game
  rules are named, with an explicit tester request. The own profile showed one post,
  and its permanent page contains the submitted text and GitHub link card. No image
  was attached. Proof: `x-first-post-2026-10-07.png`.
- SideProject: [text submission](https://www.reddit.com/r/SideProject/comments/1wzfmze/deskmodes_a_free_windows_tool_for_display_setups/)
  titled "DeskModes - A free Windows tool for display setups, hotkeys and automatic rules".
  The [sidebar format](https://old.reddit.com/r/SideProject/) and submission page were
  checked. The post requests testing, bugs and ideas and links both GitHub forms.
  Its page explicitly says "Sorry, this post was removed by Reddit's filters."
  A single moderator review request was sent; "Message sent" appeared and the form
  reset. Approval is pending; no repost was attempted. Proofs:
  `reddit-sideproject-2026-10-07.png`, `reddit-sideproject-modmail-2026-10-07.png`.
- Simracing: [contextual reply](https://www.reddit.com/r/simracing/comments/1wz5kq9/comment/peb9nj8/)
  to a seven-hour-old desk/rig question. Rule 4 was expanded and read: developers can
  participate and promote reasonably while engaging with the community. The reply
  asks for GPU/connections, separates laptop input switching and cable requirements
  from same-PC display profiles, discloses authorship and invites testing feedback.
  It makes no compatibility promise for that desk. Full text remains visible at its
  permanent URL without a removal notice. Proof: `reddit-simracing-reply-2026-10-07.png`.
- Windows11: sent the prepared moderator inquiry, adapted to request a practical
  Work/Game/TV introduction with UI screenshots and a testing invitation. The form
  reset after submission. No community announcement was posted; moderator reply
  pending. Proof: `reddit-windows11-modmail-2026-10-07.png`.

These browser results establish submission and signed-in visibility, not independent
anonymous visibility or successful installations. No external tester setup report
has been verified. The release remains v1.0.2; these are outreach/documentation changes.
Ko-fi cover upload and payment eligibility remain owner steps from the October 6 entry.
Next: respond to these threads, review moderator replies, and gather five independent
setup reports. Record a short real-hardware demo for a later X/community follow-up;
DEV, Mastodon and existing Discord/forums are candidates requiring owner access and
posting-day rules. No later run or automatic publication was scheduled.

Duplicate the following block for each actual post:

```text
Date/time and account:
Community/thread URL:
Rules checked at:
Post URL and title:
Screenshot/clip and release used:
Downloads/traffic baseline (including maintainer checks):
Useful feedback and linked GitHub issues:
Replies sent and outstanding questions:
Next action and date:
```

Keep contact details, private chats and payment records outside this public journal.
After 48 hours, count useful setup reports and repeated questions. After one week,
choose the three most common obstacles; stop wider outreach if recovery or settings safety
fails, document a workaround and verify a fix. Target five independent successful setups;
stars and donations are secondary. Do not add app telemetry for this launch.
