# identify.filter

This Path of Diablo item filter is a tool to identify all stat and skill IDs. It
is meant as an aid for filter writers, *not* for use while playing the game.

If you look at the filter file (or its output ingame), you'll see a lot of stat
and skill IDs are listed either in purple, or bold (cyan). Purple means I have
no idea what the stat is or does. Cyan means I have a good guess, but no
confirmation that it's actually correct (because I don't have the item in
question). **Contributions are very welcome!**

I've defined 4 filter levels:
- Level 1 shows stat IDs 0-80
- Level 2 shows all remaining stat IDs, 81-510
- Level 3 shows all skill-related stats: SK1 through SK694, TABSK0 through TABSK50, and CLSK0 through CLSK6

These *should* be safe. The reason not everything is shown at the same time is
that this creates overly long item names that crash the game (with an
astoundingly useless error).

If you absolutely must, you can select filter level 4, which shows everything at
once. Crash the game to your heart's content!
