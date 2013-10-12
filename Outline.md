## Have following assets/links ready to go
- 8bit.levels.js
- Run Puma Run game
- Blaster Game
- Black Label background/Paper js


#HTML 5 Games
### With JavaScript and Canvas

## Outline!
- Intro (1 min)
- Some examples (3 min)
- Intro to Canvas (5 min)
- Object Oriented JS and the prototype chain (10 min)
- Libraries (3 min)
- Questions (5 min)

## Intro
- Hi, my name is...
	* photo or two
	* twitter link
- I am a front-end dev @viget
	* Photo
- Some fun things I've done this year
	- Paint Drop (RWD)
	- nav_lynx (Ruby)
	- Cell?
	- Clever World?
	- Run Puma Run (Canvas games!)

## Run Puma Run
	- Load up the game
	- Give background
		- How the project was born
		- The challenge presented
		- Not many frameworks yet
	- Demo time!

## About Canvas
### Intro
	- Single element that can be drawn to
	- no dom tree
	- vs. SVG
	- vs. Flash

### Drawing Methods
	- What can we draw?
		- images
		- video
		- canvas
		- shapes
	- Positioning
	- Layering

### Time-based animation
	- What it is
	- Not just for canvas!
		- bullet bill demo
		- Show cell-like example (can't do that with css)
	- requestAnimationFrame vs. setInterval
	- Moving sprites

## The Javascript
### Code Organization
	- Structure
	- Object Oriented Programming
		- object.prototype
		- Klass.js
		- Coffee Script
	- Main game object
	- Types

### Library or roll your own?
	- Things get complicated very fast
	- Performance considerations
	- At miniumum
		- Frame manager
		- Input controller
		- Base Object
	- Type Considerations
		- Frames
		- Game
		- Image
		- Object
		- Input
		- Sound
		- Sprite
		- Stage
		- Text
		- Tween
		- Util

### Wrapup
	- Mention Say Viget
	- Questions



#MISC NOTES:
## It's challenging to get the game mechanics just right.
- Jumping
	- How high?
	- What fake physics feel right?
		- We've very much been informed by early games like super Mario Bros.
	- Hold button longer, jump higher

## Level design
- Creating patterns that progress in difficulty at the right pace.
- Get other people to test frequently. I completely lost my sense of how hard things were after playing it a billion times while developing.
- Users were only going to spend a few moments with this game. Should have a pretty low level of entry.
- Create something easily tweakable
	- Tommy's Level Editor with Say Viget
	- My Track Array
	- Variables that are easy to change in a debugger

## Sound Design
- Really hard to get just the right sound
- Good stock sounds can be hard to find

## Spend the time making yourself tools to help you.
- Factory Game Debugger
- Level Builders
- Program in shortcuts that let you skip intro screens, levels, etc.

## Build small chunks at time

## Build in time to Optimize
- Figure out natural feeling touch controls
- Refactor to boost performance and lower battery consumption

## Use a framework?
- Canvas gives you nothing
	- Buttons
	- hovers
	- clicks
	- Any mouse interactions have to be handrolled.

- You need a framework - whether you make it yourself, or use an existing one
- CreateJS is pretty mature now
- Box2d for physics

## Find a great designer
- Design can make or break a game.
- Frees you up to focus on code.
- Run/Walk sequences are hard!

# Links
- Time Based Animation blarg post
- Joseph Le's tumblr.
- HTML 5 animation with Javascript and Canvas
- Run Puma Run
- Blockblaster Boilerplate TODO: RENAME THIS
- Say Viget
- CreateJS
- Paper.js
- Reveal.js
- Prototype chain aritcle
- Klass.js
- CoffeeScript

#TODO:
- Make game size to window
- Add section on audio.
- Add a section on sprite animation?
- end with twitter handle and urls