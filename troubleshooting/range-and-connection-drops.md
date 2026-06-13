---
gitbook_id: NEW-range-and-connection-drops
gitbook_path: troubleshooting/range-and-connection-drops
gitbook_slug: range-and-connection-drops
gitbook_updated: 2026-06-10T00:00:00.000Z
title: "Range and connection drops"
---

# Range and connection drops

If your reading keeps dropping out or the Stick disconnects mid-cook, it's almost always a Bluetooth-range issue. Here's how the signal actually works and how to keep it solid.

## How the signal travels

Your Stick sends its data over **Bluetooth** to the nearest receiver — your phone, or a Smart Base / WiFi Hub / Xtender™. That first Bluetooth hop is the fragile one. From there, a base or hub can relay the cook over WiFi to anywhere in the world, but it can only relay a signal it's actually receiving.

The Bluetooth antenna sits in the Stick's ceramic handle. A clear line of sight between the Stick and the receiver dramatically improves range — and most cooking setups don't give you one.

## The one rule that fixes most drops

**Keep the receiver within about 6 feet of your Stick — closer is better.**

The big range numbers on the box are measured in open air with nothing in the way. Real cooking is the opposite. What weakens the signal, worst first:

| Makes it worse | Why |
|---|---|
| Sealed smoker walls | Thick metal + a tight seal block the signal |
| Closed oven cavity | Metal box around the Stick |
| Sous vide bath | Water absorbs the 2.4 GHz signal |
| Metal pot (sous vide / deep fry) | Metal vessel plus liquid |
| Foil-wrapped meat | Even foil attenuates the signal |

Thicker walls, tighter seals, more liquid, more metal = more signal loss. For any of these, get the receiver as close to the Stick as the setup allows.

## How a base or hub extends your range

If your Stick comes with a Smart Base or WiFi Hub, it does two jobs:

* **Xtender™ (Bluetooth):** the base relays the Stick's signal, pushing usable range much farther than phone-direct.
* **WiFi bridge:** the base connects to your home WiFi and streams the cook to the cloud — so once it has the Stick's signal, you can monitor from the store, the office, or bed.

The trick is the same: place the **base** close to the Stick (within ~6 ft), not close to you. Set it on the smoker's side panel with the magnetic back, or right next to a sous vide bath. Once it has the signal, walk away.

Device-specific placement tips:

* [V Smart Base placement](../v-prime/smart-base.md) (antenna under the logo)
* [V WiFi Hub placement](../v-forge/wifi-hub.md)

## If you're running phone-direct (V Core, no base)

A V Core Set talks straight to your phone with no base to extend it. There's no WiFi fallback, so the phone has to stay near the cooker — within about 6 feet. To monitor from another room or leave the house, step up to a set with a built-in WiFi receiver ([V Prime](../v-prime/whats-in-the-box.md), [V Duo](../v-duo/whats-in-the-box.md), or [V Forge](../v-forge/README.md)).
