---
layout: post
title: Blocipedia
thumbnail-path: "img/blocipedia.png"
short-description: Build a production quality SaaS app that allows users to create their own wikis.

---

{:.center}
![]({{ site.baseurl }}/img/blocipedia.png)

## Explanation

This site was my second project created with "the wheels off" if you could say. This project originally was thought to take much less time than originally planned, and because of the longer time this project took, I believe it to be more pollished. This site was built with the help of my mentor Felix Clack at Bloc.io.

## Problem

Wikipedia and other wiki based sites do a great job of showcasing information to users. With this project I wanted to expand on that idea with the aspect of private wikis that could be accessed by public users when a private user granted them access to the wiki. 

## Solution

This addition of 'collaboration' was added that allowed private paying users to allow public users access to their wikis to edit them. This makes it so that as a user you can have wikis you edit, wikis you create, and finally wikis you collaborate on.

## Results

This project was tested completely by me and did not see use from any outside users. However through my testing allowing users to create private wikis was very nice. Including allowing users that have not paid to edit based on your suggestion.

## Conclusion

Again this project was created with a learning goal in mind. The two goals of this project were to create a collaboration model and controller, and to integrate payment into an app. Overall payment was not a real big issue for me, but learning how to collaborate via ```has_many :wikis, through: collorators``` was quite difficult.

<br />

{:.center}
###[Site Link](https://blocipedia-fosterk.herokuapp.com/) | [Source Code](https://github.com/GoDucks713/blocipedia)