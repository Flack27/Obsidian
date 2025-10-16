## Core Tracking

### **Resources to Track**

1. **Population** (current number of villagers)
2. **Housing Capacity** (max villagers you can house)
3. **Morale** (scale of 1-10)
4. **Marble blocks**
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
- **Requirement:** Carpenter
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

- Cost: 0 GP
- Worker: None
- Laborers: 0
- Requirements: None
- Production: None

**Level 1: Basic Operations**

- Cost: 500 GP | Time: 2 months
- Worker: Mine Foreman
- Laborers: 5
- Requirements: Mine Foreman
- Production: 10 blocks/turn

**Level 2: Expanded Operations**

- Cost: 2500 GP | Time: 4 months
- Worker: Mine Foreman
- Laborers: 10
- Requirements: Blacksmith, Mine Foreman
- Production: 25 blocks / turn

**Level 3: Full Operations**

- Cost: 10000 GP | Time: 2 months
- Worker: Mine Foreman, Pit Boss
- Laborers: 20
- Requirements: Mine Foreman, Pit Boss, Blacksmith (level 2)
- Production: 100 blocks/turn

### **FARMLAND**

**Building Slots per Level**: 2 / 5 / 10 **Workers Needed**: 4 / 10 / 20

**Level 0: Overgrown** (Starting state)

- Must clear fields (1 month free labor or 200 GP + 2 weeks)

**Level 1: Subsistence Farming**

- Cost: 400 GP | Time: 2 months
- Requirements: Fields cleared, basic tools
- Feeds: 50 villagers
- Income: 0 GP (subsistence only)

**Level 2: Productive Farming**

- Cost: 800 GP | Time: 4 months
- Requirements: Level 1, Mill, barn restored
- Feeds: 100 villagers
- Income: 50 GP/turn (surplus sold)

**Level 3: Commercial Farming**

- Cost: 1,500 GP | Time: 6 months
- Requirements: Level 2, irrigation system
- Feeds: 300 villagers
- Income: 150 GP/turn (major surplus)

### **RIVER TRADE (Harbor)**

**Building Slots per Level**: 2 / 5 / 10 **Workers Needed**: 4 / 10 / 20

**Level 0: Destroyed** (Starting state)

- Must repair basic dock (300 GP + 1 month)

**Level 1: Basic Dock**

- Cost: 300 GP | Time: 2 months
- Requirements: Dock repaired, Dock Master
- Income: 50 GP/turn
- Benefits: Can trade with Quathala, faster travel

**Level 2: Trade Port**

- Cost: 700 GP | Time: 4 months
- Requirements: Level 1, warehouse, 2+ vessels
- Income: 100 GP/turn
- Benefits: +10% to all trade-based income

**Level 3: Commercial Harbor**

- Cost: 1,500 GP | Time: 6 months
- Requirements: Level 2, multiple warehouses, 4+ vessels
- Income: 200 GP/turn
- Benefits: +25% to all trade-based income, attracts merchants

---

## Extra Facilities (Examples)

### **CARPENTER WORKSHOP**

**Building Slots**: 1 **Workers Needed**: 2 **Cost**: 300 GP | **Time**: 1 month **Requirements**: Henrik Stonewright

**Level 1 Benefits:**

- Reduces upkeep die: d12 → d10
- Reduces construction costs: -10%
- Income: 20 GP/turn

**Level 2 Upgrade**: 500 GP | 2 months

- Reduces upkeep die: d10 → d8
- Reduces construction costs: -15%
- Reduces construction time: -25% (1 month off, minimum 1)
- Income: 40 GP/turn

### **BLACKSMITH**

**Building Slots**: 1 **Workers Needed**: 2 **Cost**: 400 GP | **Time**: 1 month **Requirements**: Skilled blacksmith

**Benefits:**

- Reduces all upkeep by 2 GP
- Can craft/repair weapons and armor
- Income: 30 GP/turn
- Enables mine upgrades (needs tools)

### **INN (The Miner's Rest)**

**Building Slots**: 2 **Workers Needed**: 3 **Cost**: 500 GP | **Time**: 2 months **Requirements**: Innkeeper, population 40+

**Benefits:**

- +1 Morale (permanent)
- Income: 40 GP/turn
- Social hub (gather rumors, recruit easier)
- Party can rest free

### **MILL**

**Building Slots**: 1 **Workers Needed**: 1 **Cost**: 200 GP | **Time**: 1 month **Requirements**: Miller, Level 1 Farm

**Benefits:**

- Required for Farm Level 2+
- Lookout tower (advantage spotting threats)
- Income: 15 GP/turn (milling fees)

### **BARRACKS**

**Building Slots**: 2 **Workers Needed**: 5 (defenders) **Cost**: 500 GP | **Time**: 2 months  
**Requirements**: Population 50+, Sergeant/Leader

**Benefits:**

- Houses 5 trained guards
- +5 to defense rolls
- Defender upkeep: 5 GP per defender per turn