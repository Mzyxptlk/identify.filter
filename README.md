# identify.filter
This PoD item filter is a tool to identify all stat IDs on items by name.

If you look at the filter file, you'll see a lot of stat IDs are listed either
in purple, or bold/cyan. Purple means I have no idea what the stat is or does.
Cyan means I have a good guess, but no confirmation that it's actually correct
(because I don't have the item in question). **Contributions welcome!**

I've defined 4 filter levels:
- Level 1 shows stat IDs 0-80
- Level 2 shows all remaining stat IDs, 81-510
- Level 3 shows all skill-related stats, SK1 through SK694, TABSK0 through TABSK50, and CLSK0 throuhg CLSK6

These *should* be safe.

Now, I hear you. "Why don't you just show all stats at the same time, Mzyxptlk?"

It's a good question. The reason is that when the name of an item gets too long,
the game crashes (throwing an astoundingly useless error). However, just for the
sake of completeness I've added a final filter level (level 4, shockingly!) that
does just that. Crash the game to your heart's content! It'll happen whenever
the game has to deal with an item with an overly long name, anywhere the item
filter applies, whether in your inventory, in a shop, on the ground, etc.
