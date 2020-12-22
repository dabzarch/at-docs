## Settings Explained ##

**Convert Construction Parts**

When using the Revit Construction Modelling and Assemblies feature, you have an option of exporting either the original object or construction parts into Autodesk Navisworks. Select this box if you want to export the construction parts; clear this check box if you want to export the original object.

**Convert Element Ids**

Select this check box to export the ID numbers for each Revit element.

When this check box is clear, the file reader ignores IDs.

**Convert Element Parameters**

Specifies how Revit parameters are read. Select from the following options:

*   None
*   The file reader does not convert parameters.
*   Elements
*   The file reader converts parameters for all found elements.
*   All
*   The file reader converts parameters for all found elements, including the referenced elements. As a result, extra property tabs are available in Autodesk Navisworks.

**Convert Element Properties**

Select this check box to convert the Properties of each element in your Revit (RVT) file into Autodesk Navisworks (NWC) Properties. Leave this check box clear if you want to retain the original Revit Properties.

**Convert Lights**

Check this option if you want to export the lights contained in your Revit file into Navisworks. By default, this check box is clear.

**Convert Linked CAD formats**

Revit projects can embed external files as links. When this check box is selected, linked CAD files such as DXF, DGN, SAT and Sketchup format will be included in the exported NWC file. By default, this check box is clear.

**Convert Linked Files**

Revit projects can embed external files as links. When this check box is selected, linked RVT files will be included in the exported NWC file. By default, this check box is clear.
Note: Only linked RVT files can be exported; linked dwgs and any other file formats are not supported.

**Convert Room as Attribute**

Indicates whether room attributes are supported. By default, this check box is selected, and data for each room converts into a single shared room attribute.

**Convert URLs**

Indicates whether URL property data is converted. By default, this check box is selected and the hyperlinks are supported in the converted file.

**Coordinates**

Specifies whether to use shared or internal coordinates for file aggregation. By default, shared coordinates will be used. Shared coordinates can be viewed and modified outside of Revit.

*	Project Internal
*	Uses internal coordinates for file aggregation.
*	Shared
*	Uses shared coordinates for file aggregation.

**Divide File into Levels**

Indicates whether the Revit file structure is split into levels on the Selection Tree. By default, this check box is selected, and Revit files are organized by File, Category, Family, Type, and Instance. 

**Convert**

Specifies how to convert and load viewing options for Revit files. Select from the following options:

*	Navisworks view
    -   The default view. To use the Navisworks view, save an RVT file in Revit and use "Navis" in the name of the 3D view. If you do not use this option, the Revit First 3D View is loaded.
*	First 3D view
    -	Loads the elements visible in the Revit First 3D View.
*	Entire project
    -	Loads the whole project.

**Convert Room Geometry**

When using Revit 2017, you have the option of using either the original room geometry or converting it into construction sub-parts in Autodesk Navisworks. By default, this check box is selected and room geometry is converted into sub-parts. Clear the check box if you want to keep the original room object.

**Faceting Factor**

Enter the required value to control the level of faceting that takes place.
The faceting factor must be greater or equal to 0, where 0 results in the faceting factor being turned off. The default value is 1. To get twice the number of facets, double this value. To get half as many facets, halve this value. Larger faceting factors result in more polygons to a model and larger Autodesk Navisworks files.

**Try and Find Missing Materials**

When this check box is selected (the default option), the file reader looks for a match for the materials missing from the export.

Note: If any inappropriate materials are applied to the model geometry as a result, clear this check box to fix the problem.

Once you have selected the appropriate settings save your NWC into the appropriate project folder. After you have exported the file to NWC you should now open it in Navisworks, visually inspect it (see [Visual Coordination](/navisworks/Visual Coordination/visual-coordination/)) and export it to an NWD file (see [Publishing the Model](/navisworks/Publishing the Model/NWC to NWD/nwc-to-nwd/))


<br>
<br>
<br>
<br>



