### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 05/05/2024
### AIM: To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer
### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:
![326161689-f5f29784![326161699-90bcf3a4-23c9-4b38-98e8-ed7106b8c262](https://github.com/SdMdZahi7/WDM_EXP10/assets/94187572/322ecf74-41f9-47b4-90cd-d09806683782)
-e038-4585-b8f7-3b7bc005b81b](https://github.com/SdMdZahi7/WDM_EXP10/assets/94187572/1894d2c0-cf68-45ad-87d5-665b1f92d36d)
![326161711-ebf38b02-016a-4b60-be39-713c0c9cf305](https://github.com/SdMdZahi7/WDM_EXP10/assets/94187572/1545dd3c-81ef-4e5b-a1a4-d0c3e80fbd5e)

### Result:
Thus, sentimental analysis for twitter data using Rapidminer is done successfully.


