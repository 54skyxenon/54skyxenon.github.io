---
title: "Co-op Quest: 2021"
date: 2021-11-19
draft: true
---

<p align="center">
  <img style="max-width: 90%; border-radius: 3%;" src="/images/mw-msft-2021.png" />
</p>

Northeastern has a co-op program where upperclassmen spend 4-8 months working full-time instead of taking classes for a semester, this is how it went during my sophomore year. Some people opt for one long co-op, some break it up into two (me), and some even three. 

I interned as a software engineer at [MathWorks](https://www.mathworks.com/) working on the MATLAB engine, followed by [Microsoft](https://www.microsoft.com/en-us/) working on the Azure cloud computing platform, respectively.

## The Application Process
> Applied: **320**
> 
> Responses: **57**
> 
> Withdrawn: **15**
> 
> Offers: **3**

I learned about this the hard way last year, where I couldn't find an internship at all.

Embarking on a job hunt with no relevant experience *really* sucks, as most employers want prior experience even for internships in this day and age. A pandemic, a non-target school, and not being a junior doesn't really help either. But once you can break this Catch-22, it gets way easier.

For summer internships, be prepared to apply as soon as late July the previous year, when the current interns are finishing up. For NEU students, if you are just interested in a co-op, you can start applying once the semester starts. I do think it is better to start applying in the summer however just because you can devote more free time to interviewing before classes start -- I personally use the [PittCSC](https://github.com/pittcsc/Summer2022-Internships) GitHub repository to find job listings.

**If I could summarize what I learned in one sentence, that would be to do projects to pass the resume screen, then do [LeetCode](https://leetcode.com/) to pass the most common type of interview.** Apply with referrals if possible (helped me get an offer)! Many articles on Google can explain how to do those better than I can, so I won't go into detail here. One resource I recommend is the [Tech Interview Handbook](https://techinterviewhandbook.org/).

I got ghosted *a lot*, but from where I didn't, the first step to many applications were online assessments (OAs). These were a mix of automated algorithmic HackerRank challenges and behavioral HireVue prompts. I failed a lot of these my freshman year but found a higher success rate after intensive LeetCoding during quarantine and making a spreadsheet of answers to frequently asked behavioral questions.

The phone screens and final rounds that followed were actually easier. I enjoyed talking to a *human* and problem-solving in real-time after I had learned the [design recipe](https://htdp.org/2018-01-06/Book/part_preface.html#part._sec~3asystematic-design) my freshman year.

In early October, I was exhausted from interviewing along with a intense course load. I signed my two offers and withdrew from my remaining interviews to focus on classes, even as other companies were ramping up their interview processes.

## MathWorks
They make MATLAB and Simulink, popular scientific computing apps used in academia and government contractors.

If there's one thing I could say about MathWorks, the first that comes to mind is a **strong emphasis on work-life balance**. Many engineers I worked with were offline on Teams by 5 PM and it felt very weird to continue working after that. It's a good environment to raise a family in and employee tenure tended to be high.

Since I was a spring intern, the other interns and I could afford more attention from our mentors and get to know each other better (compared to a massive summer cohort). We had Friday bonding sessions where we'd play online games and teach each other something new about software engineering!

The first project I was assigned was adding font properties to MATLAB App Designer, a tool for building Desktop GUIs in MATLAB! It's analogous to the Swing framework in Java. Since the last time I used MATLAB was in 2018 for a machine learning course I had all but forgotten, my first task was to make a small app to refamiliarize myself with the language. What followed was an intense period of:

1. Requirements Gathering
2. Drafting an API Design
3. Talking With Design Reviewers
4. Coding
5. Code Reviews & Testing
6. Code Integration

The codebase itself conformed to a [Model-View-Controller](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) architecture, and the tech stack consisted of C++, MATLAB, and JavaScript. All that suffering in Object-Oriented Design came to use! I remember some days struggling trying to debug vast C++ files, so I must thank my mentor, manager, and coworkers for being supportive and willing to offer their help. I finished this project with around 3-4 weeks to spare and I could take on another.

My second project exhibited a stark contrast to my first: I took on a new mentor in a completely different engineering division and the focus of my project would not be software development. Instead, it would be a reverse-engineering research project: I would analyze usage of the OpenGL Graphics library on MacOS machines. Apple is infamous for introducing breaking changes in its new products, so if Apple chose to deprecate OpenGL in a future MacOS release, then it would break MATLAB as the application relies heavily on OpenGL. Gathering usage statistics would help MathWorks predict when exactly this would happen in the future.

How I could approach this analysis was much more open-ended as I was not working on a customer-facing product, so I opted to exercise my Python scripting skills. I wrote a script to iterate over binaries on older Intel-based Macs and newer M1-Chip Macs, aggregating OpenGL utilization statistics across these binaries and preparing a presentation using this data as a final deliverable. 

Both of my mentors were happy with my work, and my time in MathWorks ended on a good note.

## Microsoft
They need no introduction, but overall I didn't have the best experience. Earlier in November the previous year, the in-person program was cancelled. I lived with my parents back in Los Angeles instead of with other interns at Microsoft's sprawling Redmond headquarters. Unfortunately, not much of [this](https://medium.com/@techie4good/microsoft-has-the-best-internship-of-all-time-633f7c251773).

My first impression was that Microsoft was **complex and bureaucratic**. There are four main engineering divisions and too many different teams under each of them for me to comprehend, even amongst my own organization. While Microsoft does have a reputation in tech for good work-life balance, this is not true if you are in an Azure team.

There were no shortage of intern activities -- at times it could be overwhelming meeting many new people and being exposed to so much talent. There are signature events like [Puzzle Day](https://puzzlehunt.azurewebsites.net/pd2021/play) that you can't miss out on.

My intern project was to add Active Directory authentication to a service called Azure Database for PostgreSQL -- Flexible Server. What this means is that instead of authenticating on a PostgreSQL server with an email and password like usual, you could authenticate with your Microsoft organization account. It's like logging into a website using Facebook or Google instead of just a normal email. The scale of this project was a sizeable increase from my time at MathWorks, since instead of targeting a subset of MATLAB users, I was targeting billion-dollar enterprises that had contracts with Azure.

It took a _long long_ time to onboard, in fact nearly **25%** of the time of my internship was spent trying to do so! Figuring out what each build script did, waiting for Visual Studio to load, installing the necessary tools to debug C#, and even dealing with general Windows issues were arduous. A jumbled internal wiki with periodically outdated information did not help. On the bright side, at least I learned a bunch of cloud computing concepts and even some automata theory sifting through all that documentation!

Thankfully, I had an amazing intern partner during this time period I could bounce off ideas and resolve errors with (shoutout to Morgan)! Slowly, we began to understand each element of the codebase and its purpose. During this process, we would engage in daily standups with our mentors, gradually working towards an acceptable REST API design for endpoints that would add new Azure Active Directory users to a Postgres instance when pinged. Working with a massive codebase, we made progress through experimenting with minimal "Hello World" functions that gave us insight on how the REST API workflow would behave.

I didn't start fully coding until the last 4 weeks or so, but I did move fast when doing so. Pulling a few late-nighters, I barely managed to finish my project on time and scraped by with a return offer I was unenthusiastic about.

---

My biggest takeaway from working in industry for the first time is that coding never takes long if you carefully plan out your thoughts, which is reflected in the coding interview as well. The resulting code should be precise and unverbose.

_2022 Edition coming soon!_
<!-- Read the 2022 sequel [here](../recruiting-2022)... -->