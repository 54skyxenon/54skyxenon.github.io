---
title: "Navigating the Mid-Level Maze: 2025"
date: 2025-09-06
draft: true
---

# Navigating the Mid-Level Maze: 2025
Read the 2023 prequel [[here]](../finale-2023)

---

If you've read my three previous posts, you'd probably expect me to tell you here that Northeastern has a co-op program. That hasn't changed, but I've been out of school for a couple of years now!

Let's talk about what's changed for my job search as a mid-level candidate.

## "Why are you leaving Scale AI?"

{{% blog-shortcode caption="July 17, 2025" file="https://i.ibb.co/Vpj852GM/job-change-quest.webp" %}}

**The 2 year mark is a crucial milestone in every Scalien's career.** Beyond the 5-year post termination exercise privilege we earn through it, it's an indication that you're dedicated enough to survive the most intense periods of our history. For the typical new-grad, 2 years of experience is also signal to most companies that you've grown to a mid-level engineer -- you can operate with more autonomy than a new grad, but maybe not with the same profiency or influence as a senior engineer yet. This unlocks the flood of opportunities that people tout for a software engineer, but are also not afforded to an entry-level engineer.

Around 4 months ago, [Meta invested $14B into Scale](https://techcrunch.com/2025/06/13/scale-ai-confirms-significant-investment-from-meta-says-ceo-alexandr-wang-is-leaving/) to hire our leadership for their superintelligence lab. The cash dividend payout we got from Zuckerberg was nice, but the direction that Scale is headed remains uncertain after it. I do remain bullish on Scale, but the future won't include my generation in the picture.

## The Application Process

As usual, here are some statistics. This cycle lasted 2 months: I began recruiting mid-July and signed my offer mid-September.

{{% blog-shortcode caption="Some companies I interviewed with" file="https://i.ibb.co/1B2pdQ6/companies-2025.png" %}}

> Applied: **59**
> 
> Companies interviewed with (at least Phone/Onsite stage): **23**
> 
> Companies withdrawn: **5**
>
> Team matching interviews: **5**
> 
> Confirmed offers: **4** 

The market in 2025 still felt gritty, though it _was_ somewhat better than 2023. The biggest difference between this cycle and previous ones is that **recruiters reach out to you instead as an experienced candidate** if they want you. Working at a reputable AI company certainly helped with getting those recruiter reachouts. It's not the other way around anymore as a student where I'd spray and pray applications. 

I had the privilege of being selective with the opportunities that I found most interesting, rejecting startups requiring me to be based in SF in particular. I mainly interviewed with big tech companies, NYC-based AI startups, and financial firms.

{{% blog-shortcode caption="Dinner I had with folks from a startup who reached out to me" file="https://i.ibb.co/xtvf2dTv/startup-dinner.png" %}}

Interviewing with a full-time job was hard, but being in an West Coast headquartered company helps. My mornings from 9:00 AM - 12:30 PM EDT were cleared for interviewing before starting work. This had the added benefit of fixing my sleep schedule compared to [less powerful solutions](../no-distractions/), though my brain/vocal chords were certainly fried after those 2 months. During the climatic weeks, I was interviewing up to 4-5 times a day on top of my actual job, my heart rate was elevated going to bed, and I couldn't drag it out longer term for my own sanity.

## Interview Patterns

Here, I enumerate some of the patterns I've seen in interviews I've gotten this time around. I will not be breaking any NDAs, so don't expect me to leak interview questions!

Much of the preparation happened before I kicked off my recruiting cycle.

| Interview Type | Thoughts |
| ----------- | ----------- |
| System design | This was the area I drastically needed to upskill in before recruiting, and is a major differentiator between university and experienced recruiting. I keep a copy of [DDIA](https://dataintensive.net/) at home as a reference, but in my opinion the material is too pedantic to apply to a mid-level interview. <br/><br/> A better return-on-investment was doing the AI guided practices on [Hello Interview](https://www.hellointerview.com/dashboard) and reading the pattern articles they publish. This helped me to shape the system design grind into the same LeetCode grind I was intimately familiar with. While a put together resource, one callout here is that some niche interviewers may disregard some portions of Hello Interview's delivery framework, and it's important to adapt your presentation to their preferences.|
| Algorithmic coding | Ol' reliable. Given my experience from previous cycles and as a competitive programmer, this was one area I was not afraid of and the one I'd try to demonstrate a spike in. However, it does seem more companies are moving away from it in 2025, to my detriment. <br/><br/>To prepare, I'd still recommend going through the [Tech Interview Handbook](https://www.techinterviewhandbook.org/) and doing its associated [Blind 75](https://www.techinterviewhandbook.org/best-practice-questions/) problem collection on LeetCode. If you want to overkill this part, you could also try problems from the [USACO Guide](https://usaco.guide/dashboard) up to the Gold level. |
| Implementation heavy coding | While these interviews also may involve algorithms knowledge, I'd consider this a different category because the main challenge is ending with a working, elegant solution to what might be a multi-part problem. <br/><br/> To prepare, I'd recommend hopping on [Advent of Code](https://adventofcode.com/) to improve code implementation skill specifically. Up to Day 15 difficulty should be enough, and definitely stay away from Day 20 onwards. You'll commit your language's standard library to muscle memory by the end of it. |
| Practical coding | Due to the sheer unpredictability of what you can be asked to code, I find them harder than the two types above. More commonly seen at smaller companies. <br/><br/> In general though, to prepare, I'd recommend familiarizing yourself with technologies that can do the following:<ul><li>HTTP requests</li><li>Data analysis (e.g. Pandas)</li><li>Making API calls to a LLM (e.g. converting text to structured output/JSON)</li></ul> |
| Behavioral | The usual advice applies: follow the STAR framework and have 3-4 fleshed out stories highlighting (but not limited to) teamwork, conflict resolution, a project you did, and overcoming a challenge. <br/><br/> In particular, I enjoyed and recommend [Austen McDonald's substack](https://thebehavioral.substack.com/) for preparing for behavioral interviews. |
| Debugging/code reading | Reading code is harder than writing code, and the intuitions can only be developed with experience. That's why some companies require this type of interview. <br/><br/> If going in blind, the best advice I can give here is to aggressively make print statements at important functions given to you and question whether the data looks right at important sections of the code. |
| Frontend coding | Working as full-stack at Scale AI also qualified me for frontend-specific roles. But I learned the hard way that I was more suited for backend development after a lot of failed interviews. Frontend seems to me like one of those specializations where learning the first 90% of what you need to know is simple, with the remaining 10% becoming exponentially harder. <br/><br/> To prepare, I'd recommend working through the study plans on [GreatFrontEnd](https://www.greatfrontend.com/). Get exposure to building popular HTML/React components from first principles, and understand the fundamentals of JavaScript very well. |
| Trivia | Some companies may quiz you on niche topics during the interview. There is no way to predict what is asked, so the best approach is to develop an understanding of the fundamentals of a few important topics. <br/><br/>Here are some topics I've been quizzed on and the resources I used to prepare for them: <ul><li>Mathematics -- the [AoPS](https://artofproblemsolving.com/store/book/intermediate-counting) introductory and intermediate counting books </li><li>Computer Networks -- videos, Wireshark labs, and programming assignments from the [Kurose/Ross course](https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm) </li><li>Computer Systems -- readings from [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/), programming assignments from [CS:APP](http://csapp.cs.cmu.edu/3e/labs.html), and [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf) </li><li>Security -- basic challenges from [CTF competitions](https://ctftime.org/event/list/upcoming) </li></ul> |
| Take-home project | Uncommon outside of early-stage startups. As its name suggests, you work on them in your own time and decide when your code is "good enough" to submit. <br/><br/> To avoid the trap of overinvesting in a project that may or may not pass, I learned that timeboxing is especially important. Also, don't be afraid to turn down projects from companies who won't compensate you for your time. |

In 2025, I've noticed that companies are embracing the "vibe-coding" trend as well in interviews, permitting ChatGPT/Claude usage during them. I personally see this as more difficult as *you're expected to get farther* in the problem than you might have without AI. I also am not keen on correcting AI mistakes during an interview (in addition to the ones that I make!)

## Takeaways

### Behavioral and system design gauge seniority.

Or, in other words, determine what level you'd get hired at. That's because in these interviews, the depth of your answers and how you respond to probing questions is a better reflection of your experience than what signal a coding interview could provide.

For example: at Meta, it was possible for me to get up-leveled to a L5 (Senior Engineer) with stellar performance in these two areas. Thus, I spent a lot of mock interviews preparing for these two types.

{{% blog-shortcode caption="Before prepping" file="https://i.ibb.co/4wmj4szg/mock-may.png" %}}
{{% blog-shortcode caption="After prepping" file="https://i.ibb.co/6Rb1TtnL/mock-july.png" %}}

### Consider splitting the onsite.

Whether I feel good or bad about the first few rounds I sit, I'm the type of person who values having a day break in between them to reflect on what to do next.

More companies than not default to getting the entire onsite over with in one day, so it's important to make your preference known to your recruiter beforehand.

### Inquire about the difficulty of your panel.

It's no secret that a large factor of succeeding in interviews is getting lucky with who your interviewer is. One question you can ask your recruiter, if they do some sort of call to brief you, is if your interviewers lean towards the stricter or nicer end of those at the company. 

It not only affords you some peace of mind, but also you can use that information to decide to reschedule or not reschedule upcoming rounds. One of my recruiters recommended against rescheduling for this reason, and I took the hint with a favorable outcome.

### Save the best for last.

When you begin a new recruiting cycle, your performance is more likely going to start off bad and improve as time goes on.

In the past, I made the mistake of scheduling interviews at the companies I really wanted to work for at the beginning of the cycle, interweaved with those I was less partial towards. It's important to interview with those companies that you're lukewarm about first, gauging what stories/answers your interviewers respond well or poorly to. As a mid-level candidate, this was more in my control than compared to university recruiting where I'd rush to be first in line for the most competitive opportunities.

I will also admit here that there are some companies I interviewed with earlier on in the cycle that I ended up liking a lot more than I'd originally anticipated.

### You're not done until the team match is done.

While some companies put you in a team-specific loop when beginning the interviews, other companies don't team match you until after you pass the onsite. If the team match is unsuccessful, you don't get the offer.

In particular, Google is infamous for this happening to some candidates. I had my first taste of this unfortunate situation this cycle with Ramp.

{{% blog-shortcode file="https://i.ibb.co/sdG94TCJ/ramp-fail.png" %}}

## Acknowledgements

Many connections/ex-Scaliens at extended a helping hand this cycle, offering referrals to fast-track my applications at some great companies and helping me practice for interviews.

If you are one of those people reading this now, you have my gratitude and some of the insights in this article would not be possible without you.

## Where Next?

The end of the cycle was a nail-biter.

<details>
  <summary>(Click for spoilers)</summary>

I'd received offers from Coinbase and Meta that I used as negotiation leverage against two remaining firms I was contending with: Two Sigma and Citadel.

Things moved quickly that last week. Two Sigma declared they were moving forward with an offer, and that gave me the greenlight to drop both Coinbase and Meta who were close to deadline expiration. Concurrently, I'd reached the team match stage at Citadel and immediately notified Two Sigma. What happened next was unbelievable: Two Sigma inquired how much they'd need to offer to _just walk away_ from Citadel's process -- it's like I was witnessing a duel in front of me between these two behemoths.

Four parties at once now were applying pressure: Two Sigma's team, Citadel's team, and the competing headhunting agencies representing me for both firms. I sat two team matches interviews for Citadel, and concurrently again Two Sigma came in with an aggressive offer that I relayed back to Citadel. Citadel, while satisfied, was not moved enough by my performance to expedite their _final_ final stages and notified me they were not moving forward -- yielding to Two Sigma.

There was nothing standing in the way at that point, and I accepted an hour later after all the news settled. So starting mid-October: I will be working at **Two Sigma** as a software engineer, staying in NYC for the foreseeable future. I've been wanting to try out quantitative finance for a long time now, so there is a happy ending for this cycle!

{{% blog-shortcode file="https://ftp.pdl.cmu.edu/pub/datasets/ATLAS/images/twosigma.png" %}}
</details>
