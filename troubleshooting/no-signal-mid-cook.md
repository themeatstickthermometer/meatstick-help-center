---
gitbook_id: NEW-no-signal-mid-cook
gitbook_path: troubleshooting/no-signal-mid-cook
gitbook_slug: no-signal-mid-cook
gitbook_updated: 2026-06-10T00:00:00.000Z
title: "The app says \"no signal\" mid-cook"
---

# The app says "no signal" mid-cook

Losing the reading partway through a cook is almost always a range issue on the **Bluetooth** hop between your Stick and its receiver (your phone or base/hub). The cook itself keeps going — let's get the signal back.

## First, move the receiver closer

**Keep the receiver within about 6 feet of the Stick — closer is better.** When the Stick is sealed inside a smoker, oven, or grill, the metal and the seal weaken Bluetooth. Set your base or hub right on the cooker (use its magnetic back) rather than next to you, then walk away once it reconnects.

Water and metal make it worse — a sous vide bath, a metal pot, or foil-wrapped meat all absorb the signal. For those, get the receiver as close as the setup allows.

Full detail: [Range and connection drops](range-and-connection-drops.md).

## If you have a base or hub (Prime, Duo, Forge)

* Make sure the **base** is the thing near the Stick — it relays over Bluetooth and pushes the cook to WiFi.
* If your home **WiFi** dropped, you only lose the *remote* view. The base keeps streaming to your phone over Bluetooth whenever the phone is in range, and remote monitoring returns when WiFi does.

## If you're phone-direct (V Core)

There's no base relaying the signal, so your **phone** has to stay near the cooker (within ~6 ft). To roam farther, add a WiFi-capable set ([V Prime](../v-prime/whats-in-the-box.md), [V Duo](../v-duo/whats-in-the-box.md), or [V Forge](../v-forge/README.md)).

## Did I lose my cook data?

No. A dropout pauses live updates; it doesn't end the cook or erase what's logged. When the signal returns, the reading picks back up. If the Stick never reconnects even up close, see [My Stick won't connect](stick-wont-connect.md).
