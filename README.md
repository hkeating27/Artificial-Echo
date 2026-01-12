# Artificial-Echo

AI application that analyzed the speaking patterns of a story’s main characters, and guesses dialogues’ speaker from the testing data. Up to 150% more accurate than guessing at random

The dataset  is the entire script for the video game Final Fantasy XIV; for context, the spoken dialogue is longer than War and Peace, so it is reasonably long enough for this application. The inputs is the script as a text file with lines formatted as “Name: dialogue”, which is turned into a DataFrame as an output.

Lines less than four words long were ignored so that characters’ unique ways of speaking were more visible; the loss in data size was well worth the tradeoff for quality. 6 speakers were chosen based on their unique mannerisms and large amounts of dialogue; all other dialogue was discarded. Thus there were 9,780 total lines, split 80/10/10 for training/validation/testing.

# You must run the first cell before the rest as it asks you to upload the included .txt
