# EduMap

## To use

```sh
git clone https://github.com/andyras/edumap.git
cd edumap/edumap
gem install bundler
bundle install
rake db:create
rake db:migrate
rake db:seed
rails s
```

And visit <http://localhost:3000/>

## Curricula

### Desiderata for each curriculum
In general curricula are broken up into lessons; that is the quantum of curriculum we are working with.

#### Essentials
- Code for each lesson
  - string with no whitespace, e.g. `Code.org1.1`
- Age (or grade) range for each lesson
  - string, e.g. `"Ages 8-10"`, `"Grade 4"`
- Short description for each lesson
  - string, e.g. `"Happy Maps"`
- Time for lesson
  - string, e.g. `"1 class period"`, `"45 minutes"`
  - If you have to guess, add `"est."` before the time, e.g. `"est. 1 class period"`
- Platform/OS or materials
  - string, e.g. `"Web"`, `"iOS, Android"`,  `"pencil, paper, SPAM"`
- Plugged vs. Unplugged
  - string, either `"Plugged"` or `"Unplugged"`

#### Nice-to-haves
- Topic area
  - string, e.g. `"Loops"`, `"Internet security"`

### List and status
- [CS Unplugged](csunplugged.org)
  - scraped: age, lesson names
- [Google Computational Thinking](https://www.google.com/edu/resources/programs/exploring-computational-thinking/index.html#!ct-materials)
- [ScratchEd Creative Computing](http://scratched.gse.harvard.edu/guide/download.html)
- [Code.org](https://studio.code.org)
  - standards
  - (lesson plans require login or direct link)
- [Computational Thinking (Northwestern)](http://ct-stem.northwestern.edu/lesson-plans/)
- [CS First](http://www.cs-first.com/)
- Find more resources here...  http://cs4hs.com/resources/cscs-results.html#q=

## Standards so far
### [International Standards](https://docs.google.com/spreadsheets/d/1SE7hGK5CkOlAf6oEnqk0DPr8OOSdyGZmRnROhr0XHys/edit#gid=218360034)
- [CSTA](http://csta.acm.org/Curriculum/sub/CurrFiles/CSTA_K-12_CSS.pdf)
- [ISTE](http://www.iste.org/standards/iste-standards/standards-for-students)
- [NGSS](http://www.nextgenscience.org/search-performance-expectations)
- [Common Core ELA](http://www.corestandards.org/wp-content/uploads/ELA_Standards1.pdf)
- [Common Core ELA](http://www.corestandards.org/ELA-Literacy/)
- [Common Core Math](http://www.corestandards.org/wp-content/uploads/Math_Standards1.pdf)
- [Common Core Math](http://www.corestandards.org/Math/)
- [Common Core csv. file producer](http://www.ode.state.or.us/teachlearn/real/standards/)
