---
layout: post
title:      "CLI Data Gem: Art Throughout the Years"
date:       2019-12-27 19:29:41 +0000
permalink:  cli_data_gem_art_throughout_the_years
---

The idea of this gem is to allow the user to access information to come of the most popular works of art throughout the years. There are works ranging from Leonardo Da Vinci to Edward Hopper. I chose to use this site as it has information regarding some of my all-time favorite paintings. 

During my scraping I used the formating of the specific sections I wanted my gem to pull from while running.
![](https://imgur.com/QcyTPo0) ![](https://imgur.com/LctZHSA) 

When creating my CLI I wanted to make sure that the name, artist's name, time period, and description of each piece of work would be displayed.
So I chose to create a list_pieces method to display a list of the pieces and a print_artwork method as a menu method.
![](https://imgur.com/ya30z2I)

My biggest challenges with this CLI were presented when I had pushed my gem to Rubygems.org before I was completed with it and the updated bundler gem was not shown in it. I had forgotten that when pushing changes it is good to also push those changes as another version to Rubygems.org.
![](https://imgur.com/LuqZbdw)
I was being presented with a "cannot find gem" error that I could not figure out for quite a bit and the whole time it ended up being a simple fix of pushing the changes made back into a new version on the site.

I was also presented with an error in the title_artist_year showing as an unknown method, which for quite a while seemed uncurable. The solution for this issue was to change the information that the scraper was taking from in the my Scraper.rb.

This project was absolutely challenging but totally worth it in the end.
You will find my links below: 
Github link: https://github.com/CGonzalez0115/art_throughout_the_years.git
Coding video: https://youtu.be/bLGQXly9728
