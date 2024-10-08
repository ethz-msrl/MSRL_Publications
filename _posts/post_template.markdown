---
layout: publication
published: false # remove this line on your post 
title:  "The Title of your Paper"
year: yyyy 
authors: 
   - First Author
   - Second Author
   - Last Author
   
# at least one first author needs to match a name in authors
# if authors are sharing first author credits, you can list them here
first_authors: 
    - First Author Name
    - Shared First Author Name
link: link to the published version of your paper
# open the pdf version of your paper on research collection and collect the link there
rc_pdf_link: link to the preprint stored on ETH research collection.
# if the paper is already published
publication_date: yyyy-mm-dd
publication: Journal or Conference Title
# set to published if accepted for publication
# set to in review if the paper has not been accepted but you still want a web presence for it
# set to preprint if the paper is only published on a preprint server like arxiv
status: published
# if there is a youtube video, put it here
# Make sure to use the embed link and not the youtube link
# if not, delete this line
youtube_link: https:/youtube.com/video
# if there is a github project associated with this paper, put the link here
# if not, delete this line
github_link: https://github.com/project
# if the paper is published, put the DOI link to the published version
doi: https://doi.org/10.1109/TRO.2020.3047053 
# pub a list of meaningful tags
# use hyphens between words
# use tags that are already listed on the site as much as possible
# Use hyphens and not spaces
tags: [ first-tag, second-tag]
categories: publication
---

<!--
# The following are only suggestions of content that you can include on your publication.  
# Feel free to format this part as you prefer.)
-->

## News ##
* **Date**: Some good news about your paper!
* **Date**: Some older news.

## Abstract ##
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis varius risus. Mauris vulputate dictum dolor, sit
amet vulputate neque condimentum pharetra. Ut tempor risus malesuada turpis elementum, a dignissim orci blandit.
Phasellus vel diam justo. Fusce nisl ex, gravida a rutrum eget, cursus accumsan lorem. Etiam aliquet felis fringilla
massa dapibus, ut fermentum justo porta. Curabitur porttitor lorem nec massa laoreet, id rutrum diam euismod. Nam et
sollicitudin nisi. Proin laoreet velit et vulputate malesuada. Proin blandit tortor ut justo ullamcorper varius.
Phasellus vitae bibendum neque, vitae molestie orci. Suspendisse malesuada vulputate arcu. Fusce nulla nibh, vestibulum
sit amet massa at, hendrerit pretium ex. Curabitur convallis finibus ipsum. Nulla at malesuada nunc.

Suspendisse libero turpis, maximus in mauris a, rutrum consectetur velit. Ut imperdiet dolor non nunc congue, ac
pellentesque lorem lacinia. Integer et sem diam. Ut quam nisl, aliquam vel faucibus sed, vulputate eget justo. Nunc
consectetur mi quis eros suscipit ultrices. Sed maximus fermentum pharetra. Pellentesque posuere efficitur odio sed
tristique. Aenean ultrices erat id magna iaculis, et varius enim consequat. Donec convallis neque euismod lacus
porttitor laoreet. Donec vulputate facilisis ligula, non porttitor augue fringilla nec. Nam dui eros, volutpat vel velit
ac, pharetra ullamcorper justo. Maecenas vulputate lacus risus, vitae ornare risus hendrerit dictum. Duis vitae lacus
quis metus ullamcorper viverra.

## Some Videos ##
<!--
# Adapt to the path address of your Youtube video (use the embed link and not the Youtube link)
-->
<div class="embed-responsive embed-responsive-16by9">
    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/XqZsoesa55w" allowfullscreen></iframe>
</div>

## Some Figure ##
<!--
# Adapt to the path of your image (example below when the file is in the folder "images" of the repo
-->
![alt text for screen readers](/images/subretinal.png "Text to show on mouseover")

## Links to Resources ##
* [A link to a research collection item](https://www.research-collection.ethz.ch/handle/20.500.11850/471234)
* [A link to GitHub](https://www.github.com/ethz-msrl/Tesla)

## Link to other papers from the website ##
<!--
# If you want to link to another paper on this website (e.g. paper from the same project), you must use a relative path from the current page:
# "../../../yyyy/mm/dd/<publication_name>.html"
# where yyyy-mm-dd is the <publication_date> and the filename of the paper is <publication_date>-<publication_name>.markdown
# See the example below.
# (also try as much as possible to link the papers by common tags)
-->
* [A link to a related paper on this website]({% link _posts/2021-01-20-modeling_emns.markdown %}).

## Bibtex ##
~~~
@article{tag,
author = {Author, First, Author, Second, and Author, Last},
doi = {doi},
journal = {Journal Name},
publisher = {Publisher},
title = {Publication title},
year = {2021}
}
~~~
