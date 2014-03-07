
# Intro to DevOps

## [] Hello my name is
* Introduce myself
* Introduce talk
* New audience challenge
* Anyone familiar with the term DevOps?
* difference between Development and Operations?
* Any problems deploying to Heroku?

# [] Computer
* Our software is complicated
* same code/different env == bad


# [] A Brief History of DevOps
* At the dawn of the computer age, there was no distinction between dev and ops.

# [] Colosus

# [] Punch Cards

# [] Computer

# [] The Wall

# [] Patric Dubois
* Developers throw code over the wall

# [] Velocity Conf
# [] 10+ Deploys Per Day: Dev and Ops Cooperation at Flickr
* Two guys working at flicker
* John Allspaw, Operations
* Paul Hammond: Development
* The community knew there were problems, but these guys really called it out

# [] StarTrek
* rift
* Developers job is to add new features; Operations job is to keep the site stable and fast.
* Devs who think like Ops / Ops who think like Devs

# [] #devops
* People collaborating on common problems, finding the best solution

# [] Culture

# [] Tools

# [] Scott Cook
* Intuit's Scott Cook at the Economist conference 2011 Talking about when TurboTax:
By installing a rampant innovation culture, they now do 165 experiments in the three months of the season. Our business result? Conversion rate of the website is up 50 percent. Employee result? Everyone loves it, because now their ideas can make it to market.
* Compare to traditional retail site


# [] The Danger Zore
You need a culture that keeps pushing into the danger zone
And has the habits that enable you to survive in the danger zone.

# [] State of DevOps Report
* LinkedIn keyword 'DevOps' up 50% from 2012 to 2013

# [] What is a DevOps engineer?
* slides

# [] Questions?

# []

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
