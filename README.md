# Overview
This portfolio was created in preparation for my 2019 internship applications. It utiizes `HTML5`, `CSS3`, and `Javascript` to create a smooth and simple user experience. This portfolio highlights Projects, About Me (Resume + Photo), and Connect sections.

# Process

I knew I wanted a simple website that leaves little room for confusion. As application deadlines approached, I had little time, but wanted to create a sufficient website that properly communicates my personality (<1 week). The first step in this process was creating a simple mockup design in Adobe Illustrator that would give me direction before diving into coding.

### Mockup:

![Portfolio Mockup Image](https://i.imgur.com/kE86gXZ.png?1)

At the most I allowed for three sections, each of a dramatically different color to add guidance to the eyes of the user. I was purposeful in the color choices, with each emphasizing a positive and radiant emotion (**purple:** uniqueness   **red:** excitement   **yellow:** optimism). All possible options are displayed to the user, and each section is clearly labeled to show value.

### Coding:

I started with a HTML shell, then used CSS flexbox to evenly set sections without much legwork. Next I used CSS keyframes to create small animations to add life to a flat design. Certain Javascript elements were implemented when CSS could not finish the job. One example of this is the light animation of the section when the mouse is moved off of it. Since CSS cannot detect mouseout(), a Javascript function was necessary. 

The next task was to create an effect that fires once a section is clicked. I did not want to have a page reload, as I was following my minimalistic theme. Instead, I used Javascript to expand the section and inject elements inside of the div. I decided to have my site act as a hub that would link to all external pieces, therefore the elements inside of the section divs were strictly images with label overlays.

Responsiveness and scalability was an important aspect of this project, and while I wanted to ensure cross-platform usability, I wanted to get this done in the least amount of code possible. Setting up my images to stack vertically and scale accordingly was all I needed to get that responsiveness, leading to a very small media query code section (which is preferable). The only components that needed scaling were the section labels and my name, and that was mostly taken care of through size relation.

### Mobile Outcome:

![Mobile Outcome Image](https://i.imgur.com/7WOJnPNm.png)

### Desktop Outcome:

![Desktop Outcome Image](https://i.imgur.com/mk9MTBe.png?1)

# Conclusion:

The goal of this design was to showcase my use of Javascript and CSS3 to create a modern, simple design that displays my work in a fun and straightforward way.
