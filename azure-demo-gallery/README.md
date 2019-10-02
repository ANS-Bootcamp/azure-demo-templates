![ANS](../Images/ans_logo_small.png)
# Azure Bootcamp
For more information on the ANS Azure Bootcamp  visit https://www.ans.co.uk

# VM ScaleSet - File Viewer
**Deploy this template 3rd**

Node.js File Viewer App for Azure training, you can deploy the template using the button below, once the template has depolyed note down the template outputs as these will be required later. 

[![Deploy to Azure](../Images/azure_deploy.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FANS-Bootcamp%2Fazure-demo-templates%2Fmaster%2Fazure-demo-gallery%2Fazuredeploy.json)
[![Deploy to Azure](../Images/azure_view.png)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FANS-Bootcamp%2Fazure-demo-templates%2Fmaster%2Fazure-demo-gallery%2Fazuredeploy.json)

This template creates a virtual machine scale set and utilise a custome extension to instale Node.Js, download Gallery application code from GitHub and configure the Gallery application to run as a windows service. 

![Diagram](../Images/ScaleSet–FileViewer.jpg)