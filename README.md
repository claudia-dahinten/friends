# ![FRIENDS](FRIENDS_logo.png)

**An analysis of the sitcom F.R.I.E.N.D.S**

I am that person that you should avoid watching this TV Show with because I say all the lines before the characters. I am also the person who can’t hear the words ‘Oh My God’ without seeing Janice’s face and I also don’t think I’m capable of moving furniture without shouting ‘PIVOOOT’. I have the Friends poster in my room and I got the t-shirt too. Could I beeee any more obsessed?

When looking into possible Data Science side projects, it was therefore an easy decision to take a deeper look into my favourite TV show.


**Getting Started** <br/>

The data was scraped from the website: https://transcripts.foreverdreaming.org/ and I used Python and it’s various libraries to do the analysis.
Warning: There may be some spoilers.

**Cleaning** <br/>
The main cleaning steps included:

* Corrected misspelled character names
* Deleted stage directions
* Deleted noise from the website (e.g. advertising)
* Included characters lines if they were said by a named character (e.g. delete “tourist”, “cop”, “guy”, “girl” )
* Included character lines if they are said by one person (delete if multiple characters spoke at once)

**Data Analysis** <br/>
Some findings were:

* There were 58,382 total spoken lines
* The number of lines decreased as seasons increased (due to fewer episodes, less characters)
* Rachel is the most talkative Friend
* Phoebe is the least talkative Friend, but when she talks she talks a lot
* There are 339 character in total in Friends
* 87% of lines are by the main characters
* Mike has the most non main character lines
* Rachel and Ross and Monica and Chandler have strong networks, and Phoebe and Chandler have the least strong



