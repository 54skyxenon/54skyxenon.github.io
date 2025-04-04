---
title: "Co-op Duels: 2022"
date: 2022-04-16
draft: false
---
<!-- https://ibb.co/album/Fgq2gQ -->
# Co-op Duels: 2022
**<i>Last modified on: 2023-01-21</i>**

Read the 2021 prequel [[here]](../recruiting-2021)

---

{{% blog-shortcode caption="" file="https://i.ibb.co/BwBC3dK/snow-duol-fb-2022.png" %}}
</p>

Northeastern has a co-op program where upperclassmen spend 4-8 months working full-time instead of taking classes for a semester, here's how it went during my junior year.

I interned as a software engineer at [Snowflake](https://www.snowflake.com/) in Boston working on diagnostics reporting, followed by [Duolingo](https://www.duolingo.com) in Pittsburgh working on speech recognition, followed by [Meta](https://about.facebook.com/meta/) in NYC working on AR/VR headsets.

## The Application Process
> Applied: **104**
> 
> Interviews/OAs: **43**
> 
> Withdrawn: **8**
> 
> Offers: **7**

Was it really that time of the year again? Thankfully, I heard back from a lot more companies this cycle with Microsoft and ETH Zurich on my resume. Being a junior also *formally* qualified me for a lot more summer internship positions. This year, I wanted to gain experience at smaller and more fast-paced companies, so naturally I would interview with several unicorns and trading firms.

These companies could afford to be picky with their candidates. There was a noticeable increase in difficulty, variety, length, and thoroughness in the questions I was asked compared to normal FAANG-type LeetCode interviews. Now that I had experience, I was also expected to articulate on my past internships. At the same time, I thought these interviews were more enjoyable as they were more interactive.

For example, Stripe asked me to add a new codebase feature involving HTTP REST calls and JSON parsing as a part of their onsite. Citadel asked me some gnarly probability and object-oriented design brainteasers. Duolingo asked a data structures + algorithms design question with a relentless barrage of followups.

I found that the best way to improve at interviews was to... just interview. **If I could go back, I would change my practice routine to invest more time on non-algorithmic interviews** -- reading large codebases, operating systems knowledge, object-oriented programming, system design, and mathematics (probability) fundamentals, just to name a few.

The logistics of this application cycle were weird to say the least. I started applying in late June-early August when I was still in the US, but most of my onsites would occur late September to mid-October. During this time, I was simultaneously studying abroad in Switzerland, which is 6 hours ahead of New York time and 9 hours ahead of Bay Area time. But that actually made things more convenient, as I would have my classes in the morning/afternoon and interviews in the evening (+ I'm a night owl 🌙). I'm fortunate that companies are still using Zoom for remote interviews and that my roommates put up with hearing the same self-introduction day after day.

{{% blog-shortcode caption="Recruiting sucked the soul out of me late-September to mid-October" file="https://i.ibb.co/SKNQcS7/recruiting-state.png" %}}

I received my first offer in early October from Duolingo, whose onsite I gave *right* before my flight to Switzerland! That took care of Summer 2022, but my co-op cycle (Spring 2022) was harder to deal with because ETH Zurich holds exams up until February of the next year. Many companies I received offers from could not accommodate that start date, and ETH declined my request to take these exams earlier. 

My first instinct was to change my co-op cycle to Fall 2022. Around then, I had received an offer from Meta following my hackathon in Prague that was about to expire, which I moved to the fall. Simply too good to pass up. But that still left the awkward gap of Spring 2022 - what was I going to do up until the summer? I signed up for some part-time classes at Northeastern so I could graduate as intended, but I kept interviewing to find a solution.

After a very long hiatus in mid-November, Snowflake resumed its hiring process and invited me to a phone screen. It almost seemed too good to be true, but they were fast to schedule interviews and I got an offer just after a week. Not only that, they were willing to accommodate a late February start date and end before my summer internship began, and it was all fully remote so I could keep my part-time classes as well! 

After 5 months of interviewing, everything eventually fell into place. I would be interning year-round!

## Snowflake
People know of Snowflake because they recently had the [largest software IPO](https://www.linkedin.com/news/story/biggest-software-ipo-ever-5301906/) in history so far. Even now, I have no simple description of what Snowflake does, besides "database stuff". I enjoyed Snowflake more than Microsoft because there's less bureaucracy in a unicorn. By the end though, I knew cloud computing wasn't for me.

Snowflake was an intense place to work at with lots of opportunity, nearing its 10th anniversary and embracing an influx of **top talent from Silicon Valley veterans**. I had the privilege of being mentored by multiple senior/principal software engineers. My work-life balance was relatively good, and I was able to juggle part-time classes well at Northeastern while working remotely.

{{% blog-shortcode caption="There's also a Boston office in the financial district I sometimes walked to with my friends for free snacks. The route had a good dim sum restaurant along the way for brunch!" file="https://i.ibb.co/tztkLW4/snowflake-1.png" %}}

I interned on the Service Infrastructure team. My project was to improve how we collect and publish Java Virtual Machine (JVM) diagnostics from compute instances. Snowflake's global services operate on a Java runtime, and it's helpful for our engineers to look at JVM data to see what method calls are causing errors and even predict them ahead of time.

By the end of the internship, I added functionality to support different modes of collecting data, enabled publication of data from an entire cluster of compute instances at once, and concocted a SQL query to execute collection/publication procedures as a daemon. I wrote multithreaded code for the first time, put OOP design patterns to practice, and pushed my first bug to production that crashed existing collection processes (the classic intern mistake!) It was a lot of responsibility!

On my last day, my mentor and I had a lengthy chat about startup culture, which basically reaffirmed my preference for smaller companies. I appreciate the skills I've gained, but I still felt something was still missing...

<!--
1. specify different collection profile for an instance
2. publish on entire cluster
3. collect and compile stats for JVM data
-->

## Duolingo
Duolingo is a meme for the way it teaches languages, yet it was the best internship I've had. This was also my first in-person internship, marking the end of the pandemic in many ways for me. As soon as my term at Snowflake ended, I took an Amtrak from Boston to Maine for a quick vacation, then flew directly to Pittsburgh.

{{% blog-shortcode caption="Duolingo headquarters at night." file="https://i.ibb.co/T1ZT5gF/duolingo-hq.jpg" %}}

My first day, I realized that the **people were amazing here**. The full-timers and fellow interns I met boasted exceptional accomplishments, yet were humble. They felt genuinely committed to the mission even after a decade. It also helped that most of them were my age so it was easier to befriend coworkers compared to my previous companies.

I interned on the Generated Sessions team, which is responsible for building lessons into the main app. I was an Android developer and this was my first experience working in native mobile development. I began the internship making some minor bug fixes. My main project initially was adding the listen spell challenge, but the feature got scrapped by leadership after a couple of weeks!

We soon pivoted my project to be supporting voice input for translations as an alternative to keyboard input. Looking back, I'd say it was for the better. I enjoyed the new project more, had a hilarious time debugging speech issues, and the feature was shipped to 1+ million users and counting!

{{% blog-shortcode caption="Unfortunately, Android voice recognition still ain't perfect." file="https://i.ibb.co/rMC81Yg/duolingo-blooper.webp" %}}

Beyond the technical skills I gained, it was my best summer socially in a long time. I met up with old friends interning in Pittsburgh for the first time since the pandemic. Duolingo held its 10th anniversary party on my birthday, so I could actually drink overnight. Don't even mention all the cruises, bike tours, and <a href="https://www.tiktok.com/@xiaomanyc/video/7119913005378325803?is_from_webapp=1&sender_device=pc&web_id=7091898300404631086">that TikTok with xiaomanyc</a> I did.

{{% blog-shortcode caption="Duoversary concert by Carly Rae Jepsen!" file="https://i.ibb.co/dBXy561/duolingo-concert.jpg" %}}

From Duolingo, I realized I liked working on front-facing software usable by the common man. While I was receiving a haircut, my barber gave me feedback about the app as a user himself. This wasn't the case for all three of my previous companies, whose products were aimed towards people with technical backgrounds.

{{% blog-shortcode caption="Group photo at end of dinner cruise" file="https://i.ibb.co/HqVC4KN/duolingo-cruise.jpg" %}}

Overall, it was exciting to see Duolingo undergo its inflection point this summer. In just one summer, we grew headcount enough to move to a new office, rebranded Duolingo Plus to Super, opened the Math app to beta testing, and gained more users for Duolingo English Test by meeting with foreign dignitaries and admissions officers.

Duolingo was the closest thing to those "day in the life" videos of tech workers that I got recommended so often on YouTube. It's interesting to see how even though Duolingo and Snowflake are the same age, they ended up on widely divergent paths.

## Meta/Facebook

Technically speaking, it's my first FAANG. But unfettered growth from last year has its consequences, which I would see unfold over this season.

The fall began somberly with the stock decline, as recruiters announced return offers were being postponed. The handful of us starting realized that we were witnessing the end of an era.

{{% blog-shortcode caption="Rooftop view of the Meta Farley office." file="https://i.ibb.co/kqp7w9f/meta-office.jpg" %}}

Meta operated efficiently relative to its size -- **the "move fast" culture is still alive**, internal tooling was impressive, and Meta is a great place to grow as an engineer. The perks and benefits where extravagant, since I was put into a 1B1B in Chelsea (friends/family took huge advantage of this!) and the free food was quite good.

{{% blog-shortcode caption="Work-provided Meta Quest 2. Got motion sickness testing a few games!" file="https://i.ibb.co/r7HVmVW/meta-quest.jpg" %}}

Inspired by Sword Art Online, I interned on the Orion platform team. This team contributes to a low-level software framework powering the ~~Nervegear~~ Oculus headsets. Apart from the React starter apps I made during onboarding, most of my work was done in C++20. Since the team I worked on was quite nascent, it could be challenging finding support for my projects. For one project, I was tasked with migrating a ZIP file API from using buffers to using streams, and I remember debugging LibZip being particularly painful.

I learned a lot about modern C++ and concurrency during my time here. I would have never seen move constructors, coroutines, and custom threading libraries mentioned in Northeastern's computer systems course!

{{% blog-shortcode caption="Some Nigerian food in Midtown East with Ethan, Howard, and Victor." file="https://i.ibb.co/P5YkNvt/meta-social.jpg" %}}

As usual with hopping from city to city each semester, I formed a new friend group as well. In New York, it mainly consisted of interns at Meta and other big tech companies with off-season internships. The MTA made it easy to visit all of the "main" attractions, but in practice we just wasted a crap-ton of money eating out at Italian restaurants.

The [massive layoffs](https://about.fb.com/news/2022/11/mark-zuckerberg-layoff-message-to-employees/) in November dashed any remaining hopes of return offers. Not even Greatly Exceeds Expectations (GE) interns were getting them. In the days before, I inadvertently eavesdropped on anxious gossip from employees in the elevators and in the cafeterias. The day of layoffs, we were instructed to work from home as the offices closed - although I'm certain no one was.

Meta remains my second favorite company after Duolingo, and a Meets All Expectations (ME) rating concluded my spree of internships.

---

After another year of working in industry, my greatest takeaways were in learning how to prioritize and communicate. Not every meeting needs to be attended, and the ability to explain your blockers in simple words is important for other engineers to be willing to help you.

Read the 2023 finale [[here]](../finale-2023)