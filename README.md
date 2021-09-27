# That-is-MSDup



**Purpose:** 
This repo has been repurposed to host mathematical formulae and code-snippets for commonly derived PEPFAR indicators. When possible, code snippets will be provided R, python and Tableau (if applicable).

For example, _Viral Load Coverage_: 

* in plain text is the number of adult and pediatric ART patients with a viral load result documented in the patient medical record and/or laboratory records in the past 12 months divided by the number of adults and children currently receiving antiretroviral therapy (ART) two periods prior.   

* in mathematical notation it is $VLC = TX\_PVLS\_D / TX\_CURR_{lag\_two\_periods}$

* in R this becomes `mutate(VLC = TX_PVLS_D / lag(TX_CURR, 2, order_by = period)`


<del>Tracking MSD, Genie, and Pano errors, along with their associated resolutions for the sake of transparency and benefit to data consumers.</del>

**Process:** 
Please submit an issue if there is an indicator you would like defined in plain text, mathematical notation and code snippet exmples. 
<del>If a team member identifies an issue an any of the above data sets or systems, or becomes alerted to one through other means, they should enter it in the [Issues Tab](https://github.com/USAID-OHA-SI/That-is-MSDup/issues) and tag the issue with appropriate [labels](https://github.com/USAID-OHA-SI/That-is-MSDup/labels). Current label categories include:
 - OU;
 - Program/Tech Area; and 
 - Platform. 
 
<del>When submitting a ticket, select at least one label from each of these categories. 

Screenshots documenting the issue should be placed in [this folder](https://drive.google.com/drive/folders/1ZNlq8h3An__5NtYSMNLmxDQXayab9_s_) or alternate so long as it's accessible to the SI team. When an issue is submitted, link to the screenshot(s) and any other relevant information. 

The team member submitting the issue is also responsible for tracking resolution and updating tickets accordingly.</del>

---

*Disclaimer: The findings, interpretation, and conclusions expressed herein are those of the authors and do not necessarily reflect the views of United States Agency for International Development. All errors remain our own.*
