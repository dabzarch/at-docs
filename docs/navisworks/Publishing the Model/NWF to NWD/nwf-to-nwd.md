The process for taking an NWF to NWD is mostly the same with regard to publishing the file to NWD. The process is different though if you have you have used the [Navisworks Template](/navisworks/Navisworks Template/navisworks-template/). This is because we want to remove the clash tests before we share the information. This is done for 2 reasons. Firstly so that external teams can't extract our code that we have used to create it and secondly, so that the clashes can be reviewed in the Navisworks Freedom without the need for a licence.

This process assumes you have run [clash detection](/navisworks/Creating Clash Tests/creating-clash-tests/). To publish the NWD follow the same procedure as for NWC to NWD. 

Once you have made the NWD save the NWF and then open the NWD. Now you can [group the results](/navisworks/Grouping the Clash Results/grouping-the-clash-results/). Once the results are grouped we can prepare the model for issuing externally. Because the template data is stored in the model still the first thing we need to do is save the results in Navisworks but out of Clash Detective. To do this we need to go to the report tab in Clash Detection. 

<a href="../../.././img/nwf-to-nwd-1.png" target="_blank">
    ![Template](/navisworks/img/nwf-to-nwd-1.png){: style="height:auto" :target="_blank" .center}
</a>

For the contents we can tick everything and for the Include Clashes section we can tick just New and Active unless you have been reviewing and approving clashes. For the Output Settings we need to set the Report Type as All tests (combined) and Report Format as Viewpoints. Make sure Preserve result highlighting is ticked. And select Write Report.

<a href="../../.././img/nwf-to-nwd-2.png" target="_blank">
    ![Template](/navisworks/img/nwf-to-nwd-2.png){: style="height:auto" :target="_blank" .center}
</a>

Now if you go to Saved Viewpoints, from the View Tab and selecting it from the Windows drop down list. All the clash results are now saved as viewpoints. 

Once this is done we can go back to Clash Detective and delete all the tests. This is done by selecting Delete All

<a href="../../.././img/nwf-to-nwd-3.png" target="_blank">
    ![Template](/navisworks/img/nwf-to-nwd-3.png){: style="height:auto" :target="_blank" .center}
</a>

Once that is done we need to delete the Search Sets that the template created. This is done by going to Manage Sets from the Home tab and selecting the Sets drop down list. The folder should be called Clash Detection. Select this and delete. It may take a few seconds once you have selected that folder. Once this is done you can save the NWD file and its now ready for issuing.

<br>
<br>
<br>