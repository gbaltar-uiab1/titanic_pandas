# titanic_pandas

## About this Notebook
This Jupyter notebook, ```Titanic_Pandas_Practice_Notebook.ipynb```, showcases Basic data manipulation and analysis using Pandas on Python. <br>
The accompanying Dataset, ```titanic_dataset.csv```, is a basic CSV file containing passenger data, including survivival or decease. Leveraging Pandas, the Dataset is converted into a Dataframe and manipulated. <br>
An output CSV file is also provided.



## Background


![RMS Titanic](https://www.maritimegoods.com/content/files/2021/2/M_195783747_NWS-j3gMsDDzJhHCVM7TPcJC.jpg)



In the early 20th Century, RMS Titanic was the crown jewel of the British shipping operator White Star Line. The Titanic was the biggest ship ever built, designed to withstand almost any contingency at sea —including a head-on collision with another ship or an iceberg— and marketed as  "*practically unsinkable*". 


!['Untergang der Titanic', by Willy Stöwer (1912)](https://upload.wikimedia.org/wikipedia/commons/6/6e/St%C3%B6wer_Titanic.jpg)



Paradoxically, it did hit an iceberg, but rather than head-on, the Titanic took a glancing blow to the starboard (right side), scraping along the iceberg and sustaining multiple ruptures that, though small, flooded five compartments. The Titanic's safety specifications only guaranteed vessel buoyancy with up to three flooded compartments. Consequently, the Titanic sank in the North Atlantic on its maiden voyage, only three and a half days after its last departure from Queenstown (now Cobh) in Co. Cork, Ireland. 


Humanity's greatest feats have always been greeted with the people's awe, support, and celebration. Consequently, those that end in tragedy have a profound effect in the society of the day and somehow become part of lore, so that they are remembered for generations. Such is the case of the Hindenburg Zeppelin's disaster (1937), NASA Challenger spacecraft's disintegration (1986), and before them the RMS Titanic (1912). One can hardly argue against the fact that *Cultural Trauma* has an inequivocal effect upon *Collective Memory*.


However, when it comes to details, people rely on popular depictions such as comics, novels, or motion pictures. Such is the case of the RMS Titanic. Unfortunately, as most historic films give notice of, *"This story is based on actual events. In certain cases incidents, characters and timelines have been changed for dramatic purposes. Certain characters may be composites, or entirely fictitious."* 


James Cameron's 1997 film certainly does this, and for the sake of drama the script establishes a clear causality between passenger wealth and survival rate. So much so that the film portrays scenes of less well-off passengers being hindered and locked off to ease access to safety for wealthy patrons.<br>But if one looks at the data they would agree with the official investigation which determined the less well-off were not prejudiced against during evacuation. They did have a head start, however;
- 1st class cabins were the closest to deck (A, B and C decks)
- 1st class passengers had more time to evacuate, as the upper floors weren't impacted by the iceberg. (only F, G and orlop decks were ruptured)
- The Grand Staircase was wider on the upper levels.
<br><br>
![Cutaway diagram showing Titanic's deck layout](https://upload.wikimedia.org/wikipedia/commons/0/0d/Olympic_%26_Titanic_cutaway_diagram.png)

<br>
For illustrative purposes below is a simulation of how the Titanic passengers might have attempted evacuation as the ship progressively flooded;<br>
https://www.youtube.com/watch?v=njKZeWnidG8


