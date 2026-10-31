# 0.2.22 — Morph Unlock Handbook (Alpha)

Craft a book with rotten flesh in any order. Right-click the handbook to view your personally learned vanilla mob forms. In Creative mode, each eligible mob has a Learn this form button; learned entries are marked and disabled. Pages remain selected after the server confirms an unlock.

Unlocks persist on the player, not the book, and do not grant kill statistics, the Soul Migration Echo or free casting. Server checks current Creative mode, held handbook, valid vanilla mob and request cooldown. Client requests are rate-limited without leaving buttons permanently disabled.

Client and server must both update: Soul Migration channel protocol is now version 2. Full species parity and actual two-client acceptance remain unfinished. This is an alpha; back up worlds before updating.

Independent tests cover survival rejection without mutation, invalid/modded/non-mob rejection, idempotent creative unlocking, persistence across mode changes, and unmodified kill statistics. Existing morph regressions also run in an isolated save.
