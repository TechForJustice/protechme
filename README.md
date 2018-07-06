<h2>What is ProTechMe?</h2>

ProTechMe is a chatbot that collects protective order info quickly and efficiently in New Mexico, so the user can take a pdf and present to the district attorney or legal aid office (in person or email) without time consuming guidance. 

Originally, ProTechMe was built in Harris County, Texas. See the demo [here](https://techforjustice.github.io/protechme/).

<h2>Why Use It?</h2>
- Anyone can come onto the site and have a conversation anytime. 
- Makes compilation of info easy for both legal aid lawyer and client.
- Legal aid lawyers can now use their expertise for tasks that require their legal skills, as opposed to tasks that can be automated or done by nonlawyers. 
- Since it’s open source, anyone can replicate the chatbot.

<h2>How We Made It</h2>

First, we mapped it out on Coggle, a freeware mind-mapping web application. Like other mind-mapping software, Coggle produces hierarchically structured documents, like a branching tree.

We took the questions from the New Mexico Courts [Website](https://www.nmcourts.gov/Self-Help/domestic-violence-forms.aspx). See this [page](https://domesticviolence.nmcourts.gov/faq-s.aspx) also.

It helped us to better understand the flow of  questions and answers and determine in what order they should fall. 

We created the chatbot using [motion.ai](https://www.motion.ai/), which lacks several of problems of various others (no AIML required, no dependence on Facebook, deployable to the web but not public in a way that would endanger user privacy by default, free to start, plays nice with JavaScript, very flexible).

Pdf conversion was successful, see process and code [here](https://github.com/TechForJustice/protechmepdfconversion). 

<h2>Want one for your city or state?</h2>

Join other collaborators [here](https://justicehub.tools/protechme). 

