**Chris Benson:** Welcome to another episode of the Practical AI podcast. I am your co-host, Chris Benson. Usually I have my other co-host, Daniel Whitenack with us. He is not able to join today, but we have a great show in store. We have with us a super-interesting guest, that you may very well if you follow AI, have heard about this guest and this company, doing some super-cool stuff... So I'd to introduce Anastasis Germanidis, who is the co-founder and CTO at Runway. Sorry, I screwed up your name there. Did I get it anywhere close to right there?

**Anastasis Germanidis:** Yeah, all good. Thanks so much for having me.

**Chris Benson:** No, sorry for the stutter there. Thanks for joining us on the show. You guys are doing some really cool stuff at Runway. I wanted you to actually, before we dive fully in, tell us a little bit about your own background, and then we'll dive into the environment that you find yourself in, and the industry, and what kinds of problems out there are interesting as we dive in. So first of all, CTO of a hot AI company - how did you get there? How did you get to where you're at right now?

**Anastasis Germanidis:** Well, the first thing I would say is that I did not get here by planning for it. I think in some ways I was planning against being where I am today. So just to give you the background... So my background is a hybrid of engineering and art. So for the past decade or so I've been in different startups, working as an engineer, at the same time having my own art practice, and so doing a variety of work in media arts and interactive arts. Runway was the first time where those two different worlds have converged for me, but Runway started in art school. So this is not really where AI companies get started usually.

So my motivation for going to arts school was actually to take a break from technology, to really explore the more creative and in some ways open an exploration of those technologies without any concern about making something that would make a commercial sense at some point. But it just so happened that I met my co-founders there, and we started making those small tools, and one thing led to another, and we realized that this was a really useful thing to build out and spend our focus time on.

**Chris Benson:** It sounds like it was a bit of a passion project, without that commercial intent upfront in the beginning; you fell into it, because it was what you loved.

**Anastasis Germanidis:** Yeah. And I think that's how the best things get started. And that's been a general pattern, I would say, not just at the start, but just throughout. The way we built the company is -- there's this book that we give to every employee that's called "Why greatness cannot be planned", and it just talks about this idea that when you have very concrete goals in mind, it's actually very often you end up not meeting them, and sometimes going for the next stepping stone is the right approach to actually get to a very interesting findings or novel insights. And so that's been part of how Runway started, and that's part of how Runway has continued to grow.

But yeah, initially, I would say our main goal was - like, these machine learning models are super-difficult to understand, super-difficult to use, especially when we started around five years ago... But they're super-interesting for artists, and they can make really compelling things with it once they get to the point where they can actually use them. At that point, generative models, AI was at an earlier stage, in terms of both how many people cared about it, and also the results of those models... But it was still even at that point really useful for our days, the moment we gave the right tools for them to use it. And so that was the inception of Runway.

**Chris Benson:** I'm curious, recognizing that there wasn't the master plan that you were implementing, there was a bit of serendipity to how you arrived there... I am curious, you mentioned that you would set aside technology before you were going back into art right there... And I'm curious, did the technologies you were in prior to art school play into where you've come out here with in terms of Runway being that end result? Is there any connection there, or you just happened to be in a different area and were finding AI? Were you active in AI prior to going back into art school?

**Anastasis Germanidis:** My interest in AI goes back to at least high school and before. Before Runway I was working as a machine learning engineer, as some kind of distributed systems engineer at different companies. So I definitely had a background in this area, was very interested in AI. My interest was specifically in neural networks, which decades ago they had become kind of an ignored area of machine learning. They were seen as a dead end. That they wouldn't be able to -- at that point support vector machines were out there; those kinds of models were more popular. But there was still something very compelling about neural networks that made me actually get started working with them from high school, with some initial projects.

\[00:06:01.01\] So I've been very interested in AI throughout. The motivation for going to art school was -- just to give more context on the kinds of art school. It's a program at NYU that was exploring the intersection of art and technology. Technology was still part of it, but it was less technology for the sake of technology, or just novelty for the sake of novelty; more understanding how the technology could be used in creative ways, or in ways that are maybe unconventional.

**Chris Benson:** As you were coming into art school and you have this background as machine learning engineer, and the passion for art, what has been your initial vision for that industry? Within entertainment, human creativity, which are things that you currently are targeting, how did you see them? How did you expect to be able to impact the industries with AI going into the process? So things are moving so fast, and we're seeing these amazing technologies which we're going to be talking about in the minutes to come... But I'm really curious what your perspective was about where this was going for art and entertainment prior to actually arriving there?

**Anastasis Germanidis:** The perspective for us has always been that those models, those techniques are never gonna be a source of ideas, they're gonna be an acceleration, an expression of creators ideas. This is the mindset that we started building those tools around. And that's why from the beginning we started working very closely with filmmakers, or designers, or with artists, in making those tools and getting their feedback on how to make them.

The other aspect too in terms of how we were seeing the trajectory of those models was when we look back at 2017, or 2018, when we'd just started working on this, the results of those models were pixelated, low resolution, very experimental, the composition was off... But you could see the trend very clearly, that every year the resolution was doubling, the fidelity was improving in a fairly predictable way. And so it was not a matter of if, it was a matter of when this would arrive. Timing those things is always really difficult, so we didn't really know exactly when we're gonna get to this breakthrough where those models really start becoming actual useful... But we knew that it was going to happen at some point in the next years.

**Chris Benson:** Most people who were machine learning engineers - and I work with university students a lot, and people at the company I'm at now, and previous companies, and that's their dream job. And it's really interesting to me that you said "I'm going to set that aside for a little bit, and go and do art school." What was the driving factor for you? Because obviously, for your story, that turned out to be crucial, that juxtaposition, if you will, of those different factors. I'm just curious, what made you say "I think I'm gonna put down machine learning engineering for a while, and go back to art school"? I was just curious what that was, because obviously, that seemed to create a perfect environment for you to spring from.

**Anastasis Germanidis:** I would say mainly just the motivation and the need to explore the possibilities of something without a very clear expectation that it needed to result in a tool that was necessarily useful. Just being in an environment where I can have this open exploration of the possibilities of this technology. It was less that I wasn't interested in machine learning or wanting to get away from it, it was more I wanted to explore it in a context where there was no expectation to build something that was commercially viable, or super-useful.

Of course, that took a turn, and it ended up -- that was a way to get to something that ended up being a very good fit for a company, but I would say initially I was very interested in... At some point, I think in 2015-2016, there was just starting to emerge just this new movement around making art with AI. And there were some initial explorations, a lot of them in the open source world.

\[00:10:07.23\] And I just started contributing to making small projects around making tools to make art with AI... And so I really just want spend more time building those things, and less in purely the industry working with machine learning... Because I think those two things - you're working with the same underlying models and the same technologies, but the actual results are very different that you're creating with them.

And one more story from art school to illustrate - one of the first projects that we've built with my co-founder Chris was this drawing tool, essentially, where... There was this model that Nvidia released, that was meant for self-driving car research. And the main idea of this model was you could give a layout of -- essentially street view. So an indication to where pedestrians are, or the road is, or other cars are, and then generate an image using that layout. It doesn't sound like the most creative model or creative use case for a tool. The context of that model was very much as part of self-driving car research, and just creating synthetic data for that, and so on... But we decided to build this drawing tool around it where you could define kind of the layout of a scene, and then generate street views based on that layout.

We saw that the moment we gave it to artists, the kinds of scenes that they were creating were super-different than what the regular output of that model was. They would create giant pedestrians, or street signs flying from the sky...

So there's the same insight there that you're working with the same types of models, the same types of technologies, but seeing them with a fresh set of eyes, and a different perspective makes all the difference. And so this is what I came to art school to do, is to see the same underlying ML/AI technologies with a new set of eyes, exploring new possibilities. And this is what we hope to do also with the tool itself.

**Break**: \[00:12:16.05\]

**Chris Benson:** So you arrived at art school for that purpose of seeing all this through a new set of eyes, and you met your co-founder, Chris, and you guys had that spark of an idea which would become Runway. Can you talk a little bit about the insight that you had there, that created Runway? Before we dive fully into what Runway has done since, I'm really curious what the moment where you and Chris said "We have something here. This is something we're gonna go do." Was there a distinct moment? Did you just gradually arrive there? What was that moment like where you decided it's time to go be an entrepreneur in this context?

**Anastasis Germanidis:** So I wouldn't say it was one moment that was the turning point... So we were working on a lot of different projects with Chris and Alejandro, the other the co-founder. And each of those projects was a standalone tool around helping for, let's say, specific art projects for an artist, or for a specific medium or a specific kind of contexts. Over time, we realized that there was a lot of the same things that we had to do for each new project, and at that point being able to run models was even more difficult than it is today. Even running a Google Colab notebook was too much to ask sometimes for artists without any technical background or know how about how those models work.

So the initial idea was let's start from what's already out there in the open source world; there is already a wealth of different models, that perform different tasks. But let's make a creative tool around them. So let's bring the interface and the experience that artists are familiar with from other creative tools, but use those new models that were coming out that had all these interesting possibilities on the backend. That was the main idea of Runway initially. Also, as I mentioned before, that vision was there from the start that as these models were becoming better and better, the applicability of those models would go increasingly more from the more experimental use cases to something that's actually arriving in production, and it's really, really useful for a variety of creative workflows. And we saw that happen very quickly after starting Runway.

**Chris Benson:** You mentioned along the way there that the difficulty of implementing some of the models, and even today, with a number of different choices out there, it's still something that many companies are contending with, is how to address models, how to train them, where they're going to train them, what the deployment, how it fits into products... There's a gazillion questions out there. You were doing this at a moment where that wasn't even as sorted as it is now. And it's still in development at this point. How did you manage that? Because when I've talked to other people, that's often been one of the biggest challenges, is just getting the resources in place, especially at that time when it was still in early development. What was that like to try to bring your vision out, when obviously the environment that we were doing AI in was still fairly exclusive in a lot of ways, in the sense of access to expertise, resources... You're in an art school that's designed to help you do that, but that couldn't have been easy.

**Anastasis Germanidis:** Yeah, so we essentially had to figure out a lot of things from scratch as we were building this. So as I mentioned initially, Runway was based around providing access to existing open source models, but we quickly actually realized that we needed to build an in-house research team in order to really get those models from something that makes a good demo, or a good prototype, to something that's really useful. So that was actually from the first few months or Runway, it became very clear that we needed to do this. Of course, none of us really had built a research team before. I had an engineering and some ML/AI research background, but the experience of how to build the team, what skill sets to bring in was the -- nobody on the team had it. And so a lot of the things we just had to figure out from scratch.

\[00:17:45.07\] One nice thing I would say is that because we started so early, we had years to figure this out. So if you're just coming into AI, as part of building a new company today, the time horizon - you need to figure those things out in a much more accelerated fashion. So for us, we spent the first year figuring out what does it mean to actually build a research organization within a startup? And what does it mean to build a robust deployment pipeline, so that you can not only serve those models, but also serve them interactively? ...because a big part of the way we build tools at Runway is the interaction is a very key aspect of really making those models useful.

**Chris Benson:** When I've talked to other entrepreneurs about this, they have a tough time -- as you're getting to the place where you're at now in terms of being able to... You all have the research, you're doing amazing research, but you had to get from A to B in the meantime, and keep the company alive... How did you approach from a funding customers, things like that, while you were figuring all these things out? Because that strikes me as a pretty hard problem to tackle as you're moving along, but you still have to pay the bills, if you will. How did you tackle those kinds of issues in terms of creating an AI startup that couldn't instantly be everything that it is today, from day one?

**Anastasis Germanidis:** I would say the main insight is we want to make sure that Runway was useful at each stage of its evolution. So even though the generative models were not quite as powerful back when we started as they are today, they weren't as big a part of the initial tool offering, and we wanted to make the tool as useful from the very beginning as possible.

So the product of Runway went through many evolutions that really track how the AI models evolved, and which states were useful for which things. A big part of early Runway was building out a video editor that was really combined some of the more traditional video editing techniques with AI-based techniques, to speed up the process of a lot of video editing workflows. And that wasn't necessarily something that had generative models powering it, but it was a really useful tool, that really gave us a lot of insight about how to do tools that are really useful for creating workflows, and how to really solve real pain points \[unintelligible 00:20:05.23\]

But at the same time, while we were building those tools, we also had this research that was ongoing, that was still remaining in a kind of more academic level of just really demonstrating how we can improve the results of generative models. And at some point, there was that intersection point where we started bringing those generative models to production.

So the overall strategy was we knew that generative models would be really powerful given enough time, if we invest the resources on the research side. At the same time, we knew that at the beginning not everything is to be powered by generative models. So we were building a lot of AI-based tools that were really useful from the beginning, and that were used by video effects artists, by video editors to speed up a lot of their workflow, even far before we released things like Gen-1 or Gen-2 for text and video functionality.

**Chris Benson:** You're saying generative, but it was definitely the early days of generative... And certainly, right now it's all the rage. Everyone's talking generative in every context. But you had some insights into that. You talked about the fact that you guys knew that that was going to be the case going forward... But to your credit, not everybody did. A lot of people went "A-ha' much later than you went "A-ha." And I'm curious, is there anything that stands out as what drove the insights that you guys had, and why? Because you were really one of the very first to get these kinds of functionalities to product. That's very notable. And you might say the rest of the world didn't; not that many. So what were some of the things that gave you that confidence to say "This is clearly going to be critical to our future. This is going to drive the industry" at an early stage? You were pioneering that thought process. How did you get there?

**Anastasis Germanidis:** \[00:22:03.07\] From the very beginning, a big part of Runway was working directly with artists in building these tools. And so when we gave them even early versions of generative models, we could already see that there were really compelling aspects of working with them, even if the results were low resolution, or not as high fidelity. So early forms of things like prompt engineering, figuring out how to traverse the latent space of those models were still there at the beginning of Runway. And we saw how artists were engaging with them, how they were finding it to be really compelling and really useful.

And so really, part of it has been just having this early view into how artists would -- more early adopters, I would say, were engaging with those models... And just extrapolating that; once those models improve, other people will equally find them as compelling.

So working with artists, I think, has been a really important part of just really understanding the future of those models, and extrapolating of how they will be used. And also just looking at history of art, and tool making was always part of -- like, how new tools always allowed to create new art movements, or allowed new kinds of genres to emerge... And just assuming and predicting that the same would happen with those generative models.

**Chris Benson:** Along the way, as you were going down this path, what stumbles did you have as part of putting -- because it's quite remarkable, because you clearly could see the future before you got there, and with more clarity than others that might be in a similar position. As you did that, what kinds of things were either unexpected, or challenges that were bigger than you thought? You know, the things where maybe at a moment in time you were grinding your teeth and going "Argh, this is not exactly how I had it planned"? Do you have any stories to that effect during this process?

**Anastasis Germanidis:** Many stories and many learnings along the way, for sure. I think the biggest recurring insight that we've had around how to build for those tools, and the thing that I think that's still not fully appreciated today is how important control is in terms of interacting with those models. So every time we invested into adding more ways in which you can really control the outputs of the models that people were using inside Runway, we saw a whole new set of possibilities and whole new kinds of usage. That has been a really consistent theme.

Even at the beginning, we just saw that those models had a lot of flaws that might not always -- like, if you have a very simple way of controlling them, they might not really give you what you want, and you might have to do a lot of trials with the same \[unintlligible 00:24:47.25\] to get to where you wanted, your desired result. And so that's really what we saw with the early -- when we first released Gen-2, you could only control things with a text prompt, and we saw very quickly that that led to people just generating tens, or hundreds of outputs in order to get to the result that they wanted. And so we invested continuously, adding more and more ways in which you could manipulate things, essentially, as a film director would think about creating a scene.

So a film director would have a vision; not just a high-level description of what the scene is, but how the camera moves in a scene, or how do the characters interact with each other. So having ways in which you can control really the camera motion, or the motion, the object motion, the motion of the characters in the scene - all those things that make total sense from a creator's point of view, but they're not necessarily how maybe ML researchers would necessarily think about those models. I think there has been always the insight that we never saw negative effects from adding more and more ways of controlling those models.

**Break**: \[00:26:02.26\]

**Chris Benson:** So before the break, you brought up Gen-2, and we've had a little bit of a history on the development, which is fascinating; it's an incredible story you have. Tell us all about Runway today. You've arrived here, you have Gen-2... Just talk a little bit about how you're impacting industry today. For listeners who haven't been to your website, you talk about advancing creativity with artificial intelligence, and you specifically note that you're an applied AI research company shaping the next era of art, entertainment and human creativity. What does that mean in 2024, as you're out there in this space? Can you talk a little bit about the company as it is now?

**Anastasis Germanidis:** Yeah. To give some context, Gen-2 is a text to video and image to video generation model. So essentially, it takes a description of a scene and then generates a video output from that scene. And it's one of the many models that we have at Runway; the most well known one.

The broad vision of the company has remained the same over the last five years, and it's understanding and creating the new generation of creative tools, and then working with artists directly to figure out, to help them shape those tools as much as possible. So I think where we are today is - I would say we're still at the very early stages of where those models can go. I think video generation - this is really the year where video generation gets really good. And so we're really excited to be part of building out those technologies and figuring out how to work with artists to make them as useful as possible.

We've seen over the past year, since we've released Gen-2, film studios, streaming companies, ad agencies kind of adopting Runway. And that adoption is not just from individual creators, but it's really we see companies starting to use those models and incorporate them into workflows. And I think it's not going to be a binary shift where we go from not using generative models at all as part of making video or making art, to using it everywhere; it's a more gradual transition. And for us, the big goal is teaching folks how to use those models, supporting other creators that are making interesting things with those models. So we have an AI Film Festival where we showcase films that use AI in different ways.

So I would say for us the goal is very much holistic, of we do the research, we create the research and development and building out the next generation of those models, we build useful tools around those models, and we also work with artists and companies that want to adopt those models in their creative workflows.

**Chris Benson:** As you have been working into this for years, for most of the rest of the world the past few months have been a big eye-opener, particularly with the cloud companies producing their models and stuff, and competing in that. There's the obvious aspect of you have the industries that you're playing in and that you're strong in... But what concerns do you have from a competitive standpoint against other companies, especially these big all-encompassing cloud companies that are in the sort of AI arms race to produce the ever larger, more capable model? At no point in this conversation have you expressed any concern, have you raised that, or anything, which is quite notable. Usually people are a little bit worried about that, and you seem very strong in your space... How do you see those other big players that are out there? Do you see them as competitors even, or are they far enough from you that that's not a big deal? Or are you so tightly into your the industries that you're serving specifically that you have a huge competitive advantage? How do you see all that?

**Anastasis Germanidis:** For us, we've always had the perspective and mindset of running our own race, and so we try not to be too distracted... Especially these days, there's so much noise and discourse around AI that it's easy to get stuck in following the latest developments. So I think that's the number one aspect.

\[00:32:00.04\] When we first released Gen-2 last year, one of our positions that was not as popular last year was that video generation modules were gonna be the -- like, video was the modality that encapsulated as much world knowledge and usefulness as possible. And last year, a lot of the focus was on language, and for us it was a bit unorthodox to maybe pay so much attention to media specifically, and claim that video generation models were really the way to build really broadly useful AI systems.

And over the past months, we've seen more companies entering this space of video generation models, and so it was nothing unexpected. We know that those models are going to be really useful for a wide variety of use cases. They're going to be useful beyond building creative tools, which is really our focus. And so for us, it's really important to maintain that focus, of really not just building those models, and making cool demos around that, but really figuring out -- like, bridging that gap between those demos and really deploying them to products and really getting people to use them and making them controllable.

So there is still that gap, I would say, from doing just the research and developing the model, to actually making those models controllable and deploying useful tools. And for us, always it has been the focus to bridge that gap, and that continues to be our focus. So again, video generation models are still very early, and we haven't seen anything yet about what they'd be ultimately capable of. You can imagine a year from now, two years from now, every company is going to have a photorealistic video generation model, and that's an assumption we're making, that the competitive advantages shift over time. And at that point, what's the differentiation of Runway? For us, it's always been working very closely with artists, building really useful tools, and bridging, and making those models really controllable and useful.

**Chris Benson:** It's fascinating to me, because I talk to so many people in different companies, and they're busy trying to just AI everything, and they're kind of all about AI... You guys are doing the AI, but it sounds like competitively having been so embedded into the artistic ecosystem with your tooling is really something that keeps you right there, while everybody goes through the AI model wars, in terms of trying to produce so much. Do you think that long heritage of the toolmaking is probably key to your future, in that sense? Is that how you're thinking about it?

**Anastasis Germanidis:** I think it's the most important aspect of how we're operating. Otherwise, again, it's too easy to get lost in the short-term race of just having a marginally better model for a few weeks, versus really having the mindset of building the most useful tool long-term, and then obviously updating the model, making sure you get state of the art results with it... But it's not the goal. It's not the focus to have the best model. The focus is to get artists to make the coolest things, or the most compelling things with those models. And if that remains the goal, then that also informs how we build those models.

Another aspect of Runway is just - we have a research team, and then we also have a creative team in-house, that works with the research team on a daily basis, and tries out the latest models, informs through the research what controls we need to add to the models... And having that perspective, is really -- when I talk to researchers that work in academic labs, that are large industry labs, they might publish papers about the potential creative applications of those models, but they don't interact with artists daily. They don't often know "Is this actually useful, or is it just a hypothesis that I'm making?" And at Runway, as a researcher, you get that feedback on a daily basis, and I think that really changes how you approach building those models.

**Chris Benson:** \[00:35:56.02\] For listeners, you and I can see each other, though this is an audio-only podcast, but you had this glint in your eye a moment ago, when you were talking about where you expected these video models to be going... For just a minute there, you reminded me of the kid in the candy store; you can see your passion really flying out of your eyes there. And obviously, I'm the only one that could see that.

Talk a little bit about where you think this is going. That's what everybody is wondering. There's so many questions that people have in terms of how video fits in their life, what life becomes like when you have generative capabilities that essentially simulate life in so many ways... What are you expecting over the next year or so? I'm not holding you to it, obviously, but just what do you anticipate might happen in the video space generatively, and then how would you see it several years out, when it's exponentially had time to grow? What does that look like to you?

**Anastasis Germanidis:** The way we would like to think about those generative video models is we have this term of general world models. Essentially, they simulate different aspects of the world, because in order to -- kind of similar to how you have large language models that have been trained with a very simple task, to just predict the next token in a sentence. In order to predict the next token and perform the task really well, they have to gain all this understanding about different aspects of human knowledge, different aspects of the world, just to solve this task well, because they need to complete sentences that might come from an encyclopedia, or a foreign poster. It's like a wide variety of cases that they need to handle.

So we think very similarly on how the vision generation models operate. In order to predict the next frame, you need to gain not an understanding of the basic rules of motion, or physics, you really need to gain a more comprehensive, a broader understanding of the world. And so if I think a year from now where did those models go - essentially, becoming more higher fidelity simulations of the world, giving you the ability to really imagine all sorts of different scenarios, build out and tell all kinds of different narratives and stories... And I think that the applications of that are really -- there's wide-ranging application there, that goes beyond the current content creation use cases, which I think for us still remain the focus... But just building models that can perceive the visual world - of course, it can be used in all kinds of other ways as well.

**Chris Benson:** Thank you for sharing your story. As we finish up here, we have a lot of young listeners on the show, and I guarantee that there are quite a few young artists that are technically inclined out there. You know, high school, maybe early college age... And they're listening to this and they're going "That guy just lives the life that I'm wishing I could live. That's the kind of thing that I want to do." What would you -- whether they identify themselves as a young artist, who's technically-inclined, or technologists who love art, however they see themselves, do you have any guidance on how they might step into the future and get to that sweet spot for them, given the fact that clearly the technology, specifically with AI, and the artistic world will continue to merge and develop together for years to come? Where should they go, what should they do? Any thoughts?

**Anastasis Germanidis:** I would say the number one thing is following your curiosity and tinkering as much as possible. So there is a lot of ways in which you can start building those models yourself, you can start running them, you can start to get an understanding of what you can do with them... And that's available to really anyone. And so really, you can start getting involved today in building projects, exploring AI, or making creative projects with AI. That would be the number one thing.

It's also, I would say for me planning, trying to plan ahead too much has never quite worked. Really focusing on what I can build today, work on a curiosity and interestingness will drive me next. It has always been the guiding principle. And so that would generally be my recommendation, is not trying to think of where technology will be five years from now, because really nobody can fully plan ahead, but rather trying to really build interesting things today. It's actually surprisingly, I would say, easy to -- if you start making projects open source, and just showing them to others, it can be quite fast that you can get noticed for those projects. And you can start to build a community around them, work with other people and collaborate on your projects... And with those collaborations, one by one, you can get to a point where you can start doing this work full-time. So really focusing on the next project, I think, for me has been really the way to go.

**Chris Benson:** Well, Anastasis, thank you so much. That was fantastic guidance. Appreciate your perspective; fascinating story leading into this, and especially in all the early insight that you guys had. Thanks for coming on and talking about Runway and the world in which you guys are trying to make a bit better. I appreciate it.

**Anastasis Germanidis:** Thank you, Chris.