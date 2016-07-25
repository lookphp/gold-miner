> * 原文链接: [Design Is Mainly About Empathy](https://trackchanges.postlight.com/design-is-mainly-about-empathy-c9d51ccb208a)
* 原文作者: [Neil Renicker](https://trackchanges.postlight.com/@tinystride)
* 译文出自: [掘金翻译计划](https://github.com/xitu/gold-miner)
* 译者: 
* 校对者:

### Design Is Mainly About Empathy


![](https://cdn-images-1.medium.com/max/1200/1*pwlSr2Qq5rcVVTU7SxEAqQ.png)

It’s really interesting when a professional tries to explain their complex work to a layperson. Here’s a good example — watch theoretical physicist Richard Feynman talk about magnets:

[![video](https://i.ytimg.com/vi/wMFPe-DwULM/hqdefault.jpg)](https://trackchanges.postlight.com/media/d812c608ece9992d49752bfeafece892?maxWidth=640)

Feynman: F*****’ magnets, how do they work? FUN TO IMAGINE 4 [https://www.youtube.com/watch?v=wMFPe-DwULM](https://www.youtube.com/watch?v=wMFPe-DwULM)

The interviewer asks Feynman if he could please explain the invisible tug of one magnet on another, which edges him into what I like to imagine is the intellectual class’s version of anger:

> “It depends on whether you’re a student of physics, or an ordinary person who doesn’t know anything at all. […] I can’t explain that attraction in terms of anything else that’s familiar to you.  
> 
> For example if we say that the magnets attract like as if they were a rubber bands, I would be cheating you, because they’re not connected by rubber bands. I’d soon be in trouble, because you’d soon ask me about the nature of the band. And secondly, and if you were curious enough, you’d ask me why rubber bands tend to pull back together again, and I would end up explaining that in terms of electrical forces, which are the very things that I’m trying to use the rubber bands to explain, so I have cheated very badly, you see.  
>   
> So I’m not going to be able to give you an answer to why magnets attract each other, except to tell you that they do.”

We all feel like idiots now, Feynman. Nice work. He could have satisfied the interviewer with a tidy explanation about magnetic theory, but he wasn’t willing to round the corners of his deep domain knowledge to soften it for a layperson. He responded as a practicing physicist, not an educator.

What happens when a good educator tackles the same question?

[![video](https://i.ytimg.com/vi/hFAOXdXZ5TM/sddefault.jpg)](https://www.youtube.com/embed/hFAOXdXZ5TM?wmode=opaque&widget_referrer=https%3A%2F%2Ftrackchanges.postlight.com%2Fmedia%2Fb94633e7912577c9c43a7a0535435925%3FmaxWidth%3D700&enablejsapi=1&origin=https%3A%2F%2Fcdn.embedly.com&widgetid=1)

MAGNETS: How Do They Work? [https://www.youtube.com/watch?v=hFAOXdXZ5TM](https://www.youtube.com/watch?v=hFAOXdXZ5TM)

> Even in a magnetic material where the magnetic fields of atoms line up together, it’s possible that one chunk of the material will have all its atoms lined up pointing one way, and another chunk will have all its atoms pointing another way, and so on.

> [Ominous medieval soundtrack] If all of these domains are of a similar size, then none may be strong enough to force the others to align with it. In which case, a piece of iron, for example, may have no magnetic field at all because of all the warring magnetic kingdoms within it.

> However, if you apply a strong enough magnetic field from outside the material, you can help one domain expand its control over its neighbors, and so on, until all of the domains have been unified into one kingdom, all pointing in the same direction. And now, finally, you can rule with an iron fist! I mean, magnet.

> […] What’s remarkable is that magnetism is a fundamentally quantum property amplified to the size of everyday objects. Every permanent magnet is a reminder that quantum mechanics underlies our universe.

> [Read the full transcript](https://gist.github.com/tinystride/eab1d627fdc568922ed8461d5b7861a4)

That passage answers a lot of questions, and now we all have goosebumps from those Universe Thoughts. It isn’t very technical, but it manages to communicate complex information. It’s not overwhelming or belittling.

![](https://cdn-images-1.medium.com/max/800/1*0AtAl5KKHf37g8gcC1Acsg.gif)

The sword fight scene doesn’t hurt either

That’s an educator practicing empathy. The magnet video person wanted to empower their audience to understand the information.

* * *

Software product designers can take a lot of cues from great educators, because both groups work with information. Let’s consider a user looking for information on jousting. We know three things:

1.  **The user has a way of thinking about the information they want.** Example: “I heard about jousting and it sounds weird so I think I’ll watch some jousting videos.”
2.  **The information our user needs actually exists a certain way in the world.** Example: A database of video information with some metadata are magnetized regions of alloy on a hard drive on a server somewhere in North Carolina.
3.  **A product designer has represented the information to the user with some degree of abstraction.** Example: A web page at a certain URL shows a place to type a search query, a loading indicator, some branding, a sorted list of results with previews, and a plenty of enticing buttons to click on in case your jousting interest flickers out and Christina Aguilera on Jimmy Kimmel could help you pass the time instead.

![](https://cdn-images-1.medium.com/max/800/1*HvaeY2L1mF_NPbviSwdq7g.png)

Jousting is actually pretty interesting btw

Between the magnetized alloy and a user on a couch watching jousting videos is…a bunch of abstraction. So it’s the job of a good product designer to hold all three models of the information in her mind, and build a bridge between them. She covers the gaps between her users and the machine, so her users don’t have to bother. As [Alan Cooper](https://medium.com/u/b1fa02015e7f) puts it:

> Computer literacy is a euphemism for forcing human beings to stretch their thinking to understand the inner workings of application logic, rather than having software-enabled products stretch to meet people’s usual ways of thinking.

Let’s take a closer look at those three methods. Alan Cooper tackles all three in the seminal [_About Face: The Essentials of Interaction Design_](https://www.amazon.com/dp/1118766571/ref=pd_lpo_sbs_dp_ss_1?pf_rd_p=1944687702&pf_rd_s=lpo-top-stripe-1&pf_rd_t=201&pf_rd_i=0470084111&pf_rd_m=ATVPDKIKX0DER&pf_rd_r=04TSA54WA44Z7YC4QTSX).

The first one is the user’s _mental model._ Cooper writes that a lot of people think “electricity flows like water from the wall into the appliances through the little black tube of the electrical cord” when they plug in their vacuum or computer.

Of course, the electricity doesn’t flow like water at all. In the real world, electricity’s _implementation model_ is much more complex. But a simpler view of electricity works just fine for most of us. It’s informative enough to help us understand, for example, that we need to cram a cord into an outlet to charge our computer.

Finally, the _represented model_ is the way the thing ends up looking to the user. This is the part the designer spends their time working on, and the part that people will actually touch.

Here’s the secret for the designer, again from Cooper:

> “The closer the represented model comes to the user’s mental model, the easier he will find the application to use and understand.”

Bravo! For a designer, that might mean spending more time talking to users, and less time digging through the API. It might mean that early design phases are better spent researching user psychology instead of tinkering with typography.

<span class="markup--quote markup--p-quote is-other" name="anon_54be6b8e1ff8" data-creator-ids="anon">The user’s mental model, faulty though it may be, is our guiding light. If we don’t invest effort in understanding that model, it’s going to be really hard to know if our work is successful. Design is mainly about empathy.</span>

Example time. Animation is a great tool for practicing user empathy. Animation is a user interface pattern for aligning a user’s mental model with the product’s represented model. The notifications menu in iOS 9 isn’t physically tucked up underneath the top of the device on a curtain roll, and everyone knows that. But users have mental models of tugging on objects in their world from the near the top to reveal a new temporary state.

![](https://cdn-images-1.medium.com/max/800/1*YybkuqDoXWgLTn8fjp2G4Q.gif)
![](https://cdn-images-1.medium.com/max/400/1*wP7Nzgk19-A7Ez6DUjXsLQ.gif)

Blinds image courtesy [IKEA](http://www.ikea.com/gb/en/catalog/categories/departments/living_room/10701/)

The thing that’s special about the represented model—Cooper helped me see this—is that it’s the only part a designer can control. We can’t control the implementation model, because a good engineer will use abstractions in the codebase to make it maintainable and safe. And we can’t control our user’s mental model, since it’s shaped by their culture and dozens of other unknowable factors.

As designers, we have the power to manipulate representations. Design is the process of making our users feel awesome by representing the software in a way that meets them where they are.
