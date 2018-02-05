# Link Peak Analysis

Application which will determine the max interface utilization values for a group and time-range specified by the CAPC Dashboard. The App generates a report which provides the max value for 3 key time ranges: 1. Business hours (7 AM to 6 PM M-F) 2. Outside of business hours 3. 24x7. The App also determines the amount of time each interface spent over a threashold of 70% and color codes each cell based on a simple threshold of: 0-69.99: Green, 70-79.99: Yellow, 80-89.99: Orange, 90 and above: Red



##Installation Instructions:

### CAPC 3.0 and later:
1. Download Application ZIP file from the GitHub repository
2. Launch CAPC and access the Administration -> App Installer interface 
3. Select the file downloaded in step 1
   3a. If updating from a previous version of the App, please select the option to update existing apps
4. Add an App View to the CAPC Dashboard or context page
5. Select the Link Peak Analysis app from the drop-down menu and save the view & dashboard
6. Select the target group and time-frame with the CAPC Dashboard controls

##Key URL parameters:
1. id : Group ID of CAPC dashboard
2. starttime: Start time as defined in the CAPC Dashboard
3. endtime: End time as defined in the CAPC Dashboard
4. test: Runs the app with the sample data set

### Mods

All of the variables, thresholds, etc are hard-coded in the app. Change as needed.

===================================================================================

License (refer to license.txt in folder for 3rd party license details)

Copyright (c) 2016 CA Technologies
 
The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
 
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

===================================================================================

