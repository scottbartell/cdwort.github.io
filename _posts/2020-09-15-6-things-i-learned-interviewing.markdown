---
layout: post
title:  "6 things I learned interviewing for Staff positions"
date:   2020-09-15 11:40:51 -0500
categories: blog
taxonomy: staff, interviewing
---
I recently completed an either 9 month or 2 month search for a new job, looking for Staff-level positions for the first time in my career. I live-snarked much of the process on [Twitter](https://twitter.com/cdwort) and heard that was helpful to some folks who are also thinking about starting their first Staff-level search. Some reasons this blog post may not be interesting or ring true to you:

1. I only talked with ~10 places and chose to proceed to final interviews at 4.
1. I was primarily targeting companies with engineering departments in the 1,000-2,000 employees range.
1. I don't have a CS degree; I don't think Leetcode-style interviews are any kind of indicator of job performance; I think you can be a successful Staff engineer and never write a line of production code in that role. I know and understand why folks take different stands on these points, but they're where I'm coming from when writing this post.

## Everybody defines Staff differently

Let's start with something as basic as titles. Every new company I talked to meant diving into their levels. Is there a concept of Staff-level titles? Is "Staff" literally a title, but there are additional titles that comprise "Staff+" ranks? There's a ton of variation.

Next, not only does each company have different assumptions about what Staff means, there are likely many variants of Staff-level work within a single company. Will Larson does a good job of outlining [four different archetypes](https://staffeng.com/guides/staff-archetypes) for Staff-roles, although these are more valid for small/mid-size companies. I took a shot at outlining [archetypes at Salesforce]() (50k employees). It's likely that each company you talk to will have assumptions about what combination of skills they're hiring for and an inability to articulate them.

There are some basic questions you can ask to get a better sense of this without ruffling any feathers. You can ask if the role will involve writing production code or not. Does the role do any programming at all? If it's mostly prototype code, find someone in the role currently and ask how much time they've put into a recent prototype. You're looking for whether they talk about days, weeks or months? How much time will this role spend programming (production or prototype)? For the rest of the work, will the role be meeting heavy or writing heavy? What authority does the title provide and what is it expected that you build up as informal influence?

## Everybody interviews differently

Like most engineering roles, there's no clear way to interview for the skills that Staff-level folk need.

The most common approach is to send Staff-level candidates through the senior interview process and expect the candidate to "A+" every interview. There are a couple frustrating aspects of this. One is that many Staff-level roles just don't require upkeep of the same technical skills that seniors need, so you will be evaluated more on whether you were willing to prep for technical interviews than anything that indicates job performance. The other is that you may never get an explicit interview for Staff level skills (interfacing with product, technical leadership, shepherding cross-organizational efforts, coaching & mentorship).

I had one particularly interesting approach where they tried to test Staff-level skills *within* technical interviews by making the questions vague and what they were looking for unclear. You were evaluated on your ability to navigate what felt like a mystery technical interview and on whether you paused the technical to call out the interviewers on the unclear requirements. Needless to say, I lack the guts to successfully do that.

For companies that do Staff-specific interview processes, I got a lot of slight modifications. I'd still have one or two pure technical interviews, but it was often framed as "Just get through it so we know you're not completely buffing." I'd then get the hardest hardest design and behavioral interviews, often administered by folks who seemed pretty senior. A couple places I made it through the full interview without speaking to a single junior or mid-level engineer.

One company added in a management behavioral interview to my process, which was great! I'd strongly suggest companies consider adding some parts of their line-manager interviews to Staff-level processes. This was the only place that really dove into key parts of a Staff role: How do you grow people? How do you manage conflict? How do you grow influence? Do you know which hills you won't die on and how to retreat?

Besides the management behavioral, I had some other interviews I'd recommend:
  * Pair with a junior person. Either you or they have all the context. This was both a ton of fun and a really good way to make sure I could program while not being an ass about it.
  * Present on something you want to explain. This was such a good way to test communication ability and also whether you could say "I don't know" when asked follow-up questions.

My absolute favorite were design interviews that were an only slightly simplified version of the team's most recent technical challenge or major product feature. It helped them assess on 1) did I actually care enough to prep to know their product? 2) did I actually have the judgment they'd want? Especially when the title you'd come in with brings some degree of authority, it gives future teammates the option to tank me if they just don't think they would trust my judgment. Most importantly to me, these interviews helped me assess where the team was in terms of maturity and engineering quality. Where were they assuming that corners should be cut? Did I get nods and laughs when talking about certain scaling issues or intense, quiet note taking?

## People hire out for Team Leads frequently. Other types of Staff engineers, not so much.

It's relatively common to find jobs for "Team Lead" Staff roles. I'm not talking about the management variety of the title -- rather the role of senior-most individual contributor on a team with a manager. Common responsibilities would include mentoring junior engineers, taking on the leadership of the team's latest major launch/refactor, fixing the performance problem, etc. Typically, the company is hiring out because of a recent departure and because no one is able to step up.

It's a lot harder to find company's hiring out for roles with scopes of responsibilities broader than a single team. Every opportunity that was not vanilla Team Lead came from reaching out to my network.

Because these roles are not frequently hired out for, I had a lot of trouble talking with recruiters and some hiring managers about what I'm looking for. The mere mention that I was considering roles reporting to managers of managers caused major confusion. Even though I tried to be clear that I was open to range of different interpretations of "Staff", I got a number of "I'm sorry, we don't think we have a role for you in our company until we grow larger." Since those companies all had people reporting to managers of managers, I have now learned to interpret that as "We don't hire out for those roles currently and recruiting isn't even necessarily aware that folks fill those kinds of roles currently".

To avoid making it sound like you're not a good fit, I'd recommend trying to talk to hiring managers about their technical background before talking about how you see your role as Staff. Especially for managers who came up through the company, they may not need or want a large segment of the skills you may bring as a Staff engineer. Some of what I bring to the table sounds suspiciously like management (that's because it's leadership :tada:) and line managers especially can feel like you would be stepping on their toes. Getting your "Here's how I complement management" statement right *for that company and manager* can solidify your candidacy as someone being hired from outside the company. Getting it wrong is the fastest way to tank your candidacy without explicitly failing an interview.

If you're going to try to poke around your network a bit, be aware even that can get awkward. Staff roles and responsibilities can morph quickly and unexpectedly and much of your network may be out-of-date with your current work. Contacts may need some gentle updating and if your contact comes with different opinions of what is and is not the responsibilities of Staff individual contributors, then you're right back in the conversation above.

  * Them: "Amy is good, I'll reach out!"
  * Me: "Ummmmmm.. that's incredibly flattering because I spend most of my time having no idea what even is my job around here, but can we talk specifically about what you remember me being good at and exactly how good? Yeah, I'm better than that now."
  * Them: "... I was not prepared for this"

In addition to whether they hire out for a type of role, there's whether they'll hire from outside their industry segment. Domain experience can be a critical aspect of your success in a Staff-level role. I'm actually not sure how comfortable I would be with coming in green to certain companies. I have 6.5 years of experience building team collaboration tooling around very large blobs of data (pictures/videos/container images) that have a ton of mutable state. Should an advertising systems team have been interested in me? Honestly, I'm not sure. There's a massive difference between the architectures of managing the state for a product built to run thousands of containers indefinitely and a product that has very minimal mutable state but massive numbers of events around small bits of unchanging data. Users can't unsee an image nor unclick a link.

## There is a lot more Leetcode-style interviewing out there than you might expect

This totally depends on where you're coming from, but if you're coming from the part of tech that really cares about humane processes welcoming to diverse candidate pools, you may be a little surprised.

If you're like me and agree that leetcode-style interviews don't predict job performance, then you may be wondering "Why is this still the case?"

What I've seen suggests that the applicant pool can be so strong that tons of false negatives are accepted as the cost of avoiding false positives. This unfortunately means that the most popular companies can have the shittiest interview processes and then lots of start ups will follow suit because "Pick-your-FAANG is doing it!".

  * For example, that "You must A+ a senior interview process" type interview above where I got docked for not demonstrating requirements gathering under pressure, I got a "Well, now that you know the interview process at $COMPANY, you'll be better able to ace your interview with another team". Accepting false-negatives (and even using weedout processes) is absolutely a thing.
* That being said, consider interviewing at these places because 1) they're fascinating 2) the people are often lovely and kind 3) you may have your ass handed to you, but you'll learn about some cool stuff. If your ego can take it, I'd say it's worth it. 4) they're great competing offers.
  * One person found that by accepting leetstyle code interviews, they bumped their total compensation by 100k. Depending on where you're at, it may be more than that.
* Prep may not be that bad. You can read the answers. 2-3 an hour. A couple hours a day for a few weeks. Still shitty, unacceptably privileged, but may be worth it to you if you can.
* Depending on your background and confidence, you may be able to do a ton of these interviews and accept an ego-bruising conversion rate from interview to offer. You only need one high-comp offer to give you/your family the option of higher pay and to help with negotiation.

## Some companies will be open to negotiating how you should be interviewed.

* Works in smaller companies
* Figuring out how to evaluate something (in this case, you) without clear success criteria is part of the job.
* Mid-size and large companies may not be willing to remove interviews, but you may be able to suggest a hybrid IC/Manager process or simply add the interviews you need.
* Highly recommend adding a skip-level and product person interview to help you evaluate the company/role.

## Interviewing is miserable but the people are amazing!

The best part of interviewing is always being invited in to see a narrow window of what a team of engineers is accomplishing and how they're doing it. Interviewing was stressful and frustrating, but the people were spectacular, inspiring and so fun. Yes, I still think technical interviewing is broken but given that I had to do it, I'm so unbelievably grateful for the opportunity to meet engineers doing great work.
