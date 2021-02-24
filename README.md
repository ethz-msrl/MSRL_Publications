# Website pages for MSRL publications 

This repository contains the files to advertise your publications on the website as a member of MSRL.

## Introduction

TODO

Link to main website

## Prepare the entry

### Prepare the content and material

- Prepare a the teaser for your paper
   - Prepare your teaser video and upload it on the Youtube channel from MSRL (credentials available [here](https://wiki.msrl.ethz.ch/index.php/MSRL_Members:Youtube)) <br>
   OR
   - Prepare an image ```<name>.png```  (RESOLUTION ?) 
- Prepare a 150 x 150 icon image ```<name_small>.png``` (displayed next to the publication entry on the website main page)

Additionnaly, you are strongly encouraged to prepare richer content for the webpage (e.g. links to other website where the work has been advertised, link to open source code or dataset, extra videos uploaded on Youtube...)

### Prepare the files

- Download the publication template file ```publication-template.markdown```
- Download the author template file ```author-template.markdown```
- Create a file ```<publication_date-name>.markdown``` based on the publication template and fill it in with the required information
- Create as many authors files ```<firstname_lastname>.markdown``` as required (only for authors that are not already in the folder ```_authors```) and fill it in with the required information

## Submit and preview

First, you are going to add your files on a site that is only for preview, and is therefore not public.

### Upload files

- Create a new branch (upper-left corner) (NAME?)

![New branch](documentation/new_branch.png)

- Upload the paper file in the folder ```_posts``` 
- Upload the authors files in the folder ```_authors```
- Upload the images files in the folder ```images``

To upload a file:
- Go to the desired folder
- Click 'Add file/Upload files' (upper-right corner)
- Click 'Commit changes'

### Submit files

To preview your contribution, you have to create a new pull request:

- Click 'Compare & Pull request'

![New PR](documentation/create_pr.png)

- Under 'Create pull request', 'Click 'Draft pull request'

![Draft PR](documentation/draft_pr.png)

This automaticaly starts generating a preview.

### Preview and modify files

The generation of the preview may take up to 30 seconds. The preview is ready once all of the checks have passed:

![Checks](documentation/checks.png)

Once the preview is ready, a new comment from netlify appears with a link to the preview page: 

![Link for preview](documentation/preview.png)

It is time to check your submission:
- Verify the publication pages (text, links and images)
- Verify the author pages (text, links and images)

If editions are needed, the ```.markdown``` files can be edited from the GitHub interface (go to your file and click 'Edit this file' in the upper-rigth corner). Make sure you always commit the changes after edition. You can also replace or delete images or any other files.

![Edit MD](documentation/edit_md.png)

The preview link is updated and the checks ran anew for each new commit, just follow the same steps described in *Submit files* and wait for the preview link to be re-generated.

## Publish the entry

Once you are satisfied with the preview, request the administrators to publish your contributon on the public website. In the pull request page, click 'Ready for review'. 

![Submit for review](documentation/review_pr.png)

You are done! Your commits are going to be reviewed by the moderators and pulished on the public website.

## How to use markdown and html in your files

TO DO
