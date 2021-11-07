# multilevelTreeViewMenu

![Screenshot 2021-11-07 100122](https://user-images.githubusercontent.com/48369328/140641185-cf6705e6-78fa-4b80-ade5-fa951afd1b99.png)
![Screenshot 2021-11-07 100219](https://user-images.githubusercontent.com/48369328/140641188-328b7bae-342b-4e65-a435-c2de03cddd4d.png)



This is fully responsive multilevel dropdown navbar code sample. It is also called treeview menu. 1-st level dropdowns are opens by click, but inner submenus opens by mouse hover.

On mobile screens all menu items and their submenus work like accordion

Steps to create multilevel navbar dropdown menu with Bootstrap 5
Add your submenu ul li elements inside parent li
Hide inner dropdowns submenus by adding display:none.
Add position: absolute; left:100%; top:-7px; // or close to 0px to inner ul submenu
Make inner dropdown submenu visible display:block when mouse hovers parent li element
On smaller screens we add some javascript code to show submenus after each other, like accordion


https://bootstrap-menu.com/detail-multilevel.html
