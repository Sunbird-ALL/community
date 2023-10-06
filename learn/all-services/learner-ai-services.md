---
description: >-
  Learner AI services as part of ALL initiative, provides the instruments of the
  Platform, through easy to integrate APIs that help in enhancing reading and
  speaking ability of the learners journey.
---

# Learner AI Services

The Learner AI Services use ASR(Automated Speech Recognition) technique to decipher the learners speech, applies the ALL Learners algorithm build a Learner Profile, against each of the language set, which typically are syllable or letters or characters.  Currently the services cater to Tamil and Hindi languages.

To help the learner journey, we have the following APIs and their key usage implication:-

updateLearnerProfile – This API when fed with recorded wav file or base64 encoded text, create or update the learner profile.   This is the key API, that deconstructs the audio file into learner profile using ASR technology and ALL Learner algorithm.

GetFamiliarityScore – This API fetches the profile vector for a given user or session.  Profile vector is a json object with set of derived scores against each character in the language.

GetTargets – This API is helpful to get a next set of characters that are consistently scored low across the session(s).  This can be fed into ALL Learner Session services to fetch content, that can help him to sharpen the targeted character set, which in turn improves his Learner Profile.
