# README Notes

This document explains the purpose and contents of project & personal README documents to be included on GitHub project repos and profile.

## Contents
[Introduction ](#introduction) | 
[What's in a README ](#what-is-in-a-readme)| 
[Typical Structures ](#typical-structures)|
[Markdown ](#markdown)|
[Helpful Elements ](#helpful-elements)
[Location ](#location)|
[How to approach ](#how-to-approach)|
[What and How much to write ](#what-and-how-much-to-write)|
[Tips & Tricks ](#tips-tricks)|
[Personal READMEs ](#personal-readmes)|
[Examples ](#examples)|
[Links ](#links)|

## Introduction
A README file communicates important information about you or a project and is often the first item a visitor will see when visiting your profile or repository. 

It is important to give thought to its structure, content, and length to showcase what project is about, both project and personal READMEs demonstrate your professionalism and dedication to your audience.

Who is going to read it? Both you and others. Consider yourself as a different person months from now, you have forgotten some/most/all of the codebase but need to revisit a project - the README can help refresh your memory. Other people might be interested in the project or YOU; they may want to work with you or hire you. Knowing who will read this should help set the tone for an appropriate standard of README deliverable.

## What is in a README?
In a project repo, it typically includes information on:

- What the project does
- Why the project is useful
- How users can get started with the project
- How users can test the project
- Where users can get help with your project
- Who maintains and contributes to the project

During acquiring and building of skills in a developer's/ engineer's initial projects, it may be useful to include information to support/ showcase their learning:
- Challenges
- Key wins
- Brief and timescale
- Was it solo or collab
- Technologies used
- Development methods
- Future improvements

READMEs can also communicate expectations and help manage contributions along side files/ info like:
- Licence
- Citation file
- Contribution guidelines
- Code of conduct

## Typical Structures

The structure should depend on the project, that said they may contain certain headings. The below can be deleted or expanded on as required.

### Headings and Sub-headings
- Friendly title from project name
- Logo
- Description - try to keep to 1 sentance
- Contents
- Overview
- Infographic / How it works
- "Try here" (if deployed somewhere)
- Background
- Re-creation
    - Prerequisites
    - Links to other parts (if in seperate repos)
    - Deployment Link
    - Installation Instructions
    - Seeding Instructions if with .db
- Testing
- Brief
    - Functional Requirements
    - Non-Functional Requirements
    - Deliverables
    - Timescale
- Technologies Used. *could list by:*
    - Operating Systems
    - Languages / Formats / Packaging
    - Specific Technologies
    - Code Editors
    - Misc
    - Project Management / Version Control
- Development Lifecycle
  - Response to brief
  - Planning
  - General approach, project management, agile, sprints
  - Build/ Code Process
  - Debugging/ testing
- Result
    - Demo of componants
    - Finished code
- Wins
- Challenges / Blockers
- Bugs
- Future Content & Improvements
- Key Learnings
- Supporting Info
- Contribution Guidelines
- Licence Information
- Community and Support
- FAQ Section
- Acknowledgments
- Project Status

## Markdown
Markdown is a simple, versatile, and lightweight markup language with plain-text formatting syntax. .md files can include headers, lists, links, and formatted text, making them readable both as plain text and when rendered on platforms like GitHub. Please note, there may be other formats preffered for different languages, such as Python using reStructuredText (.rst) to be PyPi compatible.

Refer to my notes on markdown [HERE](#https://github.com/nedd-ludd/reference-github/blob/main/markdown/markdowns.md)

## Helpful Elements
- Friendly title from the directory name.

- Images, Screenshots, GIFs: Visuals are sometimes crucial for communication. Images and screenshots can provide a quick understanding of the project's UI or functionality, while GIFs can effectively demonstrate features or workflows without requiring a live demo. These can be stored in an assets folder in the root of the project directory. [Link to .gif creators (bottom)](https://github.com/matiassingers/awesome-readme)

- Code Snippets: Including sample code can help users quickly understand how to use your project or demonstrate key functionalities. It's also useful for highlighting best practices or specific ways to implement features.

## Location

If you put your README file in your repository's hidden .github, root, or docs directory, GitHub will recognize and automatically surface your README to repository visitors.

If a repository contains more than one README file, then the file shown is chosen from locations in the following order: the .github directory, then the repository's root directory, and finally the docs directory.


## How to approach
- Copy outstanding examples.
- As coding progresses, if keeping notes as the project lifecycle develops, this can contain vital information for the readme later.
- Start with rough ideas, one word points, notes and bullet points.
- Can use commenting which does not show in "preview mode" of .md:
![alt text](./assets/commenting.png)
- Color things if needed for example - 
<span style="color:red">TODO - Formatting</span>
is acheived with:
```
<span style="color:red">TODO - Formatting</span>
```
- Remember to commit changes & push as required just like with codebase.

## What and How much to write
The reader will likely be technically minded in the same field. Unless writing to document your learning, assume reader is competant in the relevant languages. That means keeping things high level, and use technical language as required. Ultimately the amount of detail depends on nature of project; see examples below.

### Collapse or Link

If something can be summarised and then linked to a seperate document do this. External and relative links can be added. Use the markdown syntax:
```
[This Appears](http://this_is_the_link.to/where?)
```
Links may be hard to manage with project changes however so the collapse syntax could be a useful tool to hide detail:


```
<details>
  <summary>Click for details</summary>
  
  ### Heading
  1. Detail point 1
  2. Detail point 2
     * sub 1
     * sub 2

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>

 Collapsed detail in action:
  
<details>
  <summary>Click for details</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>


### Wikis
_"A README should contain only the necessary information for developers to get started using and contributing to your project. Longer documentation is best suited for wikis"_ GitHub Docs

Find out about Wikis [HERE](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis)

## Tips Tricks

- Consider putting contact information first and saying you welcome questions and invite criticism. We are a community; communication and continual improvement are both vital.
- Consider READMEs as live documents, keep building, reviewing, and editing.
- Write in clear concise language.
- If there is any information that is salient, unusual or interesting, put this first to save time when reading.
- Consider tldr information at the top.
- Spell-check and get a peer to proof read.


## Personal READMEs
Here are some examples of my READMEs:

- [Whanpia](#https://github.com/nedd-ludd/whanpia-alerts/blob/main/README.md)
- [Calibre Library Hardcopies](#https://github.com/nedd-ludd/whanpia-alerts/blob/main/README.md)



## EXAMPLES
Here are below links to READMEs that I consider good/exemplar for different reasons:

### Student READMEs
- [ainokyto](#https://github.com/ainokyto/)
- [purvitrivedi](#https://github.com/purvitrivedi)
- [andy8radshaw](#https://github.com/andy8radshaw)

### Some GA SEI68 students (my cohort)
- [Linh Vu](https://github.com/linh-vup)
- [Wyndham Roy](https://github.com/wyndhams)
- [Ulas Temel](https://github.com/ulas312)
- [Jet Haze](https://github.com/CodebyJet)

### Professional
- See Matiassingers awesome READMEs list below.

## Tools
- [Tools (halfway down)](https://github.com/matiassingers/awesome-readme)

## Links

- [GitHub Docs | Repositories | About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
- [GitHub Docs | Profiles | Your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [My Markdown notes](../markdown/markdowns.md)
- [Matiassingers awesome READMEs](https://github.com/matiassingers/awesome-readme)
- [SEI68 template](./sei-template.odt)
- [freecodecamp article](#https://www.freecodecamp.org/news/how-to-write-a-good-readme-file)
- [bulldogjob article](#https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)