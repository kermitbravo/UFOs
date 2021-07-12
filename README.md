# UFOs
UFO Sightings

## Overview of the Project
In this website we will demonstrate the usage of JavaScript and HTML to filter a table using the D3 library along with other concepts, like working with Objects, functions and events.

## Results

In order for Dana to be able to leverage this website appropriately, she needs to follow these steps: 
1) Navigate to the website
2) On the left side of the website, enter the search criteria for what she's looking for: 
  - e.g. In the Enter City search box she could type "el cajon", then either hit enter or click outside of the search box: 
  ![Using the filter search box](/static/images/walkthrough_sample1.png " Using the search box to filter the UFO dataset.")
3) We can clear the input from the search box and hit enter and we should be able to get back to the starting point
4) Dana can enter multiple search criteria like so and the table will be filtered using all of the filters at the same time like so: 
  ![Using multiple filter search boxes](/static/images/walkthrough_sample2.png " Using multiple search boxes to filter the UFO dataset.")


## Summary

Onew drawback of this website design would be that in order for the users to filter they would have to know possible values and that the search criteria needs to exactly match what the dataset contains. 
 e.g. 
 - The filter search boxes are case sensitive. 

In order to improve this, I'd suggest: 

1) I'd add a clear filter button in order to simplify the user experience and maybe filtering the dataset as you type. 
2) Adding further functionality to the table displaying the results to allow users to filter or sort directly from the table header.
3) Instead of having the fields being "free text" maybe we could implement some drop-down fields instead, that way Dana and her users won't need to be very familiar with the dataset for the website to be helpful. 
