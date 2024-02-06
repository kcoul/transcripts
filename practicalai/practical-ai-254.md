**Daniel Whitenack:** Welcome to another Fully Connected episode of the Practical AI podcast. In these Fully Connected episodes we try to keep you up to date with everything that's happening in the AI and machine learning world, and try to give you a few learning resources to level up your AI game. This is Daniel Whitenack. I'm the founder and CEO of Prediction Guard, and I'm joined as always by my co-host, Chris Benson, who's a tech strategist at Lockheed Martin. How are you doing, Chris?

**Chris Benson:** Doing very well, Daniel. Enjoying the day. And by the way, since you've traveled to the Atlanta area tonight, we haven't gotten together, but you're just a few minutes away, actually, so... Welcome to Atlanta!

**Daniel Whitenack:** Just got in. Yeah, we're within - not maybe a short drive, depending on your view of what a short drive is...

**Chris Benson:** Anything under three hours is short in Atlanta, and I think you're like 45 minutes away from me right now.

**Daniel Whitenack:** Yeah, so hopefully we'll get a chance to catch up tomorrow, which will be awesome, because we rarely get to see each other in person. It's been an interesting couple of weeks for me. So for those that are listening from abroad maybe, we had some major ice and snow type storms recently, and my great and embarrassing moment was I was walking back from the office, in the freezing rain, and I slipped and fell, and my laptop bag, with laptop in it, broke my fall, which is maybe good... But that also broke the laptop. So -- actually, the laptop works, it's just the screen doesn't work, so maybe I'll be able to resolve that...

**Chris Benson:** It's like a mini portable server there, isn't it?

**Daniel Whitenack:** Yeah, exactly. You have enough monitors around, it's not that much of an issue... But yeah, I had to put Ubuntu on a burner laptop for the trip. So yeah... It's always a fun time. Speaking of personal devices, there's been a lot of interesting news and releases, not of -- well, I guess of models, but also of interesting actual hardware devices related to AI recently. One of those is the Rabbit R1, which was announced and sort of launched to preorders with a lot of acclaim.

Another one that I saw was the AI PIN, which is like a little -- I don't know, my grandma would call it a brooch, maybe. Like a large pin that you put on your jacket, or something like that... I am wondering, Chris, as you see these devices - and I want to dig a lot more into some of the interesting research and models and data behind some of these things like Rabbit... But just generally, what are your thoughts on this sort of trend of AI-driven personal devices to help you with all of your personal things, and plugged in to all of your personal data, and sort of AI attached to everything in your life?

**Chris Benson:** Well, I think it's coming. Maybe it's here... But I know that I am definitely torn. I mean, I love the idea of all this help along the way. There's so many -- I forget everything. I'm terrible. If I don't write something down and then follow up on the list, I am not a naturally organized person. My wife is, and my wife is always reminding me that I really struggle in this area. And usually she's not being very nice in the way that she does it. It's all love, I'm sure... But yeah, so part of me is like "Wow, this is the way I can actually be all there, get all the things done." But the idea of just giving up all my data, and just being -- like so many others, that aspect is not appealing. So I guess I'm -- I'm not leaping.

**Daniel Whitenack:** How much different do you think this sort of thing is than everything we already give over with our smartphones?

**Chris Benson:** It's a good point you're making.

**Daniel Whitenack:** I mean, we've had computing devices with us in our pocket or on our person 24/7 for at least the past 10 years; at least for those that have adopted the iPhone or whatever, when it came out. But yeah, so in terms of location, certainly account access and certain automations, what do you think makes -- because obviously, this is something on the mind of the makers of these devices, because I think both the AI PIN and the Rabbit make some sort of explicit statements in their launch, and on their website about "Privacy is really important to us. This is how we're doing things, because we really care about this." So obviously, they anticipated some kind of additional reaction. But we all already have smartphones. I think most of us, if we are willing to admit it, we know that we're being tracked everywhere, and all of our data goes everywhere... So I don't know, what is it about this AI element that you think either makes an actual difference in terms of the substance of what's happening with the data? Or is it just a perception thing?

**Chris Benson:** \[06:11\] It's probably a perception thing with me. Because everything that you said, I agree with; you're dead on. And we've been giving this data for years, and we've gotten comfortable with it, and that's just something that we all kind of don't like about it, but we've been accepting it for years. And I guess it's the expectation with these AI assistants that we've been hearing about for so long coming, and we're starting to see things like the Rabbit come into market, and such, that there's probably a whole new level of kind of analysis of us, and all the things, and in a sense knowing you better than you do, that is uncomfortable and probably will not be as uncomfortable in the years to come, because we'll grow used to that as well. But I have to admit, right now it's an emotional reaction, and it makes me a little bit leery.

**Daniel Whitenack:** Yeah, maybe it's prior to these sorts of devices there was sort of the perception at least that "Yes, my data is going somewhere. Maybe there's a nefarious person behind this, but there's sort of a person behind this. Like, the data is going all to Facebook or Meta, and maybe they're even listening in on me, and putting ads for mattresses in my feed", or whatever the thing is... So that perception has been around for quite some time, regardless of whether Facebook is actually listening in or whatever. Or it's another party, like the NSA and the government's listening in... But I think all of those perceptions really relied on this idea that even if there's something bad happening, that I don't want happening with my data, there's sort of a group of people back there doing something with it. And now there's this sort of idea of this agentic entity behind the scenes that's doing something with my data, without human oversight. I think maybe that's -- if there's anything sort of fundamentally different here, I think it's the level of automation and sort of agentic nature of this, which does provide some sort of difference. Although there's always like - you know, if you're processing voice or something, there's voice analytics, and you can put that to text, and... Then there are always NLP models in the background doing various things, or whatever. So there's some level of automation that's already been there, but...

**Chris Benson:** I agree. You mentioned perception up front, and I think that makes a big difference... And you mentioned NSA. Intelligence agencies - I think we all just assume that they're all listening to all the things, all the time now, and that's one of those things that's completely beyond your control. And so there's almost no reason to worry about it, I suppose, unless you happen to be one of the people that an intelligence agency would care about, which I don't particularly think I am. So it just goes someplace and you just kind of shrug it off.

There's a certain amount of what we've done these years with mobile, where you're opting in. I think it's leveling up, as we're saying, with some of these AI agents coming out; we know how much data about ourselves is going to be there, and so it's just escalating the opt-in up to a whole new level. So hopefully we'll see what happens... I hope it works out well.

**Daniel Whitenack:** Yeah. We haven't really -- for the listeners maybe that are just listening to this and haven't actually... Maybe you're in parallel doing the search and looking at these devices, but in case you're on your run, or in your car, we can describe a little bit... So I described the AI PIN thing a little bit... The Rabbit I thought was a really, really cool design. I don't know if there's any nerds out there that love the sort of synthesizer analog sequencer, teenage engineering stuff that's out there... But actually, the sort of hardware design teenage engineering was involved in that in some way.

\[10:05\] So it's like a little square thing, the Rabbit R1. It's got like one button you can push and speak a command; it's got a little actual hardware wheel that you can spin to scroll, and the screen is kind of just - they show it as black most of the time, but it pops up with the song you're playing on Spotify, or some of the things you would expect to be happening on a touchscreen, or that sort of thing... But the primary interface is thought to be in my understanding speech; not that you would be pulling up a keyboard on the thing and typing in a lot. That's kind of not the point. The point would be this sort of speech-driven conversational - and I'd even call it an operating system - conversational operating system to do certain actions or tasks, which we'll talk a lot more about the kind of research behind that... But that's kind of what the device is, and looks like.

**Chris Benson:** It's interesting that, going with the device route, and the fact that they're selling the actual unit itself... And over the years we started on our computer, or we started on desktops, and then went to laptops, and then went to our phones... And the phones have evolved over time. And we've been talking about wearables and things like that over the years as they've evolved, but I think there's a little bit of a gamble in actually having it as a physical device, because that's something else that they're presuming you're gonna put at the center of your life. That versus being kind of the traditional phone app approach, where you're using the thing that your customer already has in their hands. What are your thoughts about the physicalness of this offering?

**Daniel Whitenack:** I think it's interesting... One of the points, if you watch the release or launch or promotion video for the Rabbit R1, he talks about sort of the app-driven nature of smartphones, and there's an app for everything... And there's so many apps now that navigating apps is kind of a task in and of itself. And that Silicon Valley meme, "No one ever deletes an app", right? So you just accumulate more and more apps, and they kind of build up on your phone, and now you have to organize them into little groupings, or whatever... So I think the point being that it's nice that there's an app for everything, but the navigation and orchestration of those various apps is sometimes not seamless, and burdensome. I'm even thinking about myself, and kind of checking over here -- I got into Uber, oh, I forgot to switch over my payment on my Uber app, so now I've got to open my bank app, and then grab my virtual card number, and copy that over... But then I've got to go to my password management app to copy my password... There's all these sorts of interactions between various things that aren't as seamless, as you might think they would be. But it's easy for me to say in words, conversationally, "Hey, I want to update the payment on my current Uber ride", or whatever. So the thought that that would be an easy thing to express conversationally is interesting; and then have that be accomplished in the background, if it actually works, is also quite interesting.

1**Chris Benson:** I agree with that. And I can't help but wonder, if you look back at the advent of the phone, and the smartphone, and the iPhone comes out, and it really isn't really so much a phone anymore, but a little computer... And so the idea of the phone being the base device in your life has been something that has been with us now for over 15 years. And so one of the things I wonder is, could there be a trend where maybe the phone doesn't become -- if you think about it, you're texting, but a lot of your texting isn't really texting, it's messaging in apps... Maybe the phone is no longer the central device in your life going forward, and maybe you're actually having your primary thing. That would obviously play into Rabbit's approach, where they're giving you another device, it packages everything together in that AI OS that they're talking about, where conversationally it runs your life, if you expose your life to it the way you are across many apps on the phone... But it's an opportunity potentially to take a left turn with the way we think about devices, and maybe in the not so distant future maybe the phone is no longer the centerpiece.

**Break:** \[14:40\]

**Daniel Whitenack:** Alright, Chris, well, there's a few things interacting in the background here in terms of the technology behind the Rabbit device, and I'm sure other similar types of devices that have come out. Actually, there's some of this sort of technology that we've talked a little bit about on the podcast before. I don't know if you remember we had the episode with AskUI, which - they had this sort of multi-modal model; I think a lot of their focus over time was on testing. A lot of people might test web applications or websites using something like Selenium, or something like that, that automates desktop activity or interactions with web applications... And actually automates that for testing purposes or other purposes. AskUI had some of this technology a while back to kind of perform certain actions using AI on a user interface without sort of hard coding; like, click on 100 pixels this way, and 20 pixels down this way. So that I think has been going on for some time.

This adds a sort of different element to it, in that there's the voice interaction... But then they're really emphasizing the flexibility of this, and the updating of it... So actually, they emphasize -- I think some of the examples they gave is I have a certain configuration on my laptop or on my screen that I'm using with a browser, with certain plugins that make it look a certain way... And everything sort of looks different for everybody, and it's all configured in their own sort of way. Even app-wise, apps kind of are very personalized now, which makes it a challenge to say "Click on this button at this place." It might not be at the same place for everybody all the time. And of course, apps update, and that sort of thing.

So the solution that Rabbit has come out with to deal with this is what they're calling a large action model. And specifically, they're talking about this large action model being a neurosymbolic model. And I want to talk through a little bit of that. But before I do, I think we sort of have to back up and talk a little bit about AI models, large language models; ChatGPT has been interacting with external things for some time now, and I think there's confusion at least about how that happens, and what the model is doing... So it might be good just to kind of set the stage for this in terms of how these models are interacting with external things.

The way that this looks, at least in the Rabbit case, is you click the button and you say "Oh, I want to change the payment card on my Uber \[unintelligible 00:19:07.21\] and stuff happens in the background and somehow the large action model interacts with Uber, and maybe my bank app or whatever, and actually makes the update. So the question is how this happens. Have you used any of the plugins or anything in ChatGPT, or the kind of search the web type of plugin to a chat interface, or anything like that?

**Chris Benson:** Absolutely. I mean, that's what makes the -- I mean, I think people tend to focus on the model itself. That's where all the glory is, and people say "Ah, this model versus that." But so much of the power comes in the plugins themselves, or other ways in which they interact with the world. And so as we're trying to kind of pave our way into the future and figure out how we're going to use these, and how they're going to impact our lives, whether it be the Rabbit way, or whether you're talking ChatGPT with its plugins - that's the key. It's all those interactions, it's the touchpoints with the different things that you care about which makes it worthwhile. So yes, absolutely, and I'm looking forward to doing it \[unintelligible 00:20:12.05\]

**Daniel Whitenack:** \[20:14\] Yeah. So there's a couple of things maybe that we can talk about, and actually, some of them are even highlighted in recent things that happened, that we may want to highlight also. One of those is, if you think about a large language model like that used in ChatGPT, or NeuralChat, LLaMA 2, whatever it is... You put text in, and you get text out. We've talked about that a lot on the show. So you put your prompt in, and you get a completion, it's like fancy autocomplete, and you get this completion out. Not that interesting.

We've talked a little bit about RAG on the show, which means I am programming some logic around my prompt such that when I get my user input, I'm searching some of my own data or some external data that I've stored in a vector database, or in a set of embeddings, to retrieve text that's semantically similar to my query, and just pushing that into the prompt as a sort of grounding mechanism to sort of ground the answer in that external data. So you've got sort of basic autocomplete, you've got retrieval to insert external data via a vector database, you've got some multimodal input... And by multimodal models, I'm meaning things like LLaVA. And actually, this week there was a great - published on January 24th, I saw it in the daily papers on Hugging Face... "MM LLMs: Recent advances in multimodal large language models." So if you're wanting to know sort of the state of the art and what's going on in multimodal large language models, I just mentioned - that's probably a much deeper dive that you can go into. So check out that, and we'll link in our show notes.

But these are models that would not only take a text prompt, but might take a text prompt paired with an image, right? So you could put an image in, and you say -- also have a text prompt that says "Is there a raccoon in this image?" And hopefully the reasoning happens and it says yes or no if there's a --

**Chris Benson:** Is there always a raccoon in the image?

**Daniel Whitenack:** There's always a raccoon everywhere... That's one element of this; that would be a specialized model that allows you to integrate multiple modes of data. And there's similar ones out there for audio, and text, and other things. So again, in summary, you've got text-to-text autocomplete, you've got this retrieval mechanism to pull in some external text data into your text prompt, you've got specialized models that allow you to bring in an image in text... All of that's super-interesting, and I think it's connected to what Rabbit is doing. But there's actually more to what's going on with, let's say when people perform actions on external systems, or integrate external systems with these sorts of AI models. And this is what in the sort of Langchain world, if you've interacted with Langchain at all, they would call this maybe tools. And you even saw things in the past like ToolFormer and other models where the idea was "Well, okay, I have - maybe it's the Google Search API", or one of these search APIs, right? I know that I can take a JSON object, send it off to that API, and get a search result, right? Okay, so now if I want to call that search API with an AI model, what I need to do is get the AI model to generate the right JSON-structured output that I can then just programmatically - not with any sort of fancy AI logic, but programmatically - take that JSON object and send it off to the API, get the response, and either plug that in in a sort of retrieval way that we talked about before... And just give it back to the user as the response that they wanted, right?

\[24:28\] So this has been happening for quite a while. This is kind of - like, we saw one of these cool AI demos every week, where "Oh, the AI is integrated with Kayak now, to get me a rental car. And the AI is integrated with this external system." All really cool, but at the heart of that was the idea that I would generate structured output that I could use in a regular computer programming way to call an API, and then get a result back, which I would then use in my system. So that's kind of this tool idea, which is still not quite what Rabbit is doing, but I think that's something that people don't realize is happening behind the scenes in these tools.

**Chris Benson:** I think that's really popular "in the enterprise", with air quotes there, because that approach is, in large organizations, they're going to other -- the cloud providers, with their APIs, Microsoft has the relationship with Open AI, and they're wrapping that, Google has their APIs, and they're using RAG in that same way, to try to integrate with systems, instead of actually creating the models on their own. I would say that's a very, very popular approach right now in the enterprise environments, that are still more software-driven, and still trying to figure out how to use APIs for AI models.

**Daniel Whitenack:** Yeah, and I can give you a concrete example of something we did with a customer at Prediction Guard, which is the Shopify API. So eCommerce customer, the Shopify API has this sort of Shopify -- I think it's called ShopifyQL, query language. It's structured, and you can call the regular API via GraphQL. And so it's a very structured sort of way you can call this API to get sales information, or order information or do certain tasks. And so you can create a natural language query and say "Okay, well, don't try to give me natural language out. Give me ShopifyQL, or give me something that I can plug into a GraphQL query, and then I'm going to go off and query the Shopify API, and either perform some interaction or get some data." So this is very popular. This is how you sort of get AI on top of tools.

What's interesting, I think, that Rabbit observes in what they're saying, and others have observed as well... I think you take the case like AskUI, like we talked about before... And the observation is that not everything has this sort of nice structured way you can interact with it with an API.

So think about -- pull out your phone; you've got all of these apps on your phone. Some of them will have a nice API that's well defined, some of them will have an API that me as a user, I know nothing about. There's maybe an API that exists there, but it's hard to use, or not that well documented, or maybe I don't have the right account to use it, or something... There's all of these interactions that I want to do on my accounts, with my web apps, with my apps, that have no defined structured API to execute all of those things.

\[27:58\] So then the question comes - and that's why I wanted to lead up to this, is because even if you can retrieve data to get grounded answers, even if you can integrate images, even if you can interact with APIs, all of that gets you pretty far, as we've seen, but ultimately, not everything is going to have a nice structured API, or it's not going to have an API that's updated, or has all the features that you want, or does all the things you want. So I think the fundamental question that the Rabbit research team is thinking about is "How do we then reformulate the problem in a flexible way, to allow a user to trigger an AI system to perform arbitrary actions across an arbitrary number of applications, or an application, without knowing beforehand the structure of that application or its API?" So I think that's the really interesting question.

**Chris Benson:** I agree with you completely. And there's so much complexity... They refer to it as human intentions expressed through actions on a computer. And that sounds really, really simple when you say it like that, but that's quite a challenge to make that work in an unstructured world. So I'm really curious - they have the research page, but I don't think they've put out any papers that describe some of the research they've done yet, have they?

**Daniel Whitenack:** Just in general terms... And that's where we get to the exciting world of large action models.

**Chris Benson:** Somehow that makes me think of like Arnold Schwarzenegger.

**Daniel Whitenack:** Large action heroes.

**Chris Benson:** There you go. Exactly. Yeah.

**Break:** \[29:48\]

**Daniel Whitenack:** Yeah, Chris, so coming from Arnold Schwarzenegger and large action heroes, to large action models... I was wondering if this was a term that Rabbit came up with. I think it has existed for some amount of time; I at least saw it at least as far as back as June of last year 2023, I saw Silvio Savarese's article on Salesforce AI Research blog about "LAMs, from large language models to large action models." I think the focus of that article was very much on the sort of agentic stuff that we talked about before, in terms of interacting with different systems, but in a very automated way. The term large action model as far as Rabbit refers to it, it's this new architecture that they are saying that they've come up with - and I'm sure they have, because seems like the device works... We don't know, I think, all of the details about it; at least I haven't seen all of the details, or it's sort of not transparent in the way that maybe a model release would be on Hugging Face, with code associated with it, and a long research paper... Maybe I'm missing that somewhere, or listeners can tell me if they've found it. I couldn't find that.

They do have a research page though, which gives us a few clues as to what's going on, and some explanation in kind of general terms. And what they've described is that their goal is to observe human interactions with a UI, and there seems to be some sort of multimodal model that is detecting what things are where in the UI... And they're mapping that onto some kind of flexible, symbolic, synthesized representation of a program.

So the user is doing this thing - so I'm changing the payment on my Uber app, and that's represented or synthesized behind the scenes in some sort of structured way, and kind of updated over time as it sees demonstrations, human demonstrations of this going on. And so the words that they -- I'll just kind of read this, so people, if they're not looking at the article... They say "We designed the technical stack from the ground up, from the data collection platform to the new network architecture", and here's the sort of very dense, loaded wording that probably has a lot packed into it... They say "that utilizes both transformer-style attention, and graph-based message passing, combined with program synthesizers, that are demonstration and example-guided." So that's a lot in that statement, and of course, they mentioned a few, in more description, in other places. But it seems like my sort of interpretation of this is that the requested action comes in to the system, to the network architecture, and there's a neural layer... So this is a neural symbolic model.

\[36:01\] So there's a neural layer that somehow interprets that user action into a set of symbols, or representations that it's learned about the UI; the Shopify UI, or the Uber UI, or whatever. And then they use some sort of symbolic logic processing of this sort of synthesized program to actually execute a series of actions within the app, and perform an action that it's learned through demonstration.

So this is sort of what they mean, I think, when they're talking about neurosymbolic. So there's a neural network portion of this, kind of like when you put something into ChatGPT, or a transformer-based large language model, and you get something out. In the case of - we were talking about getting JSON structured out when we're interacting with an external tool, but here it seems like you're getting some sort of thing out, whatever that is - a set of symbols, or some sort of structured thing - that's then passed through symbolic processing layers, that are essentially symbolic and rule-based ways to execute a learned program over this application. And by program here, I think they mean -- they reference a couple of papers, and my best interpretation is that they mean not a computer program in the sense of Python code, but a logical program that represents an action, like "Here is the logical program to update the payment on the Uber app. You go here, and then you click this, and then you enter that, and then you blah, blah", you do those things. Except here, those programs - so the synthesized programs are learned by looking at human intentions, and what they do in an application. And that's how those programs are synthesized.

So that was a long -- I don't know how well that held together, but that was my best, at this point, without seeing anything else, from a single sort of blog post...

**Chris Benson:** When you can keep me quiet for a couple of minutes there, it means you're doing a pretty good job. I have a question I want to throw out, and I don't know that you'll be able to answer it, obviously, but it's just to speculate... While we were talking about that, and thinking about multimodal, I'm wondering - the device itself comes with many of the same sensors that you're going to find in a cell phone these days... But I'm wondering if that feeds in more than just the speech. And it obviously has the camera on it, it comes with a \[unintelligible 00:38:50.14\] I can't say the word. GPS, accelerometer, and gyroscope. And obviously -- so it's detecting motion, and location, all the things; it has the camera, it has the mic... How much of that do you think is relevant to the large action model in terms of inputs? Do you think that there is potentially relevance in the non-speech and non-camera concerns on it? Do you think the way people move could have some play in there? I know we're being purely speculative, but it just caught my imagination.

**Daniel Whitenack:** Yeah, I'm not sure. I mean, it could be that that's used in ways similar to how those sensors are used on smartphones these days. Like, if I'm asking Rabbit to book me an Uber, to here, or something like that, right? Now, it could infer the location maybe of where I am, based on where I'm wanting to go, or ask me where I am. But likely, the easiest thing would be to use a GPS sensor, to know my location and just put that as the pin in the Uber app, and now it knows.

So I think there's some level of interaction between these things. I'm not sure how much, but it seems like, at least in terms of location, I could definitely see that coming into play. I'm not sure on the other ones.

**Chris Benson:** \[40:16\] Well, physically, it looks like a lot like a smartphone without the phone.

**Daniel Whitenack:** Yeah, a smartphone -- a different sort of aspect ratio, but still kind of touchscreen. I think you can still pull up a keyboard, and that sort of thing. And you see things when you prompt it. So yeah, I imagine that that's maybe an evolution of this over time, as sensory input of various things. I could imagine that being very interesting in running, or fitness type of scenarios. If I've got my Rabbit with me, and I instruct Rabbit to post a celebratory social media post every time I keep my mileage, or my time per mile, at a certain level, or something, and it's using some sort of sensors on the device to do that. I think there's probably ways that will work out \[unintelligible 00:41:15.12\]

**Chris Benson:** It'll be interesting that if this approach sticks - and I might make an analogy to things like the Oura ring for health, wearing that, and then competitors started coming out, and then Amazon has their own version of a health ring that's coming out. Along those lines, you have all these incumbent players in the AI space that are, for the most part, very large, well-funded cloud companies, and in at least one case, a retail company blended in there... And so if this might be an alternative, in some ways, to the smartphone being the dominant device, and it has all the same capabilities, plus more, and they have the LAM behind it to drive that functionality, how long does it take for an Amazon or a Google or a Microsoft to come along after this and start producing their own variant? ...because they already have the infrastructure that they need to produce the backend, and they're going to be able to produce -- Google and Amazon certainly produce frontend stuff quite a lot as well. So it'll be interesting to see if this is the beginning of a new marketplace opening up in the AI space as an \[unintelligible 00:42:29.29\]

**Daniel Whitenack:** So there's already really great hardware out there for smartphones, and I wonder if something like this is kind of a shock to the market. But in some ways, just as phones with external key buttons sort of morphed into smartphones with touchscreens, otherwise I could see smartphones that are primarily app-driven in the way that we interact with them now being pushed in a certain direction because of these interfaces. So smartphones won't look the same in two years as they do now, and they won't follow that same sort of app-driven trajectory like they are now, probably because of things that are rethought... And it might not be that we all have Rabbits in our pocket, but maybe smartphones become more like Rabbits over time. I'm not sure. I think that that's very likely a thing that happened.

\[43:37\] It's also interesting to me - it's a little bit hard to parse out for me what's the workload like between what's happening on the device and what's happening in the cloud, and what sort of connectivity is actually needed for full functionality with the device. Maybe that's something, if you want to share your own findings on that, in our Slack community at Changelog.com/community, we'd love to hear about it.

My understanding is there is at least a good portion of the LAM and the LAM-powered routines that are operating in a centralized sort of platform and hardware. So there's not this kind of huge large model running on a very low-power device that might suck away all the energy... But I think that's also an interesting direction, is how far could we get, especially with local models getting so good recently, with fine-tuned, local, optimized, quantized models doing action-related things on edge devices in our pockets, that aren't relying on stable and high-speed internet connections... Which also, of course, helps with the privacy-related issues as well.

**Chris Benson:** I agree. By the way, I'm going to make a prediction... I'm predicting that a large cloud computing service provider will purchase Rabbit.

**Daniel Whitenack:** Alright, you heard it here first. I don't know what sort of odds Chris is giving, or... I'm not gonna bet against him, that's for sure. But yeah, I think that's interesting. I think there will be a lot of action models of some type, whether those will be tool using LLMs, or LAMs, or SLMs, or whatever; whatever we've got coming up.

**Chris Benson:** And they could have named it a Lamb instead of a Rabbit, I just wanna point out. They're getting their animals mixed up.

**Daniel Whitenack:** Yeah, that's a really good point. I don't know if they came up with Rabbit before LAM, but maybe they just had the lack of the b there... But I think they probably could have figured out something.

**Chris Benson:** Yeah. And the only thing that could have been in \[unintelligible 00:45:59.01\] is a raccoon, of course. But that's beside the point. I had to come around full circle there.

**Daniel Whitenack:** Of course, of course. We'll leave that device up to you as well. \[laughs\] Alright. Well, this has been fun, Chris. I do recommend, in terms of - if people want to learn more, there's a really good research page on Rabbit.tech, rabbit.tech/research, and down at the bottom of the page there's a list of references that they share throughout, that people might find interesting as they explore the technology. I would also recommend that people look at Langchain's documentation on tools... And also maybe just check out a couple of these tools. They're not that complicated. Like I say, they expect JSON input, and then they run a software function and do a thing. That's sort of what's happening there. So maybe check out some of those in the array of tools that people have built for Langchain, and try using them. So yeah, this has been fun, Chris.

**Chris Benson:** It was great. Thanks for bringing the Rabbit to our attention.

**Daniel Whitenack:** Yeah. Hopefully see you in person soon.

**Chris Benson:** That's right.

**Daniel Whitenack:** And yeah, we'll include some links in our show notes, so everyone, take a look at them. Talk to you soon, Chris.

**Chris Benson:** Have a good one.