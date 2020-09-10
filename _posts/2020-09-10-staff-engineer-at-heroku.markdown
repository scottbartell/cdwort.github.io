---
layout: post
title:  "How I operated as a Staff engineer at Heroku"
date:   2020-09-10 11:40:51 -0500
categories: interviewing
---

I was incredibly lucky to spend 5 amazing years at Heroku. By the end of my time, I was operating in a Staff capacity, although I'm honestly completely unclear which titles at Salesforce actually map to Staff.

Because titles are unclear and because my role was a little amorphous, I chose not to submit a story to Will Lethain's [great collection](https://staffeng.com/stories/) at StaffEng.com. That being said, I added a few questions to his questionnaire that I hadn't seen answered elsewhere, so I figured I'd post this.

**_Tell us a little about your current role: where do you work, your title and generally the sort of work do you and your team do._**

Until recently, I was a Principal engineer at Salesforce, working for their Heroku product. I joined almost five years ago, working on the Heroku Add-ons product, and then transferred to the Heroku API team. For the last year and a half, I worked on the API team for the Salesforce Functions product, which runs on top of Heroku infrastructure.

The API team is at the center of defining how the Salesforce Functions product will work, so there are a lot of different tasks our team does. First and foremost, we write the code to store the state that the customer *intends* their infrastructure to converge to and then push that down into the infrastructure layer. If you're interacting with Salesforce Functions, you're going through our code. We also do a lot of reconciling what the infrastructure can do with the hopes and dreams of product. I did a balance of work, but more towards the "hopes and dreams" side of things.

**_What does a “normal” Staff-plus engineer do at your company? Does your role look that way or does it differ?_**

There is really no "normal" Staff engineer at Salesforce. I usually talk about four different approaches I see in the company, some of which line up with [Will's archetypes](https://staffeng.com/guides/staff-archetypes) and some which don't. A lot of folks are a mix of these and rotate through them over a long career at the company.

*Team(s) Lead/Right Hand*

You are the primary technical point of contact for 10-20 engineers, across one or more teams. You are typically reporting to a manager of managers. Responsibilities vary based on individuals' strengths and the strengths of their manager, but there are some common things you *must* do. If you're not making your delivery timelines and this is a surprise to your organization, you and your manager have a problem. If product has a dream and no one knows what it would take to build it (time, resources, architecture), you have a problem. If you can't answer "Why are we building this in this way?" then you have a problem.

*Product Architect*

If it's on TechCrunch or promoted at our corporate conferences, there is an Architect for it. If the project (40+ engineers) fails to be a success, you share responsibility along with the (typically) VP+ engineering manager and Product owner. If you have any type of personal presence, you will be put on a stage and in front of customers. This is the level where you're helping advocate with your VP for major initiatives to go after certain markets. If we made the wrong bet, some blame is with product, but it's also on you, and the manager probably won't look great.

*Deep Diver*

You have a lot of deep technical expertise on a particular component or system. You tend to stay on a single team or a single area of the organization. If you work in our legacy codebases, which are the core of our profitability, you are basically unfireable because you know so much. You may write code for some of the gnarliest problems of the legacy system you're being kept around for, but you'll often find yourself spending more time interfacing with other teams to explain why your system can't do what they want and how we can work around it to deliver on a reasonable timeline. You will work closely with your Team Lead on a daily/weekly basis and occasionally have your entire day/week blown up because the Product Architect has identified a need for your expertise and all of a sudden you're being trotted out to present to some team you've never heard of.

*The Management*

There are two variants. First, you're pendulum'ing over to a line manager role, but since your IC title is the same grade as Director or VP, making you a manager would result in a massive pay cut. You're likely managing a smaller team, given Salesforce targets 12-15 reports. In the second variant, you're roughly an extension of a VP+ leader. Maybe you're working on how we keep our many thousands of engineers communicating well. Maybe you're advising an SVP on where to make technical investments - does our company really have enough of a competitive advantage to go after that market? Sure, the SVP/C-suite person is being told by Product that if you only give us $100 million we can do a ton. Is that true? Hey, we just bought a multi-billion dollar business (or we're about to): Can you figure out what we should do with them? Many, including Will, call this fire-fighting, but that's too narrow a view of how these roles really deliver value to large companies: it's fast-paced opportunity scouting and truth-telling. That being said, you'll most likely be looking for opportunities and the real truth within the more challenged parts of the business, so I see the fire-fighting analogy.

**_How do you define success in your role?_**

First and foremost, I am successful if the folks I work with understand how business decisions tie into their day-to-day work.

At a minimum, this involves a fair amount of understanding why we're being asked to build something, running ahead of the team to make sure product plans are in place for us, working across teams to come up with an achievable plan and then championing IC concerns as they crop up.

But it also means pushing forward discussions about what kinds of risk are worth taking on in our code at the moment. Is now the right time to commit to this abstraction? Is now the time to address a performance issue with a re-architecture? We're moving quickly, but also seeing a lot of incidents - what kinds of testing should we invest in?

Success looks like seeing conversations about timeline and priorities between ICs start from a shared background. Success looks like having no major blow ups about "How could you suggest we ship this hack?" Instead, folks can talk about technical choices through a business lens: "I know we're currently low on staff compared to our product ambitions, but is this the right place to simplify?" Success looks like a team with a shared goal for the quality and resiliency of code that we're writing. Success also looks like other ICs feeling confident in advocating for changes, since they see our team making technical decisions with a consistent goal in mind. When I talk with ICs in 1:1s, there should be no "I'm not sure why I'm doing X" when it comes to code, infrastructure and incidents.

Next, I am successful when my management chain clearly understanding the particular risks we're taking on. All of the architectural decisions a team makes will be wrong, eventually. Whether technology changes, our customer base changes or the product itself changes, it's only a matter of time before we regret those big choices. The key is understanding what bets we're making and how long we think before we'll need to revisit them.

Architecture in a large enterprise is a lot about risk management. A large org has a lot of existing momentum in the market and naturally becomes more cautious. I only have a few places where I can advocate for higher-risk bets and those bets are going to be far lower risk than at a start up. While I need to embrace the fact that our decisions will be wrong, I need to be able to speak to the ways in which we will likely be wrong, when we'll know and what our mitigation strategy will be.

Third, I am successful if I'm saying the right "No"s to my manager. If the ICs that report to my manager end up feeling like "I told you so" or "We knew this was a bad idea" and that wasn't surfaced for a discussion, that's on me. As a Staff engineer, I have the responsibility to course correct my manager when we're over-committed or committed to the wrong thing.

Finally, I'm successful if my organization has a healthy engineering culture. No one person owns culture, but that doesn't mean we all don't equally share the burden of building a world-class engineering organization.

**_How do you spend your time day-to-day?_**

While I do write code from time-to-time, it's only after I've delivered on my obligations on these four functions.

*Information gathering* - In order to help my team understand the context within which we're building a thing, I need a lot of information. I almost unfailingly start my day with a list of longer emails and docs of all varieties to digest. I also spend a fair amount of time in cross-org chats with assorted managers & ICs, whose purpose is a combination of information gathering and the coaching I mention below.

*Planning* - Knowing a bunch of stuff isn't helpful unless we actually do something with it, so I also spend a lot of time in planning activities. This is a lot of writing docs and running meetings. Planning activities are usually very collaborative -- I rarely know the most on any one thing, but I can knit them all together into a plan.

*Context sharing* - Knowing what we want to do isn't helpful unless a lot of people understand the plan, so the final category of work that's execution oriented is sharing all of that context. I attend meetings with other teams to share what we are doing, I review PRs to make sure we're making small decisions in-line with larger goals, and hold standing team 1:1s to make sure each person feels confident in the direction we're headed.

*Coaching & Culture* - The final category of work isn't oriented towards delivering a product, but it's still critically important to our organization's long-term health to invest in our engineers. My personal approach is far more on invest in people, not in process. Given how much I love calendars, spreadsheets and process in my personal life, I'd say this approach is very much a reaction to dehumanizing nature of working in large corporate environments. I spend a fair amount of time in 1:1s, doing some mentoring of juniors but mostly focusing on coaching our senior engineers who actually have fewer opportunities for advice. Every once in a while, I'll dip my toes into our formal processes, as I did in helping reformat our VAT team after our ~120 person org merged in closer to Salesforce.

I also end up being the [RACI](https://en.wikipedia.org/wiki/Responsibility_assignment_matrix) enforcer for external folks coming into our team slack channels, PRs and doc comment threads. For managers with fewer reports, it maybe possible to keep up with all that every day. I have a lighter meeting load and can jump in with variants of "Thanks for that opinion, we'll keep that in mind. My understanding is that your team doesn't share responsibility for that decision." I confidently trade on my manager's authority in ways my teammates may struggle with. Because of my time and my deeper involvement in the technical details being discussed, it is my responsibility to step in and deescalate if a technical conversation is starting to circle the drain. Most times I can resolve it; very rarely, I need to pull in my manager or skip-level in between their meetings to help navigate some strange cross-team dynamic that is resulting in someone unintentionally being a bit of an ass to our ICs. This means that most of my small moments in between meetings (and during the more boring ones) are filled with cycling through tab upon tab of docs, PRs and threads, watching how communication is going today.

**_How do you keep in touch with how things really work as you spend less time on hands-on development?_**

As someone who still does write code occasionally, this is something I struggle with. Our codebase shifts underneath me constantly, in ways I often don't see. It has been my goal for the year to make sure I say "I'm not sure, let me check" even when I feel confident.

**_How have you sponsored other engineers? Is sponsoring other engineers an important aspect of your role?_**

Yes. Everybody wants to hire senior engineers; nobody wants to make them. That's really messed up. Mentorship and coaching can only go so far -- you need to provide opportunities for folks to grow and fail in stretch assignments.

Sponsorship within my team worked the same as when I was a senior engineer -- I'd talk with my manager and team about who was doing what work and put forward suggestions. As a Staff engineer, I have new opportunities to sponsor folks across the organization into some of the organizational coordination work I do. For me, that usually looks like inviting someone to be the backup for a particular venue of technical communication, whether that's a written doc or a meeting. I'll spend time making sure the person understands the context they're working in and answer any questions they may have. I'll explicitly ask how confident they're feeling about attending/engaging/leading on a particular communication venue. Eventually, I'll switch to watching from the shadows and doing a debrief every once in a while to check in on confidence and their ability to pick up on organizational dynamics. Once they're feeling confident, it's time for me to stop engaging unless explicitly asked.

As a Staff-level engineer, sponsorship is a key way to resolve the problem of loss of time. However, you need to spend time *now* in building people up. It's easy to get so underwater that you don't actually have the time to coach & mentor enough to get someone to the point where you can sponsor them for taking something off your plate. Investing early in sponsorship starts opening your eyes to delegation in a healthy way that's not just dumping something on someone.

**_How do you build a network at a remote company?_**

Being able to make connections within your org to help deliver initiatives faster and with fewer road blocks is a key competency to being a Staff engineer. However, that can feel a little harder in remote settings and requires dedicated effort.

I start by making a habit of reaching out after meetings, even if it's just to say that it was nice to meet you. Often, this translates into some of the personal connection you might unintentionally pick up on in an office environment: How did someone get into tech and come to this job? What's their life look like outside of work? Do they seem like they're really run down working on the latest project?

For folks who seem like they're open to it, I try to schedule a virtual coffee break. There are a lot of tools to automatically do this for your team, like Donut.ai. I find the random assignment tools can be far more time than they are worth, but if your company has one, it's a valuable tool to *reference* when setting something up -- it makes your ask seem more casual.

It will probably feel weird -- that's okay and expected! Ask open ended questions with the goal of just getting to know someone and usually your contact will be happy to share what excites them.

Make sure you provide information and value to the person you're talking with. Eagerly lend your network and expertise. Deeply listen to what someone is doing and what challenges and share context about why they might be seeing that. As you get more and more established at an organization, you may find it's easier and easier to provide value. Whether it's actionable ("Oh, talk to so-and-so in legal for that") or contextual ("Oh, that's because so-and-so hates this acquisition"), sharing what you can to help others is what solidifies your contacts into a network.

If you're established at a company, be aware that you're likely leaning heavily on notions of your organization that are year(s) out of date. You may be furthering existing misconceptions or old grudges that really should die off. Actively invest in meeting new folks as a counterbalance.

If you're new, feel confident that your outside perspective is truly a bonus to those around you. Try to find the most experienced person who will still speak honestly with you. This often involves going higher ranks than you might expect.
