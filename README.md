# belly-button-challenge
Data from the Belly Button Biodiversity Study which sampled the skin microbiota of the belly buttons from 60 healthy volunteers between January and February 2011. Specific details on the methods used to sample skin microbiota, amplify the samples obtained, and to sequence the genome of the samples to identify the specific microbiomes found are reported in the original study by Hulcr et al., 2012 (see Credits for the full reference).
Overall, Hulcr et al. found that 8 microbial species (termed operational taxonomic units, or OTUs, in the study) were present in more than 70% of people. These were dominated by Staphylococci, Corynebacteria, and several genera of Actinobacteria amongst others. The remaining OTUs found were rarer.



## Project Description:
This repository contains the code needed to create an interactive html dashboard, built using JavaScript, to visually display data summarising the OTUs identified by the Belly Button Biodiversity Study for each sample, as well the top 10 OTUs identified overall.

Within the **Starter_Code** subfolder:
**samples.json**
A **.json** formatted library containing the ID number, metadata, and OTUs found for each sample.

**index.html**
A starter browser in which the interactive dashboard is built and displayed. 

Within the **Starter_Code/static/js** subfolder:
**app.js**
This file contains the **.js** code called by the **index.html** page to build and display the interactive dashboard. 



## Installation and Run Instructions:
First, right click on the **index.html** and launch the browser using Google Chrome. Next, display the console window by right clicking anywhere on the page, selecting “Inspect”, and then selecting “Console”. Doing so will help to identify and debug any potential errors in execution.
Second, right click on *app.js** and launch the code using VSCode. Ensure you have pre-installed **Node.js** to assist you to identify and debug any potential errors in execution. Once installed, you can remote into the file path you used to save the repo, and test the code by typing **node app.js**



## Usage Instructions:
Once the connection has been made between **index.html** Google Chrome page and the **app.js** JavaScript, refreshing the **index.html** Google Chrome page will display the interactive dashboard.

Overall, the dashboard should look similar to this:
XX SNAPSHOT

Using the drop-down menu located in the top left corner, users can select a specific sample ID in order to display that sample’s metadata. Having done this, basic demographic information (e.g., ethnicity, age, sex, geographic location, belly button type, and frequency) for each sample are displayed in a table.

For each sample, the top 10 OTUs identified are displayed in horizontally stacked bar chart.

For each sample, a bubble plot displays the OTU identifier and sample value for each OTU identified. These are weighted by sample value such that OTUs found in greater concentrations are displayed as larger bubbles.



## Credits:
This code was compiled and written by me for the belly-button-challenge challenge class homework in the 2024 Data Analytics Boot Camp hosted by Monash University. Additional credits are declared below:

### Belly Button Biodiversity Study Reference:
Hulcr J., Latimer AM., Henley J., et al. (2012). A jungle in there: Bacteria in belly buttons are highly diverse, but predictable. PLoS One, 7(11), e47712. Accessed 30 May 2024 from: https://doi.org/10.1371/journal.pone.0047712 

### Basic plotly documentation:
https://plotly.com/javascript/. Accessed 29 May 2024.

### Creating bubble plots using plotly:
ttps://plotly.com/javascript/bubble-charts/ vaScript (plotly.com). Accessed 29 May 2024.

### Creating dropdown menus:
XXX

### Creating horizonal bar charts using plotly:
https://plotly.com/javascript/horizontal-bar-charts/ JavaScript (plotly.com). Accessed 29 May 2024.
