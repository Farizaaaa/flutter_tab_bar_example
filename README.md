# flutter_tab_bar_example
Sample Flutter TabBar Widget Example
## OverView
 This example contains three tabs  
## ScreenShot
| Sign-In Screen                                | 
| --------------------------------------------- |
| ![image](tabbar.png)         |
## Steps
<pre>
1:crate StatelessWidget TabBarExample
2:Add Scaffold
3:Add AppBar
4:Wrap the Scaffold uisng Widget DefauiltTabController
 4.1:Add property length to DefaultTabController(indicate the No. of tabs)
4:Inside the Appbar Add TabBar Widget using property bottom
6:Add children widgets Tab to the TabBar 
 6.1:Specify the Icons needed inside each Tab
7:Inside the body part of Scaffold add Widget TabBarView
 7.1:In the TabBarView give the needed body widgets of each Tab(Give required Widgets as per the lenth of DefaultTabController ) 
</pre>
