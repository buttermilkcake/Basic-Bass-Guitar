# Basic-Bass-Guitar
A description of the website I created, https://basic-bass-guitar.herokuapp.com/

I’ve created a website call Basic Bass Guitar that allows users to learn the notes on the fretboard of the bass guitar, the major, 
minor and blues scales, the circle of 5ths, what you need to know to start jamming, a basic blues pattern and also allow them to 
listen to and play along with some different styles of songs.

A big part of this project was attitude - learning to embrace imperfections, accepting that my first attempts at this would probably be ugly and clunky. Focusing on being in the moment, trying to focus on the step I was at, not thinking (or worrying) about the next thing I was going to have to figure out. Meeting myself where I was at at that moment in time.

Oh the fretboard diagram form…..This took me months to figure out. I wanted to create a fretboard diagram that had the strings and fret numbers filled out, but let the user guess which notes or note combos went into each fret/string coordinate. If they guessed correctly, they would get a response saying so. If they guessed incorrectly, they would get a response saying that. I knew this was an achieveable concept, but I had no freaking clue how to approach this beast. I gave up on the fillable form concept of the design for this project. I started out by creating my own fretboard diagram, saving it as a pdf and uploading it as a static element into my website. Then I dwelved into databases, and I created this information in a database in the command line, but I had no idea how to incorporate that into a table. I also didn’t know how to ‘control’ my database since I couldn’t see it and I didn’t know how to make it do what I wanted it to do.Then I read about creating a database from a model class with Django and I did that, but I still didn’t know how to incorporate that info into a table. Then I discovered how to make a table using html and I created tables. I have learned about CSS grids and I suspect these are a better way to go. I also know there are probably cleaner ways to design my tables so that they are not so lengthy. I would like to recreate this website using more html, css and Javascript. I want to learn Javascript. I also want to work more with html, css and relational databases.   
      
I originally deployed my website to Heroku on 1/22/18, not knowing that local data you enter isn't usually copied to a live deployment, that it is considered test data. So I had to re-enter that info in Heroku.

In February, I was working on another project that required that I upgrade to Python 3.6.4 from the Python 3.5.X version I was using and I must have had to upgrade Django as well from 1.11.X to 2.0. I did those things and then deleted my old versions, which Basic Bass Guitar is quite dependent on. When I then tried to access the files for this website in the local environment in early March to work on them, I was in for a rude awakening and I learned some very important lessons. I had to delete my old virtual files, reload them, reinstall Django, fix URL changes, the list goes on..... It is now March 23rd and I'm still working through the issues. I'm making progress but also wrapping my head around the possibility that I will have to start over. 

As of 4/16/18 - I solved my software version issues, made some improvements to my website and pushed those changes to Heroku. My deplyment didn't work at first because my runtime.txt file still showed my Python version as 3.5.x. Once I fixed that issue, my website updates were successfully deployed, and I felt like a rockstar!!!

5/14/18 - The spacing in my tables on the 12 bar blues page was wrong, so I fixed that with a <nobr></nobr> tag on the cells where it was needed. Are there better ways to set up the info I set up in my tables - yes, but the way I set it up is working at this point in time.







