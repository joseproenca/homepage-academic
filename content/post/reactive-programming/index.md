---
title: Reading club on Reactive Programming
# subtitle: Taken within [iMinds-Distrinet](http://distrinet.cs.kuleuven.be/), led by the Network Embedded System's group
summary: Taken within [iMinds-Distrinet](http://distrinet.cs.kuleuven.be/), led by the Network Embedded System's group
# authors:
# - joseproenca
tags: []
# categories: []
date: "2015-05-13T00:00:00Z"
# lastMod: "2015-05-13T00:00:00Z"
featured: true
draft: false


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/XN4T2PVUUgk)'
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

<h1 >Reading club on Reactive Programming</h1>
<h4>Taken within <a href="http://distrinet.cs.kuleuven.be/">iMinds-Distrinet</a>,
led by the Network Embedded System's group</h4>


<p> This page summarises our bi-weekly meetings to discuss papers related to programming languages that have the potential to be useful to us - the Network Embedded System's group.<br />
Members:
<a href="https://distrinet.cs.kuleuven.be/people/dannyh">Danny</a>,
<a href="http://jose.proenca.org">José</a> (main organiser),
Christophe,
<a href="https://distrinet.cs.kuleuven.be/people/wilfried">Wilfried</a> @
<a href="https://distrinet.cs.kuleuven.be/people">Distrinet</a>.</p>

<!-- 
<p>We have a mailing list – <a class="email" href="mailto:PLaNES@ls.kuleuven.be">PLaNES@ls.kuleuven.be</a> – to announce future events.<br />You can <a href="https://ls.kuleuven.be/cgi-bin/wa?A0=PLANES" class="external">check previous emails</a>, and <a href="mailto://jose.proenca@cs.kuleuven.be">contact me</a> to subscribe.</p>
 -->


<a name="Previous-meetings"></a>
<h2 >Meetings</h2>


<ul>
<li><strong>Synchronous and reactive C implementations</strong>
<br/>Focus on low-level and safety-critical systems; refers to Reactive C, Synchronous C, PRET, and SCC, etc.
<br/><a href="slides/low-level-reactive-languages.pdf" class="external">(slides)</a> -
<a href="https://distrinet.cs.kuleuven.be/people/muehlber">Jan Tobias</a>, 13 May 15.</li>
<li><strong>Actors à la Akka</strong>
<br/>Introduction to the Actor Model and Akka as a modern implementation of it.
<br/><a href="http://akka.io" class="external">(akka website)</a> <a href="slides/actors-a-la-akka.pdf" class="external">(slides)</a> - Christophe VG, 23 Apr 15.</li>
<li><strong>Distributed REScala: an update algorithm for distributed reactive programming</strong>
<br/>OOPSLA’14.
<br/><a href="papers/distributed-rescala.pdf" class="external">(paper)</a> <a href="http://www.rebls-ws.com/attachments/rebls14_submission_8.pdf" class="external">(followup-paper)</a> <a href="slides/DistREScala.pdf" class="external">(slides)</a> - <a href="http://jose.proenca.org">José</a>, 1 Apr 2015.</li>
<li><strong>Deprecating the Observer Pattern with Scala.React</strong>
<br/>Ingo Maier, Tiark Rompf, and Martin Odersky, 2010
<br/><a href="http://infoscience.epfl.ch/record/176887/files/DeprecatingObservers2012.pdf" class="external">(paper)</a> <a href="slides/deprecating-the-observer-pattern.pdf" class="external">(slides)</a> - Christophe VG, 18 Mar 15.</li>
<li><strong>Refraction: a reactive approach for sharing meta-data</strong>.
<br/> CBSE'15.
<br/><a href="papers/refraction.pdf" class="external">(paper)</a> -
<a href="https://distrinet.cs.kuleuven.be/people/wilfried">Wilfried</a>, 4 Mar 15.</li>
<li><strong>We have a DREAM: distributed reactive programming with consistency guarantees</strong>.
<br/>DEBS 2014
<br/><a href="http://dblp.uni-trier.de/rec/bibtex/conf/debs/MargaraS14" class="external">(bib)</a> <a href="http://www.guidosalvaneschi.com/attachments/papers/2014_We-Have-a-DREAM-Distributed-Reactive-Programming-with-Consistency-Guarantees_pdf.pdf" class="external">(paper)</a> <a href="slides/DREAMs.pdf" class="external">(slides)</a> -
<a href="https://distrinet.cs.kuleuven.be/people/wilfried">Wilfried</a>, 18 Feb 15.</li>
<li><strong>An overview of Functional Reactive Programming</strong>
<br/>(+ previous and ongoing work).
<br/><a href="https://lirias.kuleuven.be/bitstream/123456789/458251/3/p55-onward.pdf" class="external">(paper)</a> <a href="slides/presentation-bob-frp.pdf" class="external">(slides)</a> <a href="https://github.com/Tzbob/s-mt-frp" class="external">(code)</a> -
<a href="https://distrinet.cs.kuleuven.be/people/bob">Bob</a>, 4 Feb 2015</li>
<li><strong>A survey on reactive programming</strong>.
<br/>ACM Comput. Surv. 2013
<br/><a href="http://dblp.uni-trier.de/rec/bibtex/journals/csur/BainomugishaCCMM13" class="external">(bib)</a> <a href="papers/vub-soft-tr-12-13.pdf" class="external">(paper)</a> <a href="slides/survey-on-RP.pdf" class="external">(slides)</a> - <a href="http://jose.proenca.org">José</a>, 21 Feb 2015.</li>
</ul>
    

<a name="Papers-to-be-considered"></a>
<h2 >Other considered papers</h2>


<ul>
<li>[Cza13] Evan Czaplicki and Stephen Chong. 2013. <strong>Asynchronous Functional Reactive Programming for GUIs</strong>. Proceedings of the 34th ACM SIGPLAN Conference on Programming Language Design and Implementation (PLDI), pages 411–422, June 2013.</li>
<li>[Mei10] Meijer, E., <strong>Reactive extensions (Rx): curing your asynchronous programming blues</strong>, In: ACM SIGPLAN Commercial Users of Functional Programming, p. 11, ACM, October 2010.</li>
<li>[Car10] Andoni L. Carreton, Stijn Mostinckx, Tom Van Cutsem, and Wolfgang De Meuter, <strong>Loosely-coupled distributed reactive programming in mobile ad hoc networks</strong>. In: Proceedings of the 48th International Conference on Objects, Models, Components, Patterns (TOOLS’10) Springer, 41–60, 2010 - <a href="papers/vub-dist-RP.pdf" class="external">(download)</a></li>
<li>Ankush Desai, Vivek Gupta, Ethan Jackson, Shaz Qadeer, Sriram Rajamani, and Damien Zufferey - November 2012 - <strong>P: Safe Asynchronous Event-Driven Programming</strong> - <a href="http://research.microsoft.com/pubs/177118/tr.pdf" class="external">(download)</a> (referred to by Prof. Piessens with respect to state of the art in event-driven programming)</li>
<li>Geoffrey Mainland Greg Morrisett Matt Welsh - September 2008 - <strong>Flask: Staged Functional Programming for Sensor Networks</strong> - <a href="http://www.eecs.harvard.edu/~mdw/papers/flask-icfp08.pdf" class="external">(download)</a></li>
<li>Frédéroc Boussinot - <strong>Reactive C: An Extension of C to Program Reactive Systems</strong> - april <strong>1991</strong> - <a href="http://www.inf.fu-berlin.de/lehre/SS13/Sem-Prog/material/RC.pdf" class="external">(download)</a> <a href="http://mdrp.cemef.mines-paristech.fr/ReactiveProgramming/Home.html" class="external">(project website)</a></li>
</ul>