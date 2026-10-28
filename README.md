# GWEN™

GWEN™ is a Windows application bringing console Remote Play, eligible provider
cloud streaming and a personal movie library into one controller-friendly interface.

## Public beta 1.16.2

- Independent Home waves and official PlayStation/Xbox homepage loading.
- Daily HTTPS update checks; release downloads/installations remain user controlled.
- PS5 pairing, saved-console switching, multi-view, controller input and media controls.
- Professional credits and upstream source/notices included with the release.

Download the **Public Beta installer** from this repository's Releases page.
The public installer contains no developer pairings, accounts or movie history.
An existing public installation can import the matching `.gwen-update.zip` from
**Updates → Install update file**, then **Restart to apply**. Saved data is retained.
Developer/private-channel packages are deliberately rejected by the public channel.

The public update feed is `updates/public.json`. The app checks the feed daily
when enabled; it does not install code automatically. Publishing each new release
requires uploading its public assets and updating the feed version/release link.

## Status and requirements

Windows 10/11 x64. Microsoft Edge WebView2 Runtime is required for embedded websites.
Remote Play needs a compatible console, pairing and reachable network. Cloud games
require the provider's eligible account, subscription/access and supported region.
Xbox sign-in/UI integration is present; console/gameplay coverage varies by hardware.
Network quality affects stream smoothness. This is an unsigned beta, not a claim
that every controller, account, game or network has passed acceptance testing.

The separate iPhone/iPad Home maintenance package is Xcode source. Mobile Cloud
game streaming is unfinished. No signed iOS app or App Store release is included.

## Source and acknowledgements

Full corresponding integration/native source is supplied in the source release ZIP,
including upstream notices and dependency inventory. GWEN integration code uses
the included AGPLv3 terms; dependencies retain their respective licenses. Product
artwork/logos/trademarks retain their owners' rights and are not relicensed as code.
See `CREDITS.txt`, `LICENSE.txt`, and the source archive's licenses directory.
Not affiliated with Sony, Microsoft, Netflix or Plex. Provider accounts and terms
are independent of GWEN™. No subscriptions or access controls are bypassed.

Never upload a private restore installer, UserData, tokens, passwords or pairing keys.
