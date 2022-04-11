**Daniel Whitenack:** Welcome to another Fully Connected episode of The Practical AI podcast. In these episodes, Chris and I can keep you fully connected with everything that's happening in the AI community. We'll take some time to discuss some of the latest AI news and trends, and we'll dig into a couple learning resources to help you level up your machine learning game. This is Daniel Whitenack. I'm a data scientist with SIL International, and I'm joined, as always, by my co-host, Chris Benson, who is a tech strategist at Lockheed Martin. How are you doing, Chris?

**Chris Benson:** I am doing very well. It's kind of the end of winter as we're recording this, starting to warm up a little bit. Gotta say, my heart is with the people of Ukraine right now because that's -- we're about two weeks into that event as we record this today, and I'm spending a lot of my spare cycles just thinking about those folks.

**Daniel Whitenack:** Yeah, definitely. For those listening at a later date, we are in the midst of a world crisis over in the Ukraine and war over there... So yeah, it's definitely on a lot of people's minds, and I know we have -- of course, SIL has partners all around the world, and definitely... Yeah, just really concerned and praying for those involved in really tough situations. It seems like in recent years it's just from one giant global craziness to the next, really.

**Chris Benson:** It has been. We've had a string of them, it seems like, with the pandemic being the giant global thing in the middle of it... But we've rolled right out into this, and I didn't want to make the beginning of the show all about this, because that's not what our folks are here to talk about... But just - our hearts are with those folks. I know we have some folks listening to us from that part of the world, and we're thinking about you. Hang in there.

**Daniel Whitenack:** \[04:07\] Yeah, hang in there. And it's not totally disconnected from the subject. Hopefully, over the coming years we can find more and more ways to apply technology and AI to really be helpful and beneficial in these situations... So not just used as a tool to give concentrated power to one party or another, but actually to sort of democratize good things. I know in recent weeks we've had several different conversations about geospatial data, and satellite imagery, and opening that up to people that could use it in multiple ways... And I think we talked about some of that in relation to dealing with tropical storms or disasters, but of course, kind of wartime situations and the aftermath, this seems like a definite overlap with that general set of data and tasks. I'm sure that there are people out there thinking about how we can, as maybe AI practitioners, work to provide, whether it's open data or open models to help in these sorts of situations. If you have any ideas or you know people working in those areas, let us know. We'd love to have them on the show.

**Chris Benson:** Absolutely. And getting technology out there into the hands of folks who really need it. And in a lot of cases, it doesn't yet, and that's a big problem for us all to solve.

**Daniel Whitenack:** Yeah.

**Chris Benson:** And actually, there may be some -- part of today's conversation can kind of help us along that. There's a lot of context that this conversation could be had in. To avoid conflict of interest, because I'm in the defense industry, I'm not going to talk about it in the context of war and conflict. But we wanted to talk a little bit about some of the logistics of data, and probably, I think, the use case I've picked to start us off with at least, is maybe kind of talking about healthcare. And I'm going to do this as a non-expert in healthcare, and you too.

**Daniel Whitenack:** Neither of us are medical doctors.

**Chris Benson:** Yeah. I wanted to talk a little bit about moving data around where it needs to be, because that could be applied to just about any industry on the planet, and it's a need that everybody has. And there's a popular buzzword that goes with this these days, which is data fabric.

**Daniel Whitenack:** Yeah. It seems like there's just so many terms, like data this, data -- like, we've got data lake, data warehouse, data mart, data fabric... There's probably other things out there like, data bodega, data hotdog stand... I don't know what the other things out there are.

**Chris Benson:** Maybe we need a data dictionary.

**Daniel Whitenack:** Yeah. \[laughs\] I mean, I know we're going to be talking about data fabric, or what people mean when they say that. Maybe before we go there, would it be useful to maybe just differentiate it from a couple of these other terms that people have in mind?

**Chris Benson:** I think so. One thing I have discovered, just like in the early days -- we used to say this in the early episodes, for those who have been with us for a long time, that many people define AI in many different ways.

**Daniel Whitenack:** Yeah.

**Chris Benson:** And maybe that has coalesced a little bit around deep learning more recently. I think that there's more of an understanding about what we're talking about when we say AI... But just in the same way, I'm discovering that data fabrics have many different definitions, for many different people... So I'm going to offer my definition.

**Daniel Whitenack:** Cool. Add it to the mix.

**Chris Benson:** Yeah, add it to the mix there, and we can see. So for me, just like I did with AI way back when we were talking about that topic in one of our Fully Connected episodes, I defined data fabric fairly narrowly, and I tried not to encompass all those other data star terms that we have pointed out exist. So if you think of a fabric being something that you lay down like a physical fabric, being something that you lay down across something, across a small geography --

**Daniel Whitenack:** A curtain or a blanket.

**Chris Benson:** \[08:13\] Yeah, a curtain or a blanket it's a perfect example, and it kind of covers those things, and to some degree, it connects those things. So playing off that analogy, I would say that a data fabric is a way of getting data from data producers, points of origin, to all of the consumers of that data; a destination, one or more destinations. And it may be across a very diverse digital landscape on how you do that. And with technologies of different types, different generations, completely different architectures... And a data fabric's purpose is to make the data go from point A to point B in a timely manner, with performance guarantees, and ensuring arrivals so that you can do productive things with that data at whatever the consumer of that data is trying to do with that data. So it's a logistical thing.

Another analogy might be thinking about trains moving across the landscape, or highway systems with large trucks, moving goods and services all over the place, getting them where they need to be to all the -- they may start in one place, but they may move those goods and services around. So I think that is also a decent analogy for what a data fabric should do.

**Daniel Whitenack:** So I guess one question would be like -- initially, when I got into data science, I had my first position as a data scientist, working with data that was in a SQL database. To me, in that scenario, my pattern of access to that data was SQL queries. Where does the data fabric sit in as you sort of scale maybe all the people that need access to data? Are we talking about just SQL queries, or does this go beyond that? I imagine it does.

**Chris Benson:** I think it goes way beyond that. It can be inclusive of that, maybe. But if you think of about, historically, all of us will -- running with that SQL example, we have a SQL database and we make queries to it, and we're pushing data into it, and we're pulling data out of it, and we're running analytics on it, and we're transforming it... But it's all within a very local context there. And I think as we look forward, we've been talking for years about AI everywhere, and IoT everywhere, internet of things everywhere, and all of the things, and that there's a sense of scale in the future that we may not have had in the past. So that presents a fairly substantial logistical challenge to get all of that data from all of those different places to all the other places together, and have a coordinated system that provides the services.

So a data fabric is really a big software system, is what it is. A big distributed software system, and potentially, globally distributed, depending on how you're using it. So it's the trucking system of data. It's not the sexy part. It's not the thing we like to talk about in AI. But one thing - and I know this has come up in a whole bunch of conversations that we've had on the show, both with guests and just ourselves - is that there's a lot of underlying work to get data ready and to the right place and such, so that you can use it for your AI. And then you have the AI modeling process, which is a very small percentage of the overall process. And then it has to get deployed out, and all this stuff. And the data fabric covers just the part of getting the data to the right place, so that you can do something presumably useful and productive with it.

**Daniel Whitenack:** \[11:54\] Yeah. I was just, over the past couple weeks, having some discussions with another colleague at SIL, talking about how we think about the products or the things that we build, more in terms of like the outcomes we're trying to achieve with those things. So if I was to spin this a different way, how would I know if I had a data fabric? What would the outcome be in terms of the way teams would operate or interact with that?

**Chris Benson:** So kind of thinking about characteristics that make up the data fabric, to some degree?

**Daniel Whitenack:** Yeah. Like, if I went into a new company and I was trying to figure out if they did or didn't have a data fabric yet, or maybe they were just stuck in the old days, with random other systems around, how would I determine, like, "Yes, they do", or "No, they don't"?

**Chris Benson:** I would say if they do, they probably have a specific software architecture, a system that is designed to move data around. And I think a notable thing about that system is it is highly scalable, and is designed to handle N number of endpoints, N being any number that you choose to apply to that, and that the architecture fundamentally is able to support the addition and loss of endpoints as a standard operating procedure in it. Without it, that's not a remarkable thing, and you're not manually setting up connections to SQL servers constantly, and that kind of thing.

So you're able to take an endpoint, maybe an IoT device out there, or some end user, maybe a tablet computer if you're in a hospital might be another case, and it just plugs into your data architecture, and it might work with many SQL databases and many other systems out there, aggregating the data in the right places and making it available for use for there. And it's a software system designed to handle all of that complexity under the hood, or maybe I'll say under the blanket, or something.

**Daniel Whitenack:** Nice. I ask all that, I guess, just to try to -- because when you were first like, "Hey, let's talk about data fabric", I was like, "Well, I want to know a little bit of what that means", so I kind of tried to learn a little bit... And the Google searching was not that helpful. So I went to Gartner, which - they always give a definition, right? I'm not saying anything bad about the person who made this definition. It's probably really strategically worded, or whatever... But it says, "A data fabric utilizes continuous analytics", a new term I didn't know either.

**Chris Benson:** Continuous analytics?

**Daniel Whitenack:** "...continuous analytics, over existing discoverable and inferenced metadata assets, to support the design, deployment and utilization of integrated and reusable data across all environments, including hybrid and multi-cloud platforms." There's a lot of words there.

**Chris Benson:** There's a lot of words there. And I agree with many of the words, but one of the things I'll call out - it's my own bias, but I think I'm right, obviously, is I believe analytics is a separate thing. I believe analytics systems are consumers of and producers for a larger environment where a data fabric may be serving that. But to me, that is a use case that a data fabric serves, and I have seen many people try to describe data fabrics in terms of analytics, and being the digital bully that I am, I tell them they're wrong. They're wrong. It's not that, it's about the logistics.

**Break:** \[15:41\]

**Daniel Whitenack:** So Chris, I think I'm getting what you're saying. In this definition, or the definition we were talking about from Gartner, analytics sort of serves as a potential kind of plugin application to whatever we're calling a data fabric. And then they describe this -- so it's operating over, and they're describing it as existing discoverable and inferenced metadata assets. That's a mouthful.

**Chris Benson:** It is.

**Daniel Whitenack:** So metadata assets I assume just means data telling you what assets are available, or the kind and number and type... Or what's the metadata?

**Chris Benson:** So I'm going to define metadata in the context of a data fabric... Meaning if you're talking about metadata in a different context, you might take it slightly different. But I would always define metadata in the context of the thing that you're discussing, because it's meta relative to that.

**Daniel Whitenack:** I like how you're weaving these things together.

**Chris Benson:** Oh, God. \[laughter\] Oh, that was a bad one. That was even worse than mine. I hope folks are still with us. So I would think of metadata as being the metadata around the data, which are the messages you're moving around. So if you use the word messages to say, "I'm moving data from one physical place to another one, or one digital place to another one, and there are things that I care about regarding that data in the message, such as the security status of that data - and that can be a lot of different things; the routing information of that data--

**Daniel Whitenack:** Who can access it...

**Chris Benson:** Yeah, exactly. All those things. There's a whole bunch of things where you could that metadata -- it could be in the form of tags, it could be addressing prioritization, it could be addressing recipients, priorities... It may be that your data fabric is overwhelmed with the amount of data that moves through, and you have a service in your data fabric that is having to prioritize those data packets based on your needs, that you have informed in one mechanism or another the data fabric of.

So there's all these metadata bits that are being attached to the data you're moving around. But having said that, what the data is, the primary data that you're moving from a producer to the consumers, you don't really care about in the data fabric... Other than the fact that you've attached those tags of characteristics and things that you care about that we've just described; you're just moving it from one place to another and ensuring, providing guarantees that based on your priority and the importance and stuff like that that you've assigned, that it's fulfilling that promise.

**Daniel Whitenack:** \[20:19\] So you mentioned moving messages around and packets around and such operations like that. If we bring it down to the healthcare use case you were proposing, let's say I'm a data scientist and I'm creating a new model to parse healthcare records or something like that, right?

**Chris Benson:** Yes.

**Daniel Whitenack:** And let's say there's an S3 bucket over here, and it includes some healthcare records, and there's metadata attached to it, and it gets moved from there to somewhere else; what's special about the moving part? If I have the metadata about where it is, and I know where is and what's in it and who can access it, why is this distributed or movement of data piece - why is that a key piece of what you're describing?

**Chris Benson:** It may be that you don't really have a requirement for a data fabric, if it's fairly basic; if you're basically saying there's one producer and there's one consumer, and you don't have really an enormous number of them, you don't have thousands or millions of instances of a producer and a consumer...

**Daniel Whitenack:** So you're saying part of this would come in where let's say I had a thousand hospitals, and they were all pushing records into, let's say, separate buckets, or maybe even like a mix of on-premises file storage, NFS or something, and S3. Is that more...?

**Chris Benson:** Yeah, I think the scale matters. There is a cost implementing a data fabric, and that cost is not trivial. And therefore, there is a level of requirement, there is a level of need that should be in place to substantiate paying that cost and recognizing that above a certain scale of operation, the data fabric is saving you cost over the long haul, versus producing more.

So the point with the data fabric is that at some point, the automation of all that becomes a cost-effective solution. But if your needs are very low or minute in terms of what you need, you may not want to deploy a data fabric to cover that. If it's a very small operation, manually centering everything up might make more sense in a small operation. Whereas if you're dealing with millions or let's say thousands of data producers -- well, it might be millions, actually, going forward, and you also might have millions of consumers of that data; that becomes untenable, obviously, to try to do all that in a very by-the-connection mechanism. So you need a system that can handle that at that massive parallel and concurrent scale.

**Daniel Whitenack:** So you know me, I always try to get down to the distill the practical... So if I get what you're saying, let's say we have the scenario where we have thousands of hospitals, all of those are producing medical records, which in and of themselves have security issues and things attached to them... But then they're stored in, let's say, S3, or a mix of NFS, or a diversity of sources... So those are my producers, and then up at my consumers, I have maybe a few different things. I have hospital web apps or something for staff members to access records, and then I have like a team of data scientists internally that's building models to maybe parse those records automatically in a better way... And then I have a third group of maybe researchers who are researching like a certain disease or effect of a trial or something within a certain set of those records, across different places.

\[24:09\] So in between those people -- so I've got, on the one side, the data, on the other side I've got these different consumers. In the middle, if I put a "fabric" there, the things that would need to happen, or each of those people would need to efficiently get the data that they need, regardless of what it's stored in, and they would need to be authenticated against that data, and understand in a sort of metadata way where all of the right pieces of data are located. So the data fabric would do that in a metadata kind of protocol between the consumers and the data, and make that process efficient. Am I sort of getting there?

**Chris Benson:** I would argue you're getting there, but I want to throw in a couple of things that would raise the value proposition of applying a data fabric. You mentioned the fact that all these producers, the actual machines or whatever, are going to S3, as an example... But what I would argue is the use cases that you described in the example - none of those are real-time. None of those imply that there might be a life or death concern there. It might be that as we have more and more machines that are constantly producing data, and sensors constantly producing data, that you could have critical care patients in that hospital, that it's not just an analytical thing, but there's also -- but even the analytics themselves, there are analytics that are needed in near real-time to save a life, and there are analytics that might be able to happen kind of whenever, because you're doing a study maybe or something, and they're not urgent. And there might also be sensor data on that patient that needs to alert a condition that the sensor is picking up, and you need a doctor in that room working on that patient immediately. So it's not going to go to an S3 bucket, or at least not just to an S3 bucket; it also needs to alert with specific data that goes right to whatever kind of unit that doctor is carrying around, who's in a completely different part of the hospital, and that doctor understands, "I have an urgent situation and it's measured in seconds, and I need to do something." And things like that happen in real life. It happens to date in real life, but we don't have very good mechanisms to deal with that.

So if you can automate that urgent thing to where you're able to prioritize the data that's coming from a sensor that is critical immediately to a patient's life would get priority over a data that's just going to the S3 bucket at any point if there's any kind of resource contention. And so you're able to get the information to that. And it may be that not all things are going to the S3 bucket. As a data store, there might be data stores that are collecting things for historical reasons, but you also may be sharing directly between one device and another device, without putting a store between them, so that you get more efficient. Or you may be meshing multiple sensors together regarding that patient together, so that you get a complete picture of that patient's condition at the time.

And so as you do that, the data fabric gives you that logistical routing prioritization, the metadata and the intelligent services wrapped around it, which may include AI, though you may have lots of deep learning models that are part of that mesh that are able to actually do the metadata tagging. It looks at the data, it looks at other considerations that are inputs to the model, and the model is giving you inference that say, "This is what you do with the data right now." So the model itself can be a service and supporting the data fabric.

**Daniel Whitenack:** \[27:53\] Yeah. So I guess in this case they referenced this inferenced metadata, or discoverable and inferenced metadata. So if you've got a producer of data, like you're saying, a sensor or something like that, that's kind of under-defined or annotated, something like that - then maybe there's actually automation or models in place there to infer certain things about that data and prioritize it accordingly, or something like that.

**Chris Benson:** Sure. I'm really glad you brought that up, because if you think about it, kind of going back to the very beginning of our conversation, there's lots of different types of technologies and different generations of technologies, modern new stuff, old antiquated legacy stuff that's out, there and all of it needs to plug in. So another typical function or service of a data fabric is the connectivity to lots of different types of connected technology. In some cases, it's essentially wrapping a limited set of functionality and legacy so that you can basically bring more functionality to something that otherwise you would not think of having it, and therefore, make better use of it. So that's a key thing, is being able to actually connect all the things in a productive way.

**Daniel Whitenack:** Yeah. And maybe that connection piece gets to this integrated and reusable data side of things that was in the definition. So you've got the metadata, but then it's sort of integrated and reusable across different environments, whether that's the kind of edge environment, like you're talking about with the doctor being alerted, or something like that, or that's an environment where you're doing some sort of batch analysis for research purposes, or something like that. And they specifically also call out the hybrid and multi-cloud sort of thing, and I guess that's probably because in a healthcare hospital situation, like we have in mind - but there are many other examples of this, right? ...there's still a lot of mix between where data is stored - at the edge, or on-premises, or at a certain location...

**Chris Benson:** Yes.

**Daniel Whitenack:** ...and the mix of where it's stored online. We'd like to think that everything we do is in the cloud, but it's not quite so.

**Chris Benson:** It's not all. And we have more and more things at the edge. And the edge is like this gigantic blanket term. We talk about the edge like, "Oh, of course, I know what the edge is. It's the edge, man. We know where that is." But the edge actually describes a huge variety of potential targets that you're trying to deploy data to or pull data from. And so yeah, that diversity is important, and so we can address that in a moment.

**Daniel Whitenack:** So Chris, you were talking about the kind of diversity of environments and platforms... And cloud means a lot of things, and edge means a lot of things... I guess you've seen a lot of different types of edge devices and producers of data, and am I right that those could be -- I mean, you've already mentioned sensors, but in a lot of cases, and I know I've looked at a little bit of this for my wife's business too, specifically in manufacturing too, a lot of times edge devices are actually fairly beefy compute nodes that are just sitting in a factory. They're not in the cloud or in a data center, but they're sitting out on the factory floor, or something like that.

**Chris Benson:** Yeah. Endpoints at the edge can have huge capability. And not only that, but you want to be able to take advantage of it. And I think if we go back over this conversation and kind of -- I'm going to tie it all together a little bit in a bow here... Is that the data fabric has a way of declaring context for different kind of data profiles that you're able to create, to support whatever your need is that you're supporting there. And you might have a few profiles, of for a large scale you might have thousands, potentially millions of profiles, each of those profiles kind of this aggregation of routing, aggregating data, producers, consumers that are all trying to affect a purpose.

\[32:17\] And so the whole idea here is to automate and scale this in a standardized way, and allow the fact that you have endpoints that may come and go as doctors come and go from the hospitals, or machines are moved around, or it goes from one ward of the hospital to another, and that changes the capability in a particular area... All these things are possible by acknowledging simple things about "Where's my data originating? Where's it going to? What's the metadata that makes it useful for the various purposes I have? And how do I capture that in a profile that's reusable over time in a productive way?"

**Daniel Whitenack:** So I'm going to play devil's advocate here a little bit...

**Chris Benson:** Okay.

**Daniel Whitenack:** So it seems like at a certain point when you had disparate data systems, and if you wanted to do this, you sort of figured out where the database was and connected your app, and whatever... That was all handled, at least in scenarios I've been involved with, via documentation, right? You have some documentation, and here's how this system works, and here's how this system works etc. and you've figured it out and you did your thing. It sounds like with this data fabric idea that you've still got all this diversity of producers of data, and maybe the way it's stored, but then you've got this layer of metadata and tagging and rules, which brings all of that together. But in my mind, this metadata is going to end up looking so complicated, right? So how do you make it discoverable, I guess, is what I'm getting at? So if I have a new application and I'm building the next best thing for my company, and there's this layer of extremely complicated metadata, what advantage do I have in that scenario, versus the previous scenario where maybe I just go searching through docs to figure out which system to connect to, or something?

**Chris Benson:** To abstract it a little bit - and because I think it's important maybe in this last segment that we do talk a little bit about possible implementation, just to keep it practical, since we like to do that... If you're thinking of it that way, then you have endpoints that are coming and going, and so you have to have a distributed registry of some sort. There's different options on how you might do that, but you need a registry that can handle that. And you also need the equivalent, or maybe - going back to our joke earlier about a data dictionary that kind of identifies the characteristics of the metadata, and it constrains them to an operable sort. You can't have an infinite number of things or it becomes unmanageable. So in your use case, whatever your business is and your organization does, the data fabric has to be addressing the characteristics that matter to your situation, and you have to have a manifestation of that in the sense of these kind of dictionaries that capture those and registries of your endpoints, with the right metadata to do it. So it's got to get real.

At the end of the day, today, as we are sitting here in 2022, you usually do this through microservices, with containers. I like to tell people "Kubernetes in all the places", and people were kind of coming into an era where people are not just thinking about a Kubernetes cluster, but they're now starting to think about multi clusters, and sometimes maybe thousands of clusters that are connected. And you might put a cluster on a small device. You might have a whole Kubernetes cluster that is in something that fits in your pocket, because of the things that it's doing and the services that you need there.

\[35:55\] So we live in an amazing moment where not only are things like data fabrics being ideated in terms of as a solution for the massive scale that we're seeing coming into the real world, but also we're having these technologies that used to be hard, and now we're now getting good at them, and we're starting to put them everywhere. And if you take advantage of the way we do things across these different areas, like Kubernetes and containerization, handling that layer, standard networking protocols underneath it, microservices to handle the things that the data fabric needs to do that are in a standardized way - it's a doable thing. You've just got to constrain it and you have to not try - to use the cliché, to boil the ocean with it. It's got to be really practical to your use case, and not trying to overreach. And that's why I tell people, "Your analytics is not your data fabric. You're getting carried away." Add that in. You already have analytics; plug it into the data of fabric you build.

**Daniel Whitenack:** And so as an AI practitioner, if I'm working with my organization to provide some better thinking around data management... Maybe we're dealing with distributed systems like you've talked about, and a variety of producers of data and all of those things, as an AI practitioner, and very often we might be part of these conversations, although maybe we're not like the architects of the system, but maybe part of the conversation, I guess some things that might be useful for the practitioner to bring to the table are requests and advocacy for kind of standard protocols and access layers for data, which would include like prioritization, and speaking to like "Hey, if I create a training data set, I want to make sure I'm not overreaching, I'm using data that I should have access to... I don't want to get in trouble by using data I shouldn't have access to, but I also want to make sure that I can update my models, and so I want to make sure I have a standardized way of accessing this data that's coming from all of our devices everywhere..." So that's maybe the AI practitioner consumer point of view. But also, an AI practitioner could bring things to the table, it sounds like, in terms of the actual annotation and services built into whatever fabric this is, in terms of data's coming off of these devices, there may be ways to annotate them automatically with models --

**Chris Benson:** Absolutely.

**Daniel Whitenack:** ...that make them more useful at the next level up, right?

**Chris Benson:** Yes.

**Daniel Whitenack:** So whether that's detecting entities in text, or detecting anomalous conditions, which would change a priority of something. It sounds like that's a piece that the AI practitioner can play as well.

**Chris Benson:** Oh, totally. And not only that, you actually didn't go where I thought you're headed...

**Daniel Whitenack:** Oh, okay. I never do, Chris...

**Chris Benson:** \[laughs\] No, you're addressing using the inference to do the metadata and all that, but it may be that the actual data that's moving across the data fabric - not the data fabric itself, but the constituent data that it's moving from producer to consumers, it may be that many, many of those consumers may be MLOps pipelines that are taking data in and doing continuous training - I had to say that - or iterative training on a rapid scale, and producing models or producing things that matter for "How do I treat this thing in the hospital? How do I treat that thing in the hospital?" And it's going all the time. And none of that's the data fabric itself. Those are lots of AI models that are getting fed. We've spent several episodes talking about MLOps, we kind of figured out how to do that, we've got some really amazing capability out there that our listeners now know about... And now if they can get the data from all those other places to where it needs to be, then you can go do all that and you can be that AI practitioner that's incredibly productive, because you're able to do it continuously. So it fits that piece of the puzzle where you need automation, standardization, and scale.

**Daniel Whitenack:** \[40:18\] Yeah. And it sounds like this is necessarily a multidisciplinary venture.

**Chris Benson:** Indeed.

**Daniel Whitenack:** So I'm thinking - well, let's say that there's people out there in their own company saying, "Hey, it would be great if we could move towards this layer of standardization and access", whatever that looks like in their situation. It sounds like that is a multidisciplinary thing. So if you're including maybe AI analytics people, but also DevOps people, or MLOps people and infrastructure people in order to make this work, it sounds like you probably need some buy-in from those different groups, and some willingness to -- because I could also see someone say, "Well, it seems like a lot of work. I'm just going to copy some stuff out to my own S3 bucket and deal with my own stuff."

**Chris Benson:** We're in early days... And we've been doing this podcast for several years, and in that time, the resources available for deep learning have evolved quite a lot. So we're in early days right now for data fabrics, and I think that probably not terribly long after we release this episode, we're going to discover you're having companies and open source projects and such... Some are already out there, and you're going to see a whole bunch more pop up, because scale is becoming very real in this area and it needs a community of solutions around that to choose from. So I think you'll see a lot of out the box data fabrics that can then be applied and customized, and there are some stuff that's already out there, and we may talk to some of those in the days ahead. So it's just the infancy of this particular part of the ecosystem.

**Daniel Whitenack:** I'm glad to know what it is now, and I feel more comfortable saying the term data fabric now, whereas before I probably would've cringed just a little bit to say it. So I appreciate that part of the conversation. It's always great to have these conversations and learn about a topic together in this format. Speaking of learning, we do always like to share some learning resources in these episodes where it's just Chris and I. And the one that I wanted to share - I don't think we have a ton this episode, but I think one I wanted to share, which I kind of forgot was open and online, is Jake VanderPlas's Python Data Science Handbook.

If you just search for Python Data Science Handbook, there's a GitHub static page and you can see... So just to kind of give some of the table contents, there's -- you know, starting with IPython, moving into NumPy, and Data Manipulation with Pandas, but then going to data visualization and machine learning... And each of these has a way to run the examples straight from the page and open it in a Colab notebook, which is always good to see an easy way to run things and run a bunch of tutorials. So I would definitely take a look at this. And if you want to buy the book, you can, but also, there's more than enough to dig into on this online site, and you can open it in the notebooks and such, too.

**Chris Benson:** That sounds like a really good one, and I'm going to offer one as well.

**Daniel Whitenack:** Cool.

**Chris Benson:** The one that I'm going to offer - it's in the theme of data fabrics, and the fact that we have containers with microservices, and we're using containerized software to move things around. I like writing those microservices in Go. I think it is a good lane. If you're ready to move beyond Python into doing some software services and microservices around your data operations and your AI, then I think Go is a darn good language to do that in. So I'm going to reference go.dev. It is maintained by the Go programming language team. It has a lot of great resources to get going and understand the language, and it's a good place to start. So if you have some pretty cool things that you're doing out there and you want to try to get it out there in the world by integrating it into software, this is an awfully good place to start.

**Daniel Whitenack:** Yeah. Awesome. Well, I've been excited to get to chat about these things with you, Chris, and I appreciate you setting me straight. So yeah, looking forward to chatting about it more in the future. We'll see you next time.

**Chris Benson:** See you next time. Thanks a lot, Daniel.