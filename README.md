## Alveo
Alveo is a real-time trading application for charting and performing technical analysis of the markets.

To download the platform: https://apiaryfund.com/software

To request features & report bugs: https://apiaryfund.com/develop  

## Setting Up Visual Studio for Alveo Development
1. Open the Visual Studio Solution from the repository
2. Locate the dll's
  *  The dll's can be found in the Alveo folder under C:\\Program Files\\Alveo
  *  **You may need to show hidden files in windows explorer to view the dll files**
3. Reference the dlls in the Visual Studio solution
  *  In the UserCode Solution Right click on References and select *Add Reference*
  *  Click *Browse* and navigate to the location of the dll files
  *  Select the dll files and press *Add*

## Creating an Indicator
Look at an [example](https://github.com/marlais/Alveo/blob/master/AlveoSampleSolution/Indicators/CustomIndicator.cs) indicator.

Look at the [Wiki](https://github.com/marlais/Alveo/wiki) for additional information on creating an indicator

## Using Custom Indicators
Custom indicators can be used in Alveo  
1.  Open Alveo  
2.  Select *Code*  
3.  Select *Editor*  
4.  Paste the code for the indicator into the editor and press the green *build* button  
5.  Save the indicator  
6.  Add the custom indicator to your chart by going to Insert > Indicators and selecting the indicator from the list
