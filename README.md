tfsconsole
==========
It's a windows command line utility to display test results summary associated with tfs builds. 
The output contains details like :
- number of tests passed/failed
- date and time of run

Dependencies :

  - Team Explorer 

     To build tfsConsole.exe, Team Explorer needs to be installed. It can be downloaded from 
     http://www.microsoft.com/en-au/download/details.aspx?id=329
     
  - tcm command

     tfsConsole.exe uses tcm commands to generate some of the build details. Therefore it 
     has to be added in the path.
     

Usage :

  >tfsconsole.exe -c "http://10.236.202.1:8080/tfs/abc" -e "nath.alok@gmail.com" -b "buildDefinition1|buildDefinition2"
