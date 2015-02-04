# Douglas Crockford Better parts revisited
- A lot of talk about language design
- ES6 is the future
- this is insecure
- How will we recognize the next best language when it arrives
  - it takes one generation to add or remove every feature from common practice (or add it)
  - examples: goto, objects
  - reason: we retire or die before we get consensus

- Systems languages
  - we are still stuck with C

- Application Languages
  - Java (can't decide which it is)
  - Mostly OO languages
  - prototypal vs classical
    - js is prototypal
      - elminates need to refactor
      - me no understand
    - prototypal inheritance
      - great memory benefit in object.create instead of object.copy was initial reason for this
      - now we have a cost of Own vs inherited
   - class free object oriented programming is JS's gift to humanity
    - closures


# Traitify
- Simple personality quiz (pictures plus words 5 mins)
- gives you an archetype (I'm a lone wolf intellectual)
- people to people to things instead of people to things
- developer.traitify.com


#Web components

- Silo ability
- Native
- Reduces number of Dom nodes == performance

- shadow Dom = Dom within a Dom - this is what makes components awesome
- scopes the css within the component (still can explicitly target both ways)

- templates are key to not writing hundreds of lines of boilerplate

- shadow Dom not new used for sliders and other elements in the past


# NO MORE (front end css) TOOLS!
we hate tools, so here's a list of tools???
- Image optimization
  - svgomg jake archibald
- Remove code bload
  - uncss
  - helium-css
  - 'query dom for selectors and clean up stylesheets for stuff that doesn't need to exist'
- Performance
  - zeman/perfmap
  - adyedinboarough/stress-css
- Debuggin layouts
  - pesticide.io

Forget gulp and grunt just use npm and package.json
  -  The era of gulp and grunt is soon to end bwhahah
  - bit.ly/leveldb-example
  - bit.ly/npm-task-automation

Grunt gulp blah blah

Make
  - bit.ly/building-static

Shouldn't require everyone to run build locally... uh oh...

These tools fail at making people feel empowered to make their own changes. Tools turn into a barrier for entry.

Its easier to build overcomplicated solutions than to maintain them


# Sarah Love and Node 

- Relatability in motion
  - smiley bot gets help from people
  - got admonished for behavior

- How to give your robot a soul
  - give it a face
  - imply a sense of agency`
  - social behavior, teaching objects to remember you
  - variability better than predictability == personality

- Arduino
  - Node via Johnny5
- Tessel
  - Straight node
