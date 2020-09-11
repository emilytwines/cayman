---
title: 'AI for the Art World: 
Neural Nets and Artistic Application'
date: 2019-06-08
permalink: /posts/blog-AI
tags:
  - art
  - AI
---
Thanks to AI specialist: Jeff Jacobs of Columbia University

"In 500 words or less, please describe your biggest historical influences"
------

<!-- wp:image {"id":332} -->
<figure class="wp-block-image"><img src="http://emilytwines.com/wp-content/uploads/2019/08/IMG_1917.jpg" alt="" class="wp-image-332"/></figure>
<!-- /wp:image -->

"Who are my biggest influences?" It's a dreaded prompt. Inquiries such as these often imply deep soul-searching evenings and endless grant application re-writes… Yes I know I _like_ the Expressionists, but do they influence my work? Do I think of them when I paint? What does it even mean to be influenced?
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
But.
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
But what if you could just — get an objective response? No talk of process or who you admire or who you grew up with plastered on your wall — just a quantifiable, numerical answer?
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
You’re in luck if you know a computer scientist, because advances in a leading AI technique called, for short, “Neural Nets” can provide just this solution. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Named for its vague resemblance to the networks of neural pathways inside the human brain, a neural network finds relationships between two or more given things. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Like — did we all see those contemporary, every day pictures that were reproduced in the style of famous artists — “Starry Starry my trip to Vegas” or Delacroix’s famous “La Bathroom Selfie?” These are both examples of a neural style transfer.
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
How do they do it? I’m glad you asked. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
First, you feed the computer a “content image,” or the basis from which future extrapolations are made. So, in our first example, your Van Gogh. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Second, the computer learns, by Pavlovian reinforcement, a custom compression algorithm for your image, similar to the generic codecs you might use for a picture to save space on your drive. In this self-compression, or  “autoencoding,” the computer effectively chooses certain traits it considers definitive for the art piece. As each piece has different sets of qualities that a computer might recognize as integral, the autoencoding process is unique to each content image. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Third, you feed the computer your new data (your newest Instagram pic). It analyzes the picture using the same autoendoder, so that the painting that it spits out, content-wise, is still the second art piece, but encoded according to stylistic qualities of the first. Bingo-bango, you’ve got your image stylized according to one of the greats — your own personal classic.
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
And you say this works with video too?
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Yep. While doing this work by hand would take a ton of time, the computer doesn’t really care if you add a dimension. There are ways of applying a given picture to a temporal art object (i.e. video); you just watch the boundaries and relative densities identified in an initial image. This means that you can, in fact, apply style to an unrelated video, and with shockingly — dare I sayi it? — _artistic_ effects.
<!-- /wp:paragraph -->

<!-- wp:video {"id":334,"align":"center"} -->
<figure class="wp-block-video aligncenter"><video controls loop muted src="http://emilytwines.com/wp-content/uploads/2019/08/artisto-video.mp4"></video></figure>
<!-- /wp:video -->

<!-- wp:paragraph -->
“So, this is all well and good,” you might say, “but how can neural nets help me answer the question: 'Who are my biggest influences?'” 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Start with one of your art pieces (just one to keep things as simple as possible). Autoencode it. Then choose a paradigmatic, say, Degas, and autoencode it using the same algorithms. Finally, ask a computer to compare two matrices: "How does the original Degas compare with its compressed representation?" The response to this will answer the telling question: "Mathematically, how close is my stye to theirs?"
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Now, repeat this process. Like, a bunch of times. For Kahlo, Klimt, Munch, Basquiat… And see how each set of matrices compares. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
So now you have your own work, and a whole lot of numbers, yeah? 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
Last step. You remember that band Joy Division? Remember that album cover with all the little mountain bumps? There’s a plot named after that image where you can compare groupings of points with each other. The groups make up the mountains, and when you compare several groups, you get the whole Joy Division Plot. 
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
So group all your artists together by movement — your Romantics, your Cubists, your Futurists, etc. — as they will likely return similar difference sums. Insert them into the plot, and, with your work as point zero for each line, compare visually which groups are furthest left, or in other words, which are closest to zero. The closer the mountain is to zero, the greater the stylistic similarities to your own piece there are that were noticed by the neural network. The more spatially left the grouping, the more likely it is that this movement of artists influenced your work.  
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
So there you have it — a plot of historical works that visualizes which ones your own piece most resembles, thereby offering good candidates for your biggest influences — all quantified and categorized. 

And the best part? 

There's no essay required. 
