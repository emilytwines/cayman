---
title: 'Letters from Quarantine, or Why Theatre People Should Care About Video Games'
date: 2020-09-11
permalink: /posts/blog-lookingGlass
tags:
  - art
  - gaming
  - theatre
---
Taking Stock
------
Theatre, an art form founded on the concept of physical closeness, on the gathering and the witnessing of live bodies in space, and on the communal experience of shared, lived events, demands togetherness. And in the time of COVID-19, where being together in the traditional ways is impossible, theatre is in crisis.  

Since March 2020, artists across the world have been facing a conundrum, one which still has no clear answers and no obvious direction: how do we make theatre without the aid of a stage, of black walls, of lights, of flats, of seats; in short, how do we make theatre without anyone stepping foot inside of one? 

A Digital Translation
------
I am a theatre person. I have an MA in reading it and an MFA in making it, so when NYC started (understandably) shutting theatres down in the middle of final rehearsals, I was more or less freaked. Theatre was my life, my livelihood (well sort of), and my love – what was my community supposed to do without it? 

Or are we without it?

We have, at least temporarily, lost our form – the stage, the lights, the costumes – true, but have we lost the artform? What really is theatre after all? There are, of course ardently opposed positions on this matter, but, I’d like to suggest, for the sake of argument, that, theatre is any collective artistic experience that succeeds in connecting people. The ancient Greeks used theatre as an open political arena; Brecht used it to point out and to implicate audiences in their political realities; Boal used it as a place to act out tests of possible solutions to community problem. Perhaps then theatre is that which allows communities a space and a reason to address contemporary issues, allowing them to move forward in the world with slightly greater wisdom. If this is the case, then the moment in late March where theatre seemed impossible, actually was a moment that needed to believe, that needed connecting, that needed, in short, theatre to thrive. 

What is the translation then, if not from the page to the stage, but onto the computer screen? I’m a theatre person who’s interested in making interactive, participatory works, so the option to do Zoom theatre that to my mind preserves and perpetuates the proscenium division between artist and audience – not with a raised stage, but with the uni-directional blockade of the screen – is not great solution. 

To appropriately adapt the stage piece I had been working on, I needed a virtual space that a virtual audience could, by their own autonomous actions, explore; with which they could interact; from which they could learn a new perspective. 

An Admission
------

Now here’s my shameful admission: I am not, or was not at this point, a “gamer.” I grew up with a Nintendo 64 and played the hell out of some Zelda and Mario, but was not up on the newest and shiniest, and had no idea how to go about making game. A quick Google search brings up Unity and Unreal though, and a coin toss chooses between them, so with a month to go before my project was due (because yes, of course someone still expected a product, pandemic-be-damned), I started making a video game. 

First – and I highly recommend doing this first – I had to learn to code. Codecademy was offering free pro memberships so I sprinted through their online pro course in C# (the Unity base language) in about a week. I found Unity was also offering free access to their premium features (because _yes_ free stuff) and was able to benefit from that as well. Mostly, though, I pay would like to take this chance to pay homage to the gods among men who post to YouTube – Jayanam, if you ever read this, you saved me bro, mad love to you forever.

The Show
------

But, really, how does a theatre piece – an “experimental” theatre piece at that – translate to a 3D video game? They’re so different… right?

Well yes and no – I’ll give an example: when my theatrical team created the first scene for the staged version – an office hell-scape of an escape room – we made it long. Really, really long. Leaning in to duration and discomfort, we knew that an audience was more or less trapped with us in the room, and that we had up to a certain point before they would walk out, before which we could make them pretty damned uncomfortable. 

We each, as the three actors present, had a single, simple action to perform throughout the scene. Our tasks would be interrupted from time to time by the sound of water at and blue lights suggeting that the sink in the corner fo the stage had turned on. We would all fight to wash our hands, wash our bodies, and luxuriate in the experience of being cleansed. 

At the end of the scene (spoiler alert), the water stops coming on. We become enraged, and we pull the sink off the wall, revealing another layer of the stage that had been hidden up to this moment. We go through, and this is where Act II (of III) takes place. 

The Game
------
This translated in the original showing of the game on May 15, 2020 as follows. First, I wanted the game to be accessible to as many people as possible, so I went with a browser build rather than something everyone would download onto their own machines. However, WebGL is not supported on mobile devices, and I know a bunch of people who don’t have laptops, so I decided to also provide a scheduled Twitch-style stream of myself playing the game for people who might either not be familiar enough with gaming to succeed or wouldn’t have the hardware necessary for it. That way they could either 1.) start playing then jump on the stream and ask questions in the comments as if it were a live forum, or 2.) watch the entirety of the play-through via the stream without ever having to touch a control. 

The game, _lookingGlass_, as I eventually called it, starts with a short video prologue introducing themes of the show, then it drops the player into a small, dim office. I had to make the concession for technical reasons that there would only be one avatar in the scene, but because the project was becoming more and more clearly about a movement from isolation and alienation (both in the Brechtian and Marxian senses of the word) to togetherness, this sense of being alone in the world seemed to actually work to the game’s advantage. 

The sink and cues remained surprisingly intact – whereas before we demonstrated need to get to the sink with growing desperation and infighting between ourselves in performance, in the game, I created a health meter that constantly decreased no matter what you did, and only filled when you ran into the collider of the sink while it was lit up blue and the water audio played. You would literally die if you didn’t get to the sink, and would have to start the day over, which accomplished the durational and or frustration effect that we were going for. 

There is also very little instruction in the scene, which again, follows along with our mission of replicating via metaphor the feeling of being trapped inside a workplace hell. If you survive until 5pm (there is a clock that counts the hours), a sledgehammer appears, and a health bar hovers over the top of the sink. Should you decide to smash the sink, the back wall of the office drops out, and you can run to the end of a newly exposed hallway to trigger the next scene (read: enter Act II).

This translation, though easier than anticipated, was not without difficulties. Unlike a theatre room, in an online game, there is very little keeping the audience from leaving; you as the designer have a lot less of a grace period to make people uncomfortable before they give up. 

This may be for a number of reasons, but I have two theories: 

1.) Theatre audiences may not all be used to video games, and may not be used to the level of active interaction and decision making that they require. Theatre, or traditional, proscenium theatre at least, _delivers_ content. By contrast, in a video game, if you don’t figure out the rules and how to play, then you don’t advance the story; you have to seek out the content yourself.

2.) Video game players are perhaps used to the rules being clear or there being a way to “win” immediately, as long as you push the right buttons at the right times, employ the right strategies, demonstrate the right skills -- and when they cannot on command cause a successful advancement, they may become frustrated with the pacing. This is, of course, _the point_. 

Because players who had the benefit of both theatre and gaming backgrounds played through successfully, I think that it is possible to do this kind of theatre gaming work. Perhaps, though, it requires marketing and preparation of the audience to be very specific and worked further than I was able to fully achieve. The live stream was very important to this point, because people who had tried the game and not escaped the office were able to switch over and watch the rest. Today, in our current edits to the playing experience, we are exploring in-game tips and multi-player communication plug-ins to take the place of the parallel live-stream so that more people can successfully play through to the end.

Conclusions
------
Forgive me for the tired question, but after everything I have to ask again: “What is theatre?” If we as "Theatre People" are to continue our work during this time of isolation and separation, we must know what is central to the art form; we have to know what it is that makes it powerful and indispensable. 

The experience I had working on _LookingGlass_, particularly from March to May, has led me to the conclusion that perhaps theatre is simply that which, in real time, builds community through its collective experience. Liveness as temporal togetherness, I believe, is the marker of theatre, not necessarily bodily closeness. We can be together, if not in space, in the dark, cool theatre that we seem to collectively imagine, then in time. 

Presence, after all, is an action; it is something people do, not a thing that happens just because you are close together. Who among us has not seen a well-known play done poorly, where the audience is there – they don’t leave – but they are not engaged, they are not actively watching and responding; they are not present?

My suggestion is that not only is it possible to make theatre online – to achieve this presence despite distances -- but that it is imperative that we continue to do so, and because of the separation we are all enduring at the moment, that theatre as a connective force is necessary now more than ever. 

But the kind of theatre we make must be thoughtful; I do not believe that doing the same plays the same way from our separate homes without careful thought as to how to voices and bodies presented will interact will be successful; we must ask ourselves with each project we create: “Will the audience be emotionally and intellectually present for this -- open and active and present -- or will they passively watch?” Because one is theatre, and one is not. 

To make theatre in 2020, we need to translate, not graft, our work to fit the new medium. Theatre to me has a function -- bringing people together -- and I know that we can still achieve this, even if we are worlds apart. 
 







