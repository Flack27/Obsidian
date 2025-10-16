## Core Tracking

### **Resources to Track**

1. **Population** (current number of villagers)
2. **Housing Capacity** (max villagers you can house)
3. **Morale** (scale of 1-10)
4. **Marble blocks** (20 GP / Block)
5. **Buildings** (what exists and their levels)
6. **Workers Assigned / Available** (population % 2)

---

## Morale System

### **Morale Scale: 1-10**

### **Morale Effects**

**Low Morale (1-3):**

- Recruitment: Disadvantage on checks
- Risk: Each turn, roll d20. On 1-5, lose 1d6 villagers (they leave)

**Normal Morale (4-7):**

- Everything functions normally

**High Morale (8-9):**

- Recruitment: Advantage on checks
- Growth: +1d4 villagers arrive each turn

**Excellent Morale (10):**

- Recruitment: Advantage on checks
- Growth: +1d6 villagers arrive each turn
- Advantage on all checks related to village or villagers

### **Morale Modifiers** (Calculated each turn)

**Automatic Modifiers:**

- **Housing**: Shortage (more people than capacity) **-1** / Surplus (10+ empty spaces) **+1**
- **Food**: Shortage (can't feed everyone) **-1** / Surplus (can feed 10+ more) **+1**
- **Leadership**: Leader absent 4+ turns **-1**  / Leader present **+1**
- **Security**: Recent loss defending village (last 4 turns) **-2** / recent victory defending village: **+2

**Party Actions** (DM discretion, temporary bonuses lasting 1-4 turns)


---

## Housing System

### **Housing Types**

**Basic House**

- **Capacity**: 5 villagers
- **Cost**: 100 GP
- **Requirement:** Carpenter
- **Time**: 1 month (4 turns)

**Large House**

- **Capacity**: 10 villagers
- **Cost**: 250 GP
- **Requirement:** Carpenter (level 2)
- **Time**: 1.5 months (6 turns)

---

## Food System

### **Food Cost**

- Pay **10 GP per 10 villagers** per turn (rounded up)
### **Farm Production** (Once built)

- **Level 1 Farm**: Feeds 50 villagers
- **Level 2 Farm**: Feeds 100 villagers
- **Level 3 Farm**: Feeds 300 villagers

### **Food Calculation**

**Simple Check:**

- Can farm feed everyone? If yes, no cost
- Can farm feed 10+ more than population? +1 Morale
- Can't feed everyone? -1 Morale AND pay 10 GP per 10 unfed villagers

**Example**: 60 villagers, Level 1 farm

- Farm feeds 50
- 10 unfed: -1 Morale + pay 10 GP this turn
- Need Level 2 farm or build more houses to reduce population

---

## Base Facilities

### **MARBLE MINE**

**Level 0: Collapsed**

- Must clear broken equipment / rubble (1 month + 500 GP)

**Level 1: Basic Operations**

- Cost: 500 GP | Time: 2 months
- Worker: Mine Foreman
- Laborers: 5
- Requirements: Mine Foreman + Mine cleared
- Production: 10 blocks/turn

**Level 2: Expanded Operations**

- Cost: 2000 GP | Time: 4 months
- Worker: Mine Foreman
- Laborers: 10
- Requirements: Mine Foreman + Blacksmith
- Production: 25 blocks / turn

**Level 3: Full Operations**

- Cost: 10000 GP | Time: 2 months
- Worker: Mine Foreman + Pit Boss
- Laborers: 20
- Requirements: Mine Foreman + Pit Boss + Blacksmith (level 2)
- Production: 100 blocks/turn

### **FARMLAND**

**Level 0: Overgrown** (Starting state)

- Must clear fields (1 month free labor or 200 GP + 2 weeks)
- Pay **10 GP per 10 villagers** per turn (rounded up) without enough food production

**Level 1: Subsistence Farming**

- **Cost**: 400 GP | **Time**: 2 months
- **Worker**: Experienced Farmer
- **Laborers**: 5
- **Requirements**: Fields cleared + Blacksmith
- **Production**: Feeds 50 villagers

**Level 2: Productive Farming**

- **Cost**: 800 GP | **Time**: 4 months
- **Worker**: Experienced Farmer
- **Laborers**: 10
- **Requirements**: Blacksmith + Barn restored (300 GP)
- **Production**: Feeds 150 villagers

**Level 3: Commercial Farming**

- **Cost**: 1,500 GP | **Time**: 6 months
- **Worker**: Experienced Farmer
- **Laborers**: 20
- **Requirements**: Blacksmith (level 2)
- **Production**: Feeds 300 villagers

### **RIVER TRADE (Harbor)**

**Level 0: Destroyed** (Starting state)

- Must repair basic dock (300 GP + 1 month)

**Level 1: Basic Dock**

- **Cost**: 500 GP | **Time**: 2 months
- **Worker**: Dock Master + Captain
- **Laborers**: 5
- **Requirements**: Dock repaired + Carpenter
- **Production**: Can transport and sell marble blocks
- **Ship**: Small Cargo Barge (capacity: 10 blocks)
- **Trade Routes**:
    - **Quathala**: 1 turn round trip, base price + 1d10% markup
- **Benefits**: Party can travel to Quathala on ship

**Level 2: Trade Port**

- **Cost**: 1000 GP | **Time**: 4 months
- **Worker**: Dock Master + Captain x 2
- **Laborers**: 20
- **Requirements**: Level 1, warehouse
- **Production**: Multiple trade routes
- **Ships**:
    - Medium Cargo Ship (capacity: 50 blocks)
    - Small Sloop (party travel vessel)
- **Trade Routes**:
    - **Quathala**: 1 turn, base price + 1d10% markup
    - **Shurima**: 2 turns, base price + 1d20+10% markup (10-30% more)
- **Benefits**: 

**Level 3: Commercial Harbor**

- **Cost**: 5000 GP | **Time**: 6 months
- **Worker**: Dock Master + Captain x 3
- **Laborers**: 40
- **Requirements**: Level 2, multiple warehouses, shipping office
- **Production**: Major trade hub
- **Ships**:
    - Large Cargo Galleon (capacity: 100 blocks)
    - Large Cargo Galleon (capacity: 100 blocks)
    - Fast Clipper (twice as fast as a sloop)
- **Trade Routes**:
    - **Quathala**: 1 turn, base price + 1d10%
    - **Shurima**: 2 turns, base price + 1d20+10% (10-30% more)
    - **Piltover**: 4 turns, base price + 2d20+20% (20-60% more)
    - **Bilgewater**: 6 turns, base price + 2d100% (2-200% more, very volatile)
- **Benefits**: Run two trade routes at once, warehouse stores 200 blocks

---

## Extra Facilities

### **CARPENTER WORKSHOP**

**Level 1: Basic Workshop**

- **Cost**: 300 GP | **Time**: 1 month
- **Worker**: Carpenter
- **Laborers**: 2
- **Requirements**: Carpenter
- **Benefits**: Reduces all construction time by 25% (minimum 1 month)

**Level 2: Master's Workshop**

- **Cost**: 600 GP | **Time**: 2 months
- **Worker**: Carpenter
- **Laborers**: 3
- **Requirements**: Carpeting books (400 GP)
- **Benefits**: Reduces construction time by 33% (minimum 1 month)

---

### **BLACKSMITH**

**Level 1: Basic Forge**

- **Cost**: 400 GP | **Time**: 1 month
- **Worker**: Blacksmith
- **Laborers**: 2
- **Requirements**: Blacksmith
- **Benefits**: can craft/repair basic weapons and armor (costs normal price)

**Level 2: Master Forge**

- **Cost**: 700 GP | **Time**: 2 months
- **Worker**: Blacksmith
- **Laborers**: 3
- **Requirements**: Blacksmith
- **Benefits**: can craft all weapons/armor (costs half price)

**Level 3: Arcane Smithy**

- **Cost**: 2,000 GP | **Time**: 4 months
- **Worker**: Blacksmith + Enchanter
- **Laborers**: 4
- **Requirements**: Blacksmith + Enchanter

**Crafting Capabilities** (Based on worker skill levels):

**Common Magic Items**:

- Requirements: Basic Enchanter
- Cost: 100 GP + 1 week

**Uncommon Magic Items**:

- Requirements: Basic Enchanter
- Cost: 500 GP + 2 weeks

**Rare Magic Items**:

- Requirements: Intermediate Enchanter
- Cost: 2,500 GP + 1 month

**Very Rare Magic Items**:

- Requirements: Expert Enchanter
- Cost: 15,000 GP + 3 months
- May require additional special materials

**Legendary Magic Items**:

- Requirements: Master Enchanter
- Cost: 50,000 GP + 6 months
- May require additional special materials

---

### **INN (The Miner's Rest)**

**Level 1: Basic Inn**

- **Cost**: 250 GP | **Time**: 2 months
- **Worker**: Innkeeper
- **Laborers**: 3
- **Requirements**: Population 40+
- **Benefits**: +1 Morale (permanent)

**Level 2: Grand Inn**

- **Cost**: 500 GP | **Time**: 3 months
- **Worker**: Innkeeper + Head Chef
- **Laborers**: 5
- **Requirements**: Level 1, Population 100+
- **Benefits**: +3 Morale (permanent)

---

### **MANOR (Party Residence)**

**Level 1: Basic Manor**

- **Cost**: 800 GP | **Time**: 3 months
- **Worker**: Steward
- **Laborers**: 4 (3 servants, 1 chef)
- **Requirements**: Population 20+
- **Benefits**:
    - Private residence with individual rooms
    - +1 Morale

**Level 2: Grand Estate**

- **Cost**: 2,000 GP | **Time**: 4 months
- **Worker**: Steward + Butler
- **Laborers**: 8 (6 servants, 1 chef, 1 groundskeeper)
- **Requirements**: Population 100+
- **Benefits**:
    - +2 Morale
    - Private stables (party mounts housed for free)
    - Guest quarters (can host important NPCs)

**Level 3: Noble Estate**

- **Cost**: 5,000 GP | **Time**: 6 months
- **Worker**: Steward + Butler + Estate Manager
- **Laborers**: 12 (8 servants, 1 chef, 2 groundskeepers, 1 stable master)
- **Requirements**: Population 150+
- **Benefits**:
    - +3 Morale
    - Estate Manager manages village operations when party absent no "Leader absent" penalty
    - Vault (secure storage for valuables)

---
### **LIBRARY (Research Facility)**

**Level 1: Scholar's Library**

- **Cost**: 600 GP | **Time**: 2 months
- **Worker**: None (self-service)
- **Laborers**: 0
- **Requirements**: Carpenter
- **Benefits**:
    - Can purchase research books for Enchanter training
    - Party can research here (advantage on History, Arcana, or Nature checks when they have time to study - takes 1 day per topic)

**Book Costs** (Add to library collection):

- **Intermediate Enchanting Compendium**: 2500 GP (takes 2 months to study)
- **Expert Arcane Treatises**: 7500 GP (takes 4 months to study)
- **Master's Forbidden Grimoire**: 20,000 GP (takes 6 months to study)
- **General Knowledge Books**: 100 GP per subject (History, Nature, Religion, etc. - provides knowledge and research advantage for that topic)

---
### **HUNTING LODGE**

**Level 1: Basic Lodge**

- **Cost**: 200 GP | **Time**: 1 month
- **Worker**: None
- **Laborers**: 2 (hunters)
- **Requirements**: Carpenter
- **Production**:
    - 2d6 x 10 GP worth of pelts/meat per turn
    - Provides food for 10 villagers
- **Benefits**:
    - Early warning system (hunters scout the area, advantage on spotting approaching threats)

**Level 2: Hunter's Guild**

- **Cost**: 500 GP | **Time**: 1 month
- **Worker**: Hunt Master
- **Laborers**: 4 (hunters)
- **Requirements**: Carpenter
- **Production**:
    - 4d12 x 10 GP worth of pelts/furs/meat per turn
    - Provides food for 30 villagers
- **Benefits**:
	- Early warning system (hunters scout the area, advantage on spotting approaching threats)


