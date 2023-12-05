# F23 CMP120 Final project

*This repository contains no starter code, there is no starter code. It is a repository so it can be a template for a future move to github classrooms. Students do not need to download anything.*

## Submission

All code files, reamde.txt, and video uploaded to brightspace. 

---

## The Final Project

The final project for Python CMP120 is an open-ended data-processing assignment. The goal of this project is threefold:

1. Demonstrate an understanding and ability to work with python, python syntax, and fundamental programming language features.
1. Design, architect, and assemble a reasonably complex, multi-module project from scratch. Demonstrate an understanding of code organization principles and separation of responsibilities.
1. Research and work with an external tool/library. Read documentation, and example code intelligently. Demonstrate the ability to remix, refine, and utilize existing code/libraries/modules for your own purposes without getting trapped by it.

The Project:

- You are going to create a data analysis tool of the same scope and complexity as the data analysis project. 
  - 3 or more modules, none of which need to be particularly large, reasonably separated.
  - The project is capable of answering multiple, non-trivial, interesting questions about some data source.

- The catch is: I have no data-set for you. You will have to provide your own. I have no insights or questions for you to answer. You will have to make determinations as to what is meaningful, actually meaningful, and come to conclusions about it.
- The other catch: You ARE allowed to use numby and pandos this time. In fact, you MUST use at least one external library. 
  - This is to execute and demonstrate research techniques. Reading through example projects and library documentation is not just 'real world programming', it's also an incredibly important skill! Programmers are *expected* to stand on the shoulders of others and not waste [their companies] time re-inventing wheels. 
  - If your external library is an interface to data, then congratulations, you found your dataset and your external tool in one. This is permitted.
  - It is expected that you may have to research and learn more python features. These do not count as external tools, even if they are in separate python modules that have to be included.

## The Rubric

- Fundamentals (45%)
  - Contains the following: Variables, functions, loops, lists (and/or tuples/dictionaries), modules. Not an insignificant portion of your grade will come from the project just being a reasonably complex, correct, working, python project. It must be at least complex enough to warrant having these elements, so you can demonstrate your ability to use and understand them.
  - Are you demonstrating an ability to write original python code?
- Meaningful utilization of an external tool (10%)
  - If I removed the tool from your code base, how much would break? Are the broken things core-functionality, or are they surface-level details or niceties?
- Does it do something? (10%)
  - Interesting, non-trivial question answered?
  - Not just reporting information in the data-set, but evaluating it in some programmatic way? In other words, there's a point?

- At least 3 modules (python files) with clear and meaningful separation of responsibilities. (5%)
  - I can make an educated guess about what the file contains by the module name, and none of the code inside it will surprise me. You can have as many modules as you want.
  - One module must be main.py, and it must have a main() function that executes your program.

- At least 3 functions that process an input (parameter) into an output (return value) in a way that is useful and re-usable. (5%)
  - It isolates a single problem into the function, giving you a single place to deal with the logic that involves... whatever that function does. 
  - It does one thing, does it well, cleans up your code elsewhere, and get's out of the way.
  - The value returned is meaningful or useful. Probably useful: you changed your inputs into this output, but perhaps meaningful: reporting true/false if it was successful at ...doing whatever.

- Implement at least one "reasonably complex algorithm" (5%)
  - A 'reasonably complex algorithm' is defined as an algorithm where you show it to the professor during class workshops, and they go "yes, that is reasonably complex to meet the project requirements".
 
- Other (5%)
  - Code cleanliness, organization, well named files, consistent syntax, clear comments.
  - Nothing leftover or experimental. No large commented out blocks of zombie code. No unused code hanging out.
  - It's all easy to read and parse.
  - Demonstrations of effective programming outside of python fundamentals.

- Readme.txt (0%, points lost if not included)
  - With the project, include a readme.txt (or readme.md file, like this one) with the following information:
  - Name, class, year, project, date.
  - Brief description of the project. Simply and explicitly state what it *does* or *is* in 1-2 sentences.
  - External tool used. Link to homepage/repo.
  - Dataset used.
  - Attribution/credits if needed?
  - References (Links to tutorials followed, example code looked at, etc. This is partly for academic integrity, and partly for my own understanding of what resources students find)

- Explanation Video (15%)
  - Demonstrate your understanding of python, and your ability to communicate and think through the project concepts.
  - Run the project and demonstrate it working.
  - If you do the project, do the research, and spend the time on it, then this is likely a fairly simple and straightforward part of the project. If you are using features without really fully grokking them, (i.e., code lifted from elsewhere that you could not reproduce) then this is a much more difficult part of the project.
  - The project is not necessarily that complex, but your understanding of it should be complete.
  - This video is provides a non-code demonstration of understanding that goes along with submitted code, which is important for academic integrity purposes.
  - This is a <5 minute video recording of you explaining how the code works. Screen-share style, as with the graphical assignment, but looser time constraints.
  - This is not a line-by-line "read the code in my own words" video. **Please don't**. I'll be reading your code! Just walk through it at a high level, how your project is accomplishing whatever it is accomplishing. What algorithms/patterns do you use, why you put what code where, etc.
  - The more clearly and concisely you are able to explain how your code works - in your own words - the less concern with academic integrity there is.


## Project Ideas

"Does It have to be data processing? Could I make art work, or a game, or something interactive, or a tool?" **Yes with approval**. The goal of the final project is to demonstrate what you have learned, and putting it together. That being said, this is an introduction course in the data science program.

Start with your data-set or your external tool, then start working on your problem. Worry about complexity after, there are always features you could add. 

You are not limited to using only one external module/tool.

## External Tools

- Pandas - https://pandas.pydata.org/
  - I would consider this the 'default' for this assignment
- Various: https://github.com/vinta/awesome-python
- https://www.nltk.org/ - Natural Language Toolkit
  - a THOROUGH analysis of the bee movie script?
- Web scraping: (Requests, Scrapy, Selenium, Beautiful Soup, Pyspider, playwright)

## Data sources

- Meteostat - https://github.com/meteostat/meteostat-python
- https://data.fivethirtyeight.com/
- https://opendata.cityofnewyork.us/
- https://data.gov/
- https://pghgishub-pittsburghpa.opendata.arcgis.com/
