# Component Naming
---
## Family Naming

> [Originator]-[Category]-[Description]

**Originator:** ART for Architype

**Category:** choose one of the acronyms from the list below.

| Category | |
| ---- | ---------- |
|ANO|   Annotations |
|BAP|	Baluster panel|
|BPT|   Baluster post|
|BAL|   Balusters|
|CAB|	Cable Trays|
|CAS|	Casework|
|CWA|	Casework wall based|
|CEL|	Ceilings|
|COL|	Column|
|CPP|	Curtain panel pattern based|
|CUR|	Curtain wall panel|
|CUS|	Curtain Systems|
|DEI|	Detail items|
|DOR|	Door|
|DCW|	Door curtain wall|
|EEQ|	Electrical equipment|
|EFX|	Electrical fixture|
|EFC|	Electrical fixture ceiling based|
|EFW|	Electrical fixture wall based|
|ENT|   Entourage|
|FPT|	Fire Protection|
|FUR|	Furniture|
|LGF|	Lighting Fixtures|
|GEN|	Undefined Generic Model|
|MAS|	Mass|
|MEQ|	Mechanical equipment|
|PAR|	Parking|
|PLA|	Planting|
|PLU|	Plumbing|
|PRO|	Profile|
|PRH|	Profile – hosted|
|PRM|	Profile – mullion|
|PRR|	Profile – rail|
|PRV|	Profile – reveal|
|PRS|	Profile – stair nosing|
|RAL|	Railings|
|RPC|	RPC|
|SIT|	Site|
|SPC|	Speciality equipment|
|STC|	Structural column|
|STF|	Structural foundation|
|STB|	Structural framing beams & braces|
|SFT|	Structural framing complex & trusses|
|STT|	Structural trusses|
|TBL|	Titleblocks|
|	|   |
|FFT|	Floor Finish Type|
|IFT|	Internal Floor Type|
|EFT|	External Floor Type|
|EWT|	External Wall Type|
|IWT|	Internal Wall Type|
|CWT|	Curtain Wall Type|
|SWT|	Stacked Wall Type|
|FRT|	Flat Roof Type|
|PRT|	Pitched Roof Type|
|WIN|	Window|
|IDT|	Internal Door Type|
|EDT|	External Door Type|

**Description:** A short but readable description, with underscores between words. Don’t include type / specific size in file name like chair 1420, cabinet h900. 


!!! Example
    ART-FUR-Office_Chair	

---

## Family Type Naming

If a Family has only one Type, it should be named *Default* 

The Type name should be brief but descriptive. It shouldn’t include the Family name in the Type name - e.g. use 900 rather than Door 900

Where there is a dimension in the type name there should be no space between the number and the ‘x’ and the units should be shown. i.e. 1000x1200mm

You could also add the dimensions as parameters and add these to the label and use schedules to confirm the name matches the dims.

*Examples:*

ART-DEI-Plywood (Family name)

- 9mm	        (Type Name)
- 12mm

ART-DEI-Refuge_Symbol (Family name)

-	Default (Type Name)


!!! Note
    When you are loading in families or other objects, ensure that you have renamed them to comply with the standards in this document. 
    For example, when loading or using Enscape families. 

---

## Levels Naming

Levels should be named in accordance with:

> [Number]-[Volume-optional]-[Description]

**Number:** 2 digit level number

**Volume:** As described in ['File Naming'](file-naming.md)

**Description:** a concise description of the level, with underscores between words. 

!!! Example 
     01-A-First_Floor

---

##  Rooms / Spaces / Units Naming

The following full naming convention should be used:

> [Level]-[Number]-[Identifier–optional]–[Description]

**Level:** As described in ['File Naming'](file-naming.md)

**Number:** In principle, the main building entrance (or the primary space when entering the facility e.g. Entrance Lobby) will be numbered 001, the initial room number.

From Location 001, the process is referred to as the ‘left hand rule method’ where you would run your hand along the left hand wall of Location 001 and as soon as you enter another location (through a door) then this would be Location 002. 

If the room you are in has a cupboard / store located within it then this should be regarded as another Location with the appropriate number allocated.

**Stairwells:** Stairwells should be tagged with the same room number as they are on the ground floor, or whatever floor they begin on i.e. the same Location number is used for the whole stairwell (on all floors). 

**Lifts / Lift Shafts:** Each lift and the associated Lift Shaft should be allocated a room number on the lowest floor and the same number used throughout the document on subsequent levels. If there is more than one lift (and shaft) it would have its own number.

**Basements / Outbuildings:** When all floors from the Ground up have been tagged then the final step would be to tag the basement followed by any outbuildings on site.

**Identifier:** *Insert Text Here*

**Description:** a common or given name which represents the intended use or function of the room, with underscores between words. Multiple rooms in the same building may have identical room names, e.g Classroom. It is not necessary to differentiate them, e.g. Classroom A, Classroom B, etc.

!!! Example 
     A-01-001-LR-Living_Room

---

## Masses Naming

Masses are created through the ‘Massing & Site’ tab within the ‘Conceptual Mass’ panel – ‘In-place mass’. They are usually used for conceptual design to show the gross volume, gross floor area, and gross surface area of a mass or to apply walls at strange angles using ‘apply to face’.

They should be named following the families naming convention. 

> [Originator]-[Category]-[Description]

**Originator:** As described in ['File Naming'](file-naming.md)

**Category:** MAS for Mass

**Description:** A short but readable description with underscores between words. If the mass is level specific add the level or zone acronym after the description i.e. 01(Fist Floor) or SB (Sports block)

!!! Example 
    ART-MAS-Existing_Building

!!! Note
    They should not be named Mass 1, Mass 2 etc. There should be no duplicates of masses, the description should differentiate between them. 

Click <a href="https://knowledge.autodesk.com/support/revit-products/learn-explore/caas/CloudHelp/cloudhelp/2018/ENU/Revit-Model/files/GUID-A180B32D-E7B8-474F-AB31-B15EDB874F6E-htm.html" target="_blank">here</a> for more information about Masses from Autodesk Knowledge Network.

---

## Worksets

Worksets should be named in a consistent and logical manner, so as to identify the owner and purpose of the workset. Each model should have a relatively small number of worksets (likely between 5 and 10) all of which should be named following the convention below.

For further information on setting up ['Worksets'](project-setup.md#worksets)

> [Originator]-[Description]

**Originator:** As described in ['File Naming'](file-naming.md)

**Description:** Description of workset content; used in isolation in smaller projects, or in combination with one or both of Zone and Level on larger projects. Use underscores between words in the description. 

!!! Note
    The two exceptions to this rule are the default ‘Workset1’ and ‘Shared Levels and Grids’ worksets. These are default worksets, are found in all projects, and shall be kept intact. Shared Levels and Grids shall contain all Levels and Grids elements to allow for easy maintenance across the board. 


---