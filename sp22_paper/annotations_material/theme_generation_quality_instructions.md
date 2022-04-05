## Theme Generation Quality Evaluation Instructions

Below are the instructions we used for the quailty evaluation of the theme
generation model in the paper (Section VII.C.3).


### Instructions

Consider the following set of labels:

(Labels represent problems, observations, or positive aspects users have
communicated in their app reviews.)

\<set of labels\>
 
---

Which of the following statements best describes each title in summarizing the
labels above?


\<Title-1\>

- Title **covers** the vast majority of the labels.
- Title **misses** the vast majority of the labels.
- Title is **unrelated** or **misrepresents** the
labels.

\<Title-2\>

(...)

---

The labels are basically problems, observations, or positive aspects users
communicated in app reviews. A high quality title should convey all the
underlying labels as closely as possible. 


*Example*: For instance, let us take the labels "*Data Deletion, Data Editing*".
The title "*Data Management*" **covers** the vast majority of the labels since
both labels can be categorized under it. A title like "*Data Removal*"
**misses** the vast majority of the labels as it does not cover the "*Editing*"
or "*Sharing*" part. A title like "*Data Duplication*" is **unrelated** to the
labels.


Notice that it is okay for the title to be one of the labels if that label is
general enough to encapsulate the others. For example, the labels "*Data
Deletion, Data Editing, Data Management*" can still get the title "*Data
Management*" as it covers the vast majority of the labels.

If two titles are identical, please give them the same quality rating. 

---

Please review the following examples before attempting the task: 

\<sample example1\>

\<sample example1\>

\<sample example1\>