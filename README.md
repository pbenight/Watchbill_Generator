# Watchbill Generator
Watchbill is a Navy term for a shift schedule based on specific Navy requirements.
This program is built to generate a watchbill from a collection of sailors.

## Description of a watchbill's life cycle:

Firstly, what is a watchbill? A watchbill is a table of requirements listing out who is required to take what watches. Some watches are time-bound, some have more requirements, some are more harsh than others. It's good to keep all these traits in mind.

Each watchbill is made of duty sections, decided upon by the watch officer. These duty sections are passed the required days and positions that they are required to fill.

Each duty section then pulls every individual that has a specific watch qualification and places them in the most restrictive positions first, based on when the individual last stood watch. (OOD filled first, then JOOD, then unqualified watch-standers.) If there are more qualified watchstanders than there are unqualified watchstanders, they then become fair-game. For filling the spots that do not require qualifications, I recommend filling them with the individuals that have been on watch the least recent. If you've sorted correctly, this should be the most underutilized individuals anyway.

If there are time-restrictions for certain sailors based on duty-days, I'd keep those in mind too (similar for those who work nights/weekends, etc.) 
