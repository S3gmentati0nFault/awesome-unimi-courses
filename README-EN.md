## Introduction
This repo is thought to collect students reviews for courses held at Milan University.

Did you ever see a message on any of the university groups asking:

"Can you please tell me how is the course?"

or

"Do you know if, by any chance, the professor is expecting a lot from students during the exam?"

Did it ever happen to you to be reviewing a unimi course before giving the exam and thinking that
the system could be better?

If you want to be able to review any course with very little filters, this is the place for you; by
collecting experiences and reviews from different students we can actually create a great database
that can be used by future students to find their bearings.

## How can I contribute?
Do you have something to say regarding one of the courses that you followed? I am very happy that
you want to contribute to this repository, to do that though there is a set of ground rules that
need to be followed.

1. Clone the repository locally.

2. Look for the folder referring to the course you want to review (are you looking for algoritmica
   per il web? You have to find the `algoritmica-per-il-web` directory!). The folder you are
looking for is not there? All you have to do is create it!

3. Write a `.md` file containing your thoughts regarding the course, in the following I will give
   you some pointers on what is expected.

4. pull-request!

How can we write a `.md` file containing our experiences regarding a certain course? You are being
required to follow, again, some ground rules:

1. The filename has absolutely 0 value, therefore it can be anything you like, avoid insults please!

2. The review needs to be structured, therefore anything containing less than 150 words will not be
   accepted.

3. Again, avoid insults in general in your reviews please! Some courses leave extremely negative
   impressions but let's try to keep it professional, shall we?

4. Any review needs to make sense, "I like it because it's nice" or "I don't like it because it's
   not nice" are not considered logical.

You don't know how to use git but you still want your voice to be heard? You can contact me directly
on Telegram (@alexbgtt) or you can send an email to <a
href="mailto:alessandro.biagiotti@studenti.unimi.it">alessandro.biagiotti@studenti.unimi.it</a>.

## Structure of the `.md` file
I am trying to find a way to save some interesting information that could be used in the future (if
the project receives enough attention and proves itself valid) to generate graphics and allow data
analysis.

At the moment the only information required to add your entries are the following:

- When did you take the exam.
- Who was the professor.
- How difficult do you think the exam actually was (mark out of five, doesn't need to be a natural
number).
- Did you follow at least 50% of the lectures? (binary response y / n).
- How good do you think the professor actually is? (I consider this a sum of all the
characteristics: available, on time, makes him/her self clear, etc... Mark out of five, if the
answer to the previous question was "n" then please put -1 as a mark for this one).
- Would you recommend this exam to anyone? (at the moment it's just a binary response).

All you have to do, at the end of the day, is to find the folder associated with your course (or create it if necessary by `$ mkdir <my-course>`) and execute the following command

```
   $ cp /awesome-unimi-courses/template.md /<my-course>/42.md
```

## Roadmap
- [ ] Find a group of interesting metrics to keep track of.
- [ ] Gain enough reviews.
- [ ] Create a simple website to give a more user-friendly view to the repository contents.
