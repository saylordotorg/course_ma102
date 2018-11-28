**Unit 2: Applications of Integration** <span id="2"></span> 
*In this unit, we will take a first look at how integration can and has
been used to solve various types of problems.  Now that you have
conceptualized the relationship between integration and areas and
distances, you are ready to take a closer look at various applications;
these range from basic geometric identities to more advanced situations
in Physics and Engineering.*

**Unit 2 Time Advisory**  
This unit should take you 19.75 hours to complete.

☐    Subunit 2.1: 2.75 hours

☐    Subunit 2.2: 1 hour

☐    Subunit 2.3: 4.5 hours

☐    Sub-subunit 2.3.1: 3 hours  
  
 ☐    Sub-subunit 2.3.2: 1.5 hours

☐    Subunit 2.4: 2.5 hours

☐    Subunit 2.5: 1.5 hours

☐    Subunit 2.6: 2 hours

☐    Subunit 2.7: 5.5 hours

☐    Sub-subunit 2.7.1: 1.5 hours  
  
 ☐    Sub-subunit 2.7.2: 1.5 hours  
  
 ☐    Sub-subunit 2.7.3: 0.5 hours  
  
 ☐    Sub-subunit 2.7.4: 2 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Find the area between two curves.
-   Find the volumes of solids using ideas from geometry.
-   Find the volumes of solids of revolution using disks and washers.
-   Find the volumes of solids of revolution using shells.
-   Write and interpret a parameterization for a curve.
-   Find the length of a curve.
-   Find the surface area of a solid of revolution.
-   Compute the average value of a function.
-   Use integrals to compute the displacement and the total distance
    traveled.
-   Use integrals to compute moments and centers of mass.
-   Use integrals to compute work.

**2.1 The Area between Curves** <span id="2.1"></span> 
*Suppose you want to find the area between two concentric circles.  How
would you do this?  Logic dictates that you subtract the area of the
smaller circle from that of the larger circle.  As this subunit will
demonstrate, this method also works when you are trying to determine the
area between curves.*

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 4: Integration: “Section 4.5: Areas between Two
    Curves”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 4: Integration: “[Section 4.5: Areas between Two
    Curves](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-4.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 4.5
    in its entirety (pages 218 through 222).  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 21: Applications
    to Logarithms and Geometry”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 21: Applications of
    Logarithms and
    Geometry](http://www.youtube.com/watch?v=TstOpsPnsAc)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     Instructions: Please watch the segment of this video lecture from
    time 21:30 minutes through the end.  Note that lecture notes are
    available in PDF; the link is on the same page as the lecture.  In
    this lecture, Dr. Jerison will explain how to calculate the area
    between two curves.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: The video above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-21-applications-to-logarithms/)
    (Flash or MP4).

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Aaron Robertson’s “Area
    between Curves I” and “Area between Curves II”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Aaron Robertson’s “[Area between
    Curves I](http://cow.math.temple.edu/)” (HTML) and “[Area between
    Curves II](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Applications of Integration,” and click
    button 115 (Area between Curves I).  Do problems 6-13.  Next, choose
    button 116 (Area between Curves II), and do problems 4-10.  If at
    any time a problem set seems too easy for you, feel free to move
    on.  
      
     Completing these assessments should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Indiana University Southeast: Margaret Ehringe’s
    “Practice on Area between Two Curves”**
    Link: Indiana University Southeast: Margaret Ehringe’s [“Section 5.3
    Area between Two
    Curves”](http://homepages.ius.edu/MEHRINGE/M120/Supplement/AreaBetweenCurves.htm) (HTML)  
      
     Instructions: Click on the link above, and do problems 1-3 and
    6-9.  When you have finished, scroll down the page to check your
    answers.  
      
     The point of this third assessment is for you to practice setting
    up and completing these problems without the graphical aids provided
    by the Temple University media; you will have to graph these curves
    for yourself in order to begin the problems.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2 Volumes of Solids** <span id="2.2"></span> 
*We often take basic geometric formulas for granted.  (Have you ever
asked yourself why the volume of a right cylinder is
V=πhr<sup>2</sup>?)  In this subunit, we will explore how some of these
formulas were developed.  The key lies in viewing solids as functions
that revolve around certain lines.  Consider, for example, a constant,
horizontal line, and then imagine that line revolving around the x-axis
(or any parallel line).  The resulting shape is a right cylinder.  We
can find the volume of this figure by looking at infinitesimally thin
“slices” and adding them all together.  This concept enables us to
calculate the volume of some extremely complex figures.  In this
subunit, we will learn how to do this in general; in the next, we will
now take a look at two conventional methods for doing so when the figure
has rotational symmetry.*

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Volumes I”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus:
    Volumes
    I](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: Please click on the link, scroll down to Video 27:
    “Volumes I,” and view the entire video.  This video explains how to
    use integral calculus to calculate the volumes of general solids.   
      
     Viewing this lecture and pausing to take notes should take
    approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus I: Finding Volumes by Slicing”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus I: Finding Volumes by
    Slicing](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-2.2-Finding-Volumes-by-Slicing.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/math150supnotes/supplemental25.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the three examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/math150supnotes/supplemental25.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**2.3 Volume of Solids of Revolution** <span id="2.3"></span> 
*When we are presented with a solid that was produced by rotating a
curve around an axis, there are two sensible ways to take that solid
apart: slice it thinly perpendicularly to the axis, into disks (or
washers, if the solid had a hole in the middle), or peel layers from
around the outside like the paper wrapper of a crayon.  The latter
method is known as the shell method and produces thin cylinders.  In
both cases, we find the area of the thin segments and add them up to
find the volume; as usual, when we have infinitely many pieces, this
“addition” is really integration.*

**2.3.1 Disks and Washers** <span id="2.3.1"></span> 
-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 6: Applications of the Integral: “Section 6.2:
    Volumes of Solids of Revolution”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 6: Applications of the Integral: “[Section 6.2:
    Volumes of Solids of
    Revolution](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-6.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 6.2
    in its entirety (pages 308 through 318).  This reading will cover
    sub-subunits 2.3.1-2.3.2.  
      
     Studying this reading should take approximately 1 hour.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 22: Volumes by
    Disks and Shells”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 22: Volumes by Disks
    and Shells](http://www.youtube.com/watch?v=5z4Qp38Rxoc)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     Instructions: Please click on the link above, and watch the
    entirety of this video.  Note that lecture notes are available in
    PDF; the link is on the same page as the lecture.  Dr. Jerison
    elaborates on some tangential material for a few minutes in the
    middle, but returns to the essential material very quickly.  This
    lecture will cover the topics outlined for sub-subunits 2.3.1 and
    2.3.2.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour.  
      
     Terms of Use: The video above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-22-volumes/)
    (Flash or MP4).

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Aaron Robertson and Dan
    Birmajer’s “Solid of Revolution – Washers”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Aaron Robertson and Dan Birmajer’s
    “[Solid of Revolution –
    Washers](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Applications of Integration,” and click
    button 119 (Solid of Revolution – Washers).  Do problems 1-12.  If
    at any time a problem set seems too easy for you, feel free to move
    on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.2 Cylindrical Shells** <span id="2.3.2"></span> 
-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Aaron Robertson and Dan
    Birmajer’s “Solid of Revolution – Shells”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Aaron Robertson and Dan Birmajer’s
    “[Solid of Revolution –
    Shells](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Applications of Integration,” and click
    button 120 (Solid of Revolution – Shells).  Do problems 5-17.  If at
    any time a problem set seems too easy for you, feel free to move
    on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Math Centre’s “Volumes: Exercises”**
    Link: Math Centre’s “[Volumes:
    Exercises](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/9-08e.swf)” (Flash)  
      
     Instructions: This assessment is for subunits 2.2 and 2.3; do not
    complete this assessment until you have worked through these
    subunits in their entirety.  Click on the link above, and work
    through the exercises using the method you feel is most
    appropriate.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: The resource above is licensed under a [Creative
    Commons Attribution-NonCommercial-NoDerivs 2.0 UK: England & Wales
    License](http://creativecommons.org/licenses/by-nc-nd/2.0/uk/)
    (HTML).  It is attributed to Math Centre, and the original version
    can be found
    [here](http://www.mathcentre.ac.uk/resources/tests/swf/Integration/Exercises/9-08e.swf)
    (Flash).

**2.4 Lengths of Curves** <span id="2.4"></span> 
*In this subunit, we will make use of another concept that you have
known and understood for quite some time: the distance formula.  If you
want to estimate the length of a curve on a certain interval, you can
simply calculate the distance between the initial point and terminal
point using the traditional formula.  If you want to increase the
accuracy of this measurement, you can identify a third point in the
middle and calculate the sum of the two resulting distances.  As we add
more points to the formula, our accuracy increases: the exact length of
the curve will be the sum (i.e. the integral) of the infinitesimally
small distances.*

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 6: Applications of the Integral: “Section 6.3:
    Length of a Curve”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 6: Applications of the Integral: “[Section 6.3:
    Length of a
    Curve](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-6.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 6.3
    in its entirety (pages 319 through 325).  This reading discusses how
    to calculate the length of a curve, also known as arc length.  This
    includes calculating arc length for parametrically-defined curves.  
      
     Studying this reading should take approximately 45 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 31: Parametric
    Equations, Arclength, Surface Area”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 31: Parametric
    Equations, Arclength, Surface
    Area](http://www.youtube.com/watch?v=c1HvtBxEF0w)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     Instructions: Please watch this video lecture from the beginning up
    to time 26:10 minutes.  Note that lecture notes are available in
    PDF; the link is on the same page as the lecture.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: The video above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-31-parametric-equations/)
    (Flash or MP4).

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Daniel Russo’s “Arc Length”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Daniel Russo’s “[Arc
    Length](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “2. Applications of Integration,” and click
    button 125 (Arc Length).  Do all problems (1-9).  If at any time a
    problem set seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.5 Surface Areas of Solids** <span id="2.5"></span> 
*In this subunit, we will combine what we learned earlier in this unit.
 Though you might expect that calculating the surface area of a solid
will be as easy as finding its volume, it actually requires a number of
additional steps.  You will need to find the curve-length for each of
the “slices” we identified earlier and then add them together. *

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 6: Applications of the Integral: “Section 6.4:
    Area of a Surface of Revolution”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 6: Applications of the Integral: “[Section 6.4:
    Area of a Surface of
    Revolution](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-6.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 6.4
    in its entirety (pages 327 through 335).  In this beautiful
    presentation of areas of surfaces of revolution, the author again
    makes use of rigorously-defined infinitesimals, as opposed to
    limits.  Recall that the approaches are equivalent; using an
    infinitesimal is the same as using a variable and then taking the
    limit as that variable tends to zero.  
      
     Studying this reading should take approximately 1 hour.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 31: Parametric
    Equations, Arclength, Surface Area”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 31: Parametric
    Equations, Arclength, Surface
    Area](http://www.youtube.com/watch?v=c1HvtBxEF0w)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     Instructions: Please watch this video lecture from time 26:10
    minutes to time 40:35.  Note that lecture notes are available in
    PDF; the link is on the same page as the lecture.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 15-20 minutes.  
      
     Terms of Use: The video above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-31-parametric-equations/)
    (Flash or MP4).

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus I: Areas of Surfaces of
    Revolution”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Areas of Surfaces of
    Revolution](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-2.5-Areas-of-Surfaces-of-Revolution.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/math150supnotes/supplemental29.html)  
      
     Instructions: Please click on the link above, and work through each
    of the three examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 15-20
    minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/math150supnotes/supplemental29.html) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**2.6 Average Value of Functions** <span id="2.6"></span> 
*Note: You probably learned about averages (or mean values) quite some
time ago.  When you have a finite number of numerical values, you add
them together and divide by the number of values you have added.  There
is nothing preventing us from seeking the average of an infinite number
of values (i.e. a function over a given interval).  In fact, the formula
is intuitive: we add the numbers using an integral and divide by the
range.*

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 6: Applications of the Integral: “Section 6.5:
    Averages”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 6: Applications of the Integral: “[Section 6.5:
    Averages](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-6.pdf)” (PDF)  
      
     Instructions:  Please click on the link above, and read Section 6.5
    in its entirety (pages 336 through 340).  
      
     Studying this reading should take approximately 15-20 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 23: Work, Average
    Value, Probability”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 21:  Applications of
    Logarithms and
    Geometry](http://www.youtube.com/watch?v=3Z7oZpv5-Bc)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     Instructions: Please watch this video lecture from the beginning up
    to time 30:00 minutes.  Note that lecture notes are available in
    PDF; the link is on the same page as the lecture.  In this lecture,
    Professor Jerison will explain how to calculate average values and
    weighted average values.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: The video above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-23-work/)
    (Flash or MP4).

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Daniel Russo’s “Average Value
    of a Function”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Daniel Russo’s “[Average Value of a
    Function](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “4. Assorted Application,” and click button
    124 (Average Value).  Do problems 3-11.  If at any time a problem
    set seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.7 Physical Applications** <span id="2.7"></span> 
*We will now apply what we have learned about integration to various
aspects of science.  You may know that in physics, we calculate “work”
by multiplying the force of the work by the distance over which it is
exerted.  You may also know that density is related to mass and volume. 
But we now know that distance and volume are very much related to
integration.  In this subunit, we will explore these and other
connections.*

**2.7.1 Distance** <span id="2.7.1"></span> 
-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 9:
    Applications of Integration: “Section 9.2: Distance, Velocity,
    Acceleration”**
    Link: Whitman College: David Guichard’s *Calculus*: Chapter 9:
    Applications of Integration: “[Section 9.2: Distance, Velocity,
    Acceleration](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Guichard-Chapter-9.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read the Section
    9.2 in its entirety (pages 192 through 194).  
      
     Studying this reading should take approximately 15-20 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of David Guichard, and can be viewed in its original
    form
    [here](http://www.whitman.edu/mathematics/calculus/calculus_09_Applications_of_Integration.pdf#page=6)
    (PDF).  Please note that this material is under copyright and cannot
    be reproduced in any capacity without explicit permission from the
    copyright holder.

-   **Web Media: UC College Prep’s *Calculus BC II for AP*:
    “Applications of Integrals: Displacement Versus Total Distance”**
    Link: UC College Prep’s *Calculus BC II for AP*: “[Application of
    Antiderivatives & Definite
    Integrals](http://www.youtube.com/watch?v=kTFqeWazJPw)” (YouTube)   
      
     Instructions: Click on the link above, and watch the interactive
    lecture.  You may want to have a pencil and paper close by, as you
    will be prompted to work on related problems during the lecture.   
      
     Viewing this lecture should take approximately 45 minutes.  
      
     Terms of Use: The resource above is released under a [Creative
    Commons Attribution-NonCommercial-NoDerivs
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  It is
    attributed to the University of California College Prep.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus I: Displacement vs. Distance
    Traveled”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus I: Displacement vs. Distance
    Traveled](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-2.7.1-Displacement-vs-Distance-Travelled.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/math150supnotes/supplemental32.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the three examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/math150supnotes/supplemental32.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**2.7.2 Mass and Density** <span id="2.7.2"></span> 
-   **Reading: University of Wisconsin: H. Jerome Kiesler’s Elementary
    Calculus 6.6 “Some Applications to Physics”**
    Link: University of Wisconsin: H. Jerome Kiesler’s *Elementary
    Calculus* 6.6 “[Some Applications to
    Physics](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-6.pdf)”
    (PDF)  
        
     Instructions: Please click on the above link and read the indicated
    section (pages 341-351).  
      
     Studying this reading should take approximately 1 hour.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Web Media: UC College Prep’s Calculus BC II for AP: “Applications
    of Integrals: Center of Mass and Density”**
    Link: UC College Prep’s *Calculus BC II for AP*: “[Applications of
    Integrals: Center of Mass and
    Density](http://www.youtube.com/watch?v=p0Q2K_xhZrc)” (YouTube)  
      
     Also Available in:  

    [Java](http://uccpbank.k12hsn.org/courses/APCalculusBCII//course%20files/multimedia/lesson62/Container.html)  
        
     Instructions: Click on the link above and watch the interactive
    lecture.  You may want to have a pencil and paper close by, as you
    will be prompted to work on related problems during the lecture.   
      
     Viewing this lecture should take approximately 45 minutes.  
        
     Terms of Use: The resource above is released under a [Creative
    Commons Attribution-NonCommercial-NoDerivs License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/) (HTML).  It
    is attributed to The Regents of the University of California and the
    original version can be found
    [here](http://uccpbank.k12hsn.org/courses/APCalculusBCII//course%20files/multimedia/lesson62/Container.html)
    (Java).

**2.7.3 Moments** <span id="2.7.3"></span> 
-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus I: Moments and Centers of Mass”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus I: Moments and Centers of
    Mass](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-2.7.3-Moments-and-Centers-of-Mass.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/math150supnotes/supplemental30.html)  
      
     Instructions: This assessment will test you on what you learned in
    sub-subunits 2.7.2 and 2.7.3.  Please click on the link above, and
    work through each of the four examples on the page.  As in any
    assessment, solve the problem on your own first.  Solutions are
    given beneath each example.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: The material above has been reposted by the kind
    permission of Elizabeth Wood, and can be viewed in its original
    form [here](http://faculty.eicc.edu/bwood/math150supnotes/supplemental30.html) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**2.7.4 Work** <span id="2.7.4"></span> 
-   **Reading: Whitman College: David Guichard’s Calculus: Chapter 9:
    Applications of Integration: “Section 9.5: Work”**
    Link: Whitman College: David Guichard’s *Calculus*: Chapter 9:
    Applications of Integration: “[Section 9.5:
    Work](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-Guichard-Chapter-9.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 9.5
    in its entirety (pages 205 through 208).  Work is a fundamental
    concept from physics roughly corresponding to the distance travelled
    by an object multiplied by the force required to move it that
    distance.  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of David Guichard, and can be viewed in its original
    form
    [here](http://www.whitman.edu/mathematics/calculus/calculus_09_Applications_of_Integration.pdf#page=20) (PDF). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder. 

-   **Web Media: UC College Prep’s Calculus BC II for AP: “Applications
    of Integrals: Work Done Moving an Object”**
    Link: UC College Prep’s *Calculus BC II for AP*: “[Applications of
    Integrals: Work Done Moving an
    Object](http://www.youtube.com/watch?v=xbpmfLxVjYo)” (Youtube)  
      
     Also Available in:  

    [Java](http://uccpbank.k12hsn.org/courses/APCalculusBCII/course%20files/multimedia/lesson57/Container.html)  
      
     Instructions: Click on the link above, and watch the interactive
    lecture.  You may want to have a pencil and paper close by, as you
    will be prompted to work on related problems during the lecture.   
      
     Completing this resource should take approximately 30 minutes.  
      
     Terms of Use:  This video is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivatives
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/) (HTML).
     It is attributed to University of California College Prep, and the
    original version can be found
    [here](http://uccpbank.k12hsn.org/courses/APCalculusBCII/course%20files/multimedia/lesson57/Container.html)
    (Java).  

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus I: Work, Fluid Pressures, and
    Forces”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus I: Work, Fluid Pressures, and
    Forces](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/09/MA102-2.7.4-Work-Fluid-Pressures.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/math150supnotes/supplemental31.html)  
      
     Instructions: Please click on the link above, and work through each
    of the seven examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/math150supnotes/supplemental31.html) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.


