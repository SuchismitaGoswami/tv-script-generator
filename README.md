# Tv-script-generator
TV Script Generator is a part of Udacity Deep Learning Nanodegree!

# Project Overview
TV Script Generator generates "fake" Seinfeld TV scripts using RNNs. A part of the Seinfeld dataset of scripts from 9 seasons has been used to train the model. In this project, I built the Neural Network to generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

## Sample training script
```
jerry: do you know what this is all about? do you know, why were here? to be out, this is out...and out is one of the single most enjoyable experiences of life. people...did you ever hear people talking about we should go out? this is what theyre talking about...this whole thing, were all out now, no one is home. not one person here is home, were all out! there are people trying to find us, they dont know where we are. (on an imaginary phone) did you ring?, i cant find him. where did he go? he didnt tell me where he was going. he must have gone out. you wanna go out you get ready, you pick out the clothes, right? you take the shower, you get all ready, get the cash, get your friends, the car, the spot, the reservation...then youre standing around, what do you do? you go we gotta be getting back. once youre out, you wanna get back! you wanna go to sleep, you wanna get up, you wanna go out again tomorrow, right? where ever you are in life, its my feeling, youve gotta go. 

jerry: (pointing at georges shirt) see, to me, that button is in the worst possible spot. the second button literally makes or breaks the shirt, look at it. its too high! its in no-mans-land. you look like you live with your mother. 

george: are you through? 

jerry: you do of course try on, when you buy? 

george: yes, it was purple, i liked it, i dont actually recall considering the buttons. 
```
## Sample generated script

```
hoyt: so what?

hoyt: i can't believe it was an incident.

george: what happened.

jerry: i can't believe this, but i was just a writer. i mean, they had a little adjustment.

elaine:(pointing at the phone and the moops) oh, yeah.

jerry: hey!

hoyt: hey, how do you get the defendant?

jerry: i don't have any money.

hoyt: well, i was a writer. it's like a travesty of selfishness, and you know what they have to do with a bubble.

hoyt: you know, i was a cheater- and you were going to be the one of the united.

hoyt: well, i guess you could do something.

vandelay: proceed.

jerry: what?

jerry: no... you got any bread.

elaine: i don't know if you would be bleak in the courtroom. i mean, i can't believe this.

elaine: i don't know what to do. you know, i have to conserve it.

elaine: oh, no, no. no. i know, i think that would be good for me to interrupt it.

vandelay: proceed!

george: i don't think it's a good idea.

elaine: oh!!!!!!

hoyt: hi, hey, hey.

hoyt: hey, georgie!

[new witness: police steinbrenner].

george: hey, hey!

[new witness: donald sanger, right?

```
# Technology used
- Python Frameworks (NumPy, Pytorch, Matplotlib, etc.)
- Recurrent Neural Network (Tried with both Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU))


# References

- For more of the parameters offered in Tensordataset and dataloader methods as it gives us number of workers and other multiprocessing options if the dataset is big, check https://pytorch.org/docs/stable/data.html
- https://developers.googleblog.com/2017/11/introducing-tensorflow-feature-columns.html