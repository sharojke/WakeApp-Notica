<a name="readme-top"></a>




<br />
<div align="center">
  <img title="App Icon" src="/Resources/Images/WakeApp-Notica.JPG" alt="Logo" height="200">
  
  <h3 align="center">Notica</h3>
  
  <p align="center">
    <em>
      An application for creating daily notes
    </em>
  </p>
</div>




<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#company">Company</a></li>
        <li><a href="#team-composition">Team Composition</a></li>
        <li><a href="#life-span">Life Span</a></li>
      </ul>
    </li>
    <li>
      <a href="#my-participation">My Participation</a>
      <ul>
        <li><a href="#responsibilities">Responsibilities</a></li>
        <li><a href="#skills-and-technologies">Skills and Technologies</a></li>
      </ul>
    </li>
    <li>
      <a href="#functionality">Functionality</a>
      <ul>
        <li><a href="#viewing-a-note">Viewing a Note</a></li>
          <ul>
            <li><a href="#tag-and-background">Tag and Background</a></li>
            <li><a href="#bulleted-list">Bulleted List</a></li>
          </ul>
        <li><a href="#recently-deleted">Recently Deleted</a></li>   
      </ul>
    </li>
  </ol>
</details>




## About The Project


### Company

[WakeApp](https://www.wakeapp.com/) is a technological advanced mobile marketing agency, leader in the promotion of mobile applications on the international market.  
Until March 2022, this company had a department for the development of iOS applications; unfortunately, the department was closed, employees were fired.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Team Composition

- 1 **Product** manager
- 1 **Project** manager
- 1 **UI/UX** Designer
- 1-2 **QA** Engineers
- 2-3 **iOS** Developers

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Life Span

*December 2020 - February 2021*  
The development of the application began in mid-December 2020 and was fully completed at the end of February 2021.  
At the end of 2021, the app was removed from the App Store.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




## My Participation


It was my first commercial project that I developed in a team with other people. 


### Responsibilities

First of all, I had to fully immerse myself in the working atmosphere, as well as study the code style, company libraries and technologies.  
I was in a team with my mentor and worked on the project from January to February 2021, after that the work on the project was completed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Skills and Technologies

- Swift
- MVC
- UIKit, NSAttributedString, create the UI programmatically
- Realm, localise.biz, Amplitude
- Git+Sourcetree, Jira, Figma

<p align="right">(<a href="#readme-top">back to top</a>)</p>




## Functionality


The main functionality is displayed below. Of course, in addition to this, many small tasks were completed and many bugs were fixed.  
***All the functionality written below was implemented by me or with my active participation.***


### Viewing a Note

<img title="Note" src="/Resources/Images/note.png" width="200"/>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Tag and Background

Adding a tag and changing the color gave the note uniqueness.  
The views that appeared for selection were written programmatically, which gave some complexity.

<img title="Edit 0" src="/Resources/GIF/edit-0.gif" width="200"/>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Bulleted List

A lot of work has been done with NSAttributedString and NSRange. In this case, the bullet was a regular utf-symbol.  
Another problem was saving the note in the form in which the user made it. Fortunately, we can save NSAttributedString to Realm and the problem is gone.

<img title="Edit 1" src="/Resources/GIF/edit-1.gif" width="200"/>

Logic was also written to add new types of bullets. Unfortunately, the work on the project was completed without adding new types.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Recently Deleted

Each deleted note was moved to "Recently Deleted".  
There the user could permanently delete the note or restore it. 30 days after the deletion, the notes were deleted themselves.

<img title="Deleted" src="/Resources/GIF/deleted.gif" width="200"/>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<br />
