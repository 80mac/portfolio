# Feedback mechanisms

**Problem:** Users need the ability to leave feedback on what we’re doing well or poorly.
**Solution:** Conversation-level survey for broad feedback + message-level component for specific feedback.
**My role:** UX Content Strategist

## Conversation-level feedback

In the past, users had just one opportunity for leaving direct feedback: a short survey at the end of a chat session. This survey consists of the classic “How likely are you to recommend this product to friend…” question and a couple others. 

*add photos*

### Remaining problem

This survey gives our team a broad sweep at how the user’s conversation went, but presents us with a couple issues when it’s the only feedback-gathering mechanism:
* If a user doesn’t reach the end of a conversation (i.e. complete a task), they won’t even have the option to leave direct feedback.
* Even if they are able to fill out the survey, it doesn’t provide us with feedback on specific trouble or success spots within the conversation. It only gives a broad assessment of the entire experience.

In short, this solves one user problem - leaving conversation-level feedback - but it’s not sufficient for those who wish to let us know exactly where we succeeded or fell short.

## Message-level feedback

To create the best product for users, we need the ability to solicit feedback from them at any point in the conversation. This allows us to pinpoint shortcomings and replicate successes. It was clear we needed a feedback mechanism at the message level, not just the conversation level.

*embed video*

## Design principles

For our first milestone, we decided to keep it simple. During research, we learned that users had a few key requirements for the feature:

1. **Unobtrusive** - users didn’t want to feel their conversation had been interrupted when leaving feedback
2. **Speed & Simplicity** - users wanted to leave feedback quickly
3. **Assurance** - users wanted to know how their feedback would be used and receive assurance that it had been collected

We used these principles to design the form.

## Elements of the component

### Call-to-action

*add photo*

1. Unobtrusive - the call-to-action tucks neatly below each new message group, noticeable but not obtrusive
2. Speed & simplicity - in testing, users preferred the clarity of a “Give feedback” link below each message group to other options like ephemeral thumbs up/down buttons beside individual messages

### Feedback form

*add photo*

1. Unobtrusive - 
* Partial webview - the form only covers the bottom half of the screen. Users are still able to see their conversation beneath, and don’t feel as if they’ve been taken elsewhere
* Present continuous tense - “How’s your chat going?” frames the entire mechanism as a continuous and integrated piece of the overall chat experience
2. Speed & simplicity - binary feedback options - there is no room for question between the options “great” and “not good,” minimizing cognitive load for users
3. Assurance - set expectations; the “How we’ll use this info” section clarifies the timeline users can expect from feedback left through this form

### Confirmation dialogues / stamps

**"Great"**

*add photos*

**"Not good"**

*add photos*

1. Unobtrusive -
*  A confirmation dialogue appears briefly before closing and returning user to the conversation
* A stamp appears at the bottom corner of the response where feedback was left, acting as a quick reminder of their sentiment
2. Speed & simplicity - the user can easily scan their conversation for sentiment using the stamps
3. Assurance - 
* Messages in the dialogue reinforce our reception of the user’s choice; we’re appreciative in both cases, and take note where improvements are needed.
* Stamps match the sentiment shown on the form buttons - thumbs up or down

[Home](index.md)