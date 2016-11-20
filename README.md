<h2>What is ProTechMe?</h2>

ProTechMe is a chatbot that collects protective order info quickly and efficiently in Harris County, TX, so the user can take a pdf and present to the district attorney or legal aid office (in person or email) without time consuming guidance. 

<h2>Why Use It?</h2>
- Anyone can come onto the site and have a conversation anytime. 
- Makes compilation of info easy for both legal aid lawyer and client.
- Legal aid lawyers can now use their expertise for tasks that require their legal skills, as opposed to tasks that can be automated or done by nonlawyers. 
- Since it’s open source, anyone can replicate the chatbot in cities beyond Harris County

<h2>How We Made It</h2>

First, we mapped it out on [Coggle](https://coggle.it/diagram/581e2e29bca2b058492a7baa/70969a69244f843e388759825bbc6e131265e358840e5c29702c270280d407ae), a freeware mind-mapping web application. Like other mind-mapping software, Coggle produces hierarchically structured documents, like a branching tree.

We took the questions from the Texas Attorney General’s [Protective Order Kit](https://texasattorneygeneral.gov/files/cvs/protectivekit_dv.pdf).

It helped us to better understand the flow of  questions and answers and determine in what order they should fall. 

We created the chabot using [motion.ai](https://www.motion.ai/), which lacks several of problems of various others (no AIML required, no dependence on Facebook, deployable to the web but not public in a way that would endanger user privacy by default, free to start, plays nice with JavaScript, very flexible).

<b>[DEMO HERE](https://techforjustice.github.io/protechme/)</b>

<h2>When will the chatbot be ready for the public?</h2>
- Complete branching in motion.ai 
- Make it so a pdf can be formed with the responses, and then emailed to the user so they can take to their lawyer or DA office (or to their lawyer/DA office directly).

<h3><a href="https://github.com/TechForJustice/protechme/wiki">More Info</a></h3>
