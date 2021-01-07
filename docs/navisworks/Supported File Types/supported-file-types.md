# Supported File Types 

The file types that Navisworks can read are:

<captions class="captions">Table 1 – Supported CAD File Formats</captions>

| Format | Extension | File Format Version |
| -------| -----------| -------------------|
| Navisworks | .nwd .nwf .nwc | All versions |
| AutoCAD	| | .dwg, .dxf	| Up to AutoCAD 2017 |
| MicroStation (SE, J, V8 & XM)	| .dgn .prp .prw	| v7, v8 |
| 3D Studio	| .3ds .prj	| Up to Autodesk 3ds Max 2017 |
| ACIS SAT	| .sat .sab	All ASM SAT. | Up to ACIS SAT v7 |
| Catia	| .model .session .exp .dlv3 .CATPart .CATProduct .cgr	| V4, v5 |
| CIS/2	| .stp	| STRUCTURAL_FRAME_SCHEMA |
| DWF/DWFx	| .dwf .dwfx	| All previous versions |
| FBX	| .fbx	| FBX SDK 2017.0 |
| IFC	| .ifc	| IFC2X_PLATFORM, IFC2X_FINAL, IFC2X2_FINAL, IFC2X3, IFC4 |
| IGES	| .igs .iges	| All versions |
| Inventor	| .ipt .iam .ipj	| Up to Inventor 2017 |
| Informatix MicroGDS	| .man .cv7	| v10 |
| JT Open	| .jt	| Up to 10.0 |
| NX	| .prt	| Up to 9.0 |
| PDS Design Review	| .dri	| Legacy file format. Support up to 2007. |
| Parasolids	| .x_b	| Up to schema 26 |
| Pro/ENGINEER	| .prt .asm .g .neu	Wildfire 5.0, | Creo Parametric 1.0-3.0 |
| RVM	| .rvm	| Up to 12.0 SP5 |
| Revit	| .rvt	| Up to 2017 |
| SketchUp	| .skp	| v5 up to 2016 |
| Solidworks	| .prt .sldprt .asm .sldasm	| 2001 Plus-2015 |
| STEP	| .stp .step	| AP214, AP203E3, AP242 |
| STL	| .stl	| Binary only |
| VRML	| .wrl .wrz	| VRML1, VRML2 |
| PDF	| .pdf	| All versions |
| Rhino	| .3dm	| Up to 5.0 |

<captions class="captions">Table 2 - Supported Laser Scan Formats</captions>

| Format | Extension | File Format Version |
| -------| -----------| -------------------|
| Autodesk ReCap	| .rcs .rcp	  | n/a | 
| ASCII Laser File	| .asc .txt	| n/a |
| Faro	| .fls .fws .iQscan .iQmod .iQwsp	| FARO SDK 5.5 |
| Leica	| .pts .ptx	| n/a |
| Riegl	| .3dd	| Version 3.5 or higher |
| Trimble	| Native file NOT supported. | Convert to ASCII laser file	Same as ASCII laser file |
| Z+F	| .zfc .zfs	| SDK version 2.2.1.0 |

<captions class="captions">Table 3 - Supported Scheduling Software</captions>

| Vendor  | Product  | File Format  | Notes  |
|---|---|---|---|
| Asta	| Powerproject<br>11 (11.x)<br>12 (12.0.03-042) | .pp | Requires Asta Powerproject to be installed on same machine, to make link. |	
| Microsoft	| Project 2007 (SP1) to 2013	| .mpp	| Requires Microsoft Project to be installed on same machine, to make link.
| Oracle	| Oracle Primavera Engineering and Construction<br>6.2.1 (SP4 Hot Fix 1)<br>7.0 (SP4)<br>8.2 | n/a | Requires Primavera v6 , 7 or 8 Engineering and Construction to be installed locally or remotely, along with the corresponding version of the Primavera SDK. TimeLiner connects to the Primavera database via an ODBC data source link. |
| Oracle	| Primavera P6 Web Services<br>6.2.1 (SP1 Hot Fix 1)<br>7.0 (SP1 Hot Fix 1)<br>8.2<br>8.3 | n/a	| Requires Primavera P6 v6, 7 or 8 Web Services installed within a suitable Web Application Server such as Oracle Web Logic or JBoss on the same machine as your P6 database. |
| Microsoft	| Microsoft Project<br>Exchange Format	| .mpx	| Does not require any project software to be installed. This is the common project exchange format which can be exported to from a number of scheduling packages. |
| N/A | CSV Exchange Format	| .csv	| Does not require any project software to be installed. This is a common exchange format which can be exported from a number of applications including, Microsoft Excel.<br>Navisworks Simulate and Manage can additionally export TimeLiner task information to this format. |



