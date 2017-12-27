# Five Types of Questions You'll Encounter

As a Technical Coach, you’ll be getting all sorts of question from all sorts of different students. It can be overwhelming to have to constantly switch contexts (in terms of the student, the topic, and the question). Broadly speaking, the questions will fall into the four categories listed below. For each category of question, we’ve given examples as well as specific strategies you can use to resolve them.

## Questions Types and Resolutions at a Glance

### [**Question Type**: Learn/IDE/Workflow Issue ](https://github.com/flatiron-labs/learn-support/blob/master/common-learn-questions.md#1-learnideworkflow-issues)   
**What is it**: Problems with the platform and workflow (lights/IDE/empty cloned directory/billing/etc)  
**Resolution**: Solve the problem for the student or if they can keep moving on in the curriculum, tell them to just keep going. Report a bug if needed, but get the student to move on if possible.

### [**Question Type**: Lab tests aren’t running](https://github.com/flatiron-labs/learn-support/blob/master/common-learn-questions.md#2-lab-tests-dont-run)   
**What is it**: Environment or syntax errors or program breaks when running tests  
**Resolution**: For environment errors, solve the problem for the student. For syntax errors, use teaching strategies to get students to debug themselves.

### [**Question Type**: Lab tests run but students are getting failures](https://github.com/flatiron-labs/learn-support/blob/master/common-learn-questions.md#3-tests-run-but-student-gets-error-messages-they-dont-know-how-to-fix)  
**What is it**: Pretty self-explanatory from above title  
**Resolution**: Use the Socratic method and other teaching strategies to get students to debug the failures.   

### [**Question Type**: Conceptual](https://github.com/flatiron-labs/learn-support/blob/master/common-learn-questions.md#4-conceptual-questions)   
**What is it**: Students have trouble with larger concepts beyond a test failure  
**Resolution**: Document this in the student’s admin page and escalate if the same issue has already been noted. You can try and solve the student’s issue through a very comprehensive walkthrough of the concept.   


### [**Question Type**: Unsupported](https://github.com/flatiron-labs/learn-support/blob/master/common-learn-questions.md#5-unsupported)
**What is it**: We won't support these types of questions. Primarily these will be questions students have on assessments
**Resolution**: Be kind and tell them that we can't support the question, if it's an assessment, let them know to schedule a 1:1 with a portfolio support coach and hand out this [link](https://theflatironschool.typeform.com/to/UUhrc7)

---

## 1) Learn/IDE/Workflow Issues

* These questions are not related to the specific content of the lesson but are usually issues students are having that are preventing them from moving forward. With these questions, the goal for you as a Technical Coach is to get students through these questions as quickly as possible so that they can get to working on lessons.
* For these questions, don’t worry about using the Socratic method or making it a learning experience. In many cases, you’ll be telling students what exactly to do. Sometimes at the end you can send them links or resources that might be helpful in giving them a better understanding of the problem or for them to use as a reference in the future.
* In some cases, you might not be able to solve the problem for them but if they’re still able to progress in the curriculum content, then you will want to tell them to move on.

**Common Examples**
- Lights do not turn green
- `learn open` and `learn submit` do not work
- The lesson directory is empty
- When submitting lessons, the student is asked to enter their username and password

We'll add more of these common problems as well as resolutions for these problems. Since they are very specific, each question will usually have its own strategy. For now, let’s take one of the above examples and lay out the resolution.

### Example: Students have trouble getting their lights to turn green when they fork a lab.
*  First ask the student to **refresh the page**. This sounds simple but in many cases, it does the trick.
* If that doesn’t work, then walk the student through going to Github, deleting their fork of the lab, then having them re-fork the lab.
*  **If it doesn’t work after the above actions, then tell students that they should move on to the next lesson.** Tell the student that we will have the lights turn green for them on our end. Use the Report a Bug button in /expert-chat to report a Lights issue.

>Note: If a student is having an issue with the Test light. Pull down their code and run it locally to make sure their tests are ACTUALLY passing.

#### When Lights NEED to be Escalated

Non-working light in the Welcome Track will prevent completion of the welcome track which in turn, prevents new tracks being added to the student. Take a look at the troubleshooting steps for ['Learn IDE authentication light is broken'](https://github.com/flatiron-labs/learn-support/blob/master/learn-ide.md#authentication-light-did-not-turn-on) if that's the issue you're running into. If that does not solve the problem, you'll need to escalate issues in this track.

## 2) Lab tests don't run

![tests dont run](http://i.giphy.com/qvSGXu0VdKMBa.gif "Tests dont run")

* Student isn’t at the point where they are able to run their tests and when they try, they get errors or their program breaks.
* These errors are usually either environment issues or they can be syntax issues.

### Strategies for Resolution

*  If environment issues, then you should take a few minutes and investigate and see if you understand what the problem is. If you do, then tell the student first, in one or two sentences, what the error is. Then after that tell the student that you will walk them through the steps to fix if it’s short, or if it feels longer, you can do it for them over screen share.
    - For example, if it’s an issue with their gems and they need to run `bundle install` then tell them explicitly what the problem is and then say, ‘Ok here are the steps to fix it and we’ll see what happens’
    - Then walk them through the commands. Then, depending on how long the process took, end this with a debrief of what you just did.
    - Send any helpful links or resources that the student can use as a reference.
* If this is a syntax error and you know that it’s something that the student did wrong with their code, then read through the error. Then ask the student if they know what this error means. If the student doesn’t know within three questions of you asking, then point it out specifically. Then tell them to look through their code and see if they are missing anything and then have them re-run it. If after 10 minutes of this, they’re still stuck, then have them ask you again. At this point, you can provide them with the answer. A lot of times the error will tell you what line has a syntax issue. Make sure you point this out to the student and show them how you are solving it, so they can replicate your technique! *(Example: running a chunk of problem code in IRB or Chrome console)*.

## 3) Tests run but student gets error messages they don’t know how to fix.

![tests fail](http://i.giphy.com/xT8qB2HYA1vVSxooSY.gif "Tests fail")

Great, everything is working! But students are confused about the code. This is where the actual learning can happen. And as a Technical Coach, you will use a variety of strategies to get students to the point where they know what they need to do to get their tests to pass. Some common questions will revolve around:

- Student doesn’t know why their tests aren’t passing
- Student doesn’t understand what the error message means
- Student doesn’t know what the test requires
- Student isn’t sure what the next step in the debugging process is

### Strategies for Resolution

* Have the students read their error message(s)
* Depending on the length of the code, you may also just want them to post the code around the specific lines where the error is.
* In any event, the goal is that you need to know before you start troubleshooting with the student, what the problem is that the student is having.
* Once you know what that problem is, then this is where you start using the Socratic method to get them to figure out what to do correct.
* The easiest way to start is by saying, “Ok, decode that error message for me. What does it say?”
    - Walking students through their error message: Have the student walk you through the specific steps slowly and reinforce with a simple “yes” or “good” each time that they’re explaining things correctly. At the point of the error, you should point out that what they’re explaining or doing isn’t correct but don’t give them the answer. Instead see if they can self-correct. If they have trouble, then walk them specifically through the different parts of the error message and decode it for them. At the end of this, have them repeat the meaning of the error message to you.

    - Walking students through their code: Then go to their code, and now that they know what the error message is, ask them first if they could see what's wrong. Follow the same steps above to see if they can self-correct first. And if they don’t see what’s wrong, then ask what they need to do to get the error to pass. They may not know the specific step, but see if you can get to a general understanding of the issue.

    - Google: At this point if they can’t solve it and if it’s a simple solution or requires just a quick lookup in the docs, then have them google it. Do not, however, say “Google it.” A student might think that you’re trying to avoid helping them by saying that Instead help them with terms and specific vocabulary. You want to teach them how to Google. A helpful comment, for example, would be to say “I would try googling “ActiveRecord validations Rails". Then ask the student if that’s helpful and if they know what their next steps are. Make sure that they have a plan for dealing with the problem. Then tell them to follow up with you within 15 minutes. See if you can provide them with enough info to have them Google the problem.  Or you can follow up with them in 15 minutes to check in. And you can say something like, “Did you figure out the validation issue you were having? This lets them know that you haven’t forgotten them.

    - Giving students the information they need: At some point if students are still struggling - usually after three or four questions that they don’t know how to answer- you will want to supply them with the answer. Use your judgement though. If you feel like this is a productive question-and-answer session for the student in that these questions are leading closer and closer to the student figuring out the answer and there aren’t too many false answers/dead ends that the student is giving, then continue. Otherwise, at some point you may just want to supply the answer to the question and tell the student what to do to get the test to pass. The important thing is to feel that you’ve done enough to augment their understanding.

    - Having students debrief you: And at the end of this, have the student debrief to you what they did and why that worked. Tell them that they can take their time and that their response does not have to be just a sentence or two. Tell them that you want them to really think through the error message and what they did now to get their tests to pass.
        - This is important because you want them to reflect on their learning. And if it ended up being something that you ultimately provided the answer to, this will still ensure that they think about what happened.

    - Don’t let the question turn into pair programming. If a student has multiple test failures, then after you’ve helped them solve one of them, tell the student that now they should try to solve the next error(s) on their own. If they get stuck, then they can come back and ask additional questions but for at least 15-30 minutes, they should try to debug and Google on their own.

* In using the Socratic method, you may realize pretty early on that the problem isn’t that they have questions with error messages, but there are larger conceptual issues that they are confused about.
    - If this is the case, then review the strategies for fixing conceptual questions listed below.


## 4) Conceptual Questions

Students don’t have a specific testing issue, but instead they are struggling with broader concepts that were covered. Some common questions will revolve around:

- Students do not understand the instructions of a lab
- Students do not understand one specific instruction or how to get a test to pass on a lab
- Students will ask about a specific concept
- Students may initially have questions about failing tests, but after you’ve debugged and worked with them, you may realize that there are larger concepts that they don’t understand fully. (For example: You're working on rails form helpers and then realize that they have no idea what ‘params’ is)

**Note: If you notice a payed student (V-000 batch) is struggling with a concept, make sure to note it in their admin profile and email or slack Ruth or the Section Lead in charge of the section so we can get this student additional help!**

### Strategies for Resolution

First identify the concept that the student is having trouble with. Do this first by eliciting questions

- Click on their icon in the /expert-chat to get to the student’s /admin page.
- Make a note here that the student is having an issue with the specific concept (add detail where you can).
- If you see that other technical coaches have already pointed out that this student doesn’t understand the concept, send Ruth or the section lead in charge an email or DM explaining this and send the link to the student’s /admin page.

If this is the first time or you feel like you can explain this concept well and fairly quickly, go ahead and try to lend the student a hand. Here are some quick tips below but if you don't feel comfortable doing this, that's completely fine and you can let Ruth or the section lead in charge know.

- Pull out from the context of the specific lesson the student is working with and give other code examples of this concept. - Ask the student then to explain the underlying concept or more specifically, ask the student why the result is what it is and then have them elicit the rules from there.
- Once you know where they’re having trouble then you can make sure that you have the concept broken down into its most basic components and how these components build on top of each other.
- Start with the most basic component and use short concept questions to check to see what the student does know. Concept questions are simple and straightforward and usually require a yes/no or short answer.
- At some point you’ll see where exactly the student is lost. Now you’ll take the reins and continue demoing the rest of the concept. Walk the students through this and be didactic. Every few minutes, just check to make sure that the student understands what you’re presenting or whether they need things clarified.
- At the end of the demo, have the student summarize to you as best as they can what you just covered.

## 5) Unsupported

These are questions that we do not support students on.

Most importantly, if a student asks a question on **assessments** we will not support them. We use assessments to see how a student has done in a specific topic and instructors will pair with students and assess their skills. Because of this, students should not be asking technical coaches for help with their assessment project as they should be working on these projects on their own, scheduling a 1:1 with a portfolio coach via this [link](https://theflatironschool.typeform.com/to/UUhrc7), or reaching out to the [section lead in charge of the section](https://github.com/learn-co-curriculum/learn-expert-learn-instructors) for help.

### Strategies for Resolution

Kindly tell the student that you cannot answer their assessment questions, however they can schedule a 1:1 with a portfolio support coach via this [link](https://theflatironschool.typeform.com/to/UUhrc7). If they are feeling frustrated, tell them that they can always reach out to the section lead in charge of the topic that they're own and they'll receive help soon. We never want to annoy or add to a student's frustration so be kind, friendly, and point them in the right direction for portfolio support.

## Resources

- [A slightly more condensed version of this that you can use when on shift](https://github.com/flatiron-labs/learn-support/blob/master/common-learn-questions.md )
