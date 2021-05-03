---
layout: default
---

# Intro
This page serves as a portfolio for the work done to the video game project RUIN. I will go through different phases of the project, share my contributions to the project, tell about my responsibilities within the team and my general thoughts about the project as a whole.

RUIN is a game demo, that was developed in Ticorporate course held by Jyväskylä University of Applied Sciences (JAMK) between January and May in 2021.

The game is a third-person roguelite/roguelike action game with focus on fluid and responsive combat.

# My roles
2D-graphics | VFX | Game System design | Skill Design | UI design | Project Management (SM) 
---- | ---- |  ---- | ---- | ---- | ----



# Starting point

Lets start with some honesty here, when getting into the project I did not have too much experience with roguelike games aside from Diablo and Path of Exile which are not categorized into that genre. However one of the inspirations to the game was Genshin Impact which i was familiar with, to say the very least. I had quite good understanding of what makes that game good, and I wanted to try see how we could get those things implemented in a new game project.

I was not confident in being able to contribute on technical side, so I opted into doing content production for the game. I did not know precisely what I wanted to do when joining the team, but I had a clue that I wanted to do 2D stuff because I'm able to do it. I also wanted to learn 3D modelling and the project felt like good opportunity to have "something meaningful to do with it".

Because of the pandemic, I was certain that I would not be able to get much work done as I'd like because of the remote work. Initially I did not plan to take Scrum Master as an side role, but after some consideration and encouragement from the overlord I decided to go for that role to have more responsibility within the team aside from just getting things done, as I felt like that would force me to be more involved in the process.


## Strenghts before Ticorporate
- Experience in creating 2D graphics through own projects over the years
- Testing different games and software
- Good general understanding of game systems
- Being able to work in many types of teams
- Some experience from using Unity and Blender through JAMK courses

# What I learned
For essentially every part of the project I did, there was something new to learn, was it tools or workflow or just getting things to actually work in Unity on top of being able to use Unity itself. 
## Tools
The large part of project for me was to get used to the tools that was required for content creation, I expected to do some texturing at some point but that was kind of left behind when I decided to start focusing on effects. Down below are things I learned to do with different tools during the course.
### Unity
Unity was the fundamental part for developing the game, so being able to use Unity was the most important here. Despite being on Unity course before Ticorporate, I had forgotten most of it so using the different tools within the editor was problematic in the beginning. There were plugins that I had not used before like ProBuilder, ShaderGraph and VFX Graph.
### Blender
While I did not have any real contribution to the game through from Blender aside from doing simple shapes for animating visual effects, I think i was able to get some basic competency on using the shortcuts efficiently, create simple 3D models, using lighting to create appealing screenshots, using particles when needed and understanding UV maps.  
### Photoshop
I was already familiar with Photoshop so the learning part was understanding what kind of files, formats and resolution you should use for importing to Unity and how it will handle colors and transparency. *Spoiler alert, Unity is quite compatible with with the regular image formats*
### Git
Being able to use Git properly was important for giving the technical side the least amount of headache when you push your things for merging to the sprint branch. I probably do not handle the best practices in Git quite yet, but I'm very comfortable using it through bash.
### Zenhub
With a role that could be described as a project manager of sorts, I had to have understanding of Zenhub to keep track of the progress of the project and getting data, mostly burndown charts for reporting to the organization, in this case JAMK.

## Teamwork
### Project Management
As mentioned in the "My Roles", the SM abbreviation stands for Scrum Master which meant it was my responsibility to make sure the team uses scrum practices to their fullest extent. I did the facilitating for all of the meetings held within the team during the course, this includes sprint planning, backlog grooming, retrospective, weekly meeting, daily scrum and the additional meetings we decided to take during the time and also wrote the documents related to these meetings.
### Scrum
Working in a scrum project was a first for me, however I've been working in the same space with an functioning scrum team so I had general idea about what to expect about sprints, dailies, retrospectives et cetera when the project started.



### Project

# Stages
## Pre-production
### Setting things up
The confusion was real during the first days after the project started, we decided upon using Discord as our communication platform and added channels we thought to be useful for organizing stuff. I did take the responsibility of creating tracking for calendar and work hours along with field for marking what was done during that day to help with weekly reporting. The setup regarding calendar and daily reporting was kept through the whole project without any big changes.
### Project Planning and GDD
I did most of the planning regarding scrum events in the Project Plan and confirmed the team agreed with the conventions that were written in it. We evaluated what we should be able to achieve during the project and adjusted our MVP accordingly as the game described in Game Design Document was too large.

## Production
The first couple of weeks were learning Blender for me, I did some prototype design during that time too.
### Contribution to the game
Somewhat chronological order:
- Designing required models in the maps, designing the prototype rooms with Patrik
- Designing and documenting combat, skill, status, weapon and combo systems
- The initial design and documenting of the skills to be used in the demo with help of Mikki
- Designing and implementing VFX for stance change and whirlwind skills using Blender, Photoshop, VFX-graph and Shadergraph
- Deciding the in-game UI layout and creating UI graphics
- Main menu graphics and settings layout

Not existing in current build:
- Building the prototype room for the first demo
- Onepage as an introduction to the game testers
#### Project Management
- Facilitating the scrum related meetings, weekly meetings and creating minutes/reports of the events
- Holding the daily scrums
- Clarifying the purpose of the scrum events during the meetings

## Three Highlights
### Stance Change VFX ![Image](https://cdn.discordapp.com/attachments/163749375560908800/838805451889705021/unknown.png)
I was quite happy with the shadergraph effect I managed to make for stance change, the effect is pretty simple but it took some thinking to make it work the way I intended, tons of trial and error and understanding how the values are going to work under the hood. I was able to use this shadergraph for the charging effect in whirlwind skill aswell.

**Issues**
As with most of the things I did on this project, I had no clue where to even begin. Looking through the tutorials it became clear that I wanted to use shadergraph for this effect. It was a solid struggle to understand how the values and different filters affected the outcome, transparency was also not straightforward to get as I had not realized you can use the output as the alpha channel. Initially I used deltatime for the effect but after getting the effect to the game I realized more control was needed for the effect to work properly.
### 2D-graphics
While the original intention was not to use the scroll image as the menu image, it was a nice fit and it works with various resolutions. I was happy with how that specific graphic turned out. Consideration was made to match the game vision with the way the edges are handled, there is very slight grain added to get papery texture but still keeping it toon-like. 
### Communication
I feel like my ability to talk out my thoughts and overall ability to speak understandable has improved considerably during this course. I've learned to explain my ideas more properly so team can understand what I'm trying to talk about.

## Post production
For post production our work is not really done, we just stopped adding new features to the game. There will be a handful of bugfixing and final implementations before we go bankrupt. 

### Reflection

**What should I have done differently?**
Often I would try to figure out the issues I have by my own before raising it up as a problem with the team. I should have asked for help way more often as the solutions were usually fairly simple and was really down to inexperience with software and whatnot.

I should have done better job keeping structure in the meetings and explain more comprehensively what we are doing right now, this could have been achieved by using more visuals during the meetings as they were mostly verbal.

I should have done more 3D related stuff as that was part of my goals for the course, however I also wanted to be able to contribute to the project which is the main reason it was left out. 

**Overall feelings**
Out of the remote work courses this has been the most successful for me, the structure that project planning and scrum process kind of "forced" on us helped me tremendously for time management. I felt like I learned alot about working as a team during this course.




---
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/multtari-student/portfolio.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
