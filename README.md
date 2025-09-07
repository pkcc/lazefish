# Lazefish

Lazefish is an automatic fishing assistant for TERA that casts the line, reels in catches and keeps your inventory tidy by crafting bait and dismantling fish. It can also maintain your fish salad buff automatically once configured.

Visit https://fish.lazebot.com to activate or extend your license. A three-day free trial is available; please make sure the trial meets your needs before purchasing the full version.

## Commands

- `fish` / `!fish` - Toggle fishing on or off. This command re-checks your license before toggling.
- `fish dismantle` - Toggle auto dismantling of common fish.
- `fish gold` - Toggle auto dismantling of gold fish.
- `fish reset` - Reset bait, craft and dismantle options and disable fast mode.
- `fish list` - Show current configuration including fast mode.
- `fish fast` - Toggle fast fishing mode. Sets delays to:
  - THROW_ROD: 2000-3000 ms
  - FISH_START: 2000-3000 ms
  - FISH_CATCH: 4000-4000 ms
  - no delay based on fish tier
  Mode selection is saved automatically.
- `fish save` - Save settings to disk.
- `fish load` - Load settings from disk.
- `fish license` - Check license status.
- `fish set salad` - After running, eat a fish salad manually. Lazefish will store its item and buff IDs and auto-eat it when the buff expires.
- `fish salad` - Display the currently saved salad information.
