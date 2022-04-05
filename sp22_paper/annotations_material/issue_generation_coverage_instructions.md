## Issue Generation Coverage Evaluation Instructions

Below are the instructions we used for the coverage evaluation of the issue
generation model in the paper (Section VI.D.2).


### Instructions

Consider the following Android app review:

(Reviews are text submitted by users to share their experience or concerns with
android apps.)

\<sample review\>
 
---

Which of the following statements best describes each label set?


\<Label Set-1: label-1, label-2, label-3\>

<ul>

<input id="1" type="radio"> Label set covers the main topics mentioned in the
review. 

<input id="2" type="radio"> Label set contains keywords from the review, but
does not capture any main topics.

<input id="2" type="radio"> Label set is not related to any main topics in the
review.

</ul>


\<Label Set-2: label-3, label-4, label-5\>

(...)

---

A review might touch upon multiple main topics, so a label set can include one
or more entries (separated by comma).

*Example*: For instance, let's take the review "*I have never been flooded with
so many ads in such a rapid fashion. Why did this app keep asking for my
location?*". Label set "*Too many ads, Unnecessary Location requests*" captures
both the main topics mentioned in the review. Label "*Showing ads*" contains a
keyword from the review and indicates that the review is about ads, but it
doesn't describe the main topic of there being too many ads. Label "*Fast app*"
is not related as the user doesn't say this nor imply it, and the label
completely misses the point of the review.

---

Please review the following examples before attempting the task: 

\<sample example1\>

\<sample example1\>

\<sample example1\>