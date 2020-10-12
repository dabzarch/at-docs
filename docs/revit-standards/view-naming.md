# View Naming

---

## View Naming

> [Level-if applicable] - [Scale] - [Description-optional]

**Level:** Level of view (2 characters), not applicable for whole building sections / elevations.

> 00 	Ground Floor 	
> 01  First Floor	
> R1	Roof 	
> B1 	Basement 1	
> M1	Mezzanine 1	

**Scale:** The scale of the view. i.e. 1:100/ 1:200 etc. written as "100" or “200”

**Description:** A brief description of what the view contains, with each word separated by underscores. 
Note:

-	LOCATION always at the front of the DESCRIPTION, i.e. "LAB PARTITION"
-	Specifying part of DETAIL being drawn is always at end, i.e. "SLIDING DOOR HEAD"
-	Typical is always at the front and written as "TYPICAL"
-	MATERIAL always at end and written as " - CONCRETE"
-	"And" or "&" always written as "+"
-	When describing LOCATION use no space between multiples, i.e. "LAB+LOBBY"
-	No abbreviations when it can be avoided, i.e. "CURTAIN WALL" and not "CW"

**Example:**

> 00-100-Classroom_Layout 

In the WORKING views you can put you initials at the end of a drawing to let other team members know you are working on this particular view. When you are done or no longer need the view it should be removed. Refer to Section 2.4. 
 
---

# View Template Naming

All views that appear on sheets should have a View Template applied. The view template should be named in accordance with: 

> [Type]-[Scale]-[Description if applicable]

Type: Choose a type from the list below. 

> PLN	Plan 
> RCP	Reflected Ceiling Plan
> SCT	Section 
> DTL	Detail Views
> ELE	Elevation 
> SHE	Schedules
> 3DI	Internal 3D Views, Walkthroughs
> 3DE	External 3D Views, Walkthroughs

**Scale:** As applicable in format of 200, 100, 50 etc. *If the scale is not included in the template then replace with ‘custom’. All scales between 2-15 should be DTL. 

**Description:** Short description, for example ‘General_Arrangement’ ‘Fire’ or ‘Planning’, with each word separated by underscores. 

Always keep the description to the end so that types and scales are kept together in the list of options available. 

There should be no number after the name to suggest a duplicate like ‘Planning 2’. Try to limit the number of templates in a project, **always check** if there is a template which is already available that you can make work with your drawing before creating a new one.

When naming, remember that ‘elevation’ or ‘section’ does not need to be included in the description as it is shown in the type. For example, ART-ELE-50_InternalElevations. ‘Internal’ alone is a sufficient description.

**Example:** PLN-100-Planning

Scale can be omitted when naming templates for schedules. 
Example: SHE-Window_Assembly.
 
# Filter Naming
Filters can be applied to views to alter the visibility or graphic display of elements. There can be multiple filters applied to views and including filters in view templates can apply filters to multiple views. 

There are two types of filters, rule-based filters and selection-based filters.

-	Rule based filters identify elements using parameter values for selected categories. 
-	Selection-based filters identify elements that you select to isolate, hide, or apply graphic settings to the elements in the selection.

When naming filters follow the below rule:

> [Category]-[Rule]_[Description]

Category: The category that was ticked from the available list to make the filter. i.e. Walls

!!! Note
    **Rule: A brief explanation of the rule used i.e.NameContains**

**Description:** A description of the filter rules i.e. FireProof

Each section should use CamelCase where there is more than one word


**Example:**

Walls-NameContains_FireProof (All walls containing ‘Fireproof’ in the name will show in red)

Walls-NameNotContain_FireProof (All walls that do not have ‘Fireproof’ in the name will show as Grey)

---

# Schedule Naming
Schedules must be named in a presentable format as this is the title that appears on sheets. 

> [Type]-[Level-if applicable]-[Area-if applicable]-[Working-optional]

**Type:** What is the schedule for? Door Schedule, Floor Areas, PH Room Volumes, Sheet List etc.

**Level:** If the schedule relates to a specific level use Ground Level, First Floor etc. If the schedule applies to the whole building, then leave this part out.

**Area:** If the schedule relates to specific area of the building, then use the name of the area i.e. Sports Block or Nursery. If the schedule applies to the whole building, then leave this part out.

**Working:** If a schedule is created for the purpose of editing instances and won’t be shown on a sheet add ‘Working’ to the name. 

**Examples:**

The following schedules are included in the Revit Template:

-	Sheet List
-	View List
-	Room Schedule

---

# Legend Naming

Legends must be named in a presentable format as this is what appears in the project browser. The title is for internal use only, so that others can locate the relevant legend when needed, the one shown on the sheet is usually written in the legend itself.

Never copy/duplicate a legend and leave the name reading as ‘copy 1’. Always rename with a suitable title in accordance with:

> [Type]-[Description]-[Area-if applicable]_[Working-optional]

**Type:** The type should always be first in the tile to ensure that the list is grouped by these. 
Choose the appropriate ‘type’ from the list below.  

> Key  	    A named list of symbols	
> Legend  	A Key & Notes
> Note	    Notes to accompany a drawing or key	

**Description:** A concise description of what the Legend contains or where it should be used. i.e. ‘Access_Maintenance’, ‘Window_Types’, ‘Site_Plan’. Words should be separated by underscores. 

**Area:** If applicable an area can be added to the name to reference a specific part of the building. i.e. ‘Sports Block’, ‘Nursery’. The area can also be used to reference the type of drawing which the legend is for. i.e. ‘Section’. Words should be separated by underscores. 

**Working:** This section is optional. If a Legend is created but won’t be shown on a sheet add Working to the name. 

Examples:
Key-Site_Plan
Legend-Fill_Patterns-Working
