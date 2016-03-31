---
id: 1856
title: The Climate Change Scandal and the Importance of Good Code
date: 2009-12-10T07:00:33+00:00
author: Vicki
layout: post
guid: http://blog.vickiboykis.com/wlb/?p=1856
permalink: /2009/12/the-climate-change-scandal-and-the-importance-of-good-code/
categories:
  - Uncategorized
tags:
  - Career
  - economics
  - guest
  - Mr. B
  - professional development
---
_Vicki&#8217;s note: I decided to take down the previous post I had because, upon reflection, it wasn&#8217;t consistent with my website content and additionally, I can see it leading to long discussions of the type that I don&#8217;t necessarily want to have on this blog.</p> 

Instead, today, I have a guest post from Mr B (wooo!) on the importance of validity of code, and in general, of continuing to learn new methods and processes for more efficiency on the job.

As an analyst, I sometimes look at code, be it in SAS or SQL, from projects past.  What I&#8217;ve found to be most indicative of good code (and  actually any past project even unrelated to programming) is, most importantly, documentation of past tasks. </em>_This is 100 times more important if you are leading global warming studies that could be the cause of billions of dollars spent in policy implementations.  I know little about Fortran, but I still think this is an interesting take on the scandal that most news people don&#8217;t talk about (and not just because Mr. B peels oranges for me on a daily basis.)_

_
  


<center>
  <br /> 
  
  <div id="attachment_1857" style="width: 454px" class="wp-caption alignnone">
    <em><a href="https://raw.githubusercontent.com/veekaybee/wlb/gh-pages/assets/images/2009/12/earth-egg.jpg"><img class="size-full wp-image-1857" title="earth egg" src="https://raw.githubusercontent.com/veekaybee/wlb/gh-pages/assets/images/2009/12/earth-egg.jpg" alt="CC azrainman via Flickr" width="444" height="467" /></a></em>
    
    <p class="wp-caption-text">
      CC azrainman via Flickr
    </p>
  </div>
</center></p> 

</em>
  
You might have heard about the big <a href="http://news.yahoo.com/s/ap/eu_climate_hacked_e_mails" target="_blank">Climate Gate scandal </a>of CRU&#8217;s emails and software being leaked to the public over the past two weeks. Everyone, from John Stewart to Fox News, is highlighting passages from these emails and pointing out damning quotes which seem to show that global warming is a myth.

However what most people don&#8217;t hear about is the software that crunched the temperature data to actually give the climate models that scientist use to make their predictions. This software is written in an almost-defunct programming language called Fortran- and it shows.

Fortran is a general purpose programming language designed by IBM in 1950, for mathematical computations. It became the language of choice of many fields such as engineering, scientific research, and economic research. This was a great leap forward in innovation and allowed many computations on a scale that was never feasible before by other means.

If it&#8217;s so great, why isn&#8217;t it used now?

<div>
  <ul>
    <li>
      Fortran does not impose any discipline on the programmer and programs often end up with very little structure. It makes it difficult to reason about the logic and correctness of the program.
    </li>
    <li>
      Fortran is needlessly verbose, accomplishing something seemingly simple requires a page of code.
    </li>
    <li>
      There are limited ways of abstracting away complexity.
    </li>
  </ul>
</div>

<div>
  Here are some quotes about it:
</div>

> <div>
>
> </div>
> 
> <div>
>   <blockquote style="border-left: 1px solid #cccccc; margin: 0pt 0pt 0pt 0.8ex; padding-left: 1ex;">
>     <p>
>       FORTRAN—the &#8220;infantile disorder&#8221;—, by now nearly 20 years old, is hopelessly inadequate for whatever computer application you have in mind today: it is now too clumsy, too risky, and too expensive to use. &#8212; Edsger W. Dijkstra
>     </p>
>   </blockquote>
>   
>   <blockquote style="border-left: 1px solid #cccccc; margin: 0pt 0pt 0pt 0.8ex; padding-left: 1ex;">
>
>   </blockquote>
>   
>   <blockquote style="border-left: 1px solid #cccccc; margin: 0pt 0pt 0pt 0.8ex; padding-left: 1ex;">
>     <p>
>       FORTRAN&#8217;s tragic fate has been its wide acceptance, mentally chaining thousands and thousands of programmers to our past mistakes. &#8212; Edsger W. Dijkstra
>     </p>
>   </blockquote>
>   
>   <blockquote style="border-left: 1px solid #cccccc; margin: 0pt 0pt 0pt 0.8ex; padding-left: 1ex;">
>
>   </blockquote>
> </div>

<div>
  There are many excuses as to why it is still taught in universities and used in research:</p> 
  
  <ol>
    <li>
      A lot of legacy code is already written in Fortran and so we&#8217;re collectively stuck with it, might as well learn it
    </li>
    <li>
      It&#8217;s there it works, get used to it
    </li>
    <li>
      I already know it and it is good enough for me
    </li>
  </ol>
</div>

This type of thinking is bad for each new generation of economists and scientists.

Why was the climate study data written in Fortran? Probably because whoever wrote it, knew it and was too lazy to learn something new, by using the reasoning from (1) (2) and (3) as an excuse.

The second issue is not only that Fortran is inefficient, the code also lies.   Here is <a href="http://wattsupwiththat.com/2009/11/22/cru-emails-may-be-open-to-interpretation-but-commented-code-by-the-programmer-tells-the-real-story/" target="_blank">some actual code</a> from the project.

The moral of the story is, if you have important code that affects how people will live their
  
lives by basing their decisions on it, make sure it is easy to understand and allows you to concentrate on the problem you&#8217;re trying to answer instead of it fighting you and your colleagues with technical issues not related ot the goal. Additionally, make sure you don&#8217;t lie about it.