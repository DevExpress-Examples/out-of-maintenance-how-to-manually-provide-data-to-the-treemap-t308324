<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128572084/15.2.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T308324)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/TreeMapItemStorageSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/TreeMapItemStorageSample/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/TreeMapItemStorageSample/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/TreeMapItemStorageSample/MainWindow.xaml.vb))
<!-- default file list end -->
# How to manually provide data to the TreeMap


<p>This example demonstrates how to manually provide data for the Tree Map. To accomplish this task, use the Item Storage.</p>


<h3>Description</h3>

<p>To manually provide data for the TreeMap, assign&nbsp;the&nbsp;<strong>TreeMapItemStorage</strong>&nbsp;object to the&nbsp;<strong>TreeMapControl.DataAdapter</strong>&nbsp;property.<br />Then, populate the storage's&nbsp;<strong>Items</strong>&nbsp;collection with several&nbsp;<strong>TreeMapItem</strong>&nbsp;objects. Note that&nbsp;a tree map&nbsp;item can be a group, if the item's&nbsp;<strong>Children</strong>&nbsp;collection stores child elements.</p>

<br/>


