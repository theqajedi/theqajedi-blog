+++
date = 2020-09-18T00:51:20+02:00
title = "First post, so obligated to start from the depths of QA 📚"
description = "The post demonstrates Twemoji support"
series = ["Theme", "Hugo"]
+++
This is my first blog after a decade or so, most likely you are going to spot some grammar or spelling mistakes or even unformatted images. Completely open to feedback. 🐼      

So I have tried to summarise my limited experience in the last 4+ years as a QA (although my title was a tester, I like to use the term QA. I will explain why later)
in this blog. Most of it is by personally experiencing the magic of QA working first hand, many of it is by other's experiences, and of course, the rest is from www, an ocean of knowledge among other things. 😁

## QA Origin
![QA](/Quality-Assurance.png)

[Image source](http://wyldco.com/why-quality-assurance-matters-to-every-site/)

Most of you are already aware of Q.A. topics from either the industrial practices or the more recent (I'm being generous here 😬) adoption in the world of IT (yeah, don't be surprised!). Many of you are probably already using tools and practices to enhance the overall quality of software products, maybe still not knowing its origin or evolution. So I am going to briefly 
give you an introduction to the actual legends of QA and discuss its significance in SDLC.

Let's go back in time for its origins. There was a time when Japan was known for its poor quality products. 
Surprised? It was not too long ago, post-WW2 in the 1950s when the country was still in the control of the allied forces. General Douglas MacArthur was the Supreme Commander for the Allied Powers in Japan, who was handed the task to rebuild war-torn Japan. He appointed two American engineers W. Edwards Deming and Joseph Juran to spearhead the industry upbringing especially helping them adopting the quality practices from the US. But ironically, US businesses 
failed to adopt the advances in the field of QA whereas the Japanese took it to a whole new level and it literally took them decades to
realize and fix their mistakes, more on that later.

Deming was an engineer, statistician, professor, author who is mostly known for Plan-Do-Study-Act cycle PDSA, his 14 Points, and Seven Deadly Diseases.
Juran was a Romanian-American engineer, an evangelist of quality and quality management mostly known for authoring a number
of books on quality including the Juran trilogy. Deming more focused on the statistical process control whereas Juran focused on managing quality.
Enough of history you say? Aye, so there was already the concept of Quality Control a.k.a QC from the US, which basically involved concepts of inspection and sampling to remove defective products. But this only focused on the output, not the input nor the people responsible for the process also not the attitude towards it. During that time QA was groundbreaking which focused on the process instead of the output i.e move left of it, look at the input, process, people, etc. Sounds simple right? probably once an earth-shattering discovery is the way of life now
and we don't even find it fascinating. Such is the power of thinking beyond what meets the eye, which many of us fail to see most of the time.
Enough of the gyaan you say? Alright, so PDSA basically meant you plan a task, do it, study the outcome, factors affecting the outcome, and take required actions
to correct the mistakes as to not repeat it. Sounds familiar? Yes, this is **Agile** in a nutshell.

![PDSA](/pdsa.png)

[Image source](https://www.health.state.mn.us/communities/practice/resources/phqitoolbox/pdsa.html)

Making use of such quality concepts, from 1950-70, Japanese companies totally turned around the quality of their products.
By 1960, Japan was the second-largest economy in the world. That was some turnaround within a short span of a decade.
Companies like Sony, Toyota made use of these principles, improvised on it and the rest is history as you know it.
Total quality management, Lean manufacturing, Just in time manufacturing, Kanban, Kaizen are all practices that originated from 
Japan.

So Wikipedia defines QA as: 
_"It is the systematic measurement, comparison with a standard, monitoring of processes and an associated feedback loop that confers error prevention."_
Which is nothing but focusing on the process, people, monitoring, feedback, and prevention of defects. I guess that's enough history for today.
Let's come back to COVID-19 I mean 2020.

## Why and who
![Team_work](/team_work.jpg)

[Image source](https://tallyfy.com/guides/continuous-improvement/)

### Shift left
Sooner the bugs are detected, less costly they are to fix it. I suppose there is no argument with that.
There is no need to wait until the end of development to test a piece of code. (If you are by any chance doing this, please for the 
love of cheesus, review your process!) A simple example is code coverage of unit tests, static code analysis, etc.

### Everyone is responsible for the quality 
Everyone as part of an SDLC has some kind of deliverable and hence there can be some kind of 
testing, analysis, verification, validation that can be performed.
* Product owner: Use mocks and find possible UX defects etc
* Architect: Making sure to stick to good design patterns, evolutionary architecture, conforming to standards, etc.
* Developer: Code coverage with tests, code analysis, etc.
* Testers : Functional, non-functional UI, E2E tests etc.
As I already mentioned, the sooner a bug is discovered in SDLC, the easier and cheaper it is to correct it, So everyone can influence 
the quality of the product both reactively and proactively.

### It’s a continuous process 
Quality is not a one-time activity. It is a continuous process hence continuous integration, continuous deployments
matter. Since SDLC has constant deliverables, iterations, quality becomes coherent.

### Quality is not an act! It is a habit!
A culture has to be developed, mindset is important. Tools and processes are secondary. Collaboration and communication
about areas of influence and shared notion of quality is the need of the hour. Taking responsibility for our deliverables not as individuals but as a team.
And the magic ingredient which connects all these is a sense of ownership.

Psst, if you already didn't know, there are ISO standards for software quality.

## Difference between a Tester and QA
![QA_Testing](/qa_testing.jpg)

[Image source](https://zeeshanasgharr.wordpress.com/2013/09/11/software-quality-assurance-engineer-vs-software-tester/)

Two kinds, either there are people who know the difference or there are people who just use it interchangeably. And the latter
ones are higher. So I hope after reading this article, one will be able to make a clear distinction between the two.

It's essentially the difference between QC and QA that we discussed in the beginning. Testing is product-oriented i.e exploring a system to find defects. QA is trying to prevent bugs in the SDLC process i.e process-oriented plus the role of the testing.
Testing is a corrective activity whereas QA is preventive. 

Companies tend to use the titles interchangeably. Test engineers, test analysts, QA, Automation tester, or the more recent Software Development Engineer in Test SDET.
While I don't have a problem with that, I just want people to look at each of these titles through the lens of an actual QA. Irrespective of the designation it's the 
responsibility of the person to be reactive as well as proactive.

## Best practices
![QA_Best_Practices](/QA_Best_Practices.jpg)

[Image source](https://www.cybercoders.com/insights/qa-best-practices-for-software-development/)

I'm only going to briefly and quickly explain some key topics. The first post is already getting long. 😄 
### Automation and Continuous Integration
Automation is vital as it makes feedback faster. Ex. CI, pipelines, etc. Build jobs, run tests, deploy, run more tests, and gather metrics. Ex. Jenkins, Azure DevOps (previously known as Visual Studio Team Foundation Server), etc are the tools that can help.

### Coding practices
Adhere to best practices, talking about coding practices, and not mentioning uncle Bob here doesn't justify the topic.
The Clean-code book is a great well of knowledge that one cannot have enough of. Following such practices not only makes your code easy to read, or evolve but also makes writing tests easier. Additionally, static code analysis, quality gates, code coverage
tools help in finding potential bugs beforehand. Ex. Sonar, IDE code analysis, etc.

### Test early, test often
Shift left approach. Have a check right from the requirement gathering phase. It could be as simple as a PO or PM talking
to QA's for potential gaps or scope creep in requirements. Unit tests, integration tests, E2E tests, UI tests all help in building confidence in the deliverables which translates to less and fewer bugs discovery in production.

### Collaboration and communication
As already mentioned, everyone is responsible for quality. Each person in a team has a specific area for influencing quality.
So it becomes essential for everyone to collaborate, be open for trying new things, make quality inherent with whatever you do.
Don't just brush it off as a job for later or for a tester. Agile methodologies support you with tools for such practices as well. 
Quick feedback loops, QA as an integral part of the scrum team, etc.

## Tools and techniques
There are a lot of tools and techniques which can be adopted at all possible stages of an SDLC. I have just put forth a basic setup which is a kind of bare minimum requirement for any project. These are based on my own usage so far.

### Maven plugins – JaCoCo
Could be as simple as running a code coverage tool during the build and maintaining reports.
An example is setting a threshold for the code coverage, it does not matter the %. Maybe 75 or 85 or I have even seen projects
with 95%+ test coverage. And this is actual coverage mind you, not writing tests for just increasing the percentage.
Highly motivated teams who care for the quality of the deliverables.
JaCoCo is one such maven plugin to assess the code coverage.

### Quality gates – SonarQube
Static code analysis, quality gates are nothing but setting threshold measures for quality metrics. Ex. technical debt, 
blocker issues, probable memory leakage warnings, etc. If the code has gained a certain limit of any such metric, reject build automatically.
Can be even used earlier in IDE itself to find potential problems. 

### Build servers – Jenkins, Azure DevOps
Build servers can be used for CI/CD. All measures can be defined, customized. Merge jobs can be defined which controls effectively
what gets merged to master. All the diff tests can be executed as well and therefore you have quick feedback. Provided build times
are less. (yes, I have worked with legacy behemoths which took 1 hour just for the build) 

### Mandatory tests at different stages of development
 Testing at the end of the development cycle takes too much time and also the bugs found are very costly to fix, need more effort.
 So why not do as many tests as possible at earlier stages.

![shift-left-testing-pyramid](/shift-left-testing-pyramid.jpg)

[Image source](https://qodestack.com/adopting-shift-left-approach/)

The significance of the pyramid is that the unit tests are at the bottom i.e form the foundation. Foundation should always be strong
so the number of tests should also be high. And unit tests are faster, more reliable, and provide quick feedback. As we move from bottom to top, 
the number of tests should be less. They become more time consuming and harder to maintain. If you have nothing but UI tests in your test suite, 
only the flying 🍝 monster can save you. Amen! 
* Unit tests - Usually written by developers, fast, reliable, easy to write. (depending on who you ask! if best practices are not followed in code then good luck writing tests)
* API tests - Could be written by developers or QA's. Could be mocked or deployed services. To verify the interfaces of applications. CDC is very handy if the development
is split between teams/geographies.
* Integration tests - According to ISTQB, there are two different kinds, component integration test for between integrated components 
and system integration tests between systems or services.
* UI and E2E tests - Could be written by FE developers or QA's. To verify the entire user flow.
* Exploratory tests - Manual tests to bring in more confidence in quality. Done depending on the critical flows, 3rd party systems, etc.

Apart from these, there are non-functional tests like performance, security, etc which have to be done based on the type of application usage,
user-group, etc. Or performed during certain releases to production. The definitions of tests might vary from that of your company practice, 
it's totally fine as long as the team is on a common consensus.

### Active retrospection
Agile already facilitates retrospection, make use of them to discuss the root causes of not only impediments but also bugs, bottlenecks or delays. Try to develop an action plan
and work on them. And update the team with the progress of the action plans.

---------

To summarise, everyone in the team should don the hat of QA and ascertain that quality is **everyone’s** responsibility. 

This was just a limited view of QA things from my perspective, I can be completely wrong as well. Then there's more room for reflecting and improving.
But also I'm open to the wisdom of any kind, shape, or size. There is something new to learn every day, so keep your eyes, ears, and brain open but don't forget to filter out nonsense, which is abundant. 🙂

If you didn't already notice, the theme switching is broken ATM on the site. I wonder if only QA's were the ones who noticed it already since they are used to trying all the possible flows or functions. Anyway, I'm no FE expert so will soon tackle it when I find some time.

Until next time, may the force be with ya'll.  
Thank you and sorry for the long first post, here's a 🥔!

---