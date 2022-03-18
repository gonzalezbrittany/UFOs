# UFOs

## Overview of the Analysis:

The purpose of this analysis is to create a html page that displays information related to UFO sittings in different regions. By creating filters on the html page, users can interact with the data, so it shows only the desired information.

## Results:

Multiple filter search boxes were created to allow the user to search for the needed info without searching the data line by line. The available search boxes are shown below.

![image](https://user-images.githubusercontent.com/26393180/159060952-47c35fe4-85b5-43de-a036-669eb27af00b.png)

For example, if the user was interested in UFO sitting information for the date “1/10/2010”, state “ma”, country “us” and shape “triangle. The filter requirements would be entered like below.

![image](https://user-images.githubusercontent.com/26393180/159061458-c56b1b38-7729-4cbf-8b64-4a96c0c628cd.png)

The dataset will only show the lines of data that contain these requested variables.

![image](https://user-images.githubusercontent.com/26393180/159061495-ef28ad12-896b-4103-9894-416388d9eab3.png)


## Summary:

Even though the data is easy to read, and the user can filter the data to only show specified variables, there are some drawbacks to the webpage. For example, the UFO data presented in the table must be manually entered in the JavaScript file. If there were new UFO sitting information discovered, the user of the website would not be able to view this information until the web creator added the new information to the JavaScript file. 

There are a few areas of this webpage that can be further developed as well.
* The current dataset is limited to UFO sittings for January 2010. Recommend adding sitting information for the remainder of the year. Is there a particular month were people report more UFO sittings than others?
* To help keep the data current, another recommendation is to use web scraping so the information presented will always be the most current. This will allow users to have access to new data immediately instead of relying on the web creator to manually add the information.
