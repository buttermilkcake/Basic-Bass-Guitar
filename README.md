# Basic-Bass-Guitar
A description of the website I created, https://basic-bass-guitar.herokuapp.com/

*disclaimer: this website is a work in progress*

I’m creating a website call Basic Bass Guitar that will allow users to learn the notes on the fretboard of the bass guitar, the major, 
minor and blues scales, the circle of 5ths, what you need to know to start jamming, maybe a basic blues pattern and also allow them to 
use my song generator, which will give them a title of a song and the key it’s in. They can then go to youtube and 
play along to the song.

A big part of this project was attitude - learning to embrace imperfections, accepting that the first attempts would be very ugly and 
clunky. Focusing on being in the moment, trying to focus on the step I was at, not thinking (or worrying) about the next thing I was 
going to have to figure out. Meeting myself where I was at at that moment in time. Learning the html and creating first with just that, 
then learning the css and improving upon my html and then hopefully learning javascript and improving upon previous iterations.

Oh the fretboard diagram form…..
This took me months to figure out. I wanted to create a fretboard diagram that had the strings and fret numbers filled out, but let the 
user guess which notes or note combos went into each fret/string coordinate. If they guessed correctly, they would get a response saying
so. If they guessed incorrectly, they would get a response saying that. I knew this was an achieveable concept, but I had no freaking 
clue how to approach this beast.

I didn’t even know how to create it on a website. I started out by creating my own fretboard diagram, saving it as a pdf and uploading 
it as a static element into my website. Then I dwelved into databases, and I created this information in a database in the command line,
but I had no idea how to incorporate that into a table. I also didn’t know how to ‘control’ my database since I couldn’t see it and I 
didn’t know how to make it do what I wanted it to do.Then I read about creating a database from a model class with Django and I did 
that, but I still didn’t know how to incorporate that info into a table. Then I discovered how to make a table using html and I created 
a table that was 12 columns x 4 rows. I filled in the fret numbers and the string names. That left the 48 cells that contained the note 
or note combos. Then I started learning about forms and options. Each cell had the same 12 options and I figured out how to set that up,
but this is what it looked like in my html file - this, listed 48 times. It was a huge, ugly thing and I knew that there was a datalist 
widget and an opt group widget and If I were to read up on those, I could probably incorporate them with this and make it better. 
       <td>
          <select>
            <option value="A">A</option>
            <option value="A#_Bflat">A#_Bflat</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="C#_Dflat">C#_Dflat</option>
            <option value="D">D</option>
            <option value="D#_Eflat">D#_Eflat</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="F#_Gflat">F#_Gflat</option>
            <option value="G">G</option>
            <option value="G">G#_Aflat</option>
          </select>
          <button type="submit">Submit</button>
        </td>

At this point the submit button is freaking me out because I had no idea how to set up the submit trail and be able to take in what 
somebody entered, figure out if it was correct and if so, send that message back to them. Or if it was incorrect, let them know that 
as well. I have a form that lists the options, for each cell, has a submit button that goes nowhere and the form looks ugly. However,
it is still in the transitional phase.


I deployed my website to Heroku on 1/22/18, not knowing that local data you enter isn't usually copied to a live deployment, that it is
considered test data. So I need to retrieve my 'test data' which wasn't test data to me and put it back where it belongs!

