Installation:
Download the release file. Feel free to read the code; however, the code has already been reviewed (see safety).
Go to about:debugging#/runtime/this-firefox in your address bar in firefox (press ctrl+L to highlight your address bar).
Click "Load Temporary Add-On" and browse to mainfest.json to install the add-on into your firefox.

Usage:
You need to start audio; otherwise, the add-on will say "see console". This is because other add-ons remain active on every page you browse, and I don't like that from a theoretical security standpoint; therefore, I did better!

SAFETY:
This RAR file is VERY safe, it was designed to be safe by only boosting the volume within some safe limits, very slowly. If that is not the behavior, report a bug and I will update the code! Please, do not be careless, the developer is not responsible for the end user's hardware.
Furthermore, this project is special because it is designed to be completely secure! I want your computer to be safe from attackers; so, I wrote the add-on to a higher security standard than anything I have found in the Firefox store.

(1) It does not connect to the network at all, nor does it have any capability that could connect to the network.
(2) It does not use your entire sound card, it just live-processes the audio; so, it is completely safe from a privacy perspective.
(3) Absolutely no malware, no ads, no bullshit of any kind, guaranteed through audit, following the standards of #computerhelp .
(4) You can adjust down bass and treble to help to prevent from rattling your speakers directly.
(5) This is the most unique safety feature, which I love: this add-on ONLY READS DATA FOR THE SITES IT IS ACTIVATED ON. If there is no audio, it will say "failed, check console". I there is audio, it will just live-synth the audio.

PROJECT STRUCTURE:
This add-on contains three functions, two audio synthesizers and a PIL to convert image files to icon format (extremely useful). The browser extension is extremely unique in terms of security for these reason:

HELP SUPPORT MY WORK:
Buy me a coffee: https://www.paypal.com/paypalme/beer4jer on paypal. 

PAYING FOR SPECIFIC DEVELOPMENT? I CAN ACCOMPLISH ANYTHING IN CODE.
You may request additional features by emailing sudojm at sudojim dot com. Currently, the development path I am planning will expand the eq (already developed) so that it has precision presets at all frequencies and an undo-redo feature with bezian spline curves. And I hope to put in speaker-specific controls for the high- and low-pass filters (already developed). I was hoping to reach some reasonably low donation goal before improving the software.
