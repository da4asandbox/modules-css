<style>

    @import url('https://fonts.googleapis.com/css?family=Montserrat:thin,extra-light,light,100,200,300,400,500,600,700,800');

    @import 'https://cdn.jsdelivr.net/npm/@shoelace-style/shoelace@2.4.0/dist/shoelace-autoloader.js';
    
    #juncture { font-family: Montserrat; font-size: 20px; -hyphens: none; }
    
    #juncture a { color: #002868; }

    #juncture h1 { font-size: 32px; color: #BF0A31; font-weight: 500; }

    #juncture h2 { font-size: 28px; font-weight: 500}

    #juncture h3 { font-size: 24px; }
    
    #juncture h4 { font-size: 20px; color: #690114; font-style: italic; }

    #contents.section1 { font-size: 40px; }
    
    #activities.section1 h2 { color: #002868; padding-bottom: 0px; }
    
    #discussion2.section1 { padding-top: 0px; }

    ul li { padding: 3px 0px; }
    
    npm install @shoelace-style/shoelace
    
    import '@shoelace-style/shoelace/dist/themes/light.css';
    
    import { setBasePath } from '@shoelace-style/shoelace/dist/utilities/base-path';
    
    setBasePath('https://cdn.jsdelivr.net/npm/@shoelace-style/shoelace@2.4.0/dist/');

</style>

.ve-header "Lesson 2.3: Studying Data History (Part 2): The U.S. Census" position=top sticky logo=https://da4asandbox.github.io/modules/media/DataAdvocacyForAllLogoWebsite.jpg url=https://www.juncture-digital.org/da4asandbox/modules/historicizing-data background=#690014
    - [Homepage](/historicizing-data/)
    - [All Modules](/historicizing-data/)
    - [Module 2](/historicizing-data/)
    - [Lesson Overview](#overview)
    - [↳ Learning Goals](#goals)
    - [↳ Readings](#readings)
    - [↳ Agenda](#agenda)
    - [↳ Activity](#activity1)
    - [↳ Discussion 1](#discussion1)
    - [↳ Tutorial](#tutorial)
    - [↳ Discussion 2](#discussion2)

<p align=center>
     <sl-button href="/historicizing-data/lesson-2/" variant="neutral" size="large">Previous Lesson</sl-button>&nbsp;&nbsp;
    <sl-button href="/historicizing-data/" variant="neutral" size="large">Return to Module Overview</sl-button>&nbsp;&nbsp;
    <sl-button href="/historicizing-data/lesson-4/" variant="neutral" size="large">Next Lesson</sl-button>
</p>

# Contents {#contents}

<p align=center>
    <sl-button href="#overview" variant="default" size="medium">Lesson Overview</sl-button>
    <sl-button href="#goals" variant="default" size="medium">Learning Goals</sl-button>
    <sl-button href="#readings" variant="default" size="medium">Readings</sl-button>
    <sl-button href="#agenda" variant="default" size="medium">Agenda</sl-button>
    <sl-button href="#activity1" variant="default" size="medium">Activity: Census Data Today</sl-button>
    <sl-button href="#discussion1" variant="default" size="medium">Discussion 1: Dan Bouk, Census Stories, USA</sl-button>
    <sl-button href="#tutorial" variant="default" size="medium">Tutorial: Spreadsheet Functions and Census Data</sl-button>
    <sl-button href="#discussion2" variant="default" size="medium">Discussion 2: Who Counts in the US Census?</sl-button>
</p>

  <SlButtonGroup label="Example Button Group">
    <SlButton>Button</SlButton>
    <SlButton>Button</SlButton>
    <SlDropdown>
      <SlButton slot="trigger" caret>
        Dropdown
      </SlButton>
      <SlMenu>
        <SlMenuItem>Item 1</SlMenuItem>
        <SlMenuItem>Item 2</SlMenuItem>
        <SlMenuItem>Item 3</SlMenuItem>
      </SlMenu>
    </SlDropdown>
  </SlButtonGroup>
  
  <sl-button>Click me</sl-button>

# Lesson Plan 2.3 Overview {#overview}

This class examines one of the major sources of data used by researchers, activists, and policy-makers today: the US Census. By working with Census data and studying the history of how it has collected and categorized information about the US population, students learn how political and social categories have been mapped onto quantifiable data and some of the limitations of this population-level data.

# Learning Goals {#goals}

1. Study the social and cultural history behind census data and its creation
2. Understand the process of categorization and data collection
3. How to work with tabular datasets

# Readings {#readings}

- Bouk, Dan. “8 Miles through Alaska, as Mrs. Parrott Rows; Or, Into the Archives!” _Census Stories, USA,_ October 29, 2018. [https://censusstories.us/2018/10/29/Alaska-paths.html](https://censusstories.us/2018/10/29/Alaska-paths.html).
- Bouk, Dan. “Standing on the Crater of a Volcano.” _Census Stories, USA,_ July 27, 2020. [https://censusstories.us/2020/07/27/disfranchisement.html](https://censusstories.us/2020/07/27/disfranchisement.html).
- Bouk, Dan. “The Partners of Greenwich Village.” _Census Stories, USA,_ July 3, 2018. [https://censusstories.us/2018/07/03/partners.html](https://censusstories.us/2018/07/03/partners.html).

#### Instructor Note:
> _Dan Bouk’s Census Stories, USA is a collection of blog posts written during the course of his research for his book, Democracy’s Data. They are written in a more informal style than a traditional academic monograph, and offer bite-sized windows into the social, political, and cultural history behind the US Census. They are, above all, a reminder that data itself has a history and one that is wrapped up in the lives of individual people._

# Agenda {#agenda}

- [Activity: Census Data Today (15 min.)](#activity1)
- [Discussion: Dan Bouk, Census Stories, USA (20 min.)](#discussion1)
- [Tutorial: Spreadsheet Functions and Census Data (25 min.)](#tutorial)
- [Discussion: Who Counts in the US Census? (15 min.)](#discussion2)

# Lesson Plan {#activities}
## Activity: Census Data Today {#activity1}

#### Instructor Note:
> _This activity has students explore modern census data for their home state. They should get a sense for what kind of data the government is collecting along with sparking their interest about some of the data insights into their state. This will set up the rest of today’s discussion about how this information has been collected and used at different points in American history._

### Individually:
- Find the the US Census Bureau’s “data profile” of your home state:
    - Go to https://data.census.gov/map 
    - Click on your home state
    - Click “View Profile”
- Spend several minutes and skim through the data profile for your state. Take note of the following:
    - What KIND of information is being shown on this page? What are the different sources of this information?
    - What are 3 interesting results or patterns that you didn’t know or found surprising about your home state?
    - What other data about your state do you wish you could find on this page?

### In small groups:
- Share what you found with your group members and collectively come up with 1 interesting result + 1 additional piece of data you want to know more about.

### Whole class:
- Each group share your chosen 1 interesting result + 1 additional piece of data that you want to know more about.

## Discussion 1: Dan Bouk, Census Stories, USA {#discussion1}

### Individual Free-Write:
- Which of these “stories” did you find most compelling and why? 

### Small Group Discussion:
- Assign one of the “stories” to each group.
- Who is the main character in this story?
- What is the narrative arc of the story?
- What is one bigger takeaway from this story that helps you understand the history of data?

### Whole Class Debrief:
- What sorts of questions do these readings raise about the census data you looked at earlier for your home state?
- How do you think this modern data was collected?


## Tutorial: Spreadsheet Functions and Census Data {#tutorial}

#### Instructor Note:
> _These activities will help students get more comfortable working with spreadsheets and understanding how spreadsheet functions work while also highlighting some of the political choices that shape the Census data and how it is recorded and categorized._

### Get the Data
Today you're going to be learning some more spreadsheet skills using state-level census data from 2010 and 2020. To get started, make a copy of the following Google Sheet: https://docs.google.com/spreadsheets/d/1MqIsMvJW5EddzWiOk4jddqNojcNkN_IaNsGNtfmZL7w/edit?usp=sharing.

.ve-iframe https://docs.google.com/spreadsheets/d/1MqIsMvJW5EddzWiOk4jddqNojcNkN_IaNsGNtfmZL7w/edit?usp=sharing width=80% height=800px

### Spreadsheet Functions
Spreadsheet functions are a way to change, modify, or calculate values based on the existing data in an individual cell. The following video goes into more detail on functions and how to use them -***watch from minute 20:00 to 28:20:***

.ve-media https://www.youtube.com/watch?v=TENAbUa-R-w start=1200 end=1701 width=70% caption="Kevin Stratvert, How to use Google Sheets - Tutorial for Beginners, (November 14, 2022)"

Answer the following questions by applying some of the functions you learned in the above video to your Google Sheet:
- What was the change in total population for each state between 2010 and 2020? *Write a function in `Column D` (red) that calculates the net gain or loss for each state.*
- What was the percentage change in population for each state? *Write a function in `Column E` (yellow) that calculates the net change in population as a percentage of the state’s 2010 population.*
- How many people live in each state as a percentage of the entire country’s population? *Write a function in `Column F `(blue) that calculates the 2020 population of each state as a percentage of the combined 2020 population of all states.*

Use the spreadsheet [sorting feature](https://support.google.com/docs/answer/3540681) to sort the Population Change sheet so you can see patterns:
- ==What states LOST population between 2010 and 2020?=={description="Answer: Illinois, Mississippi, and West Virginia"}
- ==What three states had the largest GAIN in population as a percentage of their 2010 population?=={description="Answer: Utah, Idaho, Texas"}

### Missing Data:

#### Instructor Note:
> _The rest of the tutorial focuses on missing data: namely, Puerto Rico. Although the US Census collects information about Puerto Rico, oftentimes you will not see those numbers in tables of state-level census data because Puerto Rico is a federal territory, not a state. This sets up the following discussion about who “counts” in the US Census and how certain people are categorized and counted._

The total U.S. population counted by the 2020 Census was `331,449,281`. However, in a number of news articles and other data tables you will find a different, higher number: `334,735,155`. Collectively put on your detective hats and try to find the answer: ==**What accounts for this discrepancy of more than 3 million people?**=={description="Answer: Puerto Rico"}

- Insert a new row into the sheet and add the missing data.
- Sort your rows by the 2020 population. 
- Where does your new row fall in a national rank of states by population? What states is it comparable to? 
## Discussion 2: Who Counts in the US Census? {#discussion2}
The fact that Puerto Rico often does not appear in tables of state-level Census data is a direct result of the United States's history of colonialism. [The following video](https://www.youtube.com/watch?v=8EOxtY3M6Co) gives some historical background on the topic:

.ve-media https://www.youtube.com/watch?v=8EOxtY3M6Co width=70% caption="Christina Thornell, “Why Puerto Rico is not a US state,” Vox Media, (January 15, 2018), "

### Small group discussion:
- In what ways do Puerto Rico’s residents “count” within the United States population? 
- In what ways do Puerto Rico’s residents not “count”?

### Categorizing People

#### Instructor Note:
> _You can find the answers to each of these scenarios [here](https://www.census.gov/content/dam/Census/programs-surveys/decennial/2020-census/2020-Census-Residence-Criteria.pdf). All of these examples get at just how challenging it is for the US Census to not just count people, but to categorize them based on where they live._

The Census Bureau aims to record the state in which a person resides and the specific location within that state. To do so they use the concept of “usual residence,” which is defined by the Census Bureau as the place where a person lives and sleeps most of the time. Given this general definition, go through the following scenarios in small groups and come up with an answer for how you think the Census Bureau should count them:

- An international student enrolled at an American university for one semester
- An American student studying abroad in a foreign country
- Someone experiencing homelessness who sleeps in their car
- A service member stationed at a military base in another country
- A service member stationed on a vessel in international waters
- A seasonal employee who works part of the year in multiple states

### Whole class discussion:

- What are some the lessons you learned today about census data that you might apply to contemporary data advocacy projects? What should you keep in mind while working with census data?

<br>
<p align=center>
     <sl-button href="/historicizing-data/lesson-2/" variant="neutral" size="large">Previous Lesson</sl-button>&nbsp;&nbsp;
    <sl-button href="/historicizing-data/" variant="neutral" size="large">Return to Module Overview</sl-button>&nbsp;&nbsp;
    <sl-button href="/historicizing-data/lesson-4/" variant="neutral" size="large">Next Lesson</sl-button>
</p>

.ve-footer
    - [Module Overview](/historicizing-data/)
    - [Return to Homepage](/historicizing-data/)
    - [View All Modules](/historicizing-data/)
    - [Next Lesson](/historicizing-data/lesson-4/)