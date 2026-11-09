# DRIVEN Motorsport Group staff portal

Branded front door for the TeamKarting Staff Portal at https://portal.drivenmotorsportgroup.co.uk.

The portal runs on Google Apps Script. This site only holds the page that loads it full screen,
so the address bar keeps the branded address. Links like `?clock=`, `?station=` and `?invite=`
are passed straight through.

Hosted on GitHub Pages. DNS: a CNAME record `portal` pointing at the GitHub Pages host, set in
Squarespace Domains for drivenmotorsportgroup.co.uk.
