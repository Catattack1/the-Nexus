## Custom  Mana System for D&D

### Overview

This system replaces the traditional spell slot mechanic with a mana-based system, introducing more flexibility and strategic depth to spellcasting.

### Mana Points

- **Calculation**: A character's total mana points are determined by multiplying the level of each available spell slot by 2 and summing these values.
- **Regeneration**:
    - **Long Rest**: Characters regain all mana points.
    - **Short Rest**: Characters regain mana points equal to their spellcasting ability modifier.

### Mana Cost for Casting Spells
   1.  **1st-Level Spells**: Cost 1 mana point to cast.
   2. **2nd-Level Spells**: Cost 3 mana points to cast.
   3. **3rd-Level Spells**: Cost 5 mana points to cast.
   4. **4th-Level Spells**: Cost 7 mana points to cast.
   5. **5th-Level Spells**: Cost 10 mana points to cast.
   6. **6th-Level Spells**: Cost 14 mana points to cast.
   7. **7th-Level Spells**: Cost 18 mana points to cast.
   8. **8th-Level Spells**: Cost 24 mana points to cast.
   9. **9th-Level Spells**: Cost 30 mana points to cast.
### Upcasting Spells

- Upcasting spells become more mana-intensive. For each level above the spell's base level, double the mana cost of the base level spell.
- **Formula**: If a spell's base level is L and it's cast at level N (N > L), the mana cost is 2^(N - L) times the base level cost.

### Mana Potion

- Consumable items that restore mana points.
    - **Standard Mana Potion**: Restores 5 mana points.
    - **Greater Mana Potion**: Restores 10 mana points.
    - **Superior Mana Potion**: Restores 20 mana points.
    - **Supreme Mana Potion**: Restores all mana points.

### Mana-Related Feats

1. **Mana Saver**
    - Reduces the mana cost of spells by 1, minimum of 1 mana point.
2. **Mana Overflow**
    - Once per long rest, cast a spell without spending mana, up to a level equal to spellcasting ability modifier.
3. **Efficient Caster**
    - Gain extra mana points equal to twice the spellcasting ability modifier.
4. **Mana Regenerator**
    - Double the mana points regained during a short rest.
5. **Elemental Affinity**
    - Reduce the mana cost of spells with a chosen elemental damage type by 1.

### Notes for Implementation

- This system should be carefully balanced and may require adjustments based on gameplay.
- The mana system is fundamentally different from the traditional spell slot system and should be clearly explained to all players.
- Consider the impact of this system on different spellcasting classes and the overall game balance.
### Upcasting Costs

1. **Base Mana Cost for 1st-Level Spell**: 1 mana point.
    
2. **Additional Upcasting Costs**:
    
    - 1st to 2nd Level: +2 mana points
    - 2nd to 3rd Level: +4 mana points
    - 3rd to 4th Level: +6 mana points
    - 4th to 5th Level: +8 mana points
    - 5th to 6th Level: +10 mana points
    - 6th to 7th Level: +12 mana points
    - 7th to 8th Level: +14 mana points
    - 8th to 9th Level: +16 mana points

### Total Additional Cost Calculation for Upcasting from 1st to 9th Level

1. **1st to 2nd Level**: Base (1) + 2 = 3 mana points
2. **1st to 3rd Level**: Previous (3) + 4 = 7 mana points
3. **1st to 4th Level**: Previous (7) + 6 = 13 mana points
4. **1st to 5th Level**: Previous (13) + 8 = 21 mana points
5. **1st to 6th Level**: Previous (21) + 10 = 31 mana points
6. **1st to 7th Level**: Previous (31) + 12 = 43 mana points
7. **1st to 8th Level**: Previous (43) + 14 = 57 mana points
8. **1st to 9th Level**: Previous (57) + 16 = 73 mana points
### Total Additional Cost Calculation for Upcasting from 2nd to 9th Level:

- **2nd to 3rd Level**: Base (2) + 4 = 6 mana points
- **2nd to 4th Level**: Previous (6) + 6 = 12 mana points
- **2nd to 5th Level**: Previous (12) + 8 = 20 mana points
- **2nd to 6th Level**: Previous (20) + 10 = 30 mana points
- **2nd to 7th Level**: Previous (30) + 12 = 42 mana points
- **2nd to 8th Level**: Previous (42) + 14 = 56 mana points
- **2nd to 9th Level**: Previous (56) + 16 = 72 mana points
### Total Additional Cost Calculation for Upcasting from 3rd to 9th Level:

- **3rd to 4th Level**: Base (3) + 6 = 9 mana points
- **3rd to 5th Level**: Previous (9) + 8 = 17 mana points
- **3rd to 6th Level**: Previous (17) + 10 = 27 mana points
- **3rd to 7th Level**: Previous (27) + 12 = 39 mana points
- **3rd to 8th Level**: Previous (39) + 14 = 53 mana points
- **3rd to 9th Level**: Previous (53) + 16 = 69 mana points
### Total Additional Cost Calculation for Upcasting from 4th to 9th Level:

- **4th to 5th Level**: Base (4) + 8 = 12 mana points
- **4th to 6th Level**: Previous (12) + 10 = 22 mana points
- **4th to 7th Level**: Previous (22) + 12 = 34 mana points
- **4th to 8th Level**: Previous (34) + 14 = 48 mana points
- **4th to 9th Level**: Previous (48) + 16 = 64 mana points

### Total Additional Cost Calculation for Upcasting from 5th to 9th Level:

- **5th to 6th Level**: Base (5) + 10 = 15 mana points
- **5th to 7th Level**: Previous (15) + 12 = 27 mana points
- **5th to 8th Level**: Previous (27) + 14 = 41 mana points
- **5th to 9th Level**: Previous (41) + 16 = 57 mana points

### Total Additional Cost Calculation for Upcasting from 6th to 9th Level:

- **6th to 7th Level**: Base (6) + 12 = 18 mana points
- **6th to 8th Level**: Previous (18) + 14 = 32 mana points
- **6th to 9th Level**: Previous (32) + 16 = 48 mana points

### Total Additional Cost Calculation for Upcasting from 7th to 9th Level:

- **7th to 8th Level**: Base (7) + 14 = 21 mana points
- **7th to 9th Level**: Previous (21) + 16 = 37 mana points

### Total Additional Cost Calculation for Upcasting from 8th to 9th Level:

- **8th to 9th Level**: Base (8) + 16 = 24 mana points
## Max Mana Reference-M.M.R.
### sorcerer
1. Level 1: 4 mana points
2. Level 2: 6 mana points
3. Level 3: 16 mana points
4. Level 4: 20 mana points
5. Level 5: 32 mana points
6. Level 6: 38 mana points
7. Level 7: 46 mana points
8. Level 8: 54 mana points
9. Level 9: 72 mana points
10. Level 10: 82 mana points
11. Level 11: 94 mana points
12. Level 12: 94 mana points
13. Level 13: 108 mana points
14. Level 14: 108 mana points
15. Level 15: 124 mana points
16. Level 16: 124 mana points
17. Level 17: 142 mana points
18. Level 18: 152 mana points
19. Level 19: 164 mana points
20. Level 20: 178 mana points

### wizard
1. Level 1: 4 mana points
2. Level 2: 6 mana points
3. Level 3: 16 mana points
4. Level 4: 20 mana points
5. Level 5: 32 mana points
6. Level 6: 38 mana points
7. Level 7: 46 mana points
8. Level 8: 54 mana points
9. Level 9: 72 mana points
10. Level 10: 82 mana points
11. Level 11: 94 mana points
12. Level 12: 94 mana points
13. Level 13: 108 mana points
14. Level 14: 108 mana points
15. Level 15: 124 mana points
16. Level 16: 124 mana points
17. Level 17: 142 mana points
18. Level 18: 152 mana points
19. Level 19: 164 mana points
20. Level 20: 178 mana points

### warlock
1. Level 1: 2 mana points
2. Level 2: 4 mana points
3. Level 3: 8 mana points
4. Level 4: 8 mana points
5. Level 5: 12 mana points
6. Level 6: 12 mana points
7. Level 7: 16 mana points
8. Level 8: 16 mana points
9. Level 9: 20 mana points
10. Level 10: 20 mana points
11. Level 11: 30 mana points
12. Level 12: 30 mana points
13. Level 13: 30 mana points
14. Level 14: 30 mana points
15. Level 15: 30 mana points
16. Level 16: 30 mana points
17. Level 17: 40 mana points
18. Level 18: 40 mana points
19. Level 19: 40 mana points
20. Level 20: 40 mana points

### Druid
1. Level 1: 4 mana points
2. Level 2: 6 mana points
3. Level 3: 16 mana points
4. Level 4: 20 mana points
5. Level 5: 32 mana points
6. Level 6: 38 mana points
7. Level 7: 46 mana points
8. Level 8: 54 mana points
9. Level 9: 72 mana points
10. Level 10: 82 mana points
11. Level 11: 94 mana points
12. Level 12: 94 mana points
13. Level 13: 108 mana points
14. Level 14: 108 mana points
15. Level 15: 124 mana points
16. Level 16: 124 mana points
17. Level 17: 142 mana points
18. Level 18: 152 mana points
19. Level 19: 164 mana points
20. Level 20: 178 mana points

### Artificer
1. Level 1: 4 mana points
2. Level 2: 4 mana points
3. Level 3: 6 mana points
4. Level 4: 6 mana points
5. Level 5: 16 mana points
6. Level 6: 16 mana points
7. Level 7: 20 mana points
8. Level 8: 20 mana points
9. Level 9: 32 mana points
10. Level 10: 32 mana points
11. Level 11: 38 mana points
12. Level 12: 38 mana points
13. Level 13: 46 mana points
14. Level 14: 46 mana points
15. Level 15: 54 mana points
16. Level 16: 54 mana points
17. Level 17: 72 mana points
18. Level 18: 72 mana points
19. Level 19: 82 mana points
20. Level 20: 82 mana points

### Bard
1. Level 1: 4 mana points
2. Level 2: 6 mana points
3. Level 3: 16 mana points
4. Level 4: 20 mana points
5. Level 5: 32 mana points
6. Level 6: 38 mana points
7. Level 7: 46 mana points
8. Level 8: 54 mana points
9. Level 9: 72 mana points
10. Level 10: 82 mana points
11. Level 11: 94 mana points
12. Level 12: 94 mana points
13. Level 13: 108 mana points
14. Level 14: 108 mana points
15. Level 15: 124 mana points
16. Level 16: 124 mana points
17. Level 17: 142 mana points
18. Level 18: 152 mana points
19. Level 19: 164 mana points
20. Level 20: 178 mana points

### Ranger
1. Level 1: 0 mana points
2. Level 2: 4 mana points
3. Level 3: 6 mana points
4. Level 4: 6 mana points
5. Level 5: 16 mana points
6. Level 6: 16 mana points
7. Level 7: 20 mana points
8. Level 8: 20 mana points
9. Level 9: 32 mana points
10. Level 10: 32 mana points
11. Level 11: 38 mana points
12. Level 12: 38 mana points
13. Level 13: 46 mana points
14. Level 14: 46 mana points
15. Level 15: 54 mana points
16. Level 16: 54 mana points
17. Level 17: 72 mana points
18. Level 18: 72 mana points
19. Level 19: 82 mana points
20. Level 20: 82 mana points 
### Cleric
1. Level 1: 4 mana points
2. Level 2: 6 mana points
3. Level 3: 16 mana points
4. Level 4: 20 mana points
5. Level 5: 32 mana points
6. Level 6: 38 mana points
7. Level 7: 46 mana points
8. Level 8: 54 mana points
9. Level 9: 72 mana points
10. Level 10: 82 mana points
11. Level 11: 94 mana points
12. Level 12: 94 mana points
13. Level 13: 108 mana points
14. Level 14: 108 mana points
15. Level 15: 124 mana points
16. Level 16: 124 mana points
17. Level 17: 142 mana points
18. Level 18: 152 mana points
19. Level 19: 164 mana points
20. Level 20: 178 mana points


### Paladin
1. Level 1: 0 mana points
2. Level 2: 4 mana points
3. Level 3: 6 mana points
4. Level 4: 6 mana points
5. Level 5: 16 mana points
6. Level 6: 16 mana points
7. Level 7: 20 mana points
8. Level 8: 20 mana points
9. Level 9: 32 mana points
10. Level 10: 32 mana points
11. Level 11: 38 mana points
12. Level 12: 38 mana points
13. Level 13: 46 mana points
14. Level 14: 46 mana points
15. Level 15: 54 mana points
16. Level 16: 54 mana points
17. Level 17: 72 mana points
18. Level 18: 72 mana points
19. Level 19: 82 mana points
20. Level 20: 82 mana points

### Eldritch Knight (Fighter subclass)
1. Level 3: 4 mana points
2. Level 4: 6 mana points
3. Level 5: 6 mana points
4. Level 6: 6 mana points
5. Level 7: 16 mana points
6. Level 8: 16 mana points
7. Level 9: 16 mana points
8. Level 10: 16 mana points
9. Level 11: 20 mana points
10. Level 12: 20 mana points
11. Level 13: 32 mana points
12. Level 14: 32 mana points
13. Level 15: 32 mana points
14. Level 16: 38 mana points
15. Level 17: 46 mana points
16. Level 18: 46 mana points
17. Level 19: 54 mana points
18. Level 20: 54 mana points

### Arcane Trickster (Rogue subclass)
1. Level 3: 4 mana points
2. Level 4: 6 mana points
3. Level 5: 6 mana points
4. Level 6: 6 mana points
5. Level 7: 16 mana points
6. Level 8: 16 mana points
7. Level 9: 16 mana points
8. Level 10: 16 mana points
9. Level 11: 20 mana points
10. Level 12: 20 mana points
11. Level 13: 32 mana points
12. Level 14: 32 mana points
13. Level 15: 32 mana points
14. Level 16: 38 mana points
15. Level 17: 46 mana points
16. Level 18: 46 mana points
17. Level 19: 54 mana points
18. Level 20: 54 mana points




Total MP=Base MP+(MP per Level(10)×(Level−1))+ intelligence Ability Modifier



