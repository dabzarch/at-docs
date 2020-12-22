# Creating Search Sets

Search Sets are queries defined by the user to group model geometry into a collection. They are dynamic in nature and will update as the geometry in Navisworks changes. Search Sets can then be used when you [create clash tests](/navisworks/Creating Clash Tests/Basic Clash Test/basic-clash-test/).

To define the criteria of a search set you start with Find Items which can be found in the Home tab and then Select & Search

<a href="../.././img/creating-search-sets-1.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-1.png){: style="height:auto" :target="_blank"}
</a>

Once you have selected Find Items and window opens

<a href="../.././img/creating-search-sets-2.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-2.png){: style="height:auto" :target="_blank"}
</a>

On the left hand side you select when you are searching. By default this is set to standard which means you are selecting one of the models you have appended in. on the right hand side you have the criteria for the search. Most of the time you are going to search the contents of a model so the default settings are fine. 

In this example I am going to search for the Structural Columns within the Structural Model

We start by selecting the model we are going to search in. in this case it’s the Structures Model. We then need to define the Category within Navisworks. The Category here is not the same as the Category within Revit. Because we are looking for a Navisworks element under category we need to select Element. Under Property we can now define what property from the element we want to select. In most cases we will want to create Search Sets based on Revit Categories though it is not limited to this. So under Property we are going to select Category. The Condition options varies depending on what you have selected previously but for this example we are going to use =. Value also varies depending on what you have selected previously but in this example only Revit Categories are going to be available and in this case we are going to select Structural Columns.

<a href="../.././img/creating-search-sets-3.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-3.png){: style="height:auto" :target="_blank"}
</a>

To check that the criteria has worked we should select Find All and then from Visibility in the Home tab we need to pick Hide Unselected.

<a href="../.././img/creating-search-sets-4.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-4.png){: style="height:auto" :target="_blank" .center}
</a>

In Navisworks now you should only see the elements that match the criteria defined. Once we have done this we go to Sets from Select & Search in the Home tab and then Manage Sets. This brings up a new window. Currently there is nothing available here.

<a href="../.././img/creating-search-sets-5.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-5.png){: style="height:auto" :target="_blank" .center}
</a>

To save the criteria search we select the Binoculars and an item appears in the list. Name this something sensible like STR-Structural Columns. This has now saved the criteria and even when the Navisworks file is updated the search set will update the contents to match.  

<a href="../.././img/creating-search-sets-6.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-6.png){: style="height:auto" :target="_blank" .center}
</a>

Within the Set Manager we can add folders and sub folders which are useful later when we use it to [create clash tests](/navisworks/Creating Clash Tests/Basic Clash Test/basic-clash-test/). 

<a href="../.././img/creating-search-sets-7.png" target="_blank">
    ![Template](/navisworks/img/creating-search-sets-7.png){: style="height:auto" :target="_blank" .center}
</a>

Search Sets can look for any data within Navisworks its understanding where that data comes from and changing your criteria to suit is key to setting them up. 

You can also search for multiple items by adding another row in the Find Items window which create an and statement or change it to an or statement by right clicking and select Or.
