---
title: "Co-op Duels: 2022"
date: 2022-04-16
draft: false
---
<!-- https://ibb.co/album/Fgq2gQ -->
# Co-op Duels: 2022
**<i>Last modified on: 2022-09-30</i>**
Read the 2021 prequel [[here]](../recruiting-2021)

{{% blog-shortcode caption="Recruiting sucked the soul out of me late-September to mid-October" file="https://i.ibb.co/BwBC3dK/snow-duol-fb-2022.png" %}}
</p>

Northeastern has a co-op program where upperclassmen spend 4-8 months working full-time instead of taking classes for a semester, here's how it went during my junior year.

I interned as a software engineer at [Snowflake](https://www.snowflake.com/) in Boston working on diagnostics reporting, followed by [Duolingo](https://www.duolingo.com) in Pittsburgh working on speech recognition, followed by [Meta](https://about.facebook.com/meta/) in NYC working on augmented reality headsets.

## The Application Process
> Applied: **104**
> 
> Responses: **44**
> 
> Withdrawn: **8**
> 
> Offers: **7**

Was it really that time of the year again? Thankfully, I heard back from a lot more companies this cycle with Microsoft and ETH Zurich on my resume. Being a junior also *formally* qualified me for a lot more summer internship positions. This year, I wanted to gain experience working for smaller and more fast-paced companies, so naturally I would interview with several unicorns and trading firms.

These smaller yet desirable set of companies could afford to be picky with their candidates. There was a noticeable increase in difficulty, variety, length, and thoroughness in the questions I was asked compared to normal FAANG-type LeetCode interviews. Now that I had experience, I was also expected to articulate on my past internships. At the same time, I thought these interviews were more enjoyable as they were more interactive.

For example, Stripe asked me to add a new codebase feature involving HTTP REST calls and JSON parsing as a part of their onsite. Citadel asked me some gnarly probability and object-oriented design brainteasers. Duolingo asked a data structures + algorithms design question with a relentless barrage of followups.

I found that the best way to improve at interviews was to... just interview. **If I could go back, I would change my practice routine to invest more time on non-algorithmic interviews** -- reading large codebases, operating systems knowledge, object-oriented programming, system design, and mathematics (probability) fundamentals, just to name a few.

The logistics of this application cycle were weird to say the least. I started applying in late June-early August when I was still in the US, but most of my onsites would occur late September to mid-October. During this time, I was simultaneously studying abroad in Switzerland, which is 6 hours ahead of New York time and 9 hours ahead of Bay Area time. But that actually made things more convenient, as I would have my classes in the morning/afternoon and interviews in the evening (+ I'm a night owl 🌙). I'm fortunate that companies are still using Zoom for remote interviews and that my roommates put up with hearing the same self-introduction day after day.

{{% blog-shortcode caption="Recruiting sucked the soul out of me late-September to mid-October" file="https://i.ibb.co/SKNQcS7/recruiting-state.png" %}}

I received my first offer in early October from Duolingo (whose onsite I gave *right* before my flight to Switzerland)! That took care of Summer 2022, but my co-op cycle (Spring 2022) was harder to deal with because ETH Zurich holds exams up until February of the next year. Many companies I received offers from could not accommodate such a start date, and ETH declined my request to take these exams earlier. 

My first instinct was to change my co-op cycle to Fall 2022. Around then, I had received an offer from Meta following my hackathon in Prague that was about to expire, which I moved to the fall. Simply too good to pass up. But that still left the awkward gap of Spring 2022 - what was I going to do up until the summer? I signed up for some part-time classes at Northeastern so I could graduate as intended, but I kept interviewing to find a solution.

After a very long hiatus in mid-November, Snowflake resumed its hiring process and invited me to a phone screen. It almost seemed too good to be true, but they were fast to schedule interviews and I got an offer just after a week. Not only that, they were willing to accommodate a late February start date and end before my summer internship began, and it was all fully remote so I could keep my part-time classes as well! 

After 5 months of interviewing, everything eventually fell into place. I would be interning year-round!

## Snowflake
People know of Snowflake because they recently had the [largest software IPO](https://www.linkedin.com/news/story/biggest-software-ipo-ever-5301906/) in history so far. Even now, I have no simple description of what Snowflake does, besides "database stuff". I enjoyed Snowflake more than Microsoft because there's less bureaucracy in a unicorn. By the end though, I knew cloud computing wasn't for me.

Snowflake was an intense place to work at with lots of opportunity, nearing its 10th anniversary and embracing an influx of **top talent from Silicon Valley veterans**. I had the privilege of being mentored by multiple senior/principal software engineers. My work-life balance was relatively good, and I was able to juggle part-time classes well at Northeastern while working remotely.

{{% blog-shortcode caption="There's also a Boston office in the financial district I sometimes walked to with my friends for free snacks. The route had a good dim sum restaurant along the way for brunch!" file="https://i.ibb.co/tztkLW4/snowflake-1.png" %}}

I interned on the Service Infrastructure team. My project was to improve how we collect and publish Java Virtual Machine (JVM) diagnostics from compute instances. Snowflake's global services operate on a Java runtime, and it's helpful for our engineers to look at JVM data to see what method calls are causing errors and even predict them ahead of time.

By the end of the internship, I added functionality to support different modes of collecting data, enabled publication of data from an entire cluster of compute instances at once, and concocted a SQL query to execute collection/publication procedures as a daemon. I wrote multithreaded code for the first time, put OOP design patterns to practice, and pushed my first bug to production that crashed existing collection processes (the classic intern mistake!) It was a lot of responsibility!

On my last day, I remember my mentor and I having a lengthy chat about startup culture, which basically reaffirmed my preference for smaller companies. I appreciate the skills I've gained, but I still felt something was still missing...

<!--
1. specify different collection profile for an instance
2. publish on entire cluster
3. collect and compile stats for JVM data
-->

## Duolingo
Duolingo is a meme for the way it teaches languages, yet it was the best internship I've had. This was also my first in-person internship, marking the end of the pandemic in many ways for me. 

{{% blog-shortcode caption="Duolingo headquarters at night." file="https://i.ibb.co/T1ZT5gF/duolingo-hq.jpg" %}}

As soon as my first day, I realized that the **culture was amazing here**. The full-timers and fellow interns I met boasted exceptional accomplishments, yet were humble. People felt genuinely committed to the mission even after a decade. It also helped that most people were my age so it was easier to befriend coworkers compared to my previous companies.

I interned on the Generated Sessions team, which is responsible for building lessons into the main app. I was an Android developer and this was my first experience working in native mobile development. 

I began the internship making some minor bug fixes as starter tasks. My main project initially was adding the listen spell challenge, but the feature got scrapped by leadership after a couple of weeks of me working on the feature with my mentor. We soon pivoted my project to be adding voice input for translation challenges as an alternative to keyboard input. Looking back, I'd say it was for the better as I enjoyed the new project more and the feature was shipped to 1+ million users by the time I left.

Beyond the technical skills I gained, it was my best summer socially in a long time. I met some of my old friends interning in Pittsburgh for the first time since the pandemic began. Duolingo held its 10th anniversary party on my birthday, so I could freely drink overnight. And that doesn't even mention all the cruises and bike tours around Pittsburgh we had.

During my time at Duolingo, I realized I liked working on front-facing software that was usable by the common man. I remember that while I was receiving a haircut, my barber gave me feedback about the app as a user himself. This wasn't the case for all three of my previous companies, whose products were aimed towards people with technical backgrounds.

Duolingo was the closest thing to those "day in the life" videos of tech workers that I got recommended so often on YouTube. It's interesting to see how even though Duolingo and Snowflake are the same age, they ended up on widely divergent paths.

## Meta/Facebook

**More content coming soon!**

*2023 new grad finale coming eventually!*