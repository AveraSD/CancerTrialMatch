# CancerTrialMatch
TrialCurate, TrialEdit, TrialBrowse are the three shiny interfaces to curate, edit and search clinical trials. 

The source code for the three shiny interfaces: TrialCurate, TrialEdit, TrialBrowse are available at
[TrialCurate] (https://github.com/AveraSD/TrialCurate)
[TrialEdit] (https://github.com/AveraSD/TrialEdit)
[TrialBrowse] (https://github.com/AveraSD/TrialBrowse)

Examples of NCT identifiers to use for curation : NCT02428712, NCT03662126, NCT05361395 

Install Docker desktop and enable WSL integration in case of windows.

All the three shiny app interfaces are dockerized and the instructions to build and test docker images using the command line are as follows:

**Go to the folder where docker-compose is located and type**

```docker-compose up --build```

**To check docker images:**
```docker ps```

**Access the Shiny apps through a web browser at:**
[Curatelink] http://127.0.0.1:3838/TrialCurate/
[Editlink] http://127.0.0.1:3838/TrialEdit/
[Browselink] http://127.0.0.1:3838/TrialBrowse/

**To remove and clean up docker images, containers, builds etc.**
`docker-compose down -v`

**Screenshots for TrialCurate interface**

