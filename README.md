# identify.filter
This PoD item filter is a tool to identify all stat IDs on items by name.

If you look at the filter file, you'll see a lot of stat IDs are listed either
in purple, or bold/cyan. Purple means I have no idea what the stat is or does.
Cyan means I have a good guess, but no confirmation that it's actually correct
(because I don't have the item in question). **Contributions welcome!**

I've defined 3 filter levels. Level 1 shows stat IDs 0-80, and level 2 shows all
remaining stat IDs, 81-510. These *should* be safe.

Now, I hear you. "Why don't you just show all stats at the same time, Mzyxptlk?"

It's a good question. The reason is that when the name of an item gets too long,
the game crashes (throwing an astoundingly useless error). However, just for the
sake of completeness I've added a third filter level (level 3, shockingly!) that
does just that. Crash the game to your heart's content! It'll happen whenever
the game has to deal with an item with an overly long name, anywhere the item
filter applies, whether in your inventory, in a shop, on the ground, etc.
