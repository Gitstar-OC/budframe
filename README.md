# Budframe - Build your own docs framework

THis is an in progress project (sorry if you are the reviewer of this I am working on fixing those issues right now). The main thing about creating this project is itself solving the problem I am facing to create this. Here's a [link to the figma files of this project](https://www.figma.com/design/1NNuKxR20hdiExSMsuK5Da/Budframe?node-id=0-1&t=7AXg6oZZjKTsi3jy-1) which has the complete story of budframee in it and also pasted below for your convenience

If you find this idea to be time wasting you might just reject this whole idea : ( but I would love for you to hear about it a bit first then read if it's sounds exciting and you have spare time. Some part of this project is inspired by 2 of my other projects which I have made one is https://discover.iamoc.me and other one is for a non profit - ETR (Currently in NDA but simply put it's using lot of mdx files for different articles)    

Fixes are underway while you are seeing this, and I might not be able to complete this today so sorry for it :( I might just upload a simple version in couple hours. 

P.S. - You might think that oh I can take help to write it from a lot of rosources from the internet including llm's but the thing is they are not good at creating something like this which is also why I plan to release llms.txt files along with this so we can train and make our llm's better so next time you will not need to read any of this and your ai bot will be able to help you out with this stuff. Also the reason why they are not good at it is that there's not a lot of code which can teach or shows how [slugs] in nextjs is being used in repos, mostly mintlify / fumadocs / nextra serve as a provider for all the current documentation while modifying or creating custom version of documentation is super hard you will get to know why it is after you see this. (There are some ways it's not that though as there are multiple ways to achieve the same results with different methods) 

--- 

Oh, actually I was thinking of naming this something more like learn to create your own docs! but it’s acronym didn’t work out very well so I thought of other names. I knew that build-your-own-x exists on Github and is one of the most popular repo so build your own docs was the first choice. Iterating over it I finally decided to keep the name as Budframe.  (Initially I was thinking of some Japanese names for it like Shiki and cam up with nyx)


After this as I thought of writing all this things notion would have been easier for me to do all of this stuff rather than investing a lot of time in it but I am a design engineer and the point of this was to like create a page as this is a sub part of my own site with just .mdx files and nothing else, even the metadata, og images and images in this! 

I have some features here which will help you learn and copy this in a clear and concise way, You can see all the features by clicking over this or the menu icon and change the fonts, themes, sub fonts (to show notes and other stuff like this), accent color etc. I should not tell you this but you can just use cmd + and - to zoom in and out to increase or decrease text size ;P. You can also hover over texts which are in the accent color that you have selected to see additional info about it. You will need to click on it if you are on mobile, don’t worry I have increased the clickable area of each of them to make sure that you are able to click each of them and reduced this magic or new words (words which you don’t know) 

While writing this all up I just found out that I am using the pronoun ‘ I ’ a bit too much in all of this will change that later on when I get some free time. On top of that I also have invested some of my time into developing different ways to view this markdown files.  

One of them is story mode (again you can switch this using the dropdown menu). Try it out so you know what it is. It’s taken from a authors site (I forgot him and his site tbh, if you know that please share up that with me via the suggestion option in the dropdown) where you will see a line with particular words underlined in it clicking on them will expand it a bit and it will share you his complete story (all of this with a blur effect as why not, you can turn blur off btw I don’t need blur to make ui’s good looking tbh) 

Other mode is a different sub pages for all this mdx files with a sidebar (which you can turn off too!) and pagination component below to change or navigate between those pages also apologies in advance because I have not added up any toc (table of content) in the story or the layout with sidebar. I just want to showcase the work I put into animating and creating the menu rather than a simple 50 lines of code thing (don’t worry I will also teach you and your llm how to implement that)

If you read the last line properly you might know I use the word AI in it (kinda), I know you guys won’t read this whole thing to just learn about writing or creating docs and it’s framework and large language models are very bad at doing this kind of things so I also have created llms.txt file to let the model learn this and save you some money and time!  (this are also just plain markdowns tbh I don’t like wasting my time doing this small copy-pasting so either I write code to avoid this or I let my own agents do it). Well you now got some sneak peak onto what’s coming next! 

While developing this I have not used any docs framework or packages from fumadocs / nextra / docusaurus this docs frameowork to create BudFrame! It’s competely custom built using react markdown, markdown files, nextjs own mdx providers and some syntax highlighters for code, Image component from nextjs to avoid layout shifts and so on.

--- 
