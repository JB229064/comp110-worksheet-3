# COMP110 Worksheet 3: Flowcharts and pseudocode

This is the base repository for COMP110 Worksheet 3.

Fork this repository, and edit `README.md` to show your pseudocode solving the worksheet task. Tip: use triple backticks to preserve spacing, e.g.:

```
WHILE NOT found DO
  select one of the words
  IF selected_word != correct_word THEN
    evaluate likelyhood of chosen word
    see if other words have similar letter patterns
    select another word based off likelyhood
    IF word has been already chosen THEN
	   select another word
	 ELSE DO
	   submit original choice
	   IF selected_word == correct_word THEN
		  unlock terminal
  ELSE DO
    unlock terminal
```
