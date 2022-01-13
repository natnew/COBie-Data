# COBie-Data
COBie Data<br>

**Description**: This module introduces delegates to the NBS Toolkit, this is a free to use web service developed by 
**National Building Specification (NBS)**. The site allows users to register and then create their projects and 
input information at all stages from stage 0 through to stage 7. The software allows you to see what 
participants are performing what roles and tasks on your project and allows you to produce a simple 
COBie export containing basic project information<br>

**File** VP-BSW-XX-XX-M3-A-COBie2_2.rvt <br>

**Step-By-Step Process**<br>
First, we will create and setup the Project, this includes the physical address and stakeholder 
information where available. We will add the necessary parameters for the COBie Data drop at Stage 1, 
then we’ll export the information to an Excel spreadsheet.<br>

1. Open an internet browser and type https://toolkit.thenbs.com into the address bar
2. On the Home page click the Create a project button
3. On the Sign in page click the Register for free button
4. Enter the required information on the Register page and tick the I agree with the end user licence agreement.
5. Once registered, click Create new project on the Welcome page
6. On the Create New Project page enter VP-BSW for Reference, for the Title enter Byker Community Center and enter the description of works as shown in the above image
7. Click the Create now button
8. On the Project Overview page select Edit details
9. Enter the information as shown in the adjacent image.
10. Scroll down the page to the Additional Information area.
11. Select the down arrow on the Function field and select 532. Community Centres.
12. For Type of work select New build.
13. In Procurement, pick Traditional contract
14. For Functional unit enter 1500 and select m2 from the drop-down menu
15. Enter 30 for the Expected life cycle
16. Scroll down to Modelling units and select squaremeters for the Area units
17. Select millimeters for the Linear units and cubicmeters for Volume units
18. Scroll down and click Save changes, then Close
19. On the Project Overview page select Participants
20. On the Project Participants page, enter Architects Inc. and click the Add button
21. Enter info@archXYZ.com (Team member's email) in the Users field
22. Add some more organisations to the list of Project Participants as shown in the adjacent image
23. Click Back to workstages
24. On the Overview page, change the stage to Stage 1. Brief form the drop-down menu in the top left
25. Click Edit stage details in the stage information area
26. Tick the Current stage box as shown on the adjacent image
27. Scroll down and select Edit roles from the Project Team area of the Overview page
28. On the Roles at Stage 1 page click Add role and pick BIM manager from the drop-down menu
29. Click Add role
30. Set Architect and Lead designer to Architects Inc.
31. Set the BIM manager and Project lead to Information Management Consultancy
32. Set the Client to Saiwill
33. Click the Edit details button at the top of the page
34. Click Change picture
35. From the Delegate Datasets folder select Byker Community Center.png and click Open on the dialogue box
36. Select the Export button at the top of the page
37. Select the options as shown in the adjacent image
38. At the bottom of the page select Open to view the exported Excel spreadsheet


In this exercise, we provide a practical example of creating a COBie export directly from the design 
authoring software, **Revit**. As mentioned in the theory this could be an alternate design authoring tool, 
most of them will have the capability to export to COBie using an application plug in (API).<br>

1. From the Datasets folder in the Academy open the file VP-BSW-XX-XX-M3-A-COBie2_2.rvt
2. Open the default 3D view from the Project browser - Once installed, the BIM Interoperability Tools add-in 
will provide a tab with the same name containing a 
panel labelled COBie Extension, from which we will be 
selecting all the tools we need for this exercise
3. Firstly, we will add a contact, which would normally be yourself, if you were performing this task 
in the workplace
4. Select the Contacts icon to 
launch the contact manager - All assigned contacts for this 
project would be listed in the 
Contacts List down the left side, 
with the details of each contact 
listed on the right side when 
highlighted. We will add a new 
contact as shown here (we have 
zoomed in on the next page so 
don’t worry if you can’t read this!).
5. In the Contact List on the 
left, click on Add Contact…
6. Enter the information as shown in the 
adjacent image, starting with the 
Email address and working down.
7. Created By is a required field, but it cannot be completed until a contact exists so once you fill in the rest of the 
required fields - The Optional fields below the line on the right-hand side can be completed if preferred. The new 
contact is listed in the Contacts List on the left side of the dialogue box. We could then go on to add 
more contacts if we wished, although it is unlikely that you would add all the project contact 
information via Revit as this could easily be done in spreadsheet format.
8. From the bottom of the dialogue select ✓ Save and Close option - Many of the other tasks which we can perform, 
record the responsible contact as part of the 
process, hence needing to have at least one 
contact in the list. Let’s check the Project Setup 
next.
9. From the BIM Interoperability Tools tab, COBie Extension panel select the Setup Project tool - Down the left-hand side of 
the dialogue, we can see the 
various sub-sections of the 
COBie project settings. Most 
of these we will leave as the 
default values for now.
10. On this initial General 
page, set the locality to 
United Kingdom (UK), 
the Identification to 
Global Unique 
Identifier (GUID), and 
the Units such that 
Linear units are set to 
Millimeter, the Area to 
Square Meter and the 
Volume to Cubic Meter
11. Leave the Area Management Standard as default
12. In the Types sub-section, set the First Priority of the Category to Classification Manager 
‘Uniclass EF’ parameter value and note the other options available
13. In the Attributes subsection, click Select 
All to gather available 
information from all 
Revit categories - Have a browse through the 
other sub-sections of the 
settings listed on the left of 
the dialogue, to get a feel 
for the rules of information 
gathering that we can 
control.
14. Click ✓ Save and 
Close to finalise the 
settings
15. From the BIM Interoperability Tools tab, COBie Extension panel select the Zones tool
16. In the centre section of this dialogue, select Add Zone… and fill in the details shown above
17. Select Save
18. Highlight the 01 Entrance/Breakout room on the right-hand panel and drag it over the newly 
created Zone 1 in the centre panel
19. Repeat this for rooms 02, 06, 07, 09, 14 and 20 as shown below
20. Add a second Zone in the centre panel
21. Assign rooms 08, 10, 11, 12 and 13 to this zone by dragging and dropping them from the righthand side onto the Zone name in the cent
22. Select ✓ Save and Close to finalise
23. From the BIM Interoperability Tools tab, COBie Extension panel select the Select tool
24. Click Select All from the green buttons on the right, to grab all available information
25. Click ✓ Apply and Close
26. From the BIM
Interoperability 
Tools tab, COBie 
Extension panel 
select the Create 
Spreadsheet tool
27. Click Create 
Spreadsheet
28. Save the file as VP-BSW-XX-XX-M3-A-COBie2_2_Your_Initials.rvt in your folder 
29. You can now Close the model file

**Exploring the COBie Data File**



