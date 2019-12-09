# Notes to Class 8 slides

* 0: aren't you glad you don't have to listen to me talk anymore?
* 1:
  * koko: hard deadline for all assignments?
  * capstone deadline softer, other assignments not-so-much
* 3:
  * companies won't just leave you alone - you're gonna have people to work with
  * if you aren't assigned a mentor, you should latch on to someone (but like, nicely) - just be respectful of person's time
  * ask away, questions aren't dumb if you're new! better to ask than to screw it up later
  * try not to ask things you should google to refresh (ex. what does "class" mean in java)
  * also: try not to ask things multiple times if it's been answered! personal experience, it really wears out the welcome quick
  * so: while you can ask a ton, they hired you to learn the ropes. give issues a shot yourself first, as mentors who know you've already tried are more willing to help
  * gotta improve your google-fu: search your errors, make judgement calls, search any new errors.
  * boil errors down to the important bit, and omit the parts that are your code - google has no idea what AndysClass.java line 43 is, I bet your mentor doesn't either, but both know quite a few Spring errors. (yes, this is an art. you'll learn)
  * i've met these people, don't be these people: CHECK MULTIPLE GOOGLE RESULTS, DON'T JUST TAKE THE VERY FIRST ONE
* 4:
  * agile you should already have some passing familiarity with, but worthwhile to read up on user story format and different agile styles! kanban, scrum, SAFe, etc.
  * cloud is super important because you don't maintain your infrastructure. what if, instead of running on your laptop to demo, you pulled up a URL and showed your mentor?
  * faster than your laptop, right? more convenient than your laptop, right? deploy to the internet and it solves several things - now imagine it's not your capstone, but a real online shopping app. don't wanna show Amazon-on-your-computer to your customer, right?
  * LaunchCode acutally suggests you push to the cloud, with the Deployment optional assignment! worth doing in my opinion
  * DevOps is suuuuuuuuuuper popular because it's suuuuuuuuuuper convenient - know how you run/rerun your app constantly? what if you did the cloud thing, and also instead of typing in all the commands every push you just... did `git push`
  * core is Continuous Integration / Continuous Deployment (CI/CD). first is running your tests and compiling your app, second is pushing your latest app to the users
  * and microservices play well with CI/CD - in short, you build out your services as separate apps, and communicate with each other (often with APIs)
  * might be hard to imagine why, but bear with me: basic example is if you took your capstone, separated the db bit into a single app, the business logic into a single app, and the front-end into a single app.
  * seems convoluted, right? but - if you have a very complicated db, wouldn't it be easier to change the code for that without also updating the business logic when the schema changes?
  * very useful to create maintainable code in complex environments, and loosely coupled means less code conflicts
  * beware, though: not fit for everything! your capstones are ABSOLUTELY better as single apps; but, familiarity with the concept helps!
  * one last opinion: beware of "hype-driven development," where every new-and-hot technology sounds better than what you're doing. some new is good, but if everything is new then you're eventually going to abandon "new." it'll catch up to you, trust me
* 5:
  * IDEs are basically what you'd expect - some IntelliJ variants like WebStorm, PyCharm are out there too
  * DevOps gets more varied - some of the stuff you already know, `gradle` / `npm` / `git`
  * Docker is basically the industry container tool (containers is a different topic - they're _like_ virtual machines, but _only_ like)
  * github / gitlab / bitbucket are mainly git repositories, but with different bells and whistles
  * jenkins / bamboo / teamcity do CI/CD, you give them scripts and they run them on whatever trigger you define (usually pushing new code to git)
  * ...and those scripts can be built with ansible, puppet, or chef, which let you define the tasks-to-do. often infrastructure-related (e.g. building up a new server), but apps too
  * languages pretty much resembles what you learned here - java is particularly popular in STL, but C# is also common in enterprises
  * javascript is something you'll want to learn eventually, though the framework to learn with is a constant argument. I'd personally recommend Angular (to the dismay of others!) because it forces you into typescript and gives you a bunch of libraries to start, but React is also a great choice
  * [you may want to check out LC101's JavaScript curriculum](https://education.launchcode.org/intro-to-professional-web-dev/)
  * Python is popular for many reasons, a big one is data science - R is popular there too
  * Go is a Google-made language that's gaining a lot of popularity, but still somewhat niche - Kotlin is similar, Jetbrains-made and like a "hipster Java" (don't tell anyone I said that)
  * Dart, Rust also trending, but definitely niche; former was a 'JavaScript killer', Rust is a new up-and-comer that's still maturing as a community
  * whatever you learn, _do as the romans do_. learn something relevant, not just "something"
* 6:
  * yes, you have a mentor, but your manager is the one who does promotions. Meet regularly, they'll help with 2/5/10yr plans and how to progress your career
  * I'm not so good about meetups, myself... learn from my failures, folks
  * many companies will reimburse college courses or degrees, it's worth asking about (though you may not be able to as an apprentice). worst case, look for a new certification to add
* 10: final due dates for assignments coming up!
  * mentors: we will have one final retro too
