# Meetup-Options-Menu
In this prac we have created an options menu in our main activity.
First, we will create a directory named Menu in the res folder,
Right click in the Menu directory and add New Menu Resoure file which is an xml file.
Open it and add menu items asshown below,

<item android:title="Settings"
    android:id="@+id/menu_settings"></item>
    
      <item android:title="Contact Us"
        android:id="@+id/menu_contacts"></item>

    <item android:title="Help"
        android:id="@+id/menu_help"></item>
        
From the main activity,we will use the 'onCreateOptionsMenu' method to create the menu and infalte it into the layout using 'MenuInflater
To manage and manipulate the menu items we will use the 'onOptionsItemSelected' method.
