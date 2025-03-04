# mindprism / The Mind Prism

This repository defines a content organization method called the "Mind Prism" developed by Jean-Michel Tremblay, 2024-2025. 

## Abstract

The Mind Prism method is a tool-agnostic method for organizing all artifacts (documents, notes, emails, channels, images, printed documents) collected in all spheres of one’s busy life (work, family, personal, etc) in order to gain and maintain a sense of control and efficiency in an otherwise messy and complex everyday life. It does not provide a complete methodology for achieving one's goals, expanding one's knowledge, or managing one's time as other frameworks do (eg. [GTD](https://gettingthingsdone.com/), [Second Brain](https://www.buildingasecondbrain.com/]), [Mind Boxing](https://www.thegoodboss.com/p/mind-boxing-how-leaders-should-spend-2b5)), although it may overlap and/or be compatible with some of them. 

## Introduction

Our lives expose us to overwhelming amounts of information and content that we receive, collect, or produce ourselves in a multitude of contexts, for different purposes, spread across various media and tools, over varying and overlapping periods of time. This may include bills, receipts, statements, articles, manuals, memos, tax reports, notes, Slack channels, photos, etc.  A portion of this content we forget even exists and wouldn’t even recognize if we saw it again. The rest occupies a portion of our mind under various forms, from crisp internalized knowledge to faint, buried memories resurfacing as a déjà vu feeling when exposed to the same content again. All of this is what I call the **mind space**.

### Goal

The goal of the Mind Prism method is to provide a practical and sustainable method of organizing everyday artifacts in order to build and maintain an organized mind space. I believe this is a step towards gaining efficiency and reducing the stress of information overload by giving a sense of control (but I make no scientific claim about it).

### Guiding Principles

To be practical, the Mind Prism method aims to be simple and usable without the need for specialized tools or the need to gather all content in the same tool. 

To be sustainable and usable over decades, it aims to adapt to an expanding mind space and an evolving life, including changes in tooling. 

### Disclaimer  

This method was developed empirically and makes no scientific claims. 

## The Method

### Core concepts

Instead of using different methods at home and at work for example, the Mind Prism method defines these **spheres** of our lives as one dimension of a universal 3-dimensional system where the other 2 dimensions are called **purpose** and **mode** and defined the same way.   Defining the same purposes and modes consistently for all spheres makes it easier to context-switch between spheres. 

The categorization model can therefore be seen as a kind of **prism** that can be sliced and diced along 3 dimensions, down to individual cubic **cells**, where each slice and cell provides meaningful context. 

```
                        e    MIND PRISM 
                       s     _ _ _    _                            / 
                      o    /_/_/_/\ /_/\                          |  documents
     __              p    /_/_/_/\ /_/\/\                         |  
   ((  )            r    /_/_/_/\ /_/\/\/\                        |  emails
  ((    ))         u    /_/_/_/\ /_/\/\/\/\                       |
 (( MIND )) ---\  p    /_/_/_/\ /_/\/\/\/\/\   ---\  ORGANIZED   /   notes
(( SPACE )) ---/       \_\_\_\/ \_\/\/\/\/\/   ---/  MIND SPACE  \  
 ((     ))              \_\_\_\/ \_\/\/\/\/                       |  channels
   ( _ ))          m     \_\_\_\/ \_\/\/\/                        | 
                    o     \_\_\_\/ \_\/\/                         |  diagrams
                     d     \_\_\_\/ \_\/                          |  
                       e                                           \  ...
                            s p h e r e
```

In practice, the same virtual prism is used to project an arbitrary mind space in a consistent way onto any set of constrained storage systems whether they offer a flat or hierarchical structure, such as folders, tags, groups, or sections.  So even if one has to use multiple tools, which is usually inevitable, the consistency of organization across the tools makes them seem more tightly connected and harmonized.

#### First dimension: Sphere

The spheres are a small number of contexts that are mostly independent from each other and usually involve a different circle of people, such as work and family. If a sphere is small enough (eg. a temporary job), it may just start as a set of topics within another sphere.   Each sphere is represented by a letter of your choice, such as the first letter of a person's name or company name. It can also be chosen to obtain a certain alphabetical ordering (eg. a-person1 < b-person2 < f-family < x-job1 < y-job2).


#### Second dimension: Mode

The **mode** represents the mode of thinking in which the content is expected to be consumed. Modes are denoted by a multiple of 10. Five “modes” are currently defined: 

| Code | Shorthand | Mode    | Description |
| ---- | --------- | ------- | ----------- |
| 00   | -         |         | _wildcard_ |
| 10   | urg       | urgent  | short-term resolution, high visibility, quick access |
| 20   | str       | strategic | longer term or broader planning  |
|	30   | prj       | project-based | something actively being worked on, hobby |
|	40   |           |         | _for future use_ |
|	50   | ops       | operational | never-ending project, recurring tasks |
|	60   |           |         | _for future use_ |
|	70   | ref       | for reference | potentially or occasionally useful, “FYI”
|	80   |           |         | _for future use_ |
|	90   |           |         | _for future use_ |

#### Third dimension: Purpose

The **purpose** represents the primary category of reasons one may want to keep a given artifact for. Purposes are denoted by a single-digit numerical code. Five purposes are currently defined:

| Code | Shorthand | Purpose   | Description |
| ---- | --------- | --------- | ----------- |
|	0    | -         |           | _wildcard_ |
|	1    |           |           | _for future use_ |
|	2    | fin       | financial | money, budget, taxes, expense tracking |
|	3    |           |           | _for future use_ |
|	4    | hum       | human     | education, health, hiring, performance reviews, relationships, self-development |
|	5    | cmp       | compliance | compliance to laws, rules, policies, processes |
|	6    | mat       | material  | objects, products, possessions, environment |
|	7    |           |           | _for future use_ |
|	8    | fun       | fun       | leisure, entertainment |
|	9    |           |           | _for future use_ |

#### Cell code

Each sphere can therefore be seen as a slice of a 3D prism built with small cubes called cells. Each cell is identified by a cell code consisting of a letter identifying the sphere followed by the number obtained by adding the two numerical codes for mode and purpose, eg. “f32” is a cell for projects (30) of financial nature (2) in the family (f) sphere.  The cell may contain artifacts or groups of artifacts under a **topic**.

| sphere "s" | 2-fin      | 4-hum      | 5-cmp      | 6-mat      | 8-fun      |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| **10-urg** | `s12`      | `s14`      | `s15`      | `s16`      | `s18`      |
| **20-str** | `s22`      | `s24`      | `s25`      | `s26`      | `s28`      |
| **30-prj** | `s32`      | `s34`      | `s35`      | `s36`      | `s38`      |
| **50-ops** | `s52`      | `s54`      | `s55`      | `s56`      | `s58`      |
| **70-ref** | `s72`      | `s74`      | `s75`      | `s76`      | `s78`      |

### How to use

How to use the cell codes is flexible and depends on the tool and context. For example, one can start with a rather flat list like so:

- p00-triage/
- p22-budget/
- p38-trip-to-asia/
- p52-taxes/

Or create a deeper hierarchy like so: 

- f00-family/
  - f20-strategic/
    - f22-fin/
      - f22-budget.xls
  - f50-operational/
    - f52-fin/
      - f52-monthly-statements
      - f52-taxes/
        - ... 

For convenience, one can choose to bring references (70) into a project (30) like this:

- p30-projects/
  - p38-trip-to-asia/
    - p38-todo-list/
    - p78-asia-articles/

Or put a project to maintenance mode by changing its code from project-based (30) to operational (50).

See more examples in the `examples` folder.

### Advanced Concepts / Extensions

#### Archiving (+900)

To reduce clutter caused by accumulating content over time, certain inactive topics may be “archived” by adding 900 to the numerical part of their code, eg. f36-project-x becomes f936-project-x. If f36 is a folder, f936-project-x can remain in that folder or optionally be moved to a f900 archive folder. It can easily be unarchived later by subtracting 900.

#### Colors, Symbols, Pictographs, Emojis

The Mind Prism does not rely on colors, symbols, and emojis as they are not as universally available and convenient to use as letters and numbers are. But in systems supporting color-coding (eg. MacOS tags), it can somewhat enhance the experience to map purposes to colors as long as it remains consistent across systems as much as possible. This is the recommended mapping:

| Purpose | Color    | Emoji | Symbol |
| ------- | -------- | :---: | :----: |
| 2-fin   | 🟩 green  | 💰    | $ |
|	4-hum   | 🟨 yellow | 👥    | ☺︎ |
|	5-cmp   | 🟫 brown or grey | ⚖️ | ⚖︎ | 
|	6-mat   | 🟦 blue   | 🧱    | ⚛︎ |
|	8-fun   | 🟪 purple | 🎬    | ♫ |

| Mode  | Emoji | Symbol |
| ----- | :---: | :----: |
| 1-urg | 🚨    | ! |
| 2-str | 🧠    | 𝟁 |
| 3-prj | 🎯    | ⚑ |
| 5-ops | ⚙️    | ⚙︎ |
| 7-ref | 📚    | ※ |

I reserve red 🟥 and orange 🟧 as tags or annotations representing two levels of follow up. 

#### Customization

The modes and purposes defined above can theoretically be customized or extended. But there are caveats to keep in mind:

-	Choosing different definitions for different spheres would multiply the categories to remember.  It would be confusing if w32 and f32 meant widely different things.
-	It is not easy to change the meaning of codes after using them for a while. 
-	If this ever became a standard (I doubt so), using different definitions would be confusing.

## Properties

### Applicability & Tool Compatibility

The Mind Prism system works well with a variety of content systems. Cell codes work in most tools as they require no special character or punctuation and no custom ordering. They are also very short and not too obstrusive in a compact mobile view. They are unlikely to clash with other meanings although it may happen (eg. a road number). 

Examples of usage: 

-	files and folders (MacOS, Windows, Linux, Google Drive, One Drive, etc.)
-	sections of a notebook
-	email tags or folders (GMail, Outlook, etc.)
-	notes organization (Evernote, Apple Notes, Notion, Obsidian, etc.)
-	sidebar sections in Slack 

### Natural Ordering 

When using cell codes as prefix for container names (eg. folders, files, sections, tags), alphabetical ordering gives a natural ordering by sphere, mode, and purpose in which more urgent or important topics tend to appear near the top of the list. It is useful to keep the distractions away when scanning a list of Slack channels or folders. Alphabetical ordering is the most common and the default in most tools.

### Granularity 

Using 5 modes and 5 purposes allows to obtain a granularity of 25 cells for 10 items to remember. Having more modes or purposes would be harder to remember. Having fewer would yield fewer cells containing more diverse content which could necessitate a cell-level organization system.   

### Searchability

When used as prefix, the cell code carries a meaning that gives useful context in search results for documents with clashing names such as documents concerning different family members on a shared drive. 

### Language Agnosticism

The code system is not English-specific. Labels are optional and can be translated as needed. Different languages can be used for different spheres without problem. For example, one can work mostly in English and organize their personal life mostly in French using the same coding system. 

### Extensibility and Futureproofing

The coding system can accommodate 9x9 matrices at the cost of having to remember up to 18 modes and purposes instead of 10. Modes 4,6,8,9 and purposes 1,3,7,9 are reserved for such future definition. 

The coding system could also be extended by assigning a meaning to adding multiples of 100 (up to 800) to the code as we do for archiving (+900). 
Finer categorization within a cell can be achieved by adding a numerical or alphabetical suffix, such as f32.4 or f54b. But this can become quite cryptic. 

## Examples

See the `examples` folder.

----

(c) 2025 Jean-Michel Tremblay
