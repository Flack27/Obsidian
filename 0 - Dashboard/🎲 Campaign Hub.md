## Quick Session Prep

### Active NPCs This Session
**Location Filter:** Change "Stonewall" to wherever party currently is
```dataview
TABLE relationship, status, importance, character-arc
FROM "1 - Characters/NPC's"
WHERE type = "npc" AND location = "Stonewall" AND status = "alive"
SORT importance DESC, relationship ASC
```

### All Major NPCs (Cross-Reference)
```dataview
TABLE status, location, relationship, act-introduced
FROM "1 - Characters/NPC's"
WHERE type = "npc" AND importance = "major"
SORT act-introduced ASC, file.name ASC
```

### Upcoming Reveals by Act
```dataview
TABLE file.name as "What Gets Revealed", act-revealed as "When"
FROM "1 - Characters" OR "3 - Lore"
WHERE act-revealed != null
SORT act-revealed ASC
```


**Act 1 Progress:**
```dataview
TASK
FROM "0 - Dashboard/Act 1 - Stonewall"
```