Learnability and the Dynamic Textbook
=====================================

 * Think about:
   * Browsing the internet
     * Wikipedia
     * BuzzFeed
   * Reading through YA series books
   * Reading scientific papers
 * These are collections of similar documents
 * They all have links connecting individual works into **networks of information**
   * Different Characteristics
   * Different goals
     * Factual Reference
     * Bite-sized entertainment
     * Serial entertainment
     * Sharing information among experts
     * Learning new information (Needs Work)
 * Overview of talk
   * How do various systems of documents link themselves together?
   * How do different linking styles influence readers?
   * How do different linking styles influence writers?
   * What do linking styles make easy or hard?
   * What linking style would encourage learning?
   * How to implement that linking style in a _dynamic textbook_
 * How do systems of documents link themselves together?
   * Wikipedia
     * Clickable link with page title ("List of Animorphs Books")
   * BuzzFeed
     * ClickBait link ("10 Animorphs plotlines YOU WOULD NOT BELIEVE ARE REAL")
   * YA Series
     * Teaser Chapter ("Keep Reading for a teaser chapter from the next Animorphs")
   * Scientific Paper
     * Citation ("J. Stine, A. Horowitz, et. al. A Feasability Study for Human-Animal Transition, Pseudoscience, May 2009")
 * How do different linking techniques influence readers?
   * Expectations
     * BuzzFeed links tell you what kind of cheap entertainment you're getting
     * Wikipedia links tell you what the article is about
     * Series books tell you where the next plot will start
     * Paper footnotes tell you the authors of a study, where they worked, and what journal it was published in.
   * Ordering
     * Is this the next __ in the story?
     * Is this an unrelated article similar to this one?
     * Is this an article that explains a concept this article presupposes that you know?
   * Behavior
     * Links at end
       * Encourages reading many documents in sequence
     * Links throughout document
       * Encourages referencing links to learn background knowledge
 * How do different linking techniques influence writers?
   * What do your links look like?
     * You write BuzzFeed links to get readers to click on them
     * You write Wikipedia links to refer readers to a relevant article
     * You write series book links to try to get readers to continue the story
     * You write scientific paper links to show readers the level of knowledge you expect them to have.
   * How do you expect readers to find your work?
     * Series Books have serial links
       * expect you to have read the last book
       * enable long and complicated plotlines
     * Wikipedia articles have embedded links
       * expect you to come to an article to refer for information about another article
       * force articles to give a high-level overview and then branch into specifics later
     * BuzzFeed articles have links at the end of an article
       * no expectations for reader
       * force writing to be accessible and entertaining
     * Scientific Papers have embedded footnotes
       * expect you to be referring to this paper because another paper presupposes the knowledge in this paper
       * prevents papers from being broken up into pieces
 * 



Different metainformation structures make some things easy and some things difficult.  For example, the structure of the web of scientific papers makes it easy for experts to quickly and concisely learn about new discoveries.  Papers are explicitly connected by *citations*, which invoke the results of a previous paper.  If the reader needs a refresher, or simply hasn't seen the referred paper, she can look up the cited paper to bring herself up to speed.  Papers which are cited often are considered more important, since they _demonstrably_ reach conclusions which further papers elaborate on.  Furthermore, once a scientist has seen many papers, she will be able to know a large amount about a paper without even reading it, just by seeing which papers it cites.

Simultaneously, the specific structure of scientific papers discourages learning from scratch.  I can't think of anybody who has given themselves a decent education solely by reading papers, it simply can't be done.  That's because papers presuppose that the reader is an expert informed on current research.  This makes papers much shorter and easier to write by limiting the amount of established information that the writer needs to provide before presenting their results, but restricts the audience to those familiar with the topic.

But does the metainformation structure connect the documents in such a way that even if the information a reader needs to understand a paper isn't referred to in the paper itself, it is easy to find that information?  Unfortunately not. Most of the time, information that the author considers basic isn't cited, leaving a beginner high and dry, unable to understand what is written and unable to find the material needed to understand it.  And since the metainformation structure is designed to help experts share ideas, the curious beginner is left high and dry.

So far, we have talked about three metastructures:

 * The web
    * makes aimless browsing and headline journalism easy
    * discouraging long content through midstory links
 * Novels 
    * makes it easy to write longer stories with structured plots
    * makes it difficult to write shorter stories
 * Scientific papers
    * make it easy to share new results to experts 
    * makes it hard for beginners to learn.

---

Now let's talk about a fourth, and this will segue in to talking about designing a metastructure to encourage learning.

Right after the printing press was invented, many mass-produced textbooks became available.  Previous textbooks were handwritten manuscripts, which were prohibitively expensive for all but the very rich.  But what they all had in common was the purpose to help the reader to learn.  Textbooks typically contained exercises, which often consisted of memorizing passages in earlier works, although the modern idea of practice problems designed to teach skills developed slowly over time. The author of a textbook had an idea of where the reader should be before reading the textbook, and hope for the state that the reader should be in after having learned the material contained within.

The metastructure of textbooks began to be defined by the author's expectations about where the author should be at the beginning and end of the texts.  Some books assumed things other than knowledge.  For example, the [New England Primer](http://en.wikipedia.org/wiki/The_New_England_Primer) assumed that its readers would be good puritan young children, and that after having reading their work they would come out better christians, fearing god, etc.  With the exception of ideologocal textbooks, however, which form their own substructure, I will only talk about textbooks purely based on knowledge.

Most textbooks have introductions which describe what level the textbook is written for, what kind of a course it would make, is it suitable for self-study, and many other details. Some textbooks recommend prerequisite textbooks, or suggest further reading, but many don't.  This structure isn't enabled by technology at all, and it can be extremely difficult to connect information between textbooks.  Furthermore the question "what should I learn to benefit from this textbook" is rarely answered satisfactorily.  Which textbooks you have completed (by which I mean done the problems) gives others a vague idea of your skill level in the specific area that textbook addresses. However, textbooks cannot be broken up into smaller units, so you might know half of a textbook but not the second half, or begin reading and find halfway through that the textbook presupposes a level of knowledge that you don't have.  The smallest unit to break up textbooks is the chapter, but chapters often introduce several concepts and can be monolithic.

Textbooks' resistance to splitting, single-minded focus, and vague ties to other textbooks might come from the audience most likely to influence textbook writing: university professors designing courses around textbooks.  A university course exists within a system designed to advise students about what courses they should do next, so a professor writing a textbook might reason that that information is superfluous, since any learner could just visit their advisor, not realizing that some want to learn outside of the system of higher education, for fun or profit.  A single-minded focus makes sense for a university course focused on a single topic, while a resistance to splitting also makes sense, since most of the time, the textbook is designed to be taught in a single course.

So we can update our list of what metasinformation structures within document systems encourage:

* The web
    * makes aimless browsing and headline journalism easy
    * discouraging long content through midstory links
 * Novels 
    * makes it easy to write longer stories with structured plots
    * makes it difficult to write shorter stories
 * Scientific papers
    * makes it easy to share new results to experts 
    * makes it hard for beginners to learn.
 * Textbooks
    * makes it easy to design a class around the textbook
    * makes it difficult to learn small chunks, or find out where to find information

What do MOOCs do?  MOOCs advertise the college experience online.  They are Massively Open Online **COURSES**.  They resist being broken up into small units, just like textbooks, since they are fundamentally wedded to the idea of the semester-long college course.  They borrow the ideas of homework and final exams, even offering credentials in some cases.  They seem to fail in much the way college courses do at delivering a more discrete, modular approach to learning. 

Some evidence for the demand for smaller chunks of learning comes from the notoriously high dropout rate among MOOC students.  [This paper](http://lytics.stanford.edu/datadriveneducation/papers/yangetal.pdf) describes the dropouts rate from an online Bioelectricity course run by Duke University. 
~12,000 people registered, only ~7,000 watched a video, ~3,500 took one quiz, and only ~300 passed the final exam.  **96%** of the people who watched the first lecture did not complete the course, but **50%** took at least one quiz.  The authors of the paper studied the effects of social network effects, but I would like to propose a much simpler explanation:

People want smaller chunks of learning to consume individually without committing to a longer course.

Since MOOC's seem to compound the inherent metastructural issues, I won't add them to our metainformation structures paragraph, and instead just list them under textbooks.

* The web
    * makes aimless browsing and headline journalism easy
    * discouraging long content through midstory links
 * Novels 
    * makes it easy to write longer stories with structured plots
    * makes it difficult to write shorter stories
 * Scientific papers
    * makes it easy to share new results to experts 
    * makes it hard for beginners to learn.
 * Textbooks and MOOCs
    * makes it easy to design a class around the textbook
    * makes it difficult to learn small chunks, or find out where to find information

We want to consciously create a metastructure that we can optimize for learnability.  What characteristics does it have?

There should be a low barrier to entry. As soon as one discovers the information system, it should be immediately apparent where to go next.  Starting should not be difficult for people with *any* background, and it should be clear where to find prerequisite information, as well as to tell where they can use this piece of knowledge to learn more.

The metainformation structure should admit learning in all fields of study, including the sciences, the humanities, the fine arts, and vocational training.  It should be versatile enough to admit many different fields with many distinct learning styles, while still bringing an edge to it.  

The metainformation structure should minimize the barrier to entry for creators. Not everyone can write several textbook chapters, problems, as well as dealing with publishers.  This should not be a barrier in a system optimized for learning.  If you can write a chapter, make a diagram, write another problem, anything, you should be able to make a contribution to the information system.  Open-source would be extremely helpful for achieving this goal.  We have to remeber that the writers and the learners are the same people, and writing can solitidfy knowlege and make the learning even more effective.

---

We've discussed the characteristics of an information system with a metastructure optimized for learning.  Now I would like to offer a proposal for such a metastructre, which I'll call **linked-modules**, and discuss its advantages and disadvantages.

Here's an idea.  Imagine if you could break up textbooks into much smaller modules, each of which built on each other. Each module would propose an idea which builds on its dependencies and adds to them.  The module would contain its own exercises which learners could complete to assure that they have mastered the idea in the module.  Since each module explicitly lists the modules it presupposes that you have completed, it would be easy to select a module, and know exactly what you need to learn in order to do it.

For an example I'd like to chose something that is not typcally handled by many textbooks: machine shop skills, in order to demonstrate the exensibility of the linked-modules system.  A module designed around learning how to use a lathe would presuppose that one would have already completed modules about power drills, since they're needed in order to attach a piece to a lathe.  The course would already presuppose that you have taken general safety training, and perhaps some other hand tools.  The course wouldn't have dependencies more than necessary, however.  If the module about drill presses depended on the safety and hand tools requirements, then so would the module about lathes, even if it solely lists the drill press module as a prerequisite.

The lathe module would contain videos demonstrating the lathe's features, as well as videos, text, and diagrams detailing how to make various objects out of a lathe.  The exercises would be prompts to make specific parts on the lathe, with levels of detail ranging from "be creative!" to an extensive set of technical drawings.

However, a learner might not be familiar with the format the technical drawings are written in.  If the course features the technical drawing module as a dependency, then it is free to assume familiarity with the technical drawings.  However, since all of these modules are open-source, another writer could fork the module and work on her own branch.  She would rephrase the technical drawings in english, which might be cumbersome.  However, the new module wouldn't list the technical drawing module as a dependency.  The learner is now faced with a choice: learn a technical drawing module, as well as lathe module with technical drawing, and gain an additional skill(technical drawing) which makes your main skill(lathes) easier to communicate about.  Or, skip that and learn a simplified version, which focuses exclusively on the lathes and not on the notation.  These modules teach the same skill, so they are called *equivalent modules*.

The idea of equivalent modules generalizes to many situations in which equivalent information is presented.  Further courses in lathes should list only as a dependency one lathes course, then specify that they also consider all courses equivalent too it. If that specific course requires the technical drawing notation, then it should list that as a seperate dependency, in order to keep skills atomic.

Equivalent moduels could also be used for translation.  Each module could have mirrors in every language, which say almost the same thing.  These modules would be relatively easy to maintain and would only require the inital work of translation to create, but would make huge improvements for people struggling to learn english while struggling to learn things in english.

As a sidenote programming problems could also be offered in different modules this way, which will avoid many a flamewar.

The linked-modules will all be collected in a **dynamic textbook** which will contain every linked module and provide the user with this information, and suggest new courses to take, as well as giving a summary of state and recommending random courses, or exercises to keep skills sharp.  The dynamic textbook is designed to get out of the way and connect learners with the information that they want to learn.

What does the linked-modules method optimize for and against as an information system?  It seems to be a good method for learning from scratch, as well as self-studying.  However, it would be extremely difficult to teach a large class in an ordered way using this method, since each individual student would move through at her own pace.  It would also be difficult to guide a student through a long sequence of courses, since there are many equivalent variants.  Finally the linked-modules focus on brancing might encourage fragmentaiton, and it might be difficult to make creating modules the norm among the population.  The large emphasis on learning and dependencies might prove cumbersome for a researcher seeking to share the latest discoveries.

* The web
    * makes aimless browsing and headline journalism easy
    * discouraging long content through midstory links
 * Novels 
    * makes it easy to write longer stories with structured plots
    * makes it difficult to write shorter stories
 * Scientific papers
    * makes it easy to share new results to experts 
    * makes it hard for beginners to learn.
 * Textbooks and MOOCs
    * makes it easy to design a class around the textbook
    * makes it difficult to learn small chunks, or find out where to find information
 * Linked-Modules
    * makes it easy to find out what to learn next, and gives small, manageable chunks, as well as givin amateurs ideas about where to start
    * makes it difficult to share cutting-edge information, or structure long, planned stretches of learning

---

I would like to end with a word of caution.  As soon as two similar works exist, there is a metainformation structure defining the relationship between them.  By thinking about this metastructure we can make it easier or harder for various audiences to use the work for various purposes.  What is hard in a given system is trivial in another.  However, we need to commit to making a conscious choice to design our metainformation systems to facilitate learning, which is inherently disruptive.  This may be difficult, but it replaces an environment where our main methods of learning serve to strengthen entrenched and antiquated ideas about learning so popular in universities today.  If we do not structure our information, our information will structure us.  There is no avoiding the impact of information structuring and we might as well make it do good.  Thank you.


