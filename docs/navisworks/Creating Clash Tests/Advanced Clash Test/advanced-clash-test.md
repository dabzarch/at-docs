For advanced clash tests we follow the same procedure. So we Add Test and name it something appropriate such as MEP-Ducts vs Str-Floors. In selection A we change it from Standard to Sets. This now allows us to pick from the Search Sets that we have made. We do the same for Selection B.

<a href="../../.././img/advanced-clash-test-1.png" target="_blank">
    ![Template](/navisworks/img/advanced-clash-test-1.png){: style="height:auto" :target="_blank"}
</a>

You then need to select the settings to ensure you get results you want. Starting with Type:

There are four default clash test types for you to choose from:

*	Hard
    *	Choose this option if you want the clash test to detect actual intersections between geometry.
*	Hard (Conservative)
    *	This option performs the same clash test as Hard, however, it additionally applies a conservative intersection method.
*	Clearance
    *	Choose this option if you want the clash test to check for geometry within a specific distance from other geometry (see tolerance for more information). You can use this type of clash when, for example, pipes need to have space for insulation around them.
    *	Note: Clearance clashes are not the same as “soft” clashes. Clearance clashes detect for static geometry coming within a distance of other geometry, whereas soft clashes detect potential clashes between moving components. Clash Detective supports soft clash checking when you link it to Object Animation.
*	Duplicates
    *	Choose this option if you want the clash test to detect for duplicate geometry. You can use this type of clash test to check a model against itself to ensure the same part has not been drawn, or referenced twice, for example.

Tolerance controls the severity of the clashes reported and the ability to filter out negligible clashes, which can be assumed to be worked around on site. Tolerance is used for hard clash, clearance clash and duplicate clash types of clash test. Any clash found that is within this tolerance will be reported, whereas clashes outside of this tolerance will be ignored. So for Hard clashes, a clash with a severity of between zero and the tolerance value will be ignored, whereas for Clearance clashes, a clash with a severity of more than the tolerance value will be ignored as it is further away than the distance required. Similarly, a Duplicate clash with a severity of more than the tolerance value will be ignored as it is likely to be a separate, yet identical piece of geometry. 

Useful Tip - When you set the Tolerance positives numbers means that the 2 objects clashing have to exceed each other’s surface by that amount. So they physically have to clash. When you set the Tolerance to a negative number you are affectively putting a zone around the objects clashing which means that if they are within a certain distance of each other it will still raise it as a clash even though they aren’t physically clashing. 

Link allows you to link your clash detection TimeLiner. A Navisworks tool we are not talking about in this document. So in most cases this will be left as None.

Step is related to TimeLiner

Composite Object Clashing it is important that we have this option ticked as what this does is remove multiple clashes within a composite object. If you had a concrete metal deck and a column passing through it, if this wasn’t ticked then it would appear in the results twice. Once where it clashes with the metal deck and once where it clashes with the concrete. 

In the Rules tab there are 4 rules by default. You want these ticked except for Items in same file as by having this ticked it will ignore clashes that are in the same model which means you will have 0 clashes if you are checking MEP vs MEP etc. 


<a href="../../.././img/advanced-clash-test-2.png" target="_blank">
    ![Template](/navisworks/img/advanced-clash-test-2.png){: style="height:auto" :target="_blank"}
</a>

Useful Tip – change all these settings when you create the first clash test as it will remember them when you create your next one. There is no way of changing all the settings in one go once you have multiple clash tests and you will have to change all them individually.  

A clash test can have one of 4 statuses:

*	New
    *	Indicates a clash test that has not yet been run with the current model.
*	Done
    *	Indicates a clash test that has been successfully run with the latest version of the model.
*	Old
    *	Indicates a clash test that has been altered in some way since being set up. This might include changing an option, or having loaded the latest revision of the model.
    *	Note: Individual clash statuses can still be edited in a clash test with a status of Old.
*	Partial
    *	Indicates a clash test that has been interrupted during execution. Results are available up to the point of interruption.

To run the clash tests that you have created simply select update all.


<br>
<br>
<br>