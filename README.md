# Microsoft PowerBI Tutorial

🗓️ __Live Session Details__ <br>

Topic: Designing with Data (PowerBI) <br>
Presenter: Isaias Thomas Biju<br>
Day and Date: Wednesday, 22nd October 2025 <br>
Time: 3:30 PM <br>
Duration: ~1.5 hours<br>
Format: Hands-on, interactive walkthrough<br>
Platform: Power BI Service (Online)<br>
Based on: Power BI Essential Training (2024) LinkedIn Learning Course by Gini Von Courter

---

__Welcome to this interactive session on Power BI Service (Online) — Microsoft’s cloud-based platform for creating, sharing, and collaborating on data visualisations. This repository contains all the resources, demo files, and notes used during the live lecture.__

---
__What you'll gain from this session:__ <br>
<ul> 
<li>Understand Power BI Tools: Learn how to use the Power BI Service which should be enough to get you started for further learning with Power BI Desktop, and Power BI Mobile to create and share impactful visualizations.</li>
<li>Data Handling: Gain skills in importing data, creating visualizations, and arranging them into reports. Learn to pin visualizations to dashboards and ask questions about your data using Power BI Q&A.</li>
<li>Dashboard and Report Management: Differentiate between dashboards and reports, manage workspaces, and understand user roles within Power BI.</li>
<li>Power BI Mobile: Manage workspaces and tools within the Power BI mobile application.</li>
<li>Data Modeling: Use data modeling capabilities in Power BI Desktop to transform and relate data tables effectively.</li>
</ul>

---
__KAHOOT Q1__ <br>
__What is PowerBI?__
<ul>
<li>Business Intelligence: Power BI connects business decision-making to factual data, enabling better business decisions through visualizations and reports. </li>
<li>Power BI Tools: This session focuses on Power BI service (web-based). Further learning with Power BI Desktop (for data modeling and transformation), and Power BI Mobile apps is recommended in your spare time.</li>
<li>Data and Visualizations: Power BI allows you to create datasets from multiple sources, build vibrant reports, and share insights through dashboards.</li>
</ul>

----

<ul>
<li> Sign-Up Process: Visit powerbi.com or powerbi.microsoft.com, click on the "Products" link, and select "Power BI Pro" to sign up for a free trial. </li>
<li> Email Requirements: You must use a work or organizational email address (e.g., .edu, .com) to sign up. Personal email addresses (e.g., Gmail, Yahoo) are not accepted.</li>
<li> Workaround for Personal Emails: If you don't have an organizational email, you can sign up for a Microsoft 365 Business Standard one-month trial using your personal email, which will provide you with a suitable email address to use for Power BI.</li>
</ul>

---
__KAHOOT Q2__ <br>

Navigating the User Interface of PowerBI
---

__Top Navigation Bar:__

<ul>
  <li>Microsoft 365 Waffle: Located in the upper left corner, it provides access to other Microsoft 365 apps.</li>
  <li>Search: Allows you to search for specific items within Power BI.</li>
  <li>Settings Menu: Lets you change settings for Power BI and download other applications.</li>
  <li>Profile: Shows your licensing type, trial days left, and sign-out option.</li>
</ul>

__Left Navigation Pane:__

<ul>
  <li>Home: The starting point of your Power BI service.</li>
  <li>Create: For creating new reports and dashboards.</li>
  <li>Browse: To browse through existing items.</li>
  <li>Metrics: (Beyond the scope of this session) Shows metrics on application usage.</li>
  <li>Apps: Where you load new applications.</li>
  <li>Deployment Pipelines: (Beyond the scope of this course) Used for deploying Power BI solutions.</li>
  <li>Workspaces: Lists all available workspaces, including "My workspace" and any other workspaces you have access to.</li>
</ul>

__Main Screen:__

<ul>
  <li>Recommended Items: Displays items recommended by your organization.</li>
  <li>List of Objects: Shows different objects like workspaces, reports, dashboards, apps, and datasets, each with its own icon.</li>
  <li>Favorites: Items you have marked as favorites.</li>
  <li>My Apps: Apps you have loaded or created.</li>
</ul>

__Workspace Filters:__

<ul>
  <li>Content: Non-dataset items.</li>
  <li>Datasets and Data Flows: Specific datasets and data flows.</li>
  <li>Search Box: Allows you to search within your workspace or any other open workspace.</li>
</ul>

__Sorting and Browsing:__

You can sort items by owner, name, etc., and browse through dashboards and reports.

__Return to Home:__ 

Click the PowerBI button in the navigation pane to return to the main screen.

----

__Microsoft Fabric:__
<ul>
  <li>Microsoft Fabric Introduction: Released in 2023, Microsoft Fabric is a cloud-based analytics solution designed to streamline data movement, storage, and analysis. It integrates existing tools and introduces new ones to provide a unified toolset for enterprise users.</li>
  <li>Fabric Logo and Interface Changes: When you start Power BI, you'll notice a Fabric logo, indicating that you're working within the Fabric environment. The Power BI icon in the lower left-hand corner now has additional options.</li>
  <li>Terminology Update: In the Fabric environment, what were previously called "datasets" in Power BI are now referred to as "Semantic Models" due to the different meaning of "dataset" in Fabric.</li>
  <li>Performance Enhancements: Fabric's Direct Lake capability allows direct access to enterprise data, improving performance for large reports and complex dashboards. Data improvements made by data scientists and engineers are immediately available to users without needing to reconnect to data sources.</li>
  <li>Centralized Data Governance: Fabric provides centralized data governance and security management, meaning security settings are applied once and don't need to be reset in Power BI. This centralized approach aims to reduce costs and increase competitive advantage.</li>
  <li>Unified Environment: Fabric creates a single environment shared by data professionals and business users, allowing modifications made by data professionals to be immediately available to end-users without separate load events.</li>
</ul>

---

__KAHOOT Q3, Q4, Q5__ <br>
__PowerBI as data sources__

<ul>
  <li>Semantic Models: In Power BI, datasets are now referred to as semantic models, although the terminology isn't consistent throughout the application.</li>
  <li>Data Sources: You can load data from various sources, including existing semantic models, apps containing reports, and manually entered data. For larger datasets, it's best to avoid manual entry.</li>
  <li>PBIX Files: You can upload PBIX files, which include reports and data, into your workspace.</li>
  <li>Power BI Desktop: For other data sources, such as Microsoft Excel, you need to use Power BI Desktop, which will be explored later in the course.</li>
</ul>

---

__Get Existing Content From an App__ (Demo here - Census App, Sales)

<ul>
  <li>Accessing Apps: You can access apps by clicking the Apps button in the navigation pane and then selecting "Get apps" to view available apps.</li>
  <li>Types of Apps: Apps can be organizational, template, or from online services. Some apps are free, while others may cost money.</li>
  <li>Installing Apps: To install an app, click "Get It Now," confirm your details, and give permission to install. The app will be added to your list of apps.</li>
  <li>Using Apps: Once installed, you can load the app, view sample data, and connect your own data source if needed. You can also filter and search for specific apps based on your needs.</li>
</ul>

---

__Task 1: Loading Data from the Word Document:__ 

<ol>
  <li>Click the Create Button: Choose the option "Paste or manually enter data".</li>
  <li>Select Data Source: Use data downloaded from this GitHub Page, that is from the exercise files in the Chapter 02 folder.</li>
  <li>Open the Document: Open the Word document called Lead List.</li>
  <li>Copy the Table: Select the entire table in the Word document and copy it.</li>
  <li>Paste Data in Power BI: Go back to Power BI, paste the copied data into Power Query.</li>
  <li>Define Data Correctly: Ensure delimiters (lines/tabs) are detected correctly and use the first row as headers.</li>
  <li>Assign Data Types: Check and assign appropriate data types to each column.</li>
  <li>Name the Data Set: Double-click the lower left-hand corner to name the data set (e.g., "lead list").</li>
  <li>Create Data Set: Choose the option to create a data set from the data.</li>
</ol>

<p>These steps will help you create a new data set in Power BI using data from a Word document.</p>

---

__Task 2: Loading Data from a PBIX file, a report:__

<ol>
  <li>Select Workspace: Choose 'My workspace' where you want to upload the PBIX file.</li>
  <li>Choose Upload: Click on the upload option.</li>
  <li>Select File Source: You can upload a PBIX file from OneDrive for Business, SharePoint, or browse to find it stored elsewhere.</li>
  <li>Navigate to File: Locate the exercise files folder, and navigate to the Chapter 02 files.</li>
  <li>Select PBIX File: Choose the PBIX file named "Retail Analysis Sample PBIX.pbix".</li>
  <li>Upload File: Click Upload. The process might take some time.</li>
  <li>Access Uploaded File: Once uploaded, the file will be available in your workspace.</li>
  <li>Open PBIX File: Open the PBIX file to access the report pages and the underlying data.</li>
  <li>Edit Mode: Switch to Edit mode to view and work with the semantic model and tables.</li>
  <li>Add to Favorites from Home: Optionally, add the file to your favorites for easy access throughout the course.</li>
</ol>

---

__Visualisations:__

<ol>
  <li>Open Report in Edit Mode: Navigate to the Home tab and open the retail analysis sample report in Edit mode.</li>
  <li>Explore Visualizations Gallery:
    <ul>
      <li>The report editor will display the fields list and the visualizations gallery.</li>
      <li>The visualizations are based on the same dataset.</li>
    </ul>
  </li>
  <li>Create and Edit Reports: You can create reports from scratch, edit existing reports, and modify visualizations.</li>
  <li>Types of Visualizations:
    <ul>
      <li>Chart Visualizations: Bar charts, column charts, line charts, area charts, pie charts.</li>
      <li>Esoteric Charts: Combo charts, bubble charts, scatter charts, donut charts, gauges, funnel charts, waterfall charts.</li>
      <li>Text Visualizations: Single number cards, multi-row cards, KPI visualizations.</li>
      <li>Tabular Data: Tables and matrix visualizations.</li>
      <li>Geospatial Visualizations: Maps, filled maps, ArcGIS maps.</li>
      <li>Other Visualizations: Tree maps, slicers, and images.</li>
    </ul>
  </li>
  <li>Custom Visualizations: Use the "Get more visuals" button to add custom visualizations from the gallery.</li>
  <li>Telling a Data Story:
    <ul>
      <li>Combine visualizations to tell a story within a report.</li>
      <li>Create an app workspace to share the report for collaboration.</li>
      <li>Pin visualizations to a dashboard for broader sharing.</li>
    </ul>
  </li>
</ol>

---

__Work with visualizations in a report:__

<ol>
  <li>Open PBIX File:
    <ul>
      <li>Navigate to the homepage and search for the PBIX file.</li>
      <li>Click on the report to open it.</li>
    </ul>
  </li>
  <li>Navigate Report Pages:
    <ul>
      <li>Use the page tabs to navigate through different pages of the report.</li>
      <li>Collapse or expand the info page as needed.</li>
    </ul>
  </li>
  <li>View Visualizations: Examine the visualizations on the overview page, including pie chart, column chart, map, and bubble chart.</li>
  <li>Filter Data:
    <ul>
      <li>Click on a district manager's name to filter the report by that manager's data.</li>
      <li>Use multi-select with the Control key to filter by multiple managers.</li>
    </ul>
  </li>
  <li>Reset Filters:
    <ul>
      <li>Click on an unselected item or use the "Reset Filters, Slicers, and Other Data View Changes" button to reset the report.</li>
    </ul>
  </li>
  <li>Interact with Visualizations:
    <ul>
      <li>Select data in one chart to filter other charts on the page.</li>
      <li>Use the column chart to filter by month or chain.</li>
    </ul>
  </li>
  <li>Lasso Data: Drag to select a set of items and use them as a filter for other visualizations.</li>
  <li>Clear Filters: Click in the background of a chart to clear the filter and reset the visualization.</li>
  <li>Edit Mode:
    <ul>
      <li>Switch to Edit mode by clicking the pencil icon to modify visualizations and work with the data.</li>
      <li>Return to Reading View by clicking the Reading View button.</li>
    </ul>
  </li>
</ol>

---

__Task 3: Create a new report:__

<ol>
  <li>IGNORE THIS STEP, THIS IS ONLY FOR YOU TO UNDERSTAND: Create a Report from an Existing Report:
    <ul>
      <li>Open the existing report.</li>
      <li>Go to the File menu.</li>
      <li>Choose "Save a copy".</li>
      <li>Provide a new unique name for your report.</li>
      <li>Choose a workspace.</li>
      <li>Click "Save" to create a copy that you can modify.</li>
    </ul>
  </li>
  <li>Create a New Report from Scratch:
    <ul>
      <li>Go to your workspace.</li>
      <li>Navigate to your dataset.</li>
      <li>Click the "More options" button next to the dataset.</li>
      <li>Select "Create report".</li>
    </ul>
  </li>
  <li>Report Editor Interface:
    <ul>
      <li>The new report canvas will open in the report editor.</li>
      <li>On the right, you will see the Filters pane, Visualizations pane, and Fields pane.</li>
      <li>At the top, you have options to save the report, save a copy, print the current page, and adjust view settings.</li>
    </ul>
  </li>
  <li>Customize the Report Canvas:
    <ul>
      <li>Adjust view settings such as "Fit to page" and "Smart guides".</li>
      <li>Turn on options like grid lines and snap to grid based on your preference.</li>
    </ul>
  </li>
  <li>Add Pages: Use the page tabs at the bottom to rename the current page or add new pages.</li>
  <li>Create a Report Using Power BI Desktop: Another method to create a report is by using Power BI Desktop, which will be covered later in the course.</li>
</ol>

---

__Task 4: Create and Arrange Visualisations:__

<ol>
  <li>Add a Visualization:
    <ul>
      <li>Select the data field (e.g., district manager) to create a visualization.</li>
      <li>Power BI will automatically choose a visualization type (e.g., table).</li>
    </ul>
  </li>
  <li>Change Visualization Type: Select the visualization and choose a different type from the visualizations gallery if needed.</li>
  <li>Add a Map Visualization:
    <ul>
      <li>Click on the map icon and select geospatial data (e.g., postal code) to populate the map.</li>
    </ul>
  </li>
  <li>Add Sales Data Visualization: Select the sales data field (e.g., total units sold this year) to create a chart.</li>
  <li>Arrange Visualizations: Move and resize visualizations on the canvas using grid lines and guidelines for alignment.</li>
  <li>Change Visualization Type for Better Representation: Select a visualization and change its type (e.g., from chart to card) for better clarity.</li>
</ol>

---

__Task 5: Save and Format a Visualisation:__

<ol>
  <li>Save the Report:
    <ul>
      <li>Click on File > Save or use the save button on the right.</li>
      <li>Enter a name for your report (e.g., "My Retail Analysis").</li>
      <li>Save it in My workspace.</li>
    </ul>
  </li>
  <li>Switch Between View and Edit Modes:
    <ul>
      <li>After saving, the report switches to View mode.</li>
      <li>To return to Edit mode, click the edit option.</li>
    </ul>
  </li>
  <li>Collapse Filters Pane: Collapse the filters pane to give more room for formatting.</li>
  <li>Use Canvas Zoom Control:
    <ul>
      <li>Use the zoom control at the bottom to zoom in and out.</li>
      <li>Use Fit to page to see how it will look for users.</li>
    </ul>
  </li>
  <li>Common Attributes for Visualizations: All visualizations can have a title, location, and size on the page.</li>
  <li>Format a Table Visualization:
    <ul>
      <li>Select the table visualization.</li>
      <li>Use the Formatting button to adjust properties like title, background color, visual border, and shadow.</li>
      <li>Adjust text size and color as needed.</li>
    </ul>
  </li>
  <li>Format a Map Visualization:
    <ul>
      <li>Select the map visualization.</li>
      <li>Change the title and adjust the size and text color.</li>
    </ul>
  </li>
  <li>Format a Card Visualization:
    <ul>
      <li>Select the card visualization.</li>
      <li>Adjust the callout value size and category label.</li>
    </ul>
  </li>
</ol>

---

__Task 6: Create Chart Visualisations:__

<ol>
  <li>Create a New Page: Click the New Page button to create a blank canvas.</li>
  <li>Choose Fields:
    <ul>
      <li>Expand the Item table and select Category. Keeping this selected move to the next step.</li>
      <li>Expand the Sales table and select Total Units Last Year and Total Units This Year.</li>
    </ul>
  </li>
  <li>Adjust Visualization Type:
    <ul>
      <li>Initially, a table visualization is created.</li>
      <li>Change the visualization type to a Line Chart.</li>
      <li>For better representation, switch to a Stacked Column Chart or Stacked Bar Chart.</li>
    </ul>
  </li>
  <li>Format the Chart:
    <ul>
      <li>Select the visualization and click on Format your visual.</li>
      <li>Adjust general options and specific options for the visual.</li>
    </ul>
  </li>
  <li>Fit the Canvas: Use the view options to Fit to width or Fit to page for better working space.</li>
  <li>Create Another Visualization:
    <ul>
      <li>Copy the existing visualization (Ctrl+C) and paste it (Ctrl+V).</li>
      <li>Move the new visualization to a different position.</li>
    </ul>
  </li>
  <li>Modify the New Visualization:
    <ul>
      <li>Change the data fields if needed (e.g., remove Total Units Last Year).</li>
      <li>Change the category to Segment, Family Name, or Buyer.</li>
    </ul>
  </li>
  <li>Change Visualization Type: Change the new visualization to a Tree Map for better comparison of sizes.</li>
  <li>Explore Chart Types: Familiarize yourself with the different chart types available in the visualization gallery.</li>
  <li>Work with Your Data: Remember that working with your own organizational data will make using Power BI easier and more relevant.</li>
</ol>

---

__Task 7: Use text and map visualisations:__

<ol>
  <li>Add a New Page:
    <ul>
      <li>Click on the New Page button to create space for visualizations focused on territories.</li>
      <li>Rename the new page by double-clicking the page tab and entering "Territories".</li>
    </ul>
  </li>
  <li>Create a Table Visualization:
    <ul>
      <li>Go to the Field list, expand Store, and select Territory.</li>
      <li>Power BI will automatically create a map visualization.</li>
      <li>To create a table instead, start by selecting the Table visualization type.</li>
      <li>With the table visual selected, choose Territory again to list the territories in the table.</li>
      <li>Adjust the font size to around 12 or 13 for better readability.</li>
    </ul>
  </li>
  <li>Create a Map Visualization:
    <ul>
      <li>Click on the canvas to deselect the table.</li>
      <li>Select Territory again to create a map visualization.</li>
      <li>Resize the map by dragging its edges for better visibility.</li>
    </ul>
  </li>
  <li>Use a Filled Map:
    <ul>
      <li>In the visualization gallery, select the Filled Map option.</li>
      <li>This will overlay the territories on the map, showing each territory in total.</li>
    </ul>
  </li>
  <li>Create an ArcGIS Map:
    <ul>
      <li>Delete the existing map visualization.</li>
      <li>With no visualization selected, choose the ArcGIS Map from the gallery.</li>
      <li>Sign in to ArcGIS if prompted, but focus on adding location-based data.</li>
      <li>Select City under Store and add it to the location field.</li>
      <li>The map will now display a dot for each store location.</li>
    </ul>
  </li>
  <li>Consider Geospatial Data:
    <ul>
      <li>Reflect on the types of geospatial data available in your organization.</li>
      <li>Think about which users would find map visualizations helpful and useful.</li>
    </ul>
  </li>
</ol>

---

__Task 8: Create a Gauge Visualisation:__

<ol>
  <li>Add a Gauge Visualization:
    <ul>
      <li>Locate the gauge icon in the visualizations pane (same row as maps).</li>
      <li>Click on the gauge icon to add it to your report canvas.</li>
    </ul>
  </li>
  <li>Position and Resize the Gauge:
    <ul>
      <li>Move the gauge to your desired location on the page.</li>
      <li>Resize the gauge by dragging its edges to fill the space appropriately.</li>
    </ul>
  </li>
  <li>Select Data for the Gauge:
    <ul>
      <li>With the gauge selected, go to the Fields pane.</li>
      <li>Drag the desired data field (e.g., This Year Sales) into the Value well of the gauge visualization.</li>
    </ul>
  </li>
  <li>Set the Goal (Target Value):
    <ul>
      <li>Drag the goal data field (e.g., This Year Sales Goal) into the Target value well.</li>
      <li>If the gauge does not display as expected, ensure the goal is in the correct well.</li>
    </ul>
  </li>
  <li>Adjust the Maximum Value: If necessary, move the goal data field to the Maximum value well to set the maximum value for the gauge.</li>
  <li>Format the Gauge:
    <ul>
      <li>Go to the Format pane and expand the Gauge axis section.</li>
      <li>Change the Target color to your preferred color (e.g., brick red).</li>
      <li>Ensure the goal is correctly placed in the Target value well for the color change to take effect.</li>
    </ul>
  </li>
  <li>Interact with the Gauge:
    <ul>
      <li>Select different territories or data points to see the gauge update dynamically.</li>
      <li>The gauge will reflect the selected data, showing performance against the goal.</li>
    </ul>
  </li>
  <li>Further Formatting:
    <ul>
      <li>Use the formatting tools to adjust titles, colors, and other visual elements to meet your design requirements.</li>
      <li>Ensure consistency in colors and styles across your visualizations for a cohesive look.</li>
    </ul>
  </li>
</ol>

---

__Task 9: Slicers to filter:__

<ol>
  <li>Add a Table Visualization:
    <ul>
      <li>Ensure no other visualization is selected.</li>
      <li>Click on the Table icon and place it on the canvas.</li>
      <li>Drag fields to populate the table (e.g., City under Store).</li>
    </ul>
  </li>
  <li>Convert Table to Slicer:
    <ul>
      <li>Select the table visualization.</li>
      <li>Click on the Slicer icon in the visualization gallery (left of the table icon).</li>
      <li>The table will convert to a slicer with checkboxes.</li>
    </ul>
  </li>
  <li>Use the Slicer:
    <ul>
      <li>Select items in the slicer to filter data (e.g., select Ohio to filter data for Ohio).</li>
      <li>Hold Control to multi-select items (e.g., Maryland, Ohio, and Tennessee).</li>
    </ul>
  </li>
  <li>Change Slicer Display:
    <ul>
      <li>Switch between List and Dropdown display options for the slicer.</li>
      <li>List shows all items with checkboxes.</li>
      <li>Dropdown allows selecting one item at a time, saving space.</li>
    </ul>
  </li>
  <li>Add a Title to the Slicer:
    <ul>
      <li>Go to Formatting > General settings.</li>
      <li>Add a title like "Choose one or more territories" to instruct users.</li>
    </ul>
  </li>
  <li>Rearrange Elements:
    <ul>
      <li>Modify the page layout and rearrange elements as needed.</li>
      <li>Ensure the current types of visualizations are maintained.</li>
    </ul>
  </li>
</ol>

---

__Task 10: Sort, copy, and paste visualisations:__

<ol>
  <li>Sort Visualizations:
    <ul>
      <li>Select the visualization you want to sort.</li>
      <li>Click the More Options button (three dots) on the visualization.</li>
      <li>Choose Sort by and select the column you want to sort by (e.g., Sales Goal or District Manager).</li>
      <li>Choose Ascending or Descending order.</li>
    </ul>
  </li>
  <li>Add a Column for Sorting:
    <ul>
      <li>Go to the Fields pane and select the column you want to add (e.g., This Year's Sales Goal).</li>
      <li>Drag the column to the visualization to add it.</li>
      <li>Use the More Options button to sort by the new column.</li>
    </ul>
  </li>
  <li>Copy a Visualization:
    <ul>
      <li>Select the visualization you want to copy.</li>
      <li>Press Ctrl + C to copy the visualization.</li>
    </ul>
  </li>
  <li>Paste a Visualization:
    <ul>
      <li>Click on the canvas where you want to paste the visualization.</li>
      <li>Press Ctrl + V to paste the copied visualization.</li>
      <li>You can paste it on the same page or a different page.</li>
    </ul>
  </li>
  <li>Delete a Page:
    <ul>
      <li>Click the Page tab of the page you want to delete.</li>
      <li>Click the small X that appears in the upper right-hand corner of the tab.</li>
      <li>Confirm the deletion when prompted.</li>
    </ul>
  </li>
</ol>

Save the report at the end of this section here.

__End with KAHOOT Q6-10__

__GREAT JOB ON MAKING IT SO FAR, I HOPE YOU'VE REALLY LEARNED SOMETHING USEFUL TODAY!!__

---

__Extra: Skip over this during the session except for renaming (step 6):__

<ol>
  <li>Duplicate the Page: Right-click on the page you want to duplicate and select "Duplicate Page".</li>
  <li>Access the Filters Pane:
    <ul>
      <li>Collapse the visualizations pane.</li>
      <li>Expand the filters pane.</li>
    </ul>
  </li>
  <li>Add a Filter:
    <ul>
      <li>Go to the data field you want to filter by (e.g., Store > Territory).</li>
      <li>Drag and drop the field into the filters pane to filter the page.</li>
    </ul>
  </li>
  <li>Select Filter Values: Choose the specific values you want to filter by (e.g., Georgia, North Carolina, South Carolina).</li>
  <li>Advanced Filtering Options: Use advanced filter options to set conditions (e.g., contains, does not contain, starts with).</li>
  <li>Rename the Page: Double-click the page tab to rename it (e.g., Southeast Region Category & Buyer).</li>
  <li>Save the Report: Save the report to apply and keep the changes.</li>
</ol>

---

__Extra: Adding a filter to the report:__

<ol>
  <li>Create a Copy of the Report:
    <ul>
      <li>Save the existing report using "Save As" and give it a new name (e.g., Southeast Retail Analysis).</li>
      <li>Place the new report in your workspace.</li>
    </ul>
  </li>
  <li>Enter Edit Mode: Click "Edit" to go back into edit mode.</li>
  <li>Open the Filters Pane: Open the relevant data field (e.g., Store > Territory).</li>
  <li>Add Filters:
    <ul>
      <li>Drag the field to "Filters on all pages".</li>
      <li>Use either basic or advanced filtering to select specific values (e.g., Georgia, North Carolina, South Carolina).</li>
    </ul>
  </li>
  <li>Manage Slicers:
    <ul>
      <li>Decide whether to keep or delete the slicer from the territory.</li>
      <li>Users can still use the slicer to filter by individual states if kept.</li>
    </ul>
  </li>
  <li>Hide Filters from Users:
    <ul>
      <li>Use the show/hide button to hide the filters pane from users in Reading view if you don't want them to change the filter.</li>
    </ul>
  </li>
  <li>Save and Close:
    <ul>
      <li>Save the report and close it.</li>
      <li>Return to the home page.</li>
    </ul>
  </li>
</ol>



