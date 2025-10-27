<link rel="stylesheet" href="bbc-style.css">

<div class="bbc-title" markdown='1'>

# Black Belt Club Project

<div class="bbc-meta" markdown='1'>

By: David Crowley \|

For: Hanshi John Leroux \|

Ottawa School of Karate-do

</div>

<div class="bbc-menu">

<a href="/pages/bbc/landing">BBC Project Home</a>
<a href="/pages/bbc/values">Values</a>
<a href="/pages/bbc/karate">Karate Goals</a>
<a href="/pages/bbc/personal">Personal Goals</a>
<a class="active" href="/pages/bbc/tracking">Dashboards</a>

</div>

</div>

<h2 id="bbc-values">Updated Tracking for Each Goal</h2>

<div class="tile-box">

<div class="bbc-content" markdown=1>

<div class='code-compare'>
<div markdown='1'>

### Karate Goals Summary (3 mo.)

> Updated 2025-10-26

Flexibility
: no measurable progress was made. In particular, very little training to meet this goal was performed as planned. Only routine stretching to maintain the current mobility was performed.

Strength (stability)
: while very little specific training was performed outside the dojo, cues from the workouts (pushing feet into ground) as well as from class (focus forward, foot/knee positioning on kokutsu dachi) were applied internally on almost all reps. I feel like oi tsuki in zenkutsu dachi has become more stable and my back stance has also improved, at least technically.

Skill
: considerable effort was put into both ukemi and throws during extra mat time. I am satisfied with the progress of the back rolls and enjoyed the secondary benefits of core development from repeating the ukemi kata. Mechanics of the throw, especially tilting from the hip with knees bent before "lifting" (extending knees), still need work.

Overall:
- some progress was made despite significantly less training than expected, but most goals were not met outside of ukemi
- the areas that received the most training improved the most
- in order to stay on track for the one-year goal, training effort outside the dojo needs to be put into proper stance mechanics and strength.

</div> {% comment %}Fin côté droit{% endcomment %}
<div markdown='1'>

### Personal Goal Summary (3 mo.)

> Updated 2025-10-26

Significant progress was made during the summer, and while the July 
time-on-task was short, I was able to make up for it in August. Nevertheless, this project is still a work in progress, so the goal of availability on the first day of school was definitely not met.

The main issue is that despite the large gains documented, a lot of the progress needed to be reverted because it was either not correctly modularised (through both poor design and poor use of existing design by Copilot, the AI assistant) or not correctly reused (new website material not ported but rewritten based on the Copilot's understanding of the headers 😮‍💨).

This caused several weeks of revisions; drafting and testing of instructions files; manually correcting and rebuilding the program's architecture; and slow, deliberate use of the various prompts created to restart development on the remaining task items.

A coop student has joined the project but is spending most of their time learning some of the coding and tooling basics. They should be a great asset in a few weeks. Their joining has lead to the reorganisation of the project documentation into more standard team materials on the GitHub platform : Issues, Milestones, Projects, Branch Rules, Pull Requests and Reviews. This porting has taken time but has also allowed for some useful input from the automated code reviews by Copilot.

In all, remaining time on known Issues is estimated at well over the initial total time expected for the project, not including fixing the website materials based on the preexisting ones. **Total project time should be about 5x the initial estimate!**

That's the danger of projects that require learning significant amounts of new tools. In this case : pair programming with an AI Agent, larger python project architecture, efficient SQL database structure, Google Drive API's and authentication, efficient and secure distribution of configuration data.

<details>
<summary>Original task list</summary>
<div markdown='1'>

> Updated 2025-10-26

- [x] plan course content items for all 4 programming courses in the first semester
- [x] devise modular, regular-interval assessment system that includes interviews and allows for retakes
  - [x] Set-up student local datastructure (SQLlite and JSON)
  - [x] Test connections to Google API
  - [ ] Create student Sheets copies from contract template based on course
  - [x] Create script to traverse student copies and produce quizzes based on newly completed and need-to-retake items
- [ ] prepare all assessment items (questions) for all 4 programming courses
  - [x] prepare prototype data structure (JSON)
  - [x] confirm understanding of all items with AI assistant
  - [ ] generate all items
  - [ ] review and test all items (test quiz including all items from all sections in both languages)
- [ ] prepare interview sheets for all content items
  - [x] identify items for group interview versus individual interview
  - [x] generate questions (3 types)
  - [ ] generate student copies for all interviews based on course
  - [ ] create script for scheduling interviews based on item status 
- [x] plan course project sequences for all 4 courses, including senior/junior interactions where appropriate
  - [x] 3U
  - [x] 4U
  - [x] 3C
  - [x] 4C
- [x] write project descriptions and rubrics for all 4 courses
  - [x] 3U
  - [x] 4U
  - [x] 3C
  - [x] 4C
- [x] update online course materials to be divided into lessons coherent with the content items/modules used for the assessments
  - [x] decompose existing course materials based on new item list
  - [x] identify items with little or no existing material and generate fresh material for them
  - [ ] for items with existing material, aggregate material from existing files
  - [ ] clean-up and simplify each item's lessons
- [ ] generate sample projects in both python and Java
  - [ ] text-based game
  - [ ] text-based game with locally saved state (high scores)
  - [ ] gui-based game with mouse and locally saved state (level, high score)
  - [ ] cli to find files in a given subfolder
  - [ ] note-taking app (persistent data)
  - [ ] media viewer using strategy pattern for different types of media, as necessary

Bonus tasks

- [ ] start the above preparations for next semester's 2 robotics courses

</div>
</details>

</div> {% comment %}Fin côté gauche{% endcomment %}
</div> {% comment %}Fin code-compare{% endcomment %}

</div> {% comment %}Fin bbc-content{% endcomment %}

</div> {% comment %}Fin tile-box{% endcomment %}