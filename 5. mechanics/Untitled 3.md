32

### Mana Cost for Casting Spells
   1.  **1st-Level Spells**: Cost 1 mana point to cast.
   2. **2nd-Level Spells**: Cost 3 mana points to cast.
   3. **3rd-Level Spells**: Cost 5 mana points to cast.
   4. **4th-Level Spells**: Cost 7 mana points to cast.

### Upcasting Spells

- Upcasting spells become more mana-intensive. For each level above the spell's base level, double the mana cost of the base level spell.
- **Formula**: If a spell's base level is L and it's cast at level N (N > L), the mana cost is 2^(N - L) times the base level cost.