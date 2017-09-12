# GetSpellInfoVanilla
An addon to help developers access information about spells, for example to create buffs for addons


There are essentially 4 global methods you can call from other addons:

> Name is always the spellname as returned by GetSpellInfo(id) in World of Warcraft 2.0+
>
> Icon is the client's path to the used icon e.g. "\\Interface\\..." as returbed by GetSpellInfo(id) in World of Warcraft 2.0+

### function GetSpellInfoById(id) 

returns [name, rank, icon, cost, isFunnel, powerType]

### function GetSpellInfoByIcon(Icon) 

returns a table of [name, rank, icon, cost, isFunnel, powerType] with the spellID as keys

### function GetSpellInfoByName(Name) 

returns a table of [name, rank, icon, cost, isFunnel, powerType] with the spellID as keys

### function GetSpellInfoByIconAndName(Icon, Name)

returns a table of [name, rank, icon, cost, isFunnel, powerType] with the spellID as key


