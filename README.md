# Admin Items

> Three admin wands (explosion, lightning, meteor) granted per player from an in-game permission menu.

A Bedrock add-on with three wands and a permission system. A background loop enforces who is allowed to hold which wand: authorised players always keep theirs (even after death or a drop), unauthorised players lose it instantly - even if they got it through `/give`. **The first player to join a world becomes the owner** and grants the rest from the Admin Menu.

## What it does

- **Explosion Wand** - explosion on the targeted block (radius 8, with fire and block damage)
- **Lightning Wand** - 50 simultaneous lightning strikes around the target
- **Meteor Wand** - 10 burning TNT blocks rain down on the target over 2 seconds
- **Admin Menu** - set per player which wands they may hold, and tune radius, counts and spread
- Thrown/dropped wands are deleted instantly

## Download

Download **`Admin-Items-v1.0.0.mcaddon`** from the [releases page](../../releases) (or straight from this repository) and open it - Minecraft imports the packs.

1. Create or edit a world and open **Add-Ons**.
2. Activate the **Behavior Pack** and the **Resource Pack** of this add-on.
3. Requires Minecraft Bedrock **1.21.0 or newer**.

If items are missing in your world, check the world's *Experiments* page and enable *Beta APIs* and *Holiday Creator Features* as a fallback.

New to this? Follow **[SETUP-HELP.md](SETUP-HELP.md)** - it walks you through installing and starting it.

## Dev Book

Every pack of mine carries a small easter egg: craft the **Dev Book** with **9 logs** (any wood type, 3x3 in a crafting table) and right-click it. It opens like a book: page 1 the credits, page 2 what this mod is, page 3 the GitHub links (Minecraft cannot open links, so they are shown as text). It also sits in the creative inventory under *Equipment*.

## Notes

- These wands destroy terrain and can grief other players - use them on worlds and servers you run.
- Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.

---

Made by **dev:#2444** - [github.com/hash2444](https://github.com/hash2444) - [admin-items](https://github.com/hash2444/admin-items)
