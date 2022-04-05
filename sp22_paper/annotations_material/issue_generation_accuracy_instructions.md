## Issue Generation Accuracy Evaluation Instructions

Below are the instructions we used for the accuracy evaluation of the issue
generation model in the paper (Section VI.D.1).


### Instructions

Consider the following Android app review:

(Reviews are text submitted by users to share their experience or concerns with
android apps.)

\<sample review\>
 
---

Which of the following statements best describes each label?


\<Label-1\>

- The topic is discussed in the review
- Contains keywords present in the review, but is not a topic
- Unrelated to the review



\<Label-2\>

(...)

---

A review might touch upon multiple topics, and a label can describe any one of
these topics. 

*Example*: Let's take the review "*0 stars. Why do you need to know my location
and have access to my photos?*". Label "*Unneeded Location*" captures one of the
topics in the review. Label "0 stars" contains keywords from the review, but
does not describe any topic. The label "*Installation Issues*" is unrelated to
the review text.

---

Please review the following examples before attempting the task: 

\<sample example1\>

\<sample example1\>

\<sample example1\>