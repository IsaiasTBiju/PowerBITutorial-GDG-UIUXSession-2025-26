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

<ul>
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
</ul>

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
  <li>Create a Report from an Existing Report:
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

