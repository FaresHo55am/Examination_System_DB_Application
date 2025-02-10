# FaresHo55am-Examination_System_DB_Application



If you'd like to try out the GUI, please follow these steps:

1. Update the GlobalVars.cs file
a) Configure the Database Connection String
Locate the following line and replace <YourServerName> with your actual server name to connect to the Examination_System database:

public static string ConnectionString { get; }
    = "Data Source = <YourServerName>;Initial Catalog=Examination_System;Integrated Security=True;";

b) Set the RDlFolder Path
Modify the RDlFolder path to point to your reports directory:

public static string RDlFolder { get; } = @"E:\YourDirectory\..\..\Reports\";

2. Extract the database
3. You're All Set!
Once you've made these changes, you should be ready to use the GUI.
