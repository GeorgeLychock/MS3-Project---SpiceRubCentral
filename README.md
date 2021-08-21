# George Lychock - MS3 Project: uSpice
### Salem State University Fullstack Software Developer Certificate
#### Python Module
-   [View Live Dev Site](https://www.georgelychock-career.com/pages/_sandbox/MS3/index.html)

<hr>

<h1 align="center"><img src="_documentation/look-and-feel/montage-screenshot.png" /></h1>

## Table of Contents

- [Use Case](#UC)
- [User Stories](#US)
- [Requirements](#REQS)
- [UX/UI](#UXUI)
- [Design](#DES)
    -   [Wireframes](#WF)
- [Technical Background](#TECH)
- [Testing](TESTRM.md)
- [Bugs and Fixes](#BUGS)
- [Deployment](#DPLY)
- [Credits](#CREDS)
- [Project Management](#PROJ)


<a name="UC"></a>

# Use Case

uSpice is a spice rub recipe utility to help users search, rate, build, and buy spice rubs they like.

When I buy expensive pre-made spice rubs I rarely know what all the ingredients are nor do I know what the proportions are for the rub recipe. I would like an app where I can search spice rub recipes, view details about the recipe, and rate the recipe. An added feature would be if the app could help me build my own recipes, based on base rub mixes, that I can customize by adding secondary ingredients and/or changing the base mix proportions. I also would like links to vendors that sell the ingredients to the recipes.


>
> ### Notes
>
>-   The primary focus of this project is to display Python and database skills learned in the Python Essentials Module of the Salem State University / Code Institute Full Stack Software Developer Certificate Program.

<a name="US"></a>

## User Stories

-   ### Anonymous, or Logged In, User Experience
    -   **Story 1** As a Site Visitor, I want to be able to search recipes by using a quick search method.
        -  #### *Acceptance Criteria* -- Duplicated in Testing Section
            1.  A search form is presented without leaving the home page
            2.  A minimal number of search criteria is presented to choose from
            3.  A results page is presented when the criteria is submitted
    -   **Story 2** As a Site Visitor, I want to see results of my search on a new page that offers sortable headers.
    -  #### *Acceptance Criteria* -- Duplicated in Testing below
        1.  Results are displayed in a list, with recipe title, date posted, base ingredient
        2.  The list can be sorted by active headers
        3.  A recipe has a clickable link to display the recipe details

    -   **Story 3** As a Site Visitor, I want to see recipe details displayed on a recipe detail page
        -  #### *Acceptance Criteria* -- Duplicated in Testing below
            Recipe page includes the following details:
            -   a.  Recipe Name
                b.  Author
                c.  Ingredients
                d.  Description
                e.  Instructions (commentary)

    -   **Story 4** As a Site Visitor, I want to have a similar experience whether desktop, tablet, or mobile, so that I can later access information in a similar manner if I change devices.
        -  #### *Acceptance Criteria* -- Duplicated in Testing below
            1.  All content has to be accessible from desktop, tablet, or mobile device.

-   ### Logged In Only User Experience
    -   **Story 5** As a Recruiter, I want to easily und

-   ### Administrator User Experience
    -   **Story 6** As a Site Administrator, I want to be able to regulate the number of postings for any user globally
        -  #### *Acceptance Criteria* -- Duplicated in Testing Section
            1.  A search form is


<a name="REQS"></a>
## Requirements
-   Application must be responsive and fully functional to use on any device (US4)
-   Allow users to search recipes, using a quick search (US1)
-   Allow users to search recipes, using an advanced search
-   Monitor/regulate the number of recipes a user can upload per day
-   Allow users to view details about the recipe including an image
-   Allow users to rate a recipe
-   Allow users to view top 10 rated recipes
-   Allow users to print a printable version of the recipe/pie chart


<a name="DES"></a>
## Design
<a name="WF"></a>
### Wireframes

<a name="TECH"></a>
## Technical Background
### Data Structures and Dataflow
-   Data Structure Mapping - [View](https://github.com/GeorgeLychock/MS3-Project---uSpice/blob/master/_documentation/data/Site-Data-Map.jpg)


<a name="BUGS"></a>
## Bugs / Fixes
### Known Bugs
#### OPEN 
-   Logo animation bumps banner and header containers to the right while in motion on desktop

#### FIXED
-   Library Buttons:
    -   A black box appears ....
        -   FIX: 