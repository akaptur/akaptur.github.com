---
layout: post
title: "Effective Learning Strategies for Programmers"
date: 2015-10-10 15:15
comments: false
categories: python talks learning
---

In early September I gave a keynote at [Kiwi PyCon](https://nzpug.org/) in New Zealand on effective learning for programmers. There were two pieces to the talk: one about mindset, and one about particular strategies we can use. The text below is an aspirational and lightly edited transcript of the mindset piece of that talk. There's also a [video](https://www.youtube.com/watch?v=Mcc6JEhDSpo) available if you'd like to see the strategies piece.

### Recurse Center

Before I joined Dropbox last year, I spent two years working at a company in NYC called the [Recurse Center](https://www.recurse.com/). The Recurse Center is like a writers' retreat for programmers. Participants spend 3 months working on whatever is most interesting to them. So someone who'd been writing Java for ten years might come to RC to learn a new language like Clojure, or someone who just graduated with a CS degree might come work on their web development skills, or someone who'd been learning programming in their spare time might come to turbo-charge their learning. There's almost no structure to the program - no deadlines, no assignments, no teaching. It's an experiment in unstructured learning for adults.

My role as a facilitator was to help people make the most of that disorienting amount of freedom that they had at RC. People who come out of traditional educational experiences or traditional jobs very often don't know what to do with that. So I'd help them with goal-setting and help them make the most of the experience. One of the things we thought a lot about was how to have the most effective learning experience possible for programmers. Today I'll talk about some of the research into how to be an effective learner, and how we can apply that research to our daily lives as programmers and engineers.

### What to get out of this post

Take a minute and consider what you'd like to get out of this post. You might want to learn something new about how to be as efficient and effective in your job as possible. You might want to hear about how you can be a better teacher or mentor to junior engineers. Or you might want to hear about how you can make institutional change in your organization to set up a better environment for these kinds of things.

All of these are useful goals, and I'll touch on material relevant to all of them. However, I want to challenge you to consider the strategies mostly for yourself. When I hear about these strategies, very often it seems obvious to me that other people should be following them, but not necessarily obvious that I myself should. I'll come back to that tension a little bit later on.

## Growth mindset: Carol Dweck

Let's talk about the first key to effective learning. The sociologist Carol Dweck has done a ton of interesting research about how people think about intelligence. She's found that there are two different frameworks for thinking about intelligence. The first, which she calls the fixed mindset, holds that intelligence is a fixed trait, and people can't change how much of it they have. The other mindset is a growth mindset. Under a growth mindset, people believe that intelligence is malleable and can increase with effort.

Dweck found that a person's theory of intelligence - whether they hold a fixed or growth mindset - can significantly influence the way they select tasks to work on, the way they respond to challenges, their cognitive performance, and even their honesty. I'm going to run through a couple of the most interesting results from her work here.

### These mindsets cause differences in effort

The first interesting result is that this framing impacts how people view effort. If you have a fixed mindset - you believe that people are either smart or they're not, and they can't really change that - then you also tend to believe that if you're good at something, it should be easy for you, and if something is hard for you than you must not be good at it. That's a fixed-mindset view.  People who have a growth mindset believe that you need to exert effort and work hard at something to become better at it.

Several studies found that people with a fixed mindset can be reluctant to really exert effort, because they believe it means they're not good at the thing they're working hard on. Dweck notes, "It would be hard to maintain confidence in your ability if every time a task requires effort, your intelligence is called into question."

### "Praise that backfires"

The second interesting result is probably the most famous. Dweck and her collaborators showed that giving students subtly different kinds of praise significantly impacted their performance.

In this study, Dweck and her collaborators gave a students a series of problems. After the first set of problems, all of the students did pretty well. Then half of the students were told "Wow, you did really well on those problems - you must be very smart." and the other  "Wow, you did really well on those problems - you must have worked very hard."  Then they got a second set of problems, much harder, where everyone did badly. Then they got a third set of problems that were like the first set - back to the easier level.

Here, they're creating a fixed mindset in the first group of students (your performance shows that you're smart) and a growth mindset in the second set of students (your effort drives your success).

They found a bunch of interesting things from this. The first aspect of the experiment is that in between the first and second problem sets they asked the students if they'd like to do an easier exercise or a harder one next. (In practice, everyone got the harder set next.) Dweck et al. wanted to see if there would be a difference between the students who got different kinds of praise. And sure enough, there was: 90% of the students praised for effort chose to do a harder set of problems next, compared to only a third of the group praised for intelligence. The kids praised for effort were much more interested in a challenge.

The second thing that they looked at was how student performed on the third set of problems. They found that students who'd been praised for their intelligence did significantly worse on the third problem set than they had on the first, but students who'd been praised for effort did slightly better.  Students who got intelligence praise weren't able to recover effectively from hitting a wall on the second set of problems, while students who got effort praise could bounce back.

After this, they had the students write letters to pen pals about the study, saying "We did this study at school, and here's the score that I got." They found that _almost half of the students praised for intelligence lied about their scores_, and almost no one who was praised for working hard was dishonest.

So there are three implications here: a growth mindset made students more likely to choose a challenge instead of something easy, more likely to persist after a setback, and more honest about their performance, compared to the students with a fixed mindset.

What's fascinating about this is how subtle the difference in praise is. Being told you're smart leads to all of these attempts to preserve the appearance of smartness, by only doing easy things you know you can perform well on and by hiding your poor performance. Being told that you work hard leads to attempts to preserve the appearance of working hard - and the best way to do that is to actually work hard.

### Response to confusion

Another study looked at what happened when students faced a temporary period of confusion. Dweck and her collaborators designed a short course on psychology to give to elementary school students. The course was a booklet on psychology followed by a quiz. Some of the booklets had a confusing passage in them, and others didn't. The confusing part wasn't on the quiz, so students could master the material if they just completely ignored the confusing bit. The researchers wanted to see whether students would be able to recover from being totally bewildered in the middle of this booklet.

They found that students with a growth mindset mastered the material about 70% of the time, regardless of whether there was a confusing passage in it. Among students with a fixed mindset, if they read the booklet without the confusing passage, again about 70% of them mastered the material. But the fixed-mindset students who encountered the confusing passage saw their mastery drop to 30%. Students with a fixed mindset were pretty bad at recovering from being confused.

>"How can one best describe the nature of people who will most of all be that way which will make the imitating of others happen most often? Is it that these are the people we want to be like because they are fine or is it that these are the people we want to be liked by?"

I wanted to put up a section of the confusing passage because this really resonated with me. Hands up if you've ever started using a new tool and run into documentation that sounded like this. [Roughly 100% of hands go up.] It happens all the time - you get domain experts writing docs aimed at beginners, or out-of-date docs, or some other issue. It's a critical skill for programmers to push past this kind of confusion and be able to successfully retain the rest of the information in the document we're reading.

### Programmers need a growth mindset

Programmers need a growth mindset! Key skills for programmers - like responding to confusion, recovering from setbacks, and being willing to take on new challenges - are all much easier with a growth mindset, and much harder with a fixed mindset.

### Does anyone believe in a fixed mindset?

Now sometimes when people hear this idea of the fixed mindset, it almost sounds like a straw man. Like, does anyone in the tech industry actually believe this? I think that absolutely a fixed mindset is a widespread belief. Here are a couple of examples.

#### 10x engineers

Start with the idea of the 10x engineer. This is the idea that some engineers are an order of magnitude more effective than others, for some definition of effective. And there's lots of critiques of this framing, but we'll set that aside for a moment. If you believe in the idea of the 10x engineer, do you think that engineer was born as a super effective engineer? Or did they get to be 10x one x at a time?

I think very often in the popular framing of this, the 10x engineer is set up on a pedestal, as someone that other people cannot become. Very often this is approached from a fixed-mindset perspective.

#### Hero worship

Another case where we see evidence of a fixed mindset is with hero worship. So Julie Pagano did a great talk at PyCon 2014 about impostor syndrome, and one of her suggestions for a way to combat impostor syndrome was "kill your heroes." Don't put other programmers on a pedestal, don't say "that person is so different from me." Fixed/growth mindset is a really useful framing for this too. If you have programming heroes, do you consider them to be totally different from you? Could you become _more like_ the kind of person you admire? If you don't think so, that's some evidence of a fixed mindset.

So I'd argue that yes, a fixed mindset is quite prevalent in the tech industry.

### Can you change a fixed mindset? Heck yes

Hopefully by now you're convinced that a growth mindset is better for you than a fixed mindset. So the next question is: is this malleable? Can you take a fixed mindset and turn it into a growth mindset? And the answer is heck yes, you absolutely can change a fixed mindset into a growth one.

In fact, in many of Dweck's studies they experimentally induce a fixed or growth mindset, often in really subtle ways. The praise study is one example: one sentence of praise changes the students' behavior. In other studies they have students read a paragraph about a famous person's success, and at the end it says "because they worked very hard," or "because it was in their DNA." This is absolutely a malleable thing.

So how do you change a fixed mindset? Sometimes the challenge is mostly in actually identifying the fixed mindset, and once you hear yourself say the words, "I could never learn physics," it's already obvious that that's probably not true. But other times it's harder to root out the fixed mindset. So here are a couple of flags you can use to identify fixed mindsets so you can root them out.

### How do you identify a fixed mindset?
#### "I am .."
#### "Some people are just ..."

If you're on the lookout for places where your mindset might be fixed, you should be listening for sentences that start like this. Things like "I've never been good at CSS" or "I'm not a people person" or "Some programmers are just faster than others." Anything that starts with "I am ..." is a candidate. The word "just" is often present.

Now, obviously, you can say sentences with "I am" that aren't indicators of a fixed mindset. Instead, the point here is to treat sentences like this as a little bit of a yellow flag for yourself, to notice and then to examine your mindset more closely.

Just as an aside, the example "I'm not a people person" is supported by the research - Dweck and collaborators did a study on making friends and social situations, and this research holds there too. [See the Q&A for more about this.]

### How do you change a fixed mindset?
#### Reframe praise & success

Ok, so once you've identified a fixed mindset, how can you go about changing it? Here are four strategies.

The first is to reframe praise and success. By reframe praise I mean that when you get the wrong kind of compliments, turn them into growth-mindset compliments. So if someone says "wow, great job on that project, you're so smart," translate it to "yeah, it was great, I worked really hard on that project." You don't necessarily have to do this out loud! But this reframing reinforces for yourself that you gain mastery by seeking out challenges and by exerting effort.

And you can use the same techniques for successes and accomplishments. When something goes well, don't think, "Of course that went well because I'm awesome." Instead think, "I used an effective strategy on that project! I should do that more often."

#### Reframe failure

Of course the flip side of this dynamic is also really effective. A huge part of a fixed or growth mindset is how you respond to failure. What's your self-talk when you face a setback or don't get what you wanted? If you're saying, "Maybe I'm not cut out for this job after all," treat that as a red flag. Instead, ask what you _learned_ from your unsuccessful attempt or what strategies you could have used instead. It sounds cheesy, but it really works.

#### Celebrate challenges

The third way that you can change a fixed mindset is to celebrate challenges. How do you respond when you have to struggle? Try explicitly celebrating. This is something that I was really consistent about when I was facilitating at the Recurse Center. Someone would sit down next to me and say, "[sigh] I think I've got a weird Python bug," and I'd say, "Awesome, I _love_ weird Python bugs!" First of all, this is definitely true - if you have a weird Python bug, let's discuss - but more importantly, it emphasized to the participant that finding something where they struggled an accomplishment, it was intentional, and it was a good thing for them to have done that day.

As I mentioned, at the Recurse Center there are no deadlines and no assignments, so this attitude is pretty much free. I'd say, "You get to spend a day chasing down this weird bug in Flask, how exciting!" Now, at Dropbox, where we have a product to ship, and deadlines, and users, I'm not always uniformly delighted about spending a day on a weird bug. So I'm sympathetic to the reality of the world where there are deadlines. However, if I have a bug to fix, I have to fix it, and being grumbly about the existence of the bug isn't going to help me fix it faster. I think that even in a world where deadlines loom, you can still apply this attitude.

#### Ask about processes

The last strategy for changing a fixed mindset is to ask about processes. Like many of you, I work with some great engineers. Sometimes, I'll try to fix a tricky bug and won't be able to, and then one of them will be able to fix it right away. In these situations I've tried to be really disciplined about _asking how they did it._ Particularly when I was new at Dropbox, the answers would be really illuminating. Sometimes the information had come from a source I didn't know existed. Now that I've been there longer, it's usually a technique or strategy difference, or a detail about why my strategy had not succeeded.

This is a much more useful strategy in the long term than saying "Oh, of course, that person got the bug because they are a wizard."

## Confidence & imposter syndrome

Dweck's research is really interesting in the context of the discussion around impostor syndrome. Impostor syndrome is the feeling that you're secretly an unqualified fraud who will be uncovered any second now. Hands up if you've ever felt impostor syndrome in your career? [80% of hands in the room go up.] Yeah, that's lots of you, and I definitely have as well. And it _sucks_! It's so painful, and it's really bad for your career, because you're less likely to take chances or to look for new opportunities to grow if you're worrying about getting fired from the job you already have.

The proposed solutions for impostor syndrome very often center around confidence. Like, "Oh, if you feel like you're not qualified for the job you already have, you should be more confident, and then you'll be fine." This sometimes is as simple as, "Don't feel that way," which is not very helpful as advice goes. But even when it's more nuanced than that, there's a focus on confidence and past accomplishments.

### Confidence doesn't help you _respond to challenges_
#### Henderson & Dweck, 1990

But here's the catch. Dweck's research shows that confidence doesn't actually predict your success at responding to new challenges or recovering from setbacks.

Henderson and Dweck did a study of students moving from elementary school to junior high in the U.S. They asked the students to assess their confidence when they were still in the younger grade, and they also measured whether the students held fixed or growth mindsets. Then they tracked the students' academic performance in junior high.

They found that confident students with a fixed mindset suffered academically. By contrast, students with a growth mindset tended to thrive academically, regardless of whether their confidence was high or low. Confidence wasn't a useful predictor of success at all.

Now, there's lots of other research that shows confidence is correlated with success. Dweck argues that confidence is a good predictor of how well you can do _things you're already doing,_ but it's not a good predictor of how you respond to new challenges and how you feel about failure.

The second, related point that Dweck has discovered is that a history of success also doesn't impact how you respond to challenges and how you deal with failure.

So past successes don't predict your response to new setbacks and failures, and your confidence level also doesn't predict your response to failure. The thing that is a good predictor of resilience in the face of failure is having a growth mindset.

### Break the framework

This is hugely exciting to me and I think it doesn't come up nearly often enough in the discussions around impostor syndrome. This gives us a new and more useful framework for combating impostor syndrome. Basically, if you're holding a fixed mindset, you're going to be really stressed and afraid at any moment that you have to struggle. We're programmers, so it's _mostly_ struggle, right? It's struggle all the time. With a growth mindset, you can enjoy the struggling and enjoy working on something that's really hard.

And guess what? When your identity isn't being threatened by a particularly tricky bug, it's a lot easier to stay focused on the bug. You're not worried about also getting fired and being a fraud, so you can free up those cognitive resources to focus on the task at hand.

So, again: if you believe, for example, that "some people just aren't cut out for programming," you can spend a ton of time & energy trying to find evidence and validation and reassurance that you are one of the people who can make it. Instead, upend this framework. Break the idea of fixed levels of talent and move to the idea that everyone can increase their skill by exerting effort.

#### _Self-theories: Their role in motivation, personality, and development_

Having a growth mindset makes you more resilient to failure, makes it easier to exert effort, makes you more likely to take on challenges, all things that are very useful to programmers.

If you'd like to dig more into the details of this research, and also see some of the findings that I didn't have time to cover today, I highly recommend a book Dweck wrote called [_Self-theories_](http://www.amazon.com/Self-theories-Motivation-Personality-Development-Psychology/dp/1841690244).  Self-theories is a collection of short essays that summarize many major points of her research. It's got detail about the studies but is accessible to a lay reader. She's also got a book called _Mindset_ that's written for a pop-science audience, but if you want a little more nuance and detail about the particular studies, _Self-theories_ is the way to go.

### Q & A
A selection from the Q&A:

_Q_: Is there any research in growth and fixed mindsets at the team-level, and how teams approach problems?

_A_: I'm not aware of any, but that's a fascinating question. I'd love to see that research if it exists.

_Q_: I read Mindset, and I'm a father to twin girls. I found that these strategies really changed their resilience and their approach to problem solving.

_A_: Yeah, this research is kind of terrifying. Like, do you tell your children that they're smart? You're ruining them! I didn't have a chance to talk about this, but there is some research in this book about gender discrepancies, and findings that high-achieving girls are more likely to have a fixed mindset and less likely to risk failure when they hit something hard. Many of the women in the room in particular can probably relate to this.

_Q_: Is this binary, or a gray scale?

_A_: I think it probably is a spectrum, yes. For this research it's classified into a binary model. I'm not precisely sure where the line gets drawn. And some of these cases with experimental induction of a fixed or growth mindset, if someone has one mindset going in and has the other induced, they'll probably end up in a moderate place.

_Q_: Is it possible to have a fixed mindset in one area and a growth mindset in another?

_A_: Absolutely. One that is common for programmers is to have a growth mindset about programming and a fixed mindset about social skills.

_Q_ (from a CS lecturer/TA): For our new students, is there a way we can create a growth mindset in the students? A lot of people come in from school with a fixed one, and it can be damaging in those early courses.

_A_: If you're a lecturer or have a chance to get up in front of the auditorium, you can say it explicitly: "Programming is a skill that you can get better at with effort," and even though it doesn't sound like it'd convince people, the research shows that it does make a difference.

The other thing that's really interesting is a study on a values exercise. This shows that having women in particular write down their values before they enter into a context where they'd experience stereotype threat can significantly improve their performance. The basic idea here is if you're identifying as a programmer, and your programmer identity is threatened, that's very painful and difficult. But if you have these other things that you value about yourself, then that mitigates the threat. The results are really dramatic for people who are marginalized in tech (and it doesn't hurt those who aren't).
For more, see [this worksheet](https://github.com/hypatia/virtuoso/) by Leigh Honeywell.

_Q_: So this is nature versus nurture all over again, isn't it?

_A_: I wouldn't characterize it that way, in part because I think both of those remove agency from the individual. Your mindset is something that you can control to a significant extent. That's why I think it's so important to think about this research from the context of ourselves, and not just our children or our students.

_Q_: It's easy to think of lots of ways to apply this in programming, but can you talk more about ways to apply this in social situations?

_A_: Sure. In the study covered in a _Self-theories_, Dweck had children write letters applying to the pen pal club (which was a real pen pal club - they did eventually match people up). Then all the children got rejected from the pen pal club. [Audience laughter] Before writing the letter, they'd told half the children, "This is to see how good you are at making friends," and the other half, "This is a chance to practice and improve your ways of making friends." The children who heard the fixed-mindset framing sometimes wrote the same letter or sometimes wrote a shorter and less detailed letter. The kids who got the growth framing were much more likely to write longer things, to be more inviting, to say, "Oh, I love talking to you" even though it's a first letter to a pen pal. [Audience makes sympathetic noises.] Yeah, throughout this book Dweck and her collaborators were pretty careful to not traumatize any students, not to leave them thinking that they're stupid or bad at making friends.

If you're interested in particular strategies for social situations, I highly recommend the blog [Captain Awkward](http://captainawkward.com/). Captain Awkward has some constructions of social challenges, like "I'll go to a party and talk to three people, and award myself ten points for each person I talk to and learn a fact about." There's a lot of interesting stuff on the internet about strategies for coping with social anxiety that I think you can apply whether or not that's something that you struggle with.

### Thanks

My thanks to Maggie Zhou, Amy Hanlon, Alyssa Frazee, and Julia Evans for feedback on early versions of this talk.

Thanks to Sasha Laundy, who invited people to consider what they wanted to get out of her [PyCon talk on giving and getting help](https://www.youtube.com/watch?v=hY14Er6JX2s), and inspired me to use the same construction.

Thanks to the Kiwi PyCon organizers, particularly Marek Kuziel, for hosting me.
