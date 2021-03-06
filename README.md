# Rollcall scaling with R

Learn how to graph legislators on the political spectrum based on their rollcall votes, using NOMINATE and other programs developed by political scientists. April 20th, 2015, at 6pm at SUNY Albany, BB B012. 

<p align="center">
<img src="https://raw.githubusercontent.com/wmay/rollcall_scaling_intro/master/House_Clean_Bill_DHS_Funding.png" alt="" width="600px">
</p>

I'll walk through an example using the New York state legislature, starting with raw voting data and ending with fun graphs comparing the Senate to the Assembly and showing changes over time. I recommend bringing a laptop to follow along.

If you're following along, try to get these beforehand:
- R, http://www.r-project.org/
- RStudio, http://www.rstudio.com/products/rstudio/
- this code, download it by clicking the "Download ZIP" button on the bottom of the sidebar on this page
- the required R packages, install them by running the code in packages.R
- New York rollcall data from the Sunlight Foundation, http://static.openstates.org/downloads/2015-03-01-ny-csv.zip

---

Here are just a few examples of people using rollcall scaling data:  
[The polarized Congress of today has its roots in the 1970s (Pew Research)] (http://www.pewresearch.org/fact-tank/2014/06/12/polarized-politics-in-congress-began-in-the-1970s-and-has-been-getting-worse-ever-since/)  
[xkcd: Congress](https://xkcd.com/1127/)  
[How U.S. state legislatures are polarized and getting more polarized (in 2 graphs)](http://www.washingtonpost.com/blogs/monkey-cage/wp/2014/01/14/how-u-s-state-legislatures-are-polarized-and-getting-more-polarized-in-2-graphs/)  
[Martin-Quinn Judicial Ideology Scores](http://mqscores.berkeley.edu/index.php)  
[Voteview Blog](https://voteviewblog.wordpress.com/)  


I'll try to make the talk work well for people who haven't used R before. But if you haven't used R, and you want to try it out, this tutorial explains it very clearly:  
http://www.r-tutor.com/r-introduction

---

Sponsored by these wonderful groups:  
[UAlbany ASIS&T](http://ualbanyasist.com/)  
[Albany R Users Group](http://www.meetup.com/Albany-R-Users-Group/)
