<style>

    @import url('https://fonts.googleapis.com/css?family=Montserrat');

    @import 'https://cdn.jsdelivr.net/npm/@shoelace-style/shoelace@2.4.0/dist/components/button/button.js';

    #juncture { font-family: Montserrat; font-size: 20px; -hyphens: none; }
    
    #juncture a { color: #002868; }

    #juncture h1 { font-size: 32px; color: #BF0A31; font-weight: 600; }

    #juncture h2 { font-size: 28px; }

    #juncture h3 { font-size: 24px; }
    
    #juncture h4 { font-size: 20px; color: #690114; font-style: italic; }

    #contents.section1 { font-size:40px; }
    
    #activities.section1 h2 { color: #002868; }

    ul li { padding: 3px 0px; }

    
</style>

.ve-header "Lesson 2.2: Studying Data History (Part 1): U.S. Slavery" position=top sticky logo=https://da4asandbox.github.io/cameronessay-organization/media/DataAdvocacyForAllLogoWebsite.jpg url=https://www.juncture-digital.org/da4asandbox/modules/historicizing-data background=#690014
    - [Homepage](https://data4all.com)
    - [All Modules](https://data4all.com/modules)
    - [Module 2](/historicizing-data/)
    - [Lesson Overview](#overview)
    - [↳ Learning Goals](#goals)
    - [↳ Readings](#readings)
    - [↳ Agenda](#agenda)
    - [↳ Activity 1](#activity1)
    - [↳ Activity 2](#activity2)
    - [↳ Activity 3](#activity3)

<p align=center>
    <sl-button href="/historicizing-data/" variant="default" size="large">Return to Module Overview</sl-button>
    <sl-button href="/lesson-3/" variant="default" size="large">Next Lesson</sl-button>
</p>

# Contents {#contents2}

<p align=center>
    <sl-button href="#overview" variant="neutral" size="large">Lesson Overview</sl-button>
    <sl-button href="#goals" variant="neutral" size="large">Learning Goals</sl-button>
    <sl-button href="#readings" variant="neutral" size="large">Readings</sl-button>
    <sl-button href="#agenda" variant="neutral" size="large">Agenda</sl-button>
    <sl-button href="#activity1" variant="neutral" size="large">Activity 1</sl-button>
    <sl-button href="#activity2" variant="neutral" size="large">Activity 2</sl-button>
    <sl-button href="#activity3" variant="neutral" size="large">Activity 3</sl-button>
</p>


# Overview

This class examines how enslavers constructed, recorded, and used data to reinforce a system of chattel slavery in the United States in the 1700s and 1800s. By studying this history, students will wrestle with whether this kind of data can be ethically used to recover the people and lives behind the numbers. 

# Learning Goals

1. Understand the role of data within the history of slavery in the United States
2. Gain skills in working with tabular datasets 
3. Examine the tensions between using data to study the history of slavery vs. the risks of dehumanizing the people and lives behind those numbers.

# Readings
- ["Episode 176: Daina Ramey Berry, The Value of the Enslaved from Womb to Grave"](https://benfranklinsworld.com/episode-176-daina-ramey-berry-the-value-of-the-enslaved-from-womb-to-grave/), *Ben Franklin's World Podcast* (March 6, 2018).
    - Teacher’s Note: This interview is based on a larger book project by Daina Ramey Berry. If students have access to the reading, you could assign the following excerpts instead of the podcast: Daina Ramey Berry, *The Price for Their Pound of Flesh: The Value of the Enslaved, from Womb to Grave* (2016), pp. 1-9, 33-57.
- Follow the first 13 minutes of the tutorial: Kevin Stratvert, ["How to use Google Sheets - Tutorial for Beginners"](https://www.youtube.com/watch?v=TENAbUa-R-w) (November 14, 2022):

.ve-media https://www.youtube.com/watch?v=TENAbUa-R-w start=103 end=771 width=70%

# Agenda

- Introduction: Learning About Slavery (10 min.)
- Activity: The Trans-Atlantic Slave Trade Database (15 min.)
- Tutorial: Working With Tabular Data (25 min.)
- Discussion: People vs. Numbers (25 min.)

# Lesson Plan

### Introduction: Learning About Slavery



Slavery was an absolutely foundational part of United States history. Here is the "big picture":
- System of “chattel” slavery developed in United States from 1700s through 1850s
- Slavery accelerated with rise of cotton as a global commodity from 1820s-1850s, as cotton exports (based on enslaved labor) became a major part of the American economy
- US Civil War fought 1861-1865 over the issue of slavery and its expansion
- Slavery officially abolished in 1865 with passage of 13th Amendment

***Small Group Discussion:***
- What are the different ways you’ve learned about the history of slavery in the United States - ex. history classes, movies, books, etc.?
- What people come to mind when you reflect on what you’ve learned about slavery? These can be specific names or general groups of people.

***Recap:***

Studying the topic of slavery in the United States poses some major challenges: namely, that the vast majority of enslaved people did not leave behind written records of their lives. Without these records, historians have had to turn to other kinds of sources and methods. Today we are going to explore one of these approaches: data. Over today’s class you will explore **how quantitative data can (and can’t) be used to understand the history of slavery in the United States**.

To do so we are going to focus on ***two examples*** of historical data related to slavery and US history:
1. The Transatlantic Slave Trade Database
2. Daina Ramey Berry, *The Price for Their Pound of Flesh*

### Introduction: Learning About Slavery
Instructor: go over the following “big picture” of slavery and its history in the United States.
System of “chattel” slavery developed in United States from 1700s through 1850s
Slavery accelerated with rise of cotton as a global commodity from 1820s-1850s, as cotton exports (based on enslaved labor) became a major part of the American economy
US Civil War fought 1861-1865 over the issue of slavery and its expansion
Slavery officially abolished in 1865 with passage of 13th Amendment


## Activity: The Trans-Atlantic Slave Trade Database

Today we're going to look at The Trans-Atlantic Slave Trade Database, a watershed digital project focused on the history of slavery and specifically the forced transportation of enslaved people out of Africa. You're going to practice the same approach you'll be taking when you complete your [Data Biography](module-2/data-biography) of a separate dataset. 

In small groups, go to this starting page: [Trans-Atlantic Slave Trade - Understanding the Database](https://www.slavevoyages.org/voyage/about#methodology/introduction/0/en/). Set a timer for **15 minutes** and try to collectively find answers to the following questions about the dataset, writing notes for each question in a shared Google Doc. 

*Note: this database is part of the larger SlaveVoyages website. You are only  answering questions for the "Trans-Atlantic Slave Trade" databse, but to answer them you will need to explore other parts of the website.*

- **What** kind of information is contained in this database?
- **Where** did the data come from? 
- **Who** collected, processed, and made it available?
- **How** was it collected, processed, and made available?
- **Why** was it collected, processed, and made available?
- **How** is the data stored today? 

<br>
### Debrief
- Which questions did you find the hardest to answer?
- If you were going to give feedback to the project team about its website and documentation, what would you say?

### Takeaways
- One of the important takeawyays of this activity is to develop some strategies for uncovering more information about a database's biography. For this dataset, it requires both skimming the Methodology section of the specific Trans-Atlantic Slave Trade Database but also reading the [About page](https://www.slavevoyages.org/about/) for the entire website. 
- Emphasize that the About page is the primary place you will often go for data projects to answer some of the above questions. 
- Finally, sometimes a Google Search can be an even more effecient way to uncover some of this information. For instance, a Google Search for ```Trans-Atlantic Slave Trade Database``` brings up [a much more digestible summary of the project](https://hutchinscenter.fas.harvard.edu/trans-atlantic-slave-trade-database).

## Tutorial: Exploring Tabular Data

Tabular data is the storage of information through a system of rows and columns. Arguably the most common format you will come across tabular data is through a spreadsheet. Although spreadsheets can come in several different file types, for today we're going to work in Google Sheets. 

**Orientation**

To get oriented to Google Sheets, watch the first **13 minutes** of the video ["How to use Google Sheets - Tutorial for Beginners"](https://www.youtube.com/watch?v=TENAbUa-R-w). This provides a nice introduction to spreadsheets and the Google Sheets interface:

.ve-media https://www.youtube.com/watch?v=TENAbUa-R-w start=103 end=771 width=70%

<br>**Exploring the Trans-Atlantic Slave Trade Dataset**

- To get more comfortable with spreadsheets, you're going to be working with a subset of the Transatlantic Slave Trade Database. You can download the entire dataset through the project website, but this can be difficult to work with given the amount of information it includes. Instead, you're going to be looking at a subset of the data to practice your spreadsheet skills.
- [Go to this Google Sheet](https://docs.google.com/spreadsheets/d/1CUrZM06ZRBajyx2gRJN1IkRfZYx7cUgl2fkteNqpvpU/edit?usp=sharing) then make a copy of the entire file in your Google account by going to `File -> Make a copy`. 
- This new Google Sheet file is what you'll use for the rest of the tutorial.

.ve-iframe https://docs.google.com/spreadsheets/d/1CUrZM06ZRBajyx2gRJN1IkRfZYx7cUgl2fkteNqpvpU/edit?usp=sharing width=80%

<br>**Sorting Spreadsheets** 

Sorting a spreadsheet allows you to "read" a spreadsheet more easily by ordering all the rows by different criteria (typically either alphabetically or numerically - ie. smallest to largest). [Instructions on how to sort a Google Sheet](https://support.google.com/docs/answer/3540681?hl=en&co=GENIE.Platform%3DDesktop#:~:text=Sort%20data%20in%20alphabetical%20or%20numerical%20order).

- Sort the spreadsheet in **descending order by the `Total embarked` column**. This is arranging the ships in your spreadsheet by the number of enslaved people a ship began with (embarked) at the start of its voyage.
    - What was the name of the ship that had the largest recorded number of captives when it began (embarked) on its voyage? ```Ocilla```
    - How many captives did that ship carry when it embarked on its voyage? ```1500 captives```
    - What country's flag did it sail under? ```U.S.A```

>Question to put some of these numbers in context: Look around. How many students are in this classroom? If each classroom in this building had roughly the same number of students, how many classes would you need to combine to equal the total number of captives that were forced onto this single ship?

- Try sorting the spreadsheet so that you can answer the following questions: What year was the  **earliest** and **latest** recorded arrival of a transatlantic slave trade voyage in this database? ```1514``` and ```1866```
- Sort the spreadhseet by `Voyage ID` so that it is back in its original order.

**Filtering Spreadsheets** 

Filtering a spreadsheet allows you to only look at a particular subset of the spreadsheet while "hiding" the rest of the rows. This can be helpful if your dataset is quite long and you want to zero in on just some of your rows.

- To create a filter, go to `Data` -> `Create a Filter`. If you look at the first row of your spreadsheet, you'll now see a filter button (upside down triangle) appear next to the name of each column.
- Click on the filter button for the column `Vessel Name`. 
- In the pop-up menu, you will see a list of all the names of ships in this database. First click `Clear` to deselect all the values, then scroll down the list of names until you see `Abigail` then click once on the name so that a checkmark appears next to it.
- This has "filtered" your data to only show you ships named `Abigail` in your spreadsheet.
- Look at the bottom right corner of Google Sheets and you should see `17 of 36,085 rows displayed` - this is telling you that 17 ships names `Abigail` in your spreadsheet.
- You can also select multiple values for your filter. Notice that the filter button for `Vessel Name` now looks like a funnel. This means it's currently filtering your data. Click once on the filter button. You should see `Abigail` still selected. Scroll down to `Abby` and click once to add that to the filter.
- If you hit OK, you'll see that this has added three aditional rows to what we can see through this filter - bringing the total up to 20.
- To reset the filter and see all of your data, click on the filter button for `Vessel Name` then click `Select all` in the pop-up menu. 
- Practice: 
    - Use the filter option for `Flag of vessel` to **only** see ships that flew the country flags: `U.S.A` or `Great Britain`. How many vessels fall under this category? `14,275`
    - Use the filter option for `Outcome of voyage for owner`. How many voyages ended in the outcome: `Original goal thwarted (natural hazard)` ? `3,157`
    
## Debrief

- Based on your exploration of the database and some of the contents of the data, what sorts of insights do you think researchers can or have arrived at by analyzing this kind of quantitative information about slavery? Essentially, what are the benefits of this data-driven approach?
- Watch the following video of an animated data visualization using the Transatlantic Slave Trade Database and consider some of the following questions:
    - What are the strengths of this visualization for studying and understanding the Transatlantic Slave Trade?
    - What are some risks or downsides of this kind of data visualization? Does it reduce human beings into nameless dots?

.ve-media https://www.youtube.com/watch?v=SKo-_Xxfywk width=60%

**Additional resources for spreadsheets:**

https://multimedia.journalism.berkeley.edu/tutorials/spreadsheets/

.ve-footer
    - [Previous: Day 2.1](/2-1/)
    - [Data 4 All icon](somelink)
    - [Next: Day 2.3](/2-3/)
