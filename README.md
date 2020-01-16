# next-peripheral

Proof-of-concept repository to see if it is feasable to create a single [Next.js](https://nextjs.org/) app and run it in multiple output devices.

Output devices are defined as

- IE11
- Firefox
- Chrome
- Safari Mobile
- Android Browser
- Capacitor

By framing browsers as output devices and listing Capacitor amongst them, we can apply the concept of `graceful degration` and `progressive enhancement` to than and focus on out app as a single code base that can be run _anywhere_\*.

<sub>\* Probably not really anywhere, but whereever it may be possible</sub>
