**Unit 4: Parametric Equations and Polar Coordinates** <span
id="4"></span> 
*So far we have worked in Cartesian (rectangular) coordinates where
there has been one dependent variable, say x, and one dependent variable
y=f(x).  At times this has been inconvenient.  Think about the equation
describing the graph of a circle, x<sup>2</sup> + y<sup>2</sup> =
r<sup>2</sup>: here, y cannot be given as an explicit function of x. 
For situations like this one there are other ways of describing graphs
which make calculations much simpler.*  
  
 *You studied parametric equations and polar coordinates in subunits 4.2
and 4.5 of Precalculus II*
[(MA003)](http://www.saylor.org/courses/ma003/)*, so for an alternate
approach, you may review those subunits.  Make sure to come back to this
unit, because MA003 does not cover as much material.*

**Unit 4 Time Advisory**  
This unit should take you 12.5 hours to complete.

☐    Subunit 4.1: 3.5 hours

☐    Subunit 4.2: 4 hours

☐    Reading: 0.75 hours  
  
 ☐    Lecture: 0.75 hours  
  
 ☐    Assessment: 2.5 hours

☐    Subunit 4.3: 2.5 hours

☐    Subunit 4.4: 1.25 hours

☐    Subunit 4.5: 1.25 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Graph parametric equations.
-   Find derivatives of parametric equations.
-   Convert between Cartesian and polar coordinates.
-   Graph equations in polar coordinates.
-   Compute derivatives of equations in polar coordinates.
-   Compute areas under curves described by polar coordinates.
-   Compute arc length for curves given in polar coordinates.

**4.1 Parametric Equations and Their Derivatives** <span
id="4.1"></span> 
*Parametric equations treat x and y each as functions of a third
variable, typically t.  It is helpful to think of t as time, and the
equations as instructing how a curve is to be drawn, giving the pen’s
coordinates for each point in time.  This easily extends to curves in
three-dimensional space by adding an equation for z as a function of t.*

-   **Reading: University of Michigan’s Scholarly Monograph Series:
    Wilfred Kaplan’s and Donald J. Lewis’s Calculus and Linear Algebra
    Vol. 1: “3-9 Parametric Equations”**
    Link: University of Michigan’s Scholarly Monograph Series: Wilfred
    Kaplan’s and Donald J. Lewis’s *Calculus and Linear Algebra Vol.1*:
    “[3-9 Parametric
    Equations](http://quod.lib.umich.edu/cgi/t/text/pageviewer-idx?c=spobooks;cc=spobooks;rgn=full%20text;idno=5597602.0001.001;didno=5597602.0001.001;node=5597602.0001.001:5.9;view=image;seq=00000203)” (HTML)  
      
     Instructions: Please click on the link above, and read the assigned
    section.  Use the “previous” and “next” links at the bottom of each
    webpage to navigate through the reading.  This reading discusses
    parametric equations for curves and how to differentiate them.  Note
    the similarity to related rates.  Ignore the reference in the first
    paragraph to vector equations; that is Calculus III material.  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: Khan Academy's “Parametric Equations I” and “Parametric
    Equations II”; MIT: David Jerison’s “Lecture 31: Parametric
    Equations, Arclength, Surface Area” and “Lecture 32: Polar
    Coordinates; Area in Polar Coordinates”**
    Khan Academy's “[Parametric Equations
    I](https://www.khanacademy.org/math/trigonometry/parametric_equations/parametric/v/parametric-equations-1?v=m6c6dlmUT1c)” (YouTube)
    and “[Parametric Equations
    II](https://www.khanacademy.org/math/trigonometry/parametric_equations/parametric/v/parametric-equations-2?v=wToSIQJ2o_8)” (YouTube);
    MIT: David Jerison’s “[Lecture 31: Parametric Equations, Arclength,
    Surface
    Area](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-31-parametric-equations/)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     and “[Lecture 32: Polar Coordinates; Area in Polar
    Coordinates](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-32-polar-coordinates/)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2348707863?i=1154314057)  
      
     Instructions: Please click on the links above to watch Salman
    Khan’s “Parametric Equation I” and “Parametric Equations II.”  Then,
    watch Professor Jerison’s Lecture 31 from time 40:35 minutes to the
    end and Lecture 32 from the beginning up to time 22:50 minutes. 
    Note that lecture notes are available in PDF; the link is on the
    same page as the lecture.  
      
     Salman Khan’s first video gives a very intuitive example of the
    concept of parametric curves—two-dimensional motion with a time
    parameter.  The second video shows how to eliminate the parameter
    and gives a second example.  In the lectures from MIT, Professor
    Jerison will work through a more advanced example and discuss how to
    calculate arc length for curves expressed by parametric equations.  
      
     Viewing these lectures and pausing to take notes should take
    approximately 1 hour.  
      
     Terms of Use: The Khan videos above are released under a [Creative
    Commons Attribution-NonCommercial-NoDerivs 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/).  They
    are attributed to Khan Academy.  
      
     The MIT videos above are released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/).  They are
    attributed to MIT.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Parameterizations of Plane
    Curves” and “Calculus with Parameterized Curves”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Parameterization of Plane
    Curves](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-4.1-Parameterization-of-Plane-Curves.pdf)” (PDF)
    and “[Calculus with Parameterized
    Curves](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-4.1-Calculus-with-Parameterized-Curves.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental32.htm)
    (“Parameterization of Plane Curves”)  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental33.htm)
    (“Calculus with Parameterized Curves”)  
      
     Instructions: Please click on the first link above, and work
    through each of the nine examples on the page.  As in any
    assessment, solve the problem on your own first.  Solutions are
    given beneath each example.  Do the same with the second link; work
    through each of the eight examples on the page on your own before
    checking them with the given solutions.  
      
     Completing these assessments should take approximately 2 hours.  
      
     Terms of Use: The material above has been reposted by the kind
    permission of Elizabeth Wood, and can be viewed in its original form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental32.htm) (HTML)
    and
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental33.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**4.2 Polar Coordinates** <span id="4.2"></span> 
*Note: Polar Coordinates are both a different coordinate system to
describe two-dimensional space and, when related back to the “x-y
plane,” a different parameterization for curves in that system.  Instead
of representing location by horizontal and vertical distance from the
origin, we represent it by straight-line distance from the origin and
angle from the positive x-axis (measured counter-clockwise).*

-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 7: Trigonometric Functions: “Section 7.7: Polar
    Coordinates”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 7: Trigonometric Functions: “[Section 7.7: Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-7.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 7.7
    in its entirety (pages 406 through 411).  Polar coordinates use two
    parameters, angle and radius, to describe the graphs of curves.  
      
     Studying this reading should take approximately 45 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Polar Coordinates and Graphs”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus: Polar
    Coordinates and
    Graphs](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: This lecture will cover subunits 4.2 and 4.3.  Please
    click on the link, scroll down to Video 41: “Polar Coordinates and
    Graphs,” and watch the entire lecture.  In this video, you will
    learn how to graph a number of well-known figures in polar
    coordinates, such as cardioids, roses, and limaçons.  You will also
    learn more about derivatives and tangent lines in polar
    coordinates.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Dan Reich’s “Plotting Points
    in Polar Coordinates”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Dan Reich’s “[Plotting Points in
    Polar Coordinates](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “5. Geometry, Curves, and Polar
    Coordinates,” and click button 181 (Sketching Polar Curves).  Do
    five of the problems in the module as they are presented to you.  If
    at any time a problem set seems too easy for you, feel free to move
    on.  
      
     Completing this assessment should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Polar Coordinates”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-4.2-Polar-Coordinates.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental34.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the eighteen examples on the page.  As in any assessment, solve
    the problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 2 hours.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental34.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**4.3 Derivatives and Curve Sketching in Polar Coordinates** <span
id="4.3"></span> 
-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 7: Trigonometric Functions: “Section 7.8: Slopes
    and Curve Sketching in Polar Coordinates”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 7: Trigonometric Functions: “[Section 7.8: Slopes
    and Curve Sketching Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-7.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 7.8
    in its entirety (pages 412 through 419).  Here, you will learn tips
    and tricks for graphing equations in polar coordinates and discover
    how to take derivatives of such functions.  
      
     Studying this reading should take approximately 45 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Activity: Temple University: Gerardo Mendoza’s and Dan Reich’s
    Calculus on the Web: Calculus Book II: Dan Reich’s “Sketching Curves
    in Polar Coordinates”**
    Link: Temple University: Gerardo Mendoza’s and Dan Reich’s *Calculus
    on the Web: Calculus Book II*: Dan Reich’s “[Sketching Curves in
    Polar Coordinates](http://cow.math.temple.edu/)” (HTML)  
      
     Instructions: Click on the link above.  Then, click on the “Index”
    button.  Scroll down to “5. Geometry, Curves, and Polar
    Coordinates,” and click button 183 (Sketching Polar Curves).  Do
    each of the problems (six in total).  This is an exploratory
    graphing assessment which is more like an applet.  If at any time a
    problem set seems too easy for you, feel free to move on.  
      
     Completing this assessment should take approximately 45 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Graphing in Polar
    Coordinates”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Graphing in Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-4.3-Graphing-in-Polar-Coordinates.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental35.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the eight examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: The material above has been reposted by the kind
    permission of Elizabeth Wood, and can be viewed in its original form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental35.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**4.4 Areas with Polar Coordinates** <span id="4.4"></span> 
-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 7: Trigonometric Functions: “Section 7.9: Area in
    Polar Coordinates”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 7: Trigonometric Functions: “[Section 7.9 Area in
    Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-7.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 7.9
    in its entirety (pages 420 through 424).  
      
     Studying this reading should take approximately 30 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Lecture: YouTube: MIT: David Jerison’s “Lecture 33: Exam 4
    Review”**
    Link: YouTube: MIT: David Jerison’s “[Lecture 33: Exam 4
    Review](http://www.youtube.com/watch?v=Q6Sh2hhFHAs)” (YouTube)  
      
     Also Available in:  
     [iTunes
    U](http://deimos3.apple.com/WebObjects/Core.woa/Browse/mit.edu.1877315077.01877315082.2466366665?i=1898289868)  
      
     Instructions: Please watch Lecture 33 from the beginning to time
    34:58.  Note that lecture notes in PDF are available for this video;
    the link is on the same page as the lecture.  In this lecture,
    Professor Jerison will touch on computing area under curves
    described by polar coordinates and also do several more examples of
    curve sketching in polar coordinates.  
      
     Viewing this lecture and pausing to take notes should take
    approximately 45 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to MIT and the original version can be found
    [here](http://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/lecture-33-exam-4-review/)
    (Flash or MP4).

-   **Lecture: University of Houston: Selwyn Hollis’s “Video Calculus:
    Areas and Length Using Polar Coordinates”**
    Link: University of Houston: Selwyn Hollis’s “[Video Calculus: Areas
    and Lengths Using Polar
    Coordinates](http://online.math.uh.edu/HoustonACT/videocalculus/index.html)” (QuickTime)  
      
     Instructions: This lecture will cover subunits 4.4 and 4.5.  Please
    click on the link, scroll down to Video 42: “Areas and Lengths Using
    Polar Coordinates,” and watch the entire video.  This video
    discusses area (slides 1-5) and arc length (slides 7-9) in polar
    coordinates.  
      
     Viewing this video lecture should take approximately 30 minutes.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.5 Arc Length with Polar Coordinates** <span id="4.5 "></span> 
-   **Reading: University of Wisconsin: H. Jerome Keisler’s Elementary
    Calculus: Chapter 7: Trigonometric Functions: “Section 7.10: Length
    of a Curve in Polar Coordinates”**
    Link: University of Wisconsin: H. Jerome Keisler’s *Elementary
    Calculus*: Chapter 7: Trigonometric Functions: “[Section 7.10:
    Length of a Curve in Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-Kiesler-Chapter-7.pdf)” (PDF)  
      
     Instructions: Please click on the link above, and read Section 7.10
    in its entirety (pages 425 through 427).  
      
     Studying this reading should take approximately 15-20 minutes.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial-ShareAlike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) (HTML).  It
    is attributed to H. Jerome Kiesler and the original version can be
    found [here](http://www.math.wisc.edu/~keisler/calc.html) (PDF).

-   **Assessment: Clinton Community College: Elizabeth Wood’s
    “Supplemental Notes for Calculus II: Integration in Polar
    Coordinates”**
    Link: Clinton Community College: Elizabeth Wood’s “[Supplemental
    Notes for Calculus II: Integration in Polar
    Coordinates](https://resources.saylor.org/archived/wp-content/uploads/2012/09/MA102-4.5-Integration-in-Polar-Coordinates.pdf)” (PDF)  
      
     Also Available in:  

    [HTML](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental37.htm)  
      
     Instructions: Please click on the link above, and work through each
    of the nine examples on the page.  As in any assessment, solve the
    problem on your own first.  Solutions are given beneath each
    example.  The examples cover both Arc Length and Area in Polar
    Coordinates.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Terms of Use: The linked material above has been reposted by the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental37.htm) (HTML). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.


