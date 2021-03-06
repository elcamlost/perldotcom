{
   "tags" : [],
   "thumbnail" : null,
   "date" : "2014-02-10T06:00:00-08:00",
   "categories" : "community",
   "image" : null,
   "title" : "Perl Today (February 2014)",
   "slug" : "/pub/2014/02/perl-today-february-2014.html",
   "description" : "brian d foy explores the state of Perl in 2014 by soliciting opinions from various respected Perl programmers.",
   "draft" : null,
   "authors" : [
      "brian-d-foy"
   ]
}


<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/headshot_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>brian d foy is the author of <a href="http://www.masteringperl.org">Mastering Perl</a>, now available in its second edition, as well as several other Perl books. As the founder of Perl mongers, he's been active in the Perl community for almost 20 years.</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl's so big now that it's almost impossible to pay attention to everything going on. Instead of reading the thoughts of me, just one person, on the current state of Perl, why not gather several major players who can cover many areas that you may not have noticed? I've collected some voices from parts of the large and diverse Perl community to highlight a small fraction of everything going on, from community development, hard core coding, the job market, and various problem domains. Although not definitive, their combination makes a good summary.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/randal_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Randal Schwartz is the original author of Programming perl and Learning Perl, along with numerous other Perl credits. He's the current host of <a href="http://twit.tv/floss">FLOSS Weekly</a>.</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl started as a Unix shell replacement to help sysadmins get more productive with less risk and a flatter learning curve (you didn't have to learn the quirks of dozens of small utilities, just the quirks of One <a href="http://www.wall.org/~larry/">Larry Wall</a>).</p>
<p>But then along came the web, and "scripts" could be used to provide interactive web pages, and Perl became the darling language of the web, first with "cgi-lib.pl", and then with [CGI]({{<mcpan "CGI" >}}>, and later with larger frameworks like <a href="http://www.masonhq.com">Mason</a> and <a href="http://www.catalystframework.org">Catalyst</a>.</p>
" >}}<p>Of course, Perl's scripting abilities also matured, and the ability to scale Perl programs with modern testing and OO frameworks (like <a href="http://moose.perl.org">Moose</a>) empowered programmers to write 10-line scripts and 100,000-line applications using the same core language features: a distinctive advantage.</p>
<p>Perl 5 development stagnated a bit, trigging the whole <a href="http://perl6.org">Perl 6</a> revival, and the relationship between Perl 5 and Perl 6 is still not understood by most people outside the direct Perl community (nor even by some who are \*in\* the community). But with the establishment of the quarterly point release, and the annual major releases, Perl 5 seems to have gotten firmly back in the saddle of modern development again. And while Perl 6 continues to be developed and redesigned, parts of it are already quite useful for early adopters.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/kp_headshot_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Karen Pauley was a founding member of the Belfast Perl Mongers, a volunteer with the YAPC Europe Foundation, and is the President of The Perl Foundation.</em></p>
</div>
</div>
<div class="row">
<br />
<p>For me, Perl is a reason for creating community systems to support Perl itself. <a href="http://www.perlfoundation.org/">The Perl Foundation</a> doesn't write the Perl language, we don't influence its direction; instead we work with the Perl community to organize funding, volunteers, marketing, and legal counsel.</p>
<p>The <a href="http://www.perlfoundation.org/perl_5_core_maintenance_fund">Perl 5 Core Maintenance</a> fund was created in June 2011, in collaboration with some of Perl 5's most generous supporters, such as <a href="http://www.booking.com/">Booking.com</a> and <a href="http://www.craigslist.org/about/charitable">craigslist Charitable Fund</a>. Our goal was to pay a few key volunteer developers to spend more of their time working on the maintenance and development of Perl 5. So far we have raised over $280,000 allowing us to compensate Perl internals experts including Nicholas Clark and Dave Mitchell to do more than they could on an unpaid basis.</p>
<p><a href="http://www.perlfoundation.org/">The Perl Foundation</a>, with help from our volunteers and donors, will continue to seek ways to strengthen the language, its community, and the F/OSS world in the coming years.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/steffen_head_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Steffen is a physicist-turned-software developer. A long time contributor to Perl and <a href="https://metacpan.org/author/SMUELLER">author of many Perl modules</a> on the CPAN, he currently works at <a href="http://www.booking.com/">Booking.com</a> where he manages software infrastructure development.</em></p>
</div>
</div>
<div class="row">
<br />
<p>With <a href="http://www.booking.com/">Booking.com</a>, Perl powers one of the most successful, profitable e-commerce companies on the planet. Perl is used throughout our stack from the web layer to mission-critical, highly-available infrastructure. We love it because its flexibility aligns with our aggressive pace of development on our code base of millions of lines of code. We believe that the language's versatility has given us a competitive advantage.</p>
<p>Outside of Booking.com, I am an individual contributor to Perl and the <a href="http://www.metacpan.org">CPAN</a>. Thus I have had the chance to directly support users in more than just a handful of Fortune 500 companies including major banks as well as the IT, automotive, and chemical industries. Perl is used in critical systems of many companies albeit usually in much less prominent roles. It is a humble work horse and truly deserves its reputation as a Swiss Army Chainsaw.</p>
<p>At Booking.com, we believe that one of Perl's great strengths is its community. Unlike many corporations, we maintain strong symbiotic ties to this development community. Many of our technical staff are active contributors to Perl and Perl modules on the CPAN. We encourage our developers to publish their code. This has both helped with getting our name out to potential future employees and improved the quality of our software overall.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/ricardo_signes.jpg" />
</div>
<div class="col-md-10">
  <p><em>Ricardo Signes is the current Perl 5 project manager, part of the CPAN toolchain maintenance team, and a <a href="https://metacpan.org/author/RJBS">prolific contributor to the CPAN</a>.</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl 5 is entering its fifth year of fixed-schedule releases, meaning that the first few releases on the yearly plans are now out of their supported lifetime. With the release support policy solidly in place, we've begun to hammer out exactly how we handle Perl's iffiest behaviors: deprecated and experimental features. Enumerating just which features are experimental let us get an idea of what we mean when we say something is experimental, which has led to a means to add new features to Perl without as much fear of getting locked in to bad ideas.</p>
<p>We've gotten a number of exciting new features in the latest perl builds, as experiments. Lexical subroutines, regexp character sets, and postfix dereferencing are the three I'm most excited about, and the prospect of experimental subroutine signatures still looks good.</p>
<p>Over the next few releases, I'm hoping we'll see improvement continue in three main areas: Perl 5's already-excellent Unicode support, the useful but troublesome PerlIO system, and the ability to provide annotations for improving performance.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/Joel_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Joel Berger has a Ph.D. in Physics from the University of Illinois at Chicago. He is currently employed writing software for a major financial institution.</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl is my language of choice for almost any task. In my research I routinely found that the flexibility of Perl allowed me to structure a script or simulation in the way that I was thinking about the problem, not the way the language wanted me to think about it. Modern tools like the <a href="http://moose.perl.org/">Moose object framework</a> give Perl the ability to model the most complex set of interdependent classes (as often arises in Physics) with ease. Combine that with the massive <a href="http://www.metacpan.org/">CPAN</a> module archive, from which you can find tools to transform nearly any data format, manipulate and analyze data, or do nearly any other task.</p>
<p>In my spare time, I contribute to the <a href="http://mojolicio.us/">Mojolicious</a> web framework, which brings the trendy non-blocking web to Perl, a robust and stable language (and the only language with CPAN). Mojolicious comes with lots of functionality like a non-blocking UserAgent (which is also the backbone of the extensive test framework), DOM parser, WebSockets, JSON, and a powerful template system, all built in.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/sawyer_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Sawyer X is one of the core developers on <a href="http://www.perldancer.org">Dancer</a>, a Perl web framework inspired by Ruby's <a href="">Sinatra</a>http://www.sinatrarb.com/).</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl is often remembered as the original language of the web. It had good CGI support and was the go-to language for any web programming. The CGI protocol had its issues and so was replaced in time by FastCGI, embedded interpreters in the web servers (mod\_perl, mod\_php, etc.), and servers implemented in the application language.</p>
<p>While you weren't watching, Perl has developed a common protocol, binding web servers, web frameworks, and web applications: <a href="http://plackperl.org">PSGI</a>. PSGI allows any web server to support any web framework and web application. It allows any web framework to support any server, and any user to use any framework on top of any server. In two words: *anything goes*.</p>
<p>On one hand new frameworks appeared (<a href="http://www.perldancer.org">Dancer</a>, <a href="http://mojolicio.us/">Mojolicious</a>, <a href="http://amon.64p.org/">Amon2</a>) and mature frameworks (<a href="http://www.catalystframework.org">Catalyst</a>) started supporting PSGI, and on the other hand web servers written entirely in Perl grew into existence, such as [Starman]({{<mcpan "Starman" >}}), <a href="https://metacpan.org/module/Twiggy">Twiggy</a>, <a href="https://metacpan.org/module/Corona">Corona</a>, and more.</p>
" >}}<hr />
</div>


<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/stevan_little_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Stevan Little created <a href="http://moose.perl.org/">Moose</a>, a post-modern object system for Perl 5. He's working on adding this to the Perl core language.</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl has had object oriented capabilities since the first release of Perl 5 almost 20 years ago. Since then, best practices have come and gone, along with a sea of modules on the CPAN to help programmers implement those best practices. Although many OO styles still abound, the current <a href="http://www.onyxneon.com/books/modern_perl/index.html">Modern Perl</a> movement has come to settle around the style of OO implemented by the <a href="http://moose.perl.org/">Moose</a> module.</p>
<p>Moose itself is based heavily on the OO features that have been designed for <a href="http://perl6.org">Perl 6</a>, along with input from several other languages including LISP, Ruby, Smalltalk and others. Moose brings not only support for basic class based OO programming, but it also brings deep meta programming capabilities, and the idea of "Roles" to Perl OO programming. Roles - which were originally derived from the Smalltalk community where they were called "Traits" - provide a means of code re-use similar to mix-ins but with an added degree of compositional safety through the use of conflict detection. Moose was originally released in 2006 and in the past 7 years more 2,100 CPAN modules have been released which depend upon it.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/mertens_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>David Mertens is a Visiting Assistant Professor at Dickinson College and a contributor to PDL and Prima.</em></p>
</div>
</div>
<div class="row">
<br />
<p>I have been using Perl for my scientific computing since roughly 2007. Prior to Perl I wrote the bulk of my scientific code in C++ and Matlab. My first exposure to Perl was due to its well known string processing capabilities, but I quickly realized that it was a well designed general purpose programming language. After programming in Perl, Matlab felt cludgy and C++ felt verbose. Once I discovered the <a href="http://pdl.perl.org">PDL (Perl Data Language)</a>, I switched all of new scientific computing to Perl.</p>
<p>My most exciting work with Perl has been at the interface of PDL and other modules. A few years ago I discovered the <a href="http://www.prima.eu.org">Prima graphical toolkit</a> and eventually wrote PDL-based methods for fast and flexible drawing to a Prima canvas. As my familiarity with Prima has grown, I have begun using it to write interactive simulations for talks and lectures.</p>
<p>Time and again I found other Perl developers had solved 90% of my problem, leaving the last and most exciting 10% to me. From numerical simulations to web servers to interactive lectures, I can always find the right Perl tool for the job, and the right Perl glue to put it all together.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/Dave.png" />
</div>
<div class="col-md-10">
  <p><em>Dave Cross is the owner of <a href="http://mag-sol.com">Magnum Solutions Ltd.</a>, a Perl training and consultancy company based in London. He founded <a href="http://london.pm.org/">London.pm</a>, the first Perl Monger group outside of North America. Dave blogs about Perl at <a href="http://perlhacks.com/">Perl Hacks</a>.</em></p>
</div>
</div>
<div class="row">
<br />
<p>I've been running Perl training courses for six or seven years. The demand for these courses has never been higher than I've seen over the last year, coming from all kinds of companies--financial services companies, media giants, dotcoms and many others.</p>
<p>The nature of those enquiries has been changing. Previously I would get enquiries about generic beginners, intermediate or advanced Perl courses, these days it is just as likely to be a request for training about a specific Perl module like <a href="http://moose.perl.org/">Moose</a> or <a href="https://metacpan.org/pod/DBIx::Class">DBIx::Class</a>. These enquiries are coming from companies who have been using Perl for many years but who finally seem to be getting the message that Perl has changed over the last ten years and that by keeping the knowledge of their Perl teams up to date they will retain the competitive advantage that was the reason for them choosing Perl in the first place.</p>
" >}}<p>Part of this, I'm sure, is driven by the recruitment market in London. There are a lot of companies trying to employ a relatively small number of Perl programmers. This means that the best programmers can be picky and only work for companies that are only using the most modern tools.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/ash2013_small.jpg" />
</div>
<div class="col-md-10">
  <p><em>Andrew Shitov is a Perl enthusiast working with the language since 1998, the organiser of 30+ local and international Perl events in 8 countries, including two YAPC::Europe conferences. <a href="http://moscow.pm.org">Moscow.pm</a> leader in 2007-2013.</em></p>
</div>
</div>
<div class="row">
<br />
<p>Perl is not the only programming language in the Universe any more, and thus it might feel that developers do not consider it as the only option. This, on the one hand, is a very pleasant time for improving the language, but on the other hand, Perl suffers from the fact that the language core developers might not feel the responsibility for keeping their product perfect, compatible and suitable for the need of modern programming. Perl faces the danger coming from inside of itself: we have seen a number of annoying incompatibilities introduced in recent releases, not counting the delay of Perl 6 which made Perl less competitive. All in all, Perl is now in a very comfortable position to be able to flush all the bad stuff and be re-born.</p>
<p><em>from brian: since Andrew is active in the Russian Perl community, I wanted to publish his response in Russian too.</em></p>
<p>Сегодня перл находится в таком состоянии, когда он уже не единственный язык во Вселенной, поэтому ему может казаться, что разработчики больше не выбирают его. Это, с одной стороны, очень приятное время для развития языка, но, с другой стороны, перл страдает от того факта, что разработчики языка не ощущают ответственности за поддержание своего продукта качественным, совместимым и отвечающим нуждам современного программирования. Перл столкнулся с опасностью, исходящей из самого себя: мы видели много раздражающих несовместимостей, введенных в последних релизах, не считая задержку с Perl 6, которая сделала перл менее конкурентноспособным. Так или иначе, сейчас перл находится в очень удобном положении и способен сбросить все плохое и переродиться. Мы должны воспользоваться этим шансом.</p>
<hr />
</div>

<div class="row">
<div class="col-md-2">
  <img src="/images/_pub_2014_02_perl-today-february-2014/neilb_small.png" />
</div>
<div class="col-md-10">
  <p><em>Neil has managed research and development teams for startups and multinationals. He's currently working on a startup that uses Perl, and also likes to work on projects related to CPAN curation. He started programming in Perl in 1993.</em></p>
</div>
</div>
<div class="row">
<br />
<p>The Perl Authors Upload Server (PAUSE), our gateway to CPAN, has been seeing more and more action. 844 people created a new account in 2013 (second only to 2012, with 858). Of those 844 new users, 389 have released something on <a href="http://www.cpan.org">CPAN</a> to date. Overall, 1803 of the 11k PAUSE users released something in 2013 (2012's total was 1759). Those 1803 users released 7440 different distributions in 2013, the best year ever. Read more about CPAN in 2013 on the <a href="http://neilb.org/cpan-report/">CPAN Report</a>.</p>
<p><a href="http://birmingham.pm.org/talks/barbie/ct-future/index.html">Recent upgrades</a> to the awesome <a href="http://cpantesters.org">CPAN Testers</a> mean we see results within an hour of uploading a module. Within days of releasing a distribution we get feedback on how well our code tests out on a wide range of configurations. Roughly one million reports are uploaded each month.</p>
<p><a href="http://prepan.org/">PrePAN</a> is a new website where we can describe module ideas and get feedback before we commit a specific design to CPAN.</p>
<p><a href="http://questhub.io/">Questhub</a> has a growing community of Perl developers who use it to manage their backlog of Perl projects ('quests'). <a href="http://questhub.io/realm/perl/stencils">Template quests</a> encourage you to contribute to Perl, get involved with the community, improve your distributions, and help others with theirs.</p>
<p>The <a href="http://neilb.org/adoption/">adoption list</a> identifies stale distributions that are of value to CPAN (e.g. being <a href="http://deps.cpantesters.org/depended-on-by.pl">used by other distributions</a>), but might have lost their primary developer. If you're looking for a project, consider taking on something from the list.</p>
<hr />
</div>
