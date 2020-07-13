## Deploy Data Factory with optional SQL Server and SQL Database

#### Prerequisites:
1. Resource group for the deployment.

#### To be provided:
1. Resource Group
2. Option (Yes or No) to deploy or not to deploy SQL Server, SQL Database and SQL sink within the pipeline.
3. Storage Account Name
4. Data Factory Name
5. SQL Server Name (If selected 'Yes')
6. SQL Database Name (If selected 'Yes')

**NOTE** - If you go with SQL sink, the name of the table where data is written is _**covid_tracking**_.

Click the following button to deploy all the resources.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fosamaemumba%2Farm-template-button-with-condition%2Fmaster%2FbritishColumbia%2Fcomplete_conditional_sql_sink_arm_template.json)
