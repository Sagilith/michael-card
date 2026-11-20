# Michael Wunderlich — digital business card

A simple mobile page for Michael, a kayak and paddleboard guide at SURFIT USA in Sarasota. Built to open from an NFC bracelet tap.

## Venmo handle

The handle is a single constant at the top of the script in `index.html`:

```js
const VENMO_HANDLE = "michael-wunderlich-13";
```

Change that value to update the on-page handle, the **Pay with Venmo** button (`https://venmo.com/u/<handle>`), and the QR code. Leave it as an empty string (`""`) to show “Venmo handle coming soon” instead.
