# Notes to Class 2 slides

* 0:
  * sorry, no live demos today
  * small break in the middle, not big one
* 1:
  * scrum: invented 1990s
  * based on rugby term "scrum" or "scrummage" - restart play by huddling
  * originally a journal article, eventually utilized for software by two of the co-signers of the agile manifesto
  * well-defined roles driving empiricism - be as effective as possible now, and learn+improve as you go
  * work is committed to in two-week sprints, avoiding scope changes for sprint
  * kanban: originally a lean manufacturing process invented @ Toyota 1960s
  * meant to maintain inventory levels - make things as customers need them most
  * think of a grocery store - people buy what they need, only what they need; store stocks only what it expects people to buy in a week
  * software ver is kanban-inspired, appearing around 2010 +/- 5 (book published, but in use before)
  * in software, roles are left to team - lots of overlap with scrum in implementation
  * another carryover from Toyota: limit wip so you can focus+finish
  * anything at the top of the backlog is what's next... which means you're always in the backlog making sure the most valuable thing is next
* 2: hope you remember the user story examples from last week!
  * right-sized isn't necessarily bite-sized, but usually should be
  * use T-shirt system: Small, Medium, Large - bigger than Large, should be separate stories
  * actionable is important for making TODOs into DONEs
  * "learn react" = bad, "do react tutorial" = good
  * jayke had a suggestion on slack: make an Epics column, make a labelled Epic card, then use same color for other cards
  * standup is to help keep team up-and-up on everyone: mentor for individual proj, teammates for groups
  * you can't do it all at once, so do it little by little
  * remember last week? we're bad at focusing, estimating time, waiting
* 3: remember our car user stories? let's talk a model t
  * useful to the user: drives; not useful: self-start (original model t had to be cranked!)
  * what about pedals? (it had a hand throttle, pedals were for gears) - more important that it goes
  * speedometer? (it had an 'ammeter') gas supply? (you checked with a stick)
  * yes, the model t sounds sucky today - but that's cuz we've iterated over decades and decades
  * MVPs are meant to be iterated upon! Gary's app had 7-8 features, but coming out of Liftoff it only had the 3-5
  * difficulty of implementation needs to be measured vs value
  * user signup? sure. superuser permission? maybe. persistent user sessions? wanna learn what cookies are really for?
  * dependencies also important - esp in groups! prioritize the initial deps (i.e. "install React") to do the later ones
  * build 'tracks of work' on your dep chains, so you do all the stuff at once - or one dev in your group does all the stuff in a chain
  * remember: 3-5 features for your capstone - 'aggressive' prioritization means you cut off the less-valuable features (epics), and you cut out stories that don't meet the valuable features!
* 6:
  * avg salary according to glassdoor = ~90k - also in pretty high demand
  * we can't learn to be ux people, but it's important to understand some principles
  * if you don't have users then you dont get $$$
  * "if you build it they will come" - not always, but they'll stay if you have good user experiences
  * how many times have you used a shopping site only to find out the checkout process sucks? think of how easy it is in amazon
  * tesla's really pushing the elite / futuristic angle, and it makes you want to buy a car
  * you can tell how much money an election campaign has from how nice the website is
  * [if you're curious, the winner's site is much nicer](http://web.archive.org/web/20160728073509/http://billeigel.com/issues)
  * remember: users aren't always customers!
  * it's hard to delete an account because tumblr doesn't want you to!
  * there's also dark ux - it's like hidden fees, but in design. ever click an x in an ad, but miss it by a pixel?
* 7:
  * feeds into plan - if you know what it looks like it's easier to code
  * will help you expose problems early, rather than after you've already spent 8 hrs coding!
  * engineering time is expensive - much cheaper to draw a picture and toss, than to code a whole app then toss
  * not only the look, but the app flow - in cheese, what happens after making a new cheese? a new menu?
  * once you have the look + flow down it's easier to generate user stories - I know this firsthand!
* 8:
  * not required but useful for making sure your work matches your wireframe! since wireframes can capture actions
  * like the standard user story format - three blanks, don't make them too big
  * even if you don't use BDD, let's think about how to  break down actions into code-friendly user stories
  * back to the car example! when user does X, Y happens
  * important relationship to the AS A ___ part: the 'persona' is what you're designing for
  * user personas - won't cover in much detail, but capture the 'who'
  * in BDD format, capture the person taking the action: regular user or admin, for example
  * example: user clicks login button, goes to login page. two user stories right there: button shows up on the home page, button goes to a new login page - both should be in your wireframe and your user stories, and both can have BDD!
  * real life example: I use it to make sure my devs code to match the design - if it doesn't meet the acceptance criteria, I'll say 'no' and tell them why
  * acceptance criteria == how a story is considered 'done'
  * usually not devs writing acceptance, more product-oriented
  * BDD also super useful for TDD (XP), if you'd like to hear more about that ask me!
* 9:
  * low + high both fine, more important to capture the high-level flow
  * don't worry, these are professionals - your own wireframes don't need too much detail
  * just about all of them follow grids - you should do the same!
* 10: look @ both project outline and project planning submissions
* 12:
  * MAKE STANDUP SHORT
  * lean on mentor for wireframe+mvp help
