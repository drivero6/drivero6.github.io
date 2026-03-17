# Reference Documentation

## **General FAQ**

**What is the data format used with My Favorite Albums?** 

* User’s data is stored in a CSV file, which can be edited in RStudio. 

**Where can I access the source code for My Favorite Albums software?** 

* The source code for the software can be retrieved from a Github page in the form of a ZIP file. 

**Are R and RStudio necessary for using My Favorite Albums?** 

* While R and RStudio are not the only Integrated Development Environments (IDE) that can run My Favorite Albums, the code for the software was written in R for RStudio. Users can use an IDE of their choice, but they would have to re-write the code for the My Favorite Albums application in a different language. 

**Do I need an external application to download the packages needed to run My Favorite Albums?** 

* No, all additional packages and libraries can be downloaded through RStudio. 

**What are the minimum requirements to run My Favorite Albums?** 

* To use My Favorite Albums, users should have installed:   
  * R and RStudio  
  * My Favorite Albums ZIP file containing the clone source code and related files  
  * Operating system to install programming software on 

**Can I edit the webpage interface?**

* Yes, to edit the webpage interface, edit the source code through the **app\_ui.R** and **app\_server.R** files in RStudio. You cannot edit the webpage interface directly through the interface. 

## **Troubleshooting**

**My generated webpage (application interface) on R Studio is not loading**  
  * Make sure to save changes made to the CSV file and that the spacing for each entry is correct.   

![Image of sample CSV file displayed in the upper-left tab of RStudio](edit_music_data.png)
> Note: Turn on **Show whitespace** to remove unnecessary spaces   

**The application interface will still not run**  
  * Make sure that columns (categories) 1-6 are filled out as they are required to run the application interface. Vinyl, EP, and Live categories are not required. Rerun the application interface.   

**On the Favorite Artists tab, selecting Exclude EPs and Live Albums prompts a “No rows to aggregate message”**   
  * Because this tab’s option excludes both EPs and Live Albums alike, lacking either one in the csv file will result in this error message. Include at least one of each to generate the web application successfully.

**I have lost the project I was working on in RStudio**   
  * Switch between projects by navigating to the top right corner of your screen and selecting the drop down menu, which should show currently opened projects.   
    ![][image3]

**My musical data cannot be read by RStudio**   
  * Make sure you have your data saved as a CSV (\*.csv) file with the following categories as the main columns. Make sure to save edits done to the CSV file to run the application interface successfully.  
    ![][image4]
