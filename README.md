# QA Technical Interview
Interview questions for QA engineers.

## About Cleanroom
Cleanroom is an application gui used to drag and drop files into a drop zone, which then processes your files through the glasswall engine. You can then download the files and see details of what the engine has done to the file afterwards.

## Exercise 1
Write some test cases for the following User story. 

#### Example User story
#### Title
Trial mode of cleanroom

#### Description
A trial mode limitting the amount and size of files that can be dropped into cleanroom. Links to the site also need to be added to allow users/potential client to contact us to purchase cleanroom or our other products

#### Acceptance Criteria
- Sample files supporting main file types and example archives and folders included that can be dragged into the drop zone
- Limits:
  - Limited to 20 files at a time
  - Each file capped at 5mb
  - Breaching either limit gives an error screen and flags if one or both have been breached
- Upgrade link in file drop area takes you to glasswall website
- Book a demo link link added to left panel to link to glasswall website


## Exercise 2
2nd part - Perform some exploratory testing from the above User story.

Link to cleanroom: https://cleanroom.glasswall.com/

#### Test Charter

Explore Glasswall Cleanroom trial mode  
With a variety of files of different sizes and types  
To discover any issues that are introduced outside of the acceptance criteria
