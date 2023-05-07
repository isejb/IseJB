# isejb.github.io
A “Jailbreak” that takes advantage of keybagd. This was made for my high school finals.
Simple explanation:
This jailbreak utalizes the "MacDirtyCow" Exploit (CVE-2022-46689)
This jailbreak works for up to five minutes before it needs to be refreshed.
This jailbreak installs sileo but no tweaks can be used. Since this runs in a entirely different environment opposed to ALL jailbreaks.
Tweaks need to be specifically programmed for this jailbreak.

Risks:
This jailbreak is not near stable.
Unlike literally all jailbreaks this can brick your device. See the bottom of this file for more information for the exact cause.
If your device is powered on while running this jailbreak it will work until restarting. Your phone will not turn on again ever.
Do not use a Apple MFI Certified cable while running this. A DCSD Alex cable is recommended but any cheap gas station lightning cable should work fine
This exploit supports all MacDirtyCow Supported devices (Not confirmed)

Cause of Unstability:
#define NS_PUT16(s,cp) ns_put16((s), ((cp)+=2)-2)
#define NS_PUT32(l,cp) ns_put32((l), ((cp)+=4)-4)
#define NS_QFIXEDSZ 4
#define NS_RRFIXEDSZ 10
#define NS_SIG_ALG 2
#define NS_SIG_EXPIR 8
#define NS_SIG_FOOT 16
#define NS_SIG_LABELS 3
#define NS_SIG_OTTL 4
#define NS_SIG_SIGNED 12
#define NS_SIG_SIGNER 18

This project is not open sourced. I may consider it in the future.

No, Coolstar did not develop this. Some retard named "MidasLeaks" Edited the showcase video.

- isan hamza
