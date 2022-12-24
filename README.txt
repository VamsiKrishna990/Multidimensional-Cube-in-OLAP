Pre-requisite for Designing and Building a Multidimensional cube:
• Following services should be running: 
 o SQL Server
 o SQL Service Analysis Server 
• Analysis engine must be installed in MS SQL Server. 
• Analysis Service Extension Should be installed in visual studio. 
• A Sample Data Warehouse is needed.
Steps for Designing and Building a Multidimensional cube: 
Step 1: Create a new project with Analysis Services Multi-Dimensional and Data mining project and  name it as Adventure Works DW2019.ds
Step 2: Connect to new Data source by selecting the sample Data Warehouse Adventure works  DW2019. Set the Authentication to SQL Server Authentication.
Step 3: Create a Data Source View with the existing tables.
Step 4: Create a Data cube by following the below steps: 
• Select use existing Table and click next. 
• Select the core table which contains all the tables (in our case Factinterntsales) in this step  and click next. 
• Click next 3 times to finish creating the cube. 
Step 5: Before you deploy the Data cube, we must specify the attributes and hierarchy for each  dimension. 
Step 6: Deploy and Process the data cube. The Cube is finally built and deployed. We can use SQL analysis services to perform MDX queries on  the cube. 
Use MDX queries to pull the data from the data cube to perform business analysis. We can also impliment power BI to visualize our result.
