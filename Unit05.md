**Unit 5: Infinite Sequences and Series** <span id="5"></span> 
*In this unit, you will become acquainted with the infinite lists called
sequences and infinite sums called series.  The main question for each
is whether it converges: do the terms of the sequence have a finite
limit?  Do the series terms have a finite sum?  You will learn ways to
test for convergence or divergence.  After learning a number of such
tests, we will look at Taylor series, which are infinite polynomials. 
Any function that may be differentiated an unlimited number of times
gives rise to a Taylor series, whose partial sums are approximations to
the function using ever higher-order derivatives.  We will consider
questions like: for which values of the variable does the series
converge?  For those values, is it equal to the function from which it
was defined?  
  
 Many students find series the most difficult of the topics in Calculus
II.  There are multiple expositions of each topic included in this unit,
so be patient with yourself and study each resource carefully.*

**Unit 5 Time Advisory**  
This unit should take you 29.5 hours to complete.

☐    Subunit 5.1: 4 hours

☐    Reading: 1 hour  
  
 ☐    Lecture: 1 hour  
  
 ☐    Assessment: 2 hours

☐    Subunit 5.2: 3.75 hours

☐    Subunit 5.3: 8.75 hours

☐    Sub-subunit 5.3.1: 1.75 hours  
  
 ☐    Sub-subunit 5.3.2: 2 hours  
  
 ☐    Sub-subunit 5.3.3: 1 hour  
  
 ☐    Sub-subunit 5.3.4: 1.5 hours  
  
 ☐    Sub-subunit 5.3.5: 1.5 hours  
  
 ☐    Sub-subunit 5.3.6: 1 hour

☐    Subunit 5.4: 5 hours

☐    Sub-subunit 5.4.1: 1.5 hours  
  
 ☐    Sub-subunit 5.4.2-5.4.4: 0.5 hours  
  
 ☐    Sub-subunit 5.4.5: 0.5 hours  
  
 ☐    Sub-subunit 5.4.6: 2.5 hours

☐    Subunit 5.5: 11.75 hours

☐    Sub-subunit 5.5.1: 4.25 hours  
  
 ☐    Sub-subunit 5.5.2: 0.75 hours  
  
 ☐    Sub-subunit 5.5.3: 4 hours  
  
 ☐    Sub-subunit 5.5.4: 2.75 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Define convergence and limits in the context of sequences.
-   Define convergence and limits in the context of series.
-   Find the limits of sequences and series.
-   Discuss the convergence of the geometric and binomial series.
-   Show the convergence of positive series using the comparison,
    integral, limit comparison, ratio, and root tests.
-   Show the divergence of a positive series using the divergence test.
-   Show the convergence of alternating series.
-   Define absolute and conditional convergence.
-   Show the absolute convergence of a series using the comparison,
    integral, limit comparison, ratio, and root tests.
-   Manipulate power series algebraically.
-   Differentiate and integrate power series.
-   Compute Taylor and MacLaurin series.
-   Approximate functions using power series.

**5.1 Sequences** <span id="5.1"></span> 
*A sequence is merely a list of terms (usually numbers) that are
arranged in a particular order.  In this subunit, we will look at a
sequence of numbers ordered by some rule or function.*

-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 11:
    Sequences and Series: “Section 11.1 Sequences”**
    Link: Whitman College: David Guichard’s *Calculus*: Chapter 11:
    Sequences and Series: “[Section 11.1:
    Sequences](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Guichard-Chapter-11.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read the brief
    introduction to chapter 11 and Section 11.1 (pages 253 through
    260).  
      
     Studying this reading should take approximately 1 hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of David Guichard, and can be viewed in its original
    form
    [here](http://www.whitman.edu/mathematics/multivariable/multivariable_11_Sequences_and_Series.pdf) (PDF). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder. 

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Sequences I” and “Sequences II”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus:
    Sequences
    I](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)
    Lecture and “[Sequences
    II](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: Please click on the link, scroll down to Video 47:
    “Sequences I,” and watch the entire video.  Next, scroll down to
    Video 48: “Sequences II,” and watch it from the beginning through
    the 7<sup>th</sup> slide (the end of the slide marked 7 of 12).  If
    you are interested, feel free to watch the rest of the video.  
      
     In the first video, Dr. Hollis discusses sequences and limits, goes
    over several important limits, and explains growth rates and order
    comparisons.  In the second video, he gives a precise definition of
    limits, shows how to do an epsilon-N proof for limits of sequences,
    and discusses *boundedness* and *monotonicity*.  In the optional
    slides (8-12), he discusses recursively-defined sequences, fixed
    points, and cobweb plots.  
      
     Viewing these lectures and note-taking should take approximately 1
    hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “Limits of
    Sequences”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[Limits of
    Sequences](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “1. Sequences,” and click button 184 (Limits
    of Sequences).  Do problems 1-22.  If at any time a problem set
    seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 2 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2 Series** <span id="5.2"></span> 
*A series is the sum of the terms in an infinite sequence.  You are
likely familiar with series arranged in an arithmetic or geometric
progression; this subunit will take a look at terms defined by more
intricate functions.  You can also view a series as another type of
sequence – a sequence of partial sums.  In the following readings, you
will learn what it means for a series to converge and study some
important types of series.*

**5.2.1 Series and Basic Convergence** <span id="5.2.1"></span> 
-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 11:
    Sequences and Series: “Section 11.2 Series”**
    Link: Whitman College: David Guichard’s *Calculus*: Chapter 11:
    Sequences and Series: “[Section 11.2:
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Guichard-Chapter-11.pdf)” (PDF)  
      
     Instructions: Please click on the link above, scroll down and read
    Section 11.2 in its entirety (pages 260 through 263).  This section
    will introduce you to infinite series and make mention of the
    geometric series, which will be discussed in more detail below.  It
    also explains what it means for a series to converge.  
      
     Studying this reading should take approximately 15-20 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of David Guichard, and can be viewed in its original
    form
    [here](http://www.whitman.edu/mathematics/multivariable/multivariable_11_Sequences_and_Series.pdf)
    (PDF).  Please note that this material is under copyright and cannot
    be reproduced in any capacity without explicit permission from the
    copyright holder. 

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Series”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus:
    Series](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: This lecture will cover sub-subunits 5.2.1-5.3.1. 
    Please click on the link, scroll down to Video 49: “Series,” and
    watch the entire video.  You are welcome to break it into parts as
    you go along.  Slides 1-4 correspond roughly to 5.2.1; slides 5-7
    correspond roughly to 5.2.3; slides 8-11 are an exposition of 5.2.2;
    and slide 12 corresponds to 5.3.1.  
      
     Viewing this lecture and note-taking should take approximately 30
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.2 Properties of Infinite Series** <span id="5.2.2"></span> 
-   **Reading: Lamar University: Paul Dawkins’s Paul’s Online Math
    Notes: Calculus II “Special Series”**
    Link: Lamar University: Paul Dawkins’s *Paul’s Online Math Notes:
    Calculus II*: “[Special
    Series](http://tutorial.math.lamar.edu/Classes/CalcII/Series_Special.aspx)” (HTML)  
      
     Instructions: Please click on the link above, and read the
    information on this webpage.  You may skip the section on
    telescoping series; you are not responsible for that material. 
    However, pay attention to the beginning through the discussion
    following Example 2, pick up again at the paragraph before Example
    5, and read to the end.  The notion that any finite number of terms
    has no effect on the convergence behavior of a series is important
    and can save you a lot of effort.  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.3 Focus on the Geometric Series** <span id="5.2.3"></span> 
*A series is geometric if every successive term is the product of the
previous term with a fixed value called the ratio of the series.  For
example, 3 + 6 + 12 + 24 + ... is a geometric series with ratio 2. 
Geometric series are unusual in that not only can we easily determine
convergence or divergence for them, but in the case of convergence, we
can also find the sum of the series exactly.*

-   **Reading: MIT: Gilbert Strang’s Calculus: Chapter 10: Infinite
    Series: “Section 10.1: The Geometric Series”**
    Link: MIT: Gilbert Strang’s *Calculus*: Chapter 10: Infinite Series:
    “[Section 10.1: The Geometric
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Strang-Chapter-10.pdf)” (PDF)  
      
     Instructions: Read the several paragraphs at the beginning of
    chapter 10 (the discussion of the geometric series begins here) and
    section 10.1 (pages 366-372).  
      
     Studying this reading should take approximately 1 hour.  
      
     Terms of Use: The article above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Professor Gilbert Strang (MIT) and the original
    version can be found
    [here](http://ocw.mit.edu/resources/res-18-001-calculus-online-textbook-spring-2005/textbook/)
    (PDF).

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Daniel Russo’s “Geometric
    Series”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Daniel Russo’s “[Geometric
    Series](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “1.  Integration,” and click button 101
    (Geometric Series).  Do problems 2-10.  If at any time a problem set
    seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.4 Highlight: The Binomial Series** <span id="5.2.4"></span> 
*If you wish to expand (1 + x)<sup>2</sup> or (1 + x)<sup>3</sup>, you
may simply multiply them out.  But what are the coefficients of the
fifteen terms in the expansion of (1 + x)<sup>14</sup>?  The binomial
theorem provides an answer in terms of combinations, also known as
binomial coefficients.  The binomial series takes this even a step
further, allowing the expansion of expressions such as 1/(1 + x) and
(1 + x)<sup>1/2</sup> to infinite polynomials.*

-   **Reading: Lamar University: Paul Dawkins’s Paul’s Online Math
    Notes: Calculus II: “Sequences and Series: Binomial Series”**
    Link: Lamar University: Paul Dawkins’s *Paul’s Online Math Notes:
    Calculus II*: “[Sequences and Series: Binomial
    Series](http://tutorial.math.lamar.edu/Classes/CalcII/BinomialSeries.aspx)” (HTML)  
      
     Instructions: Please click the link above, and read this entire
    section.  Recall that combinations arise from the problem of
    counting subsets of a collection of objects: the number of ways to
    choose two of the four letters ABCD is the combination 4 choose 2,
    which is 6.  If you have not seen it before, the connection to
    powers of binomials may not be clear.  To expand (1 +
    *x*)<sup>2</sup>, you write it as two copies of 1 + *x* and multiply
    one term from the first copy by one term from the second copy, using
    every possible pairing exactly once.  Likewise, to expand (1 +
    *x*)<sup>4</sup>, you must multiply across the four copies of (1 +
    *x*), taking every possible quartet exactly once: all the 1’s, the
    first two 1’s and the last two *x’*s, the first two *x*’s and the
    last two 1’s, etc.  Combinations allow you to find the coefficients,
    because, for example, the coefficient of *x*<sup>2</sup> in the
    expansion of (1 + *x*)<sup>4</sup> is 6: the number of quartets that
    contain exactly two *x*’s, or in other words the number of ways to
    select the two copies of (1 + *x*) that provide the *x*’s.  
      
     The combination *k* choose *n* is typically written as the fraction
    (*k*!)/(*n*!(*k*-*n*)!).  Professor Dawkins writes it the way he
    does so it will generalize to negative and non-integer values of
    *k*.  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3 Test for Convergence of Positive Series** <span id="5.3"></span> 
*You will first learn how to check when a series with only positive
terms converges – i.e. the* ***limit ****of its* ***sequence of partial
sums ****exists and is finite.  The theory begins here with* ***positive
series****, because it is the simplest problem to consider; these tests
often work by “squeezing” the partial sums between zero and some larger
series which are known to converge.*  
  
 *It is important to notice many of the tests related to series are
one-directional implications: for example, if the series terms do not
limit to zero, you can conclude the series diverges.  However, if it
lacks that property, then you need more information to conclude either
convergence or divergence.  Be careful not to assume a lack of one
conclusion implies the opposite conclusion.*

**5.3.1 Divergence Test** <span id="5.3.1"></span> 
*Convergence of a series is convergence of its sequence of partial
sums.  That is, for the series to converge, the partial sums must settle
down and overall get closer and closer to a fixed finite value.  In
order for that to happen, the amount being added to each partial sum to
produce the next one must gradually shrink away to nothing.  That is the
idea of the divergence test, which applies to any series (not just those
with all positive terms): if the limit of the terms of the series is not
zero, the series diverges.*  
  
 *This is not an equivalence, however!  Many divergent series have terms
that limit to zero.  The terms must shrink to zero rapidly to give
convergence.  However, whether the terms shrink to zero at all is
straightforward to check and may save you work making more complicated
tests on a divergent series.*

-   **Reading: MIT: Gilbert Strang’s Calculus: Chapter 10: Infinite
    Series: “Section 10.2: Convergence Tests: Positive Series”**
    Link: MIT: Gilbert Strang’s *Calculus*: Chapter 10: Infinite Series:
    “[Section 10.2 Convergence Tests: Positive
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Strang-Chapter-10.pdf)” (PDF)  
      
     Instructions: This reading will cover sub-subunits 5.3.1 – 5.3.6. 
    Please click on the link above, and read Section 10.2 in its
    entirety (pages 374 through 379).  
      
     The section presents a criterion for divergence, the integral test,
    the comparison test, and the ratio and root tests.  We will revisit
    all these tests later in a slightly different context and give a
    more thorough justification of the last two tests.  
      
     Studying this reading should take approximately 45 minutes.  
      
     Terms of Use: The article above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Professor Gilbert Strang (MIT) and the original
    version can be found
    [here](http://ocw.mit.edu/resources/res-18-001-calculus-online-textbook-spring-2005/textbook/)
    (PDF).

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “The
    Divergence Test”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[The Divergence
    Test](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Series,” and click button 187 (The
    Divergence Test).  Do problems 1-10.  If at any time a problem set
    seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3.2 Integral Test** <span id="5.3.2"></span> 
*There is an imprecise correspondence between sequences and functions as
well as between series and integrals.  The integral test shows this
correspondence; though this relationship is not perfect, it is close
enough to be useful.*

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 37: Infinite
    Series and Convergence Tests”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 37: Infinite Series
    and Convergence
    Tests](http://www.youtube.com/watch?v=TZ9jX4pN5Uk)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2466366665?i=1898289868)  
      
     Instructions: This lecture will cover sub-subunits 5.3.2 - 5.3.4. 
    Please watch Lecture 37 from time 17:35 minutes to the end.  Note
    that lecture notes are available in PDF; the link is on the same
    page as the lecture.  Professor Jerison will begin his discussion of
    infinite series with the series [Sum of 1 divided by (n squared)]. 
    He introduces important terminology and then proves the convergence
    of the above series by comparison with the integral of the summand. 
    He extends this argument to state the integral test.  Finally, he
    goes over the limit comparison test for positive sequences.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: The video above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-37-infinite-series/)
    (Flash or MP4).

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    The Integral Test”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus: The
    Integral
    Test](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: Please click on the link above, scroll down to Video
    50: “The Integral Test,” and watch this entire lecture.  This short
    video restates the integral test in a more concise way and provides
    several other important applications of the integral test, such as
    proving the convergence of the p-series and estimating remainders of
    partial sums.  
      
     Viewing this lecture should take approximately 15 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “The
    Integral Test”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[The Integral
    Test](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Series,” and click button 188 (The
    Integral Test).  Do problems 1-10.  If at any time a problem set
    seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3.3 Comparison Test** <span id="5.3.3"></span> 
*Series with no negative terms either have terms that get small enough
or fast enough for the series to converge, or terms that remain too
large and hence cause the series to diverge.  It would seem logical that
if Series A converges, and the n<sup>th</sup> term of Series B is less
than or equal to the n<sup>th</sup> term of Series A for all n (at least
after a finite number of terms), then Series B should converge: if A’s
terms are small enough, B’s should also be.  Likewise, a series with
terms that are larger than the corresponding terms of a divergent series
should diverge.  This is true and is known as the (direct) comparison
test.  *

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Comparison Tests”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus:
    Comparison
    Tests](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: This lecture will cover sub-subunits 5.3.3-5.3.6. 
    Please click on the link above, scroll down to Video 51: “Comparison
    Tests,” and watch the video in its entirety.  This video states,
    proves, and applies the comparison, limit comparison, ratio, and
    root tests for positive series.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Furman University: Dan Sloughter’s Difference
    Equations to Differential Equations: “5.4 Infinite Series: The
    Comparison Test”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations*: “[5.4 Infinite Series: The Comparison
    Test](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Sloughter-Chapter-5.4.pdf)” (PDF)  
      
     Instructions: Please click the link above, and do problems 1 (a, c,
    e, g), 2 (a, c, e, g), and 4.  When finished, click
    [here](http://de2de.wordpress.com/2007/07/27/section-54/) for
    solutions (courtesy of the author’s blog).  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Dan Sloughter and the original version can be found
    [here](http://synechism.org/drupal/de2de/) (HTML). Please respect
    the copyright and terms of use displayed on the solution guide
    above.

**5.3.4 Ratio Test** <span id="5.3.4"></span> 
*The ratio and root tests are two ways of checking whether a series is
“geometric in the limit” and thereby drawing conclusions about its
behavior.  The geometric series with terms ar<sup>n</sup>, a and r
positive, has the properties that the ratio of the n+1<sup>st</sup> term
to the nth term is always r, and the n<sup>th</sup> root of the
n<sup>th</sup> term is always r times the n<sup>th</sup> root of a.  The
limit of each of those values as n tends to infinity is r.  The ratio
test and root test check the limits of those values as computed from
other series.  Although we lose some precision – i.e., a geometric
series with ratio 1 diverges, but a limit of 1 in the ratio or root test
is inconclusive – these tests greatly increase the number of series for
which we can determine convergence or divergence.  Typically, only one
of these tests is algebraically feasible for a given series, but in the
event both are, note that if one is inconclusive, the other will be as
well.*

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “The Ratio
    Test”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[The Ratio
    Test](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Series,” and click button 189 (The Ratio
    Test).  Do problems 4-17.  (See the navigation buttons below the
    problem.)  If at any time a problem set seems too easy for you, feel
    free to move on.  
      
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3.5 Root Test** <span id="5.3.5"></span> 
-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “The nth
    Root Test” Module**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[The nth Root
    Test](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Series,” and click button 190 (The nth
    Root Test).  Do problems 3-17.  (See the navigation buttons below
    the problem.)  If at any time a problem set seems too easy for you,
    feel free to move on.  
      
     Completing this assessment should take approximately 1 hour and 30
    minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3.6 Limit Comparison Test** <span id="5.3.6"></span> 
*Just as the ratio and root tests check whether a series is “geometric
in the limit,” the limit comparison test checks whether two series are
“equal in the limit,” up to a non-zero constant multiple.  If so, we can
conclude the series have the same convergence behavior.*

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: “The Limit Comparison
    Test”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[The Limit
    Comparison Test](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Series,” and click button 191 (The Limit
    Comparison Test).  Do problems 1-12.  (See the navigation buttons
    below the problem.)  If at any time a problem set seems too easy for
    you, feel free to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    Supplemental Notes for Calculus II: “Ratio and Root Test for Series
    of Nonnegative Terms” and “Infinite Series”**
    Link: Clinton Community College: Elizabeth Wood’s Supplemental Notes
    for Calculus II:  “[Ratio and Root Test for Series of Nonnegative
    Terms](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.3.6-Ratio-and-Root-Test-for-Series-of-Nonnegative-Terms.pdf)” (PDF)
    and “[Infinite
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.3.6-Infinite-Series.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental23.htm)
    (“Ratio and Root Test for Series of Nonnegative Terms”)  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental20.htm)
    (“Infinite Series”)  
        
     Instructions: This assessment will cover subunits 5.2-5.3.  Please
    click on the first link above and work through each of the seven
    examples on the page.   Next, please click on the second link and
    work through each of the thirteen examples on the page.  As in any
    assessment, solve the problem on your own first.  Solutions are
    given beneath each example.  
      
     Completing this assessment should take approximately 2 hours.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental23.htm) (HTML)
    and
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental20.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder. 

**5.4 Tests for Absolute and Conditional Convergence** <span
id="5.4"></span> 
*Thus far, we have worked with series with all non-negative terms.  When
series with negative terms are allowed, the picture changes slightly. 
If all terms are negative, of course, the series is simply -1 times a
series of all positive terms and has the same convergence behavior as
the positive series.  If the terms are mixed sign, however, the positive
and negative terms cancel each other out to some degree.  For such
series, we have essentially two options: the alternating series test,
which requires the signs alternate, or to take the absolute value of
each term and test that series for convergence.*

**5.4.1 Alternating Series Test** <span id="5.4.1"></span> 
*An alternating series is one in which the terms alternate between
positive and negative.  You may view it as a sequence of partial sums
that alternately increase and decrease.  The alternating series test
says that if the magnitudes of the terms decrease to zero in the limit,
then the series converges.  For example, if every increase or decrease
of the partial sums is smaller than the previous, and they limit to
zero, the partial sums themselves have a finite limit.  Alternating
series that are easy to write down tend either to diverge by the
divergence test or converge by the alternating series test, but be aware
that it is easy to define an alternating series with terms limiting to
zero (but not decreasing to zero) that diverges.  For example, 1 −1/2 +
2/3 −1/3 + 1/2 −1/4 + ….  This is the harmonic series in disguise, as
you will see if you pair off each positive term with the negative term
following it.*

-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 11:
    Sequences and Series: “Section 11.4: Alternating Series”**
    Link: Whitman College: David Guichard’s *Calculus*: Chapter 11:
    Sequences and Series: “[Section 11.4: Alternating
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Guichard-Chapter-11.pdf)” (PDF)  
      
     Instructions: Please click on the link above, locate Chapter 11,
    and read Section 11.4 in its entirety (pages 269 through 273).  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of David Guichard, and can be viewed in its original
    form
    [here](http://www.whitman.edu/mathematics/calculus/calculus_11_Sequences_and_Series.pdf)
    (PDF).  Please note that this material is under copyright and cannot
    be reproduced in any capacity without explicit permission from the
    copyright holder. 

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Alternating Series and Absolute Convergence”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus:
    Alternating Series and Absolute
    Convergence](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: This lecture will cover the topics outlined in
    sub-subunits 5.4.1 and 5.4.2 as well as 5.4.4 and 5.4.5.  Please
    click on the link above, scroll down to Video 52: “Alternating
    Series and Absolute Convergence,” and watch the video lecture in its
    entirety.  This video explains alternating series, conditional and
    absolute convergence, and the ratio and root tests for absolute
    convergence.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Alternating Series”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Alternating
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.4.1-Alternating-Series.pdf)” (PDF)  
      
     Also Availabe in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental24.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the five examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental24.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**5.4.2 Definition of Absolute and Conditional Convergence** <span
id="5.4.2"></span> 
*As we have seen with the harmonic and alternating harmonic series, the
cancellation effect of a mixture of positive and negative terms can be
vital for the convergence of a series.  The alternating harmonic is
called a conditionally convergent series: its convergence is conditional
on the cancellation effect.  If it is possible to eliminate the
cancellation (by taking the absolute value of each term) and still have
convergence, the series is called absolutely convergent.  When series
have a mixture of positive and negative terms but do not alternate sign,
taking the absolute value of the terms and testing the resulting series
for convergence is often a good method.  It cannot tell you if the
original series diverges, but it can show if the original series
converges, absolutely.*

-   **Reading: MIT: Gilbert Strang’s Calculus: Chapter 10: Infinite
    Series: “Section 10.3: Convergence Tests: All Series”**
    Link: MIT: Gilbert Strang’s *Calculus*: Chapter 10: Infinite Series:
    “[Section 10.3: Convergence Tests: All
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Strang-Chapter-10.pdf)” (PDF)  
      
     Instructions: This reading will cover sub-subunits 5.4.2 and
    5.4.3.  Please click on the link above, and read Section 10.3 in its
    entirety (pages 381 through 384).  It is worth pointing out that if
    a series converges conditionally, it does not have a well-defined
    sum.  By rearranging the terms, the value of the sum can be
    changed.  This is an example of the fact that infinity is a strange
    place.  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: The article above is released under [Creative Commons
    Attribution-NonCommercial-ShareAlike
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to Professor Gilbert Strang (MIT) and the original
    version can be
    found [here](http://ocw.mit.edu/resources/res-18-001-calculus-online-textbook-spring-2005/textbook/) (PDF).

**5.4.3 Comparison Test for Absolute Convergence** <span
id="5.4.3"></span> 
*Note: This topic is covered by the reading assigned below sub-subunit
5.4.1.*

**5.4.4 Limit Comparison Test for Absolute Convergence** <span
id="5.4.4"></span> 
*Note: This topic is covered by the lecture assigned below sub-subunit
5.4.1.*

**5.4.5 Ratio Test for Absolute Convergence** <span id="5.4.5"></span> 
-   **Reading: Lamar University: Paul Dawkins’s Paul’s Online Math
    Notes: Calculus II: “Sequences and Series: Ratio Test”**
    Link: Lamar University: Paul Dawkins’s *Paul’s Online Math Notes:
    Calculus II*: “[Sequences and Series: Ratio
    Test](http://tutorial.math.lamar.edu/Classes/CalcII/RatioTest.aspx)” (HTML)  
      
     Instructions: Please click the link above, and read this entire
    section.  This reading defines, applies, and proves the ratio
    test*.*  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.4.6 Root Test for Absolute Convergence** <span id="5.4.6"></span> 
-   **Reading: Lamar University: Paul Dawkins’s Paul’s Online Math
    Notes: Calculus II: “Sequences and Series: Root Test”**
    Link: Lamar University: Paul Dawkins’s *Paul’s Online Math Notes:
    Calculus II*: “[Sequences and Series: Root
    Test](http://tutorial.math.lamar.edu/Classes/CalcII/RootTest.aspx)” (HTML)  
      
     Instructions: Please click the link above, and read this entire
    section.  This reading defines, applies, and proves the root test.  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Furman University: Dan Sloughter’s Difference
    Equations to Differential Equations: “5.6 Infinite Series: Absolute
    Convergence”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations*: “[5.6 Infinite Series: Absolute
    Convergence](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Sloughter-Chapter-5.6.pdf)” (PDF)  
      
     Instructions: This assessment will cover sub-subunits 5.4.1-5.4.6. 
    Please click the link above, and do problems 1 (a, c, e, g), 2 (a,
    c, e, g), and 3 (a, b, c).  When finished, click
    [h](http://de2de.wordpress.com/2007/07/30/section-56/)[ere](http://de2de.wordpress.com/2007/07/30/section-56/) for
    solutions (courtesy of the author’s blog).  
      
     Completing this assessment should take approximately 45 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to Dan Sloughter and the original version can be found
    [here](http://synechism.org/drupal/de2de/) (HTML). Please respect
    the copyright and terms of use displayed on the solutions guide
    above.

-   **Assessment: Millersville University: Bruce Ikenaga’s “Absolute
    Convergence and Conditional Convergence”**
    Link: Millersville University: Bruce Ikenaga’s [“Absolute
    Convergence and Conditional
    Convergence”](http://www.millersville.edu/~bikenaga/calculus/absconv/absconv.html) (HTML)  
      
     Instructions: This assessment will cover sub-subunits 5.4.1-5.4.6. 
    Please click on the link above and scroll down the page.  Work
    through the last four examples before looking at their solutions.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Absolute and Conditional
    Convergence”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Absolute and Conditional
    Convergence](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.4.6-Absolute-and-Conditional-Convergence.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental25.htm)  
      
     Instructions: This assessment will cover sub-subunits 5.4.1-5.4.6. 
    Please click on the link above, and work through each of the six
    examples on the page.  As in any assessment, solve the problem on
    your own first.  Detailed solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 45 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental25.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**5.5 Series Representations of Functions** <span id="5.5"></span> 
*In Single-Variable Calculus I (MA101), we learned that we can
approximate a function about a point when we have information about the
function’s value and its slope at that point.  In this subunit, you will
learn how to be even more accurate by gathering additional information
about the function at a particular point (i.e. by using the second
derivative, third derivative, fourth derivative, etc.).  The more
information you collect, the closer you will get to the function
itself.  The series representation of a function is the infinite series
about a point, taking into consideration all of the derivatives about
that point and in the form of a polynomial.  This will enable us to look
at functions, derivatives, and integrals in new and rather intuitive
ways.*

**5.5.1 Power Series** <span id="5.5.1"></span> 
*A power series is any series where the n<sup>th</sup> term contains
x<sup>n</sup> (where x as the name of the variable and the exact
matching of the term index with the exponent are not essential). 
Essentially, it is an infinite polynomial in x.*

-   **Reading: Whitman College: David Guichard’s Calculus: “Chapter 11:
    Sequences and Series: Section 11.8: Power Series”**
    Link: Whitman College: David Guichard’s *Calculus*: “[Chapter 11:
    Sequences and Series: Section 11.8: Power
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Guichard-Chapter-11.pdf)” (PDF)  
      
     Instructions: Please click on the link above and read Section 11.8
    in its entirety (pages 278 through 281).  A key term to understand
    in this section is *radius of convergence.*  
      
     Studying this reading should take approximately 15-20 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of David Guichard, and can be viewed in its original
    form
    [here](http://www.whitman.edu/mathematics/multivariable/multivariable_11_Sequences_and_Series.pdf)
    (PDF).  Please note that this material is under copyright and cannot
    be reproduced in any capacity without explicit permission from the
    copyright holder. 

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 38: Taylor Series”
    and Haynes Miller’s “Lecture 39: Final Review”**
    Link: YouTube: MIT: David Jerison’s [“Lecture 38: Taylor
    Series”](https://www.youtube.com/watch?v=IopAw6boUwQ) (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2469020398?i=1141761607)  
      
     and Haynes Miller’s [“Lecture 39: Final
    Review](https://www.youtube.com/watch?v=rEgNSmCCwR4)[”](https://www.youtube.com/watch?v=rEgNSmCCwR4) (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2465367293?i=1653200549)  
      
     Instructions: These lectures cover subunits 5.5.1-5.5.3. After
    completing the readings for these sections, click on the first link,
    and watch Lecture 38 from the 22:45 minute mark to the end. In this
    lecture, Professor Jerison will discuss general power series before
    introducing Taylor Series. Then, watch Lecture 39.  Professor Miller
    will continue this exposition; he will go over the derivations for
    the power series for the exponential, the sine, and the cosine
    before moving on to other examples.   
     Note that on the original pages (linked below), the lecture notes
    are available in PDF under the "Related Resources" tab.   
      
     Watching these lectures and pausing to take notes should take
    approximately 1 hour and 15 minutes.  
      
     Terms of Use: The videos above are released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/). They are
    attributed to MIT and the original versions can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-38-taylors-series/)[ ](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-38-taylors-series/)and
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-39-final-review/).

-   **Reading: Clinton Community College: Elizabeth Wood’s “Supplemental
    Notes for Calculus II: Power Series and the Uses of Power Series”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Power Series and the Uses of Power
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.5.1-Power-Series-and-the-Uses-of-Power.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental26.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the six examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 45 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental26.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “Power
    Series”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[Power
    Series](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “3. Power and Taylor Series,” and click
    button 192 (Power Series).  Do the problems in the module as they
    are presented to you (18 total).  These problems all deal with
    computing the radius of convergence for a power series.  If at any
    time a problem set seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 2 hours.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.5.2 Calculus with Power Series** <span id="5.5.2"></span> 
*Happily, our infinite polynomials interact with integration and
differentiation in the same way as finite polynomials: the integral of a
sum is the sum of the integrals of each term, and likewise for
derivatives.  The bookkeeping aspects of this topic will be easier if
you think of the “point of view” of the mathematical operators: the
integral sign and derivative operator d/dx see x as a variable and n as
a constant (a different fixed value for each series term).  On the other
hand, the summation operator sees n as the variable and x as the
constant (a value that will be the same for every series term).*

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 9: Infinite Series: “Section 9.8: Derivatives and
    Integrals of Power Series”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 9: Infinite Series: “[Section 9.8: Derivatives
    and Integrals of Power
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-9.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 9.8
    in its entirety (pages 533 through 539).  
      
     Under certain conditions, power series can be differentiated and
    integrated.  Certain characteristics of the series may change,
    however, such as the interval of convergence.  We have not been
    using Keisler’s text so far this unit, because hyperreals are not as
    helpful to the intuition for series as they are for integrals.  In
    the last several sub-subunits, they do not appear except in the
    proof of Theorem 1, part (iii), on pages 537-538 of this section. 
    That statement, that the radius of convergence remains the same when
    a power series is integrated or differentiated, is typically given
    in calculus texts without proof.  Do not fret too much over the
    proof.  
      
     Studying this reading should take approximately 45 minutes to
    complete.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

**5.5.3 Taylor and Maclaurin Series** <span id="5.5.3"></span> 
*Taylor series are a particular kind of power series, defined from a
function.  Maclaurin series are a particular kind of Taylor series.  The
definition allows you to expand any function into an infinite
polynomial, which in many cases will be provably equal to the original
function, and may be much easier to compute with.*

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 9: Infinite Series: “Section 9.10: Taylor’s
    Theorem” and “Section 9.11: Taylor Series”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 9: Infinite Series: “[Section 9.10: Taylor’s
    Theorem](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-9.pdf)” (PDF)
    and “[Section 9.11: Taylor
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-9.pdf)” (PDF)  
      
     Instructions: Please click on the links above, and read Sections
    9.10 and 9.11 (pages 547 through 560).  
      
     Taylor Series use the information provided by the derivatives of a
    function (slope of the tangent line, concavity, etc.) to approximate
    the function by a sequence of polynomials.  Taylor’s Theorem tells
    how good this approximation is.  Taylor Series are used extensively
    in higher mathematics, especially in numerical analysis.  
      
     Studying these readings should take approximately 2 hours.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Taylor and MacLaurin Series”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Taylor and MacLaurin
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.5.3-Taylor-and-MacLaurin-Series.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental27.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the seven examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental27.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book III: Gerardo Mendoza’s “Taylor
    Series”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book III*: Gerardo Mendoza’s “[Taylor
    Series](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “3. Power and Taylor Series,” and click
    button 193 (Taylor Series).  Choose at least 5 of the problems to
    do.  If at any time a problem set seems too easy for you, feel free
    to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.5.4 Approximation by Power Series** <span id="5.5.4"></span> 
-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 9: Infinite Series: “Section 9.9: Approximations
    by Power Series”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 9: Infinite Series: “[Section 9.9: Approximations
    by Power
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-9.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 9.9
    in its entirety (pages 540 through 546).  Approximation by power
    series is a very important topic; for instance, it is how
    calculators compute sines and cosines!  
      
     Studying this reading should take approximately 1 hour.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Web Media: UC College Prep’s *Calculus BC II for AP*: “Infinite
    Sequences and Series: Approximating Functions Using Polynomials” and
    “Infinite Sequences and Series: Applications of Taylor Series”**
    Link:  UC College Prep’s *Calculus BC II for AP*: “[Infinite
    Sequences and Series: Approximating Functions Using
    Polynomials](http://www.youtube.com/watch?v=mcB6ItNT93s)” (YouTube)
    and “[Infinite Sequences and Series: Applications of Taylor
    Series](http://www.youtube.com/watch?v=fQv2iKJVCS8)” (YouTube)  
      
     Instructions: Click on the links above, and watch the interactive
    lectures.  You may want to have a pencil and paper close by, as you
    will be prompted to work on related problems during the lecture.   
      
     Studying these lectures should take approximately 1 hour.  
      
     Terms of Use:  The videos above are licensed under a [Creative
    Commons Attribution-NonCommercial-NoDerivatives
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  They
    are attributed to University of California College Prep.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Other Topics Related to Taylor
    Series”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Other Topics Related to Taylor
    Series](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-5.5.4-Other-Topics-Related-to-Taylor-Series.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental28.htm)  
      
     Instructions: Click on the link above, and work through each of the
    five examples on the page. As in any assessment, solve the problem
    on your own first. Solutions are given beneath each example.  
      
     Completing this assessment should take approximately 45 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental28.htm). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.


