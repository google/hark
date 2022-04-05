## Privacy Classifier Annotation Instructions

Below are the instructions we used for the manual annotations needed for the
privacy classifier training and evaluation in the paper (Section V.B.2).


### Instructions

Consider the following Android app review:

(Reviews are text submitted by users to share their experience or concerns with
android apps.)

\<sample review\>

--- 

Does this review include a statement or phrase about privacy? 
    
- [ ] Yes 
- [ ] No

---

**Privacy Label:** Reviews that discuss personal data sharing, hiding, deleting,
etc. or discuss related features are related to privacy. The word "privacy" need
not be present in the review. Also note that positive reviews when users are
pleased with the app's privacy, are considered to be about privacy.  Other
privacy topics include, but are not limited to:

- location tracking
- spying/surveillance
- privacy controls/features
- data sharing/hiding
- data collection
- explicit consent or lack thereof
- parental controls
- online safety
- personal information
- personal data deletion
- app permissions (Camera, Calendar, Storage, etc.)
- privacy features
- security/hacking issues causing loss of personal info
- personal health data

Note: When personal devices are shared with friends, privacy issues may arise.

---

**Not-Privacy Label**: These topics include, but are not limited to:

- battery drain
- bugs/crashes in apps
- ads/notification/ message spam
- money/payment issues or scams
- malware or antivirus
- content copyright issues
- mobile internet data usage limits
- feature not working as expected

Note: Reviews mentioning accuracy of personal data (e.g. wrong location or
birthday) are not about privacy.