# mta-sts-no

MTA-STS-policy för `mta-sts.resultify.no`. Publiceras via GitHub Pages.

- Filen ligger på `https://mta-sts.resultify.no/.well-known/mta-sts.txt` och ska svara 200 utan omdirigering.
- Ändra `id` i DNS-posten `_mta-sts.resultify.no` varje gång filen ändras.
- `mode: testing` tills två veckor utan fel. Därefter `mode: enforce` och `max_age: 1209600`, med nytt `id`.
