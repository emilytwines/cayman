---
title: 'Against "Messages in Bottles," or Why Theatre People Should Care About Video Games'
date: 2020-09-12
permalink: /posts/blog-lookingGlass
excerpt: "Theatre, an art form founded on the concept of physical closeness, on the gathering and the witnessing of live bodies in space, and on the communal experience of shared, lived events, demands togetherness. And in the time of COVID-19, where being together in the traditional ways is impossible, theatre is in crisis."
tags:
  - art
  - gaming
  - theatre
---
Taking Stock
------
Theatre, an art form founded on the concept of physical closeness, on the gathering and the witnessing of live bodies in space, and on the communal experience of shared, lived events, demands togetherness. And in the time of COVID-19, where being together in the traditional ways is impossible, theatre is in crisis.  

Since March 2020, artists across the world have been facing a conundrum, one which still has no clear answers and no obvious direction: how do we make theatre without the aid of a stage, of black walls, of lights, of flats, of seats; in short, how do we make theatre without anyone stepping foot inside of one? 


<!-- blank line -->
<figure class="video_container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2_DK4rcSw0?autoplay=1" frameborder="0" allowfullscreen></iframe>
</figure>


<!-- blank line -->

A Digital Translation
------
I am a theatre person. I have an MA in reading it and an MFA in making it, so when NYC started (understandably) shutting theatres down in the middle of final rehearsals for a show I was creating, I was more or less freaked. Theatre was my life, my livelihood (well sort of), and my love – what was my community supposed to do without it? 

Or are we without it?

We have, at least temporarily, lost our form – the stage, the lights, the costumes – true, but have we lost the _artform_? What really is theatre after all? There are, of course, ardently opposed positions on this matter, but I’d like to suggest, for the sake of argument, that theatre is any collective artistic experience that attempts to connect people. The ancient Greeks used theatre as an open political arena. Brecht used it to point out and to implicate audiences in their political realities. Boal used it as a place to act out tests of possible solutions to community problem. What I mean to suggest is that the moment in late March where theatre seemed impossible actually was a moment that needed to believe, that needed connecting, that needed, in short, theatre to thrive. 

What is the translation then, if not from the page to the stage, but onto the computer screen? I’m a theatre person who’s interested in making interactive, participatory works, so the option to do Zoom theatre that to my mind preserves and perpetuates the proscenium division between artist and audience – not with a raised stage, but with the uni-directional blockade of the screen – is not great solution. 

To appropriately adapt the stage piece I had been working on, I needed a virtual space that a virtual audience could, by their own autonomous actions, explore, with which they could interact, from which they could learn a new perspective. 

<img src='../../images/blanket.jpg'>


An Admission
------

Now here’s my shameful admission: I am not, or at least was not, a “gamer.” I grew up with a Nintendo 64 and played the hell out of some Zelda and Mario, but was not up on the newest and shiniest, and had no idea how to go about making game. A quick Google search brings up Unity and Unreal though, and a coin toss chooses between them, so with a month to go before my project was due (I mean the show must go on, right?), I started making a video game. 

And it wasn't impossible. There are a ton of resources available, especially right now, online for folks looking to learn some of these skills. Codecademy was offering free pro memberships so I sprinted through their online pro course in C# (the Unity base language) in about a week. Unity was also offering free access to their premium features and had done a very cool online tutorial series called Create With Code Live. And of course I have to take this chance to pay homage to the gods among men who post to YouTube – Jayanam, if you ever read this, you saved me bro, mad love to you forever...


The Show
------

But, really, how does a theatre piece – an “experimental” theatre piece at that – translate to a 3D video game? They’re so different.

Right?

Well yes and no – I’ll give an example: when my theatrical team created the first scene for the staged version – an office hell-scape of an escape room – we made it long. Really, really long. Leaning in to duration and discomfort, we knew that an audience was more or less trapped with us in the room, and that we had up to a certain point before they would walk out, before which we could make them pretty damned uncomfortable. 

We each, as the three actors present, have a single, simple action to perform throughout the scene. The monotony of our tasks is interrupted from time to time, however, by the sound of water and a sink "turning on." We all rush to the tiny sink, fighting each other off as we try to be the one to get to wash our hands, wash our bodies, and to luxuriate in the experience of being cleansed. 

At the end of the scene (spoiler alert), the water stops coming on. We become enraged. In an act of desperate solidarity, we pull the sink off the wall, revealing -- shock and surprise -- another layer of the stage that had been hidden up to this moment. We go through, and this is where Act II (of III) takes place. 

The Game
------
This translated in the original showing of the game on May 15, 2020 as follows. First, I wanted the video game version to be accessible to as many people as possible, so, knowing that my audience would skew predominantly toward theatre rather than gaming experience, I went with a browser build to avoid having something everyone would need to download onto their own machines. 

However, WebGL is not supported on mobile devices, and I know a bunch of people who don’t have laptops, so I decided to also provide a scheduled Twitch-style stream of myself playing the game for people who either might not be familiar enough with gaming to get through the first "Act," or else wouldn’t have the hardware necessary to play. That way they could either 1.) start playing, then jump on the stream and ask questions in the comments as if it were a live forum, or 2.) watch the entirety of the play-through via the stream without ever having to touch a control. 

The game, _lookingGlass_, as I eventually called it, starts with a short video prologue introducing the themes of the game, then it drops the player into a small, dimly lit office with no apparent way out. I had to make the concession because of my technical (really temporal) limitations that there would only be one avatar in the scene rather than the three characters we had originally planned, but because the project was becoming more and more clearly about a movement from isolation and alienation (as in both Brecht and Marx) to togetherness, this sense of being alone in the world seemed to actually work to the game’s advantage. 

The sink and its accompanying cues remained surprisingly intact – whereas before we demonstrated our collective need to get to the sink with growing desperation and infighting, in the game, I created a health meter that constantly decreased no matter what you, the avatar, did, and only temporarily re-filled if you ran into the collider of the sink while it was on. If you failed to feed the meter, you would die, and have to start the day over, which accomplished the duration and / or frustration effects which before had come about on account of the duration alone. 

Along these same lines, I included very little instruction in the scene, which follows along with the original mission of replicating via metaphor the feeling of being trapped inside a workplace hell. 

If you manage to survive until 5pm - either by coming to terms with the fact that there really is nothing to "do" in order to advance or by sheer luck, a series of prompted actions reveals a hallway leading to next scene (read: Act II, enter avatar).

<img src='../../images/surveillance_shot.jpg'>

The Problems
------
This translation, though more direct than anticipated, was not without difficulties. In an online game, unlike in a theatre room, there is very little keeping the audience from leaving; you as the designer have a lot less of a grace period to make people uncomfortable before they give up. Because of the intentionally frustrating nature of the opening act, this period, and how to anticipate and / or extend it, is of great interest to me.

I have two theories: 

1.) Audiences who have primarily theatrical backgrounds may not all be used to video games, and, especially if they are used to proscenium theatre, may not be accustomed to the level of active interaction and decision making that games require. Proscenium theatre, _delivers_ content. By contrast, in a video game, if you don’t figure out the rules of the world, then you don’t advance the story; you have to _seek out_ the content yourself.

2.) Audiences with backgrounds primarily in video games are perhaps used to this, and expect to be able to discover the rules and how to “win” immediately. Push the right buttons at the right times, employ the right strategies, demonstrate the right skills -- this is traditionally as I understand it the way to succeed in a video game. _lookingGlass_, however, with its wait-it-out, the-suffering-is-part-of-it first act, does not allow for this sort of on-command advancement. Consequently this audience may become frustrated with the pacing. 

Because players who had the benefit of both theatre and gaming backgrounds played through successfully, I think that it is possible in spite of these expectations to do this kind of theatrical gaming work. Perhaps, though, it requires marketing and preparation of the audience to be very specific and worked out further than I was able to fully achieve. The live stream was very important to this point, because people who had tried the game and not escaped the office were, as planned, able to switch over and watch the rest. Today, in our current edits to the playing experience, we are exploring in-game tips and multi-player communication plug-ins to take the place of the parallel live-stream so that more people can successfully play through to the end on their own.

<img src='../../images/kai.PNG'>

Conclusions
------
Forgive me for the tired question, but after everything I have to ask again: “What is theatre?” If we as "Theatre People" are to continue our work during this time of isolation and separation, we must know what is central to the art form; we have to know what it is that makes theatre powerful and indispensable. 

The experience I had working on _lookingGlass_, particularly during the initial development phase between March and May, has led me to the conclusion that perhaps theatre is simply that which, in real time, builds community through its collective experience. Liveness as temporal togetherness, I believe, is the marker of theatre, not necessarily bodily closeness. We can be together, if not in space -- in the dark, cool theatre that we seem to collectively imagine -- then in time. 

Presence, after all, is an action; it is something people do, not a thing that happens just because you are close together. Who among us has not seen a well-known play done poorly, where the audience is there – they don’t leave – but they are not engaged, they are not actively watching and responding, they are not present?

My suggestion is that not only is it possible to make theatre online – to achieve this presence despite distances -- but that it is imperative that we continue to do so, and because of the separation we are all enduring at the moment, that theatre as a connective force is necessary now more than ever. 

But the kind of theatre we make must be thoughtful; I do not believe that doing the same plays the same ways without careful thought as to how the voices and bodies presented will interact will be successful; we must ask ourselves with each project we create: “Will the audience be emotionally and intellectually present for this -- open and active and present -- or will they passively watch?” Because one is theatre, and the other is a hope, stuffed inside its bottle and thrown desperately out to sea. 

To make theatre in 2020, we need to translate, not graft, our work to fit the new medium. Theatre to me has a function -- bringing people together -- and I know that we can still achieve this, even if we are worlds apart. 
 
----

## [Join us on Twitch for ReclaimFutures 2020](https://reclaimfutures.org/rf2020/watch/) starting Friday September 18, and tune in Sunday 12:45pm EST for links to #playlookingglass live!

----

[Read more](../../new-media/2020-07-14-new-media-lookingGlass/)


<!-- blank line -->
<figure class="video_container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/IYF5CmvJnog" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</figure>

<!-- blank line -->






