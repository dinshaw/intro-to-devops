
# Flatiron
* Introduce myself
* Introduce talk
* Anyone heard of DevOps
* Dose anyone know what the difference between Development and Operations is?
* Any problems deploying to Heroku?

# [] Computer
* Enter DevOps
* DevOps is referring to a mindset that finds the best tool for the job so that we can accomplish all of the extremely complicated, interwoven tasks are our daily work, and have fun doing it.

# [] A Brief History of DevOps
* At the dawn of the computer age, there was no distinction between dev and ops.

# [] Colosus
* You mounted tapes, you flipped switches, and you wore a lab-coat.

# [] Punch Cards
* And then came the punch cards; that you handed over to an  'operator' who delivered a printout to a cubbyhole with your name on it.

# [] Computer
* And then finally, the arrival of the PC completely separated operation from user and the modern 'IT Operations' culture was born, and the wall began to go up...

# [] Patric Dubois
* 2007 Patric Dubois, Ghent, Belgium wanted to work in every possible area of IT

# [] Velocity Conf
# [] 10+ Deploys Per Day: Dev and Ops Cooperation at Flickr
* Two guys working at flicker
* John Allspaw, Operations
* Paul Hammond: Development
* The community knew there were problems, but these guys really called it out and gave it a face, if not a name, and showed a path to salvation.
* They illustrated the problem with this now famous slide
# [] StarTrek
* That there was, and still is, a rift between developers and operations. THere was a lack of trust and a  lack of respect. And it was self-perpetuating.
* Developers job is to add new features; Operations job is to keep the site stable and fast.

# [] Devs who think like Ops / Ops who think like Devs
* This was the beginning of the DevOps movement

# [] Dubois missed it!
* Complained about it on Twitter and
* people said you should start your own Velocity conf
* Dubois organizes DevOpsDays 2009 in Belgium - Ghent

# [] DevOpsDays Logo

# [] DevOpsDays
* Talk titles


# [] #devops
* People collaborating on common problems, finding the best solution
* Twitter still has lots of valuable

# [] So what's the problem?
* What is it about my life as a developer that is so bad?
* As a professionals in the software industry, our job is to:
* Deliver value to our end users by innovation
* We are supposed to be conceptualizing and building the future of the way people organize their lives.
* But the reality is that we spend a great deal of time on:
1. Unplanned work
2. Configuring and fixing our tools and environments
3. And trouble shooting the hand-off to from Dev to Ops
* And the better we get, the more complicated our tool chains and environments become, and fragility creeps into projects and lives. and that is something we have to avoid at all costs
* Critical systems cannot be fragile

# [] Why We Need DevOps Now
* Benchmarked over 1,500 organizations for 14 years
* All companies, not just SAAS products, have a huge dependency on  IT
* Led him to the heart of the DevOps movement
* I'm taking a lot of things from this presentation
# [] Culture
* What's that you say? But culture is not going to help you with your current problem.

# [] Give me tools
* Tools I can use, please...

# [] Computer - Common tools
* 'Common', because if we are all using the same tools we will get better at them quicker,
* Because a common toolset fosters the collaboration and cooperation that will lead to the trust and respect we need to start tearing down the wall

# [] TEAR DOWN THE WALL
* I'm gonna talk about some specific tools, but one example of common tooling is that developers and operations, and really the whole organization, should be using the same version control system.
* If something happens in the middle of the night, and everyone knows where to look, has access, and knows how to use the tools to say: do a version bump, then one less person gets woken up, one less person is grumpy the next morning, and everyone wins.
* In the same way we refactor legacy code, we now need to refactor  our legacy organizations and the way we work.
* When we refactor code, we succeed when it is easy to change the code without breaking anything. This is important because our job, as a developer, if you had to sum it up, is introducing change.
* We need systems that are capable and comfortable existing in a constant state of change.
* This is so far from where a lot of organizations are today, that in the Why We Need DevOps Now talk, Gene Kim says refers to this  as

# [] The Danger Zore
You need a culture that keeps pushing into the danger zone
And has the habits that enable you to survive in the danger zone.

# [] Scott Cook
* Intuit's Scott Cook at the Economist conference 2011 Talking about when TurboTax:
By installing a rampant innovation culture, they now do 165 experiments in the three months of the season. Our business result? Conversion rate of the website is up 50 percent. Employee result? Everyone loves it, because now their ideas can make it to market.
* Compare to traditional retail site


# [] Boxen project recipe
* Just like Server definitions, there can be project definitions that install the proper runtimes and data stores and fetch the latest code
* do a better job of ensuring consistency across multi–developer teams

### CI and Production
* I am guessing everyone in this room has experienced problems promoting code from a development environment to CI and Production, so i will skip the example here.
* The take away here is that these issues that we all see and accept as 'part of our job' are avoidable to some extent.
* If your development environment and your local test environment are identical to CI and Production, then the time we spend troubleshooting these issues is minimized,
* maybe more importantly, the frustration and the finger–pointing 'hey it worked on my machine, it must be your fault' is also minimized.

# [] State of DevOps Report
* LinkedIn keyword 'DevOps' up 50% from 2012 to 2013

# [] What is a DevOps engineer?
* slides

# [] What are we waiting for?
* Why aren't we doing all this already? Been around since 2007.
* Why isn't everyone doing TDD and CI? Everyone agrees its the right thing to do.
* Well, the easy answer is:
* No time! Too many other priorities...
* But there is another answer that is not as easy to say
* We are paid to be professionals, and in some cases, experts. To know what we are doing. And for the most part, we do.
* We also have a great deal of learning baked into our day-to-day.
* We learn new libraries to use in our code-bases all the time.
* But learning a new set of tools and a new way of working is going to take a little more effort.
* And even for the best of us, it can be a little overwhelming think about being a beginner again.

# [] Overwhelmed
* Muddle story…
* This is the right way to feel. It means that you are pushing the edges of your comfort zone and that you are learning. Dont be afraid to hit enter...

# [] First steps
* One of the two similarities of the High performing organizations that Gene Kim cites is Automation; the other one being version control.
* Automation is a great place for any developer to start
* Pick one small, familiar thing that you already know how to do, and automate it
* Make sure your editor removes white space when you save
THis might be a simple as setting in your preferences, but that is automation and if it works consistently, then it is valuable forward progress.
* Set up .dotfiles
* Setup a task to rotate your development logs before your machine runs out of space

* These things might seem trivial, but when we start to automate away the little things that take our time, we start to expose the next level of opportunity for optimization of our workflow.
* You will start to see opportunities to automate everything

* Automate the setup of your development environment, the way you like it. Don't worry about if it can be shared at first.
* Automate the setup of your production environment; and then do it as your development workstation.

# [] Puppet & Chef

# [] TDD
* So once we have used automation to help ensure that our machines works the way we want them to, we can start thinking about stuff a little further up stream like, 'does our code work the way we want it to?'
* The time has come to be ashamed, if we are not doing TDD
* I cannot even imagine working with untested code anymore. I would pull out my hair and then lose my mind.

# [] What we need from ops
* Ops must provide a one button environment that you can be 100% confidant is a clone of your test production environment. This becomes possible when setup of these environments is scripted with something like Chef or Puppet, and under version control
* One button deploy: we have to know that deployments are happening the same way every time.
When every deployment is done differently, every production environment is different and no mastery of procedure or configuration will ever be achieved.

# [] You build it; you run it.
* Developers do the deployment
* Developers own uptime for code

------------------------

# [] Google SRE
* When we get here, we can start foreseeing production issues before they ever happen. We can start to break things before production
# [] Choas Monkey
* ec2 outage

# [] More suggestions?
* Pair-Programming
* Maybe even from someone from the other side of the wall
* Have coffee with an operations person


# [] Chat Ops
# [] Amazon @ O'rily Velocity Conferance - June 16, 2011
# [] Links
# [] Closing
