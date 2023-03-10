# Dee and Sanna's Weekly Meeting Notes
* [2 March 2023](#date-26-february-2023)

* [26 February 2023](#date-26-february-2023)

* [23 February 2023](#date-23-february-2023)

* [13 February 2023](#date-13-february-2023)

* [Template](template-date-dd-month-yyyy)


### Date: 2nd March 2023

#### Who did you help this week?
--

#### Who helped you this week?
--

#### What did you achieve?

* Uploaded COVID competition data to HPC
* Began working through the instructions for running team 1's code (their [github](https://github.com/dungnb1333/SIIM-COVID19-Detection/tree/982a6b12955e8f53ec3f8af46754251b1678e08c)). Got through stage 2.1.

#### What did you struggle with?

* I tried running some teams' submission notebooks. While teams submit \textit{just one notebook}, if often requires a larger repository to run. It doesn't seem sufficient to run their submission notebook alone.

#### What would you like to work on next week?

* Download the rest of the external data for team one.
* Finish working on getting their code running (with a small sample of data)

#### Where do you need help from Veronika?

* 

#### Any other topics
--


### Date: 26th February 2023

#### Who did you help this week?

Each other

#### Who helped you this week?

Each other

#### What did you achieve?

* We learned that there are competitions on kaggle tagged as "code competitions". In these, the participants submit code, which kaggle will then run on their machines. We further noticed that code competitions tend to have a higher submission rate per team, with some teams up to 300 submissions, compared to competitions where a team submits an already trained model. It seems that this method of submission allows for a better tracking of the amount of times code is run, since the model-submission format does not indicate the amount of times a team trained a model for parameter tuning. Therefore, we believe we will get a more accurate result of the carbon footprint by looking into a code compeitions.
* Furthermore, code competitions are run by teams submitting code. Therefore the code is often publically available.
* The first competition we will be looking into is [SIIM-FISABIO-RSNA COVID-19 Detection](https://www.kaggle.com/competitions/siim-covid19-detection/)

#### What did you struggle with?

* We are moving on from the Data Science Bowl 2017 due to issues finding runable publically available code (much of the code we found used legacy languages and packages that are no longer supported), and issues finding a trustworthy source of data.

#### What would you like to work on next week?

* Working on a notebook to submit to the competition and run carbon-tracker on.

#### Where do you need help from Veronika?

* Finding value in what we have done (or not done) so far

#### Any other topics

--



### Date:  23rd February 2023

#### Who did you help this week?

Sanna helped Dee find the kaggle datasets.

#### Who helped you this week?

See above. 

#### What did you achieve?

* Found the kaggle datasets (not so straightforward as expected)
	* https://academictorrents.com/details/015f31a94c600256868be155358dc114157507fc	
* Found supplementary data
	* [1st](https://github.com/lfz/DSB2017)
		* [Luna 16 Grand Challenge](https://luna16.grand-challenge.org/Download/)
	* [2nd](https://github.com/juliandewit/kaggle_ndsb2017)
		* None needed
	* [7th](https://github.com/NDKoehler/DataScienceBowl2017_7th_place)
		* [Luna 16 Grand Challenge](https://luna16.grand-challenge.org/Download/)
* We found competitions that are complete, have publically available code, and have publically available data:
	* [RSNA 2022 Cervical Spine Fracture Detection](https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection)
	* [RSNA Breast Cancer Detection](https://www.kaggle.com/competitions/rsna-breast-cancer-detection)
		* Might not have publically available code in time
		* Is it too similar to the Cervical Spine Competition (<9hr run time restriction on code?)
* We learned that the category "code competition" on kaggle means teams submit code vs a trained model. Therefore competitions with this tag are more likely to have publically available code. We are thinking to narrow our investigation to competitions with the tag **code competition**. Furthermore, these types of competitions have restrictions regarding resources and environments, as well as maximum runtime. This might reduce the amount of confounding factors as well as make it easier to extrapolate on our findings. 

#### What did you struggle with?

* Finding the data for the competition.

#### What would you like to work on next week?

* The following items are needed for each project to work:
	* [1st](https://github.com/lfz/DSB2017)
		* nothing is apparently missing
	* [2nd](https://github.com/juliandewit/kaggle_ndsb2017)
		* nothing is apparently missing
	* [7th](https://github.com/NDKoehler/DataScienceBowl2017_7th_place)
		* Checkpoint folder is required to run the project, but it has been removed from dropbox

* We are moving on from the lung cancer competition for now.
* Download data for cervical spine fracture detection
* Attempt running code for the cervical spine fracture detection competition

#### Where do you need help from Veronika?

* Guidance on problem solving finding the data/missing elements
* Is it safe to download the data to the HPC from the sources we found?
* Next week... can we meet Thursday since the PURRlab event is also Thursday, and we will be at ITU?


### Date: 13th February 2023

#### Who did you help this week?

Each other.

#### Who helped you this week?

Google.

#### What did you achieve?

* Found 3 github repos for high ranking teams for the Kaggle lung cancer challenge:
	* 1st https://github.com/lfz/DSB2017
	* 2nd https://github.com/juliandewit/kaggle_ndsb2017
	* 7th https://github.com/NDKoehler/DataScienceBowl2017_7th_place

* Started working on how to actually run the first one.

#### What did you struggle with?

* Working out how to handle requirements for each repo, and looking at how to make the code run.

#### What would you like to work on next week?

* Continue with how to run the first project
* Test the requirements.txt file on Sanna's computer
* Finish setting up a requirements.txt file for HPC
* Start looking at the next submission where code is available

#### Where do you need help from Veronika?

* It seems some packages used are outdated. Is it ok if we use different versions of packages for the environment? 



### Date: [Template]

#### Who did you help this week?

Replace this text with a one/two sentence description of who you helped this week and how.


#### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

#### What did you achieve?

* Replace this text with a bullet point list of what you achieved this week.
* It's ok if your list is only one bullet point long!

#### What did you struggle with?

* Replace this text with a bullet point list of where you struggled this week.
* It's ok if your list is only one bullet point long!

#### What would you like to work on next week?

* Replace this text with a bullet point list of what you would like to work on next week.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Where do you need help from Veronika?

* Replace this text with a bullet point list of what you need help from Veronika on.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Any other topics

This space is yours to add to as needed.
