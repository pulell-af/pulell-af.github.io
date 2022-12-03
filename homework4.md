---
layout: post
title: Homework 4
subtitle: T7, T8, T9, A6, A7, TA5, TA6

---

# Theory

## T7
### Illustrate the parallels, between the properties of the relative frequency and the axioms for probability
Before understanding the concept of probability, we defined, in the previous lecture, the concept of relative frequency of a value of a certain attribute. We defined the univariate distribution and the multivariate distribution and we also defined the concept of marginal and conditional relative frequency. We started with a statistical units, then we performed a survay on the statistical units, we stored in a table some attributes to create a certain distribution and then with this value we can perform the absolute frequency of a certain characteristics, the relative frequency of a certain characteristics and so on. About of the conditional frequency, we can also explain this concept in an abstract way:

Thanks to this concept, we can intuitively described and uses some properties of the relative frequency:

The relative frequency is included between 0 and 1 and this frequency is not negative
0 ≤ freq(A) ≤ 1

If A and B are disjoint event then:
freq(A ∩ B) = freq(A) + freq (B)

Disjoint event = two event A and B are incompatible. So we cannot have both events.

This aspect is like the area. if we have two surfaces s1 and s2. And this two surfaces are disjoint then:

stot = s1 + s2

if s1 and s2 are not disjoint, we have to consider also the intersection:

stot = s1 + s2 – (s1 ∩ s2)

If set is empty then the relative frequency is 0. For example we have an event that never happen. Instead the relative frequency of the “population” is 1 because we are considering the events that happen for each unit in the statistical units.
f(∅) = 0

f(population) = 1

Before notice an important aspect that links these properties to the probability, we talk about of three definition of probability:

Classical approach: The probability of an event is the ratio between the number of favorable cases and the number of possible cases. Here we know apriori the possible cases and the favorable cases. If an experiment has n simple outcomes, this method assign a probability of 1/n to each outcome. In other words, each outcome is assumed to have an equal probabiliy of occurence.
Relative-frequency approach: The probability of an event is associated with the relative frequency of the occurrence of the event itself, on a large number of tests tending to infinity. So given a repeatable experiment and a set of events that are all the possible outcomes of that experiment, we can measure the frequency of the various events after a certain number of repetitions. Suppose that A is an event and assume that you have performed the same experiment n times, so n is the number of times A could have occurred. nA is the number of times that A did occur. And nA/n is the relative frequency. Then we can define P(A) as: P(A) = limn->∞ (nA/n). This definition is a possible explanation of the parallelism between the properties of the relative frequency and the axioms for probability measure. This definition has several problems: it is used only for repeatable experiments and we have n->∞, but we cannot never reach the ∞. This definition links probability to frequency. Then we can conclude that, if probability is a frequency, that it must have all the properties that also frequency has.
Subjective approach: The probability of an event is provided according to personal experience and available information. it is the degree of belief that we hold in the occurrence of an event.
This three definition have problem to define probability. We can notice that the properties of frequency are almost identical to the three axioms of probability. Kolmogorov realize that we cannot perfectly define the probability and he realize that the properties of the measure theory could also be applied to probability. For this reason in the 1933 Kolmogorov define the probability P as measure on the measure unit (Ω, F, P). And he defined the probability axioms:

The probability of an event is a non-negative real number: P(E)∈R, P(E) ≥ 0 ∀E∈F. Where F is the event space.  
The maximum possible probability is the probability of the whole set that is 1: P(Ω)=1. Notice that this is the only case where the property of probability is in contrast with the property of the measure theory.
The probability of the union of two disjoint events is the sum of the probability of those events:

## T8: 
### Discuss some concrete examples of Probability measure Space
In mathematics, probabilistic metric spaces are a generalization of metric spaces where the distance no longer takes values in the non-negative real numbers R ≥ 0, but in distribution functions.

Let D+ be the set of all probability distribution functions F such that F(0) = 0 (F is a nondecreasing, left continuous mapping from R into [0, 1] such that max(F) = 1).

Then given a non-empty set S and a function F: S × S → D+ where we denote F(p, q) by Fp,q for every (p, q) ∈ S × S, the ordered pair (S, F) is said to be a probabilistic metric space if:

For all u and v in S, u = v if and only if Fu,v(x) = 1 for all x > 0.
For all u and v in S, Fu,v = Fv,u.
For all u, v and w in S, Fu,v(x) = 1 and Fv,w(y) = 1 ⇒ Fu,w(x + y) = 1 for x, y > 0.
A metric space is said to be complete if every sequence of points in which the terms are eventually pairwise arbitrarily close to each other (a so-called Cauchy sequence) converges to a point in the metric space. The usual metric on the rational numbers is not complete since some Cauchy sequences of rational numbers do not converge to rational numbers. For example, the rational number sequence 3, 3.1, 3.14, 3.141, 3.1415, 3.14159, … converges to π, which is not a rational number. However, the usual metric on the real numbers is complete, and, moreover, every real number is the limit of a Cauchy sequence of rational numbers. In this sense, the real numbers form the completion of the rational numbers. The proof of this fact, given in 1914 by the German mathematician Felix Hausdorff, can be generalized to demonstrate that every metric space has such a completion.


## T9: 
### Illustrate how Measure Theory provides the mathematical foundation for Probability Theory
### What is the definition of statistics?
Statistics in Cybersecurity:
Measure theory is the study of measures. It generalizes the intuitive notions of length, area, and volume. The earliest and most important examples are Jordan measure and Lebesgue measure.

It originated in the real analysis and is used now in many areas of mathematics like, for instance, geometry, probability theory, dynamical systems, functional analysis, etc.

Given a measure m, one can define the integral of suitable real valued functions with respect to m. Riemann integral is applied to continuous functions or functions with “few“ points of discontinuity. For measurable functions that can be discontinuous “almost everywhere” Riemann integral does not make sense. However it is possible to define more flexible and powerful Lebesgue’s integral (integral with respect to Lebesgue’s measure) which is one of the key notions of modern analysis.

References: 

[https://datapeaker.com/en/big–data/axioms-of-probability-three-axioms-of-probability/](https://datapeaker.com/en/big–data/axioms-of-probability-three-axioms-of-probability/)
[https://en.wikipedia.org/wiki/Probability_axioms](https://en.wikipedia.org/wiki/Probability_axioms)
[https://sshivam-singh96.medium.com/difference-between-relative-frequency-probability-b0152600251](https://sshivam-singh96.medium.com/difference-between-relative-frequency-probability-b0152600251)
[https://en.wikipedia.org/wiki/Probability_space](https://en.wikipedia.org/wiki/Probability_space)
[https://en.wikipedia.org/wiki/Probabilistic_metric_space](https://en.wikipedia.org/wiki/Probabilistic_metric_space)
[https://www.britannica.com/science/metric-space](https://www.britannica.com/science/metric-space)
[https://en.wikipedia.org/wiki/Probability_theory](https://en.wikipedia.org/wiki/Probability_theory)
[https://warwick.ac.uk/fac/sci/maths/currentstudents/ughandbook/year3/ma359/](https://warwick.ac.uk/fac/sci/maths/currentstudents/ughandbook/year3/ma359/)

# Applications:

## A6-A7: 
### Generate a m sequences of n trials distributed according a Binomial with success probability p and represent the following quantities: absolute frequency of success, relative frequency of success, "normalized" relative frequency of success.
### In the same chart, add also a vertical histogram representing the distribution of the above 3 types of frequencies on the last trial.
The proposed solution is in the ZIP file that can be found at [this GitHub link](https://github.com/pulell-af/StatisticsHomeworks/tree/main/Homework4Csharp).


# Research
## TA5 
### Give a simple introduction to graphics in the .NET environment. How to create a bitmap and a chart on it.
The .Net framework provides umpteen numbers of options to create and edit graphics through a variety of programming techniques. The Graphics feature in .Net has been mostly implemented in a set of managed classes in the namespaces, System.Drawing, System.Drawing.Drawing2D, System.Drawing.Imaging, System.Drawing.Printing and System.Drawing.Text. These classes that help in custom drawing on the screen forms the GDI+ (Graphics Device Interface) object model of .Net framework. These classes are very intuitive and easy to use. The services provided in this model can be categorized into the following sections:

• Drawing basic graphics like line, rectangle, etc.

• Creating and using images, bitmaps, icons, etc.

• Formatting the text content to different size and shapes

Drawing graphics

Some of the classes that implement the logic for drawing two-dimensional graphics are Brush, Font, Icon, Image, Pen, etc. The names of the classes are self-explanatory to the service they provide. In addition to these classes, the Graphics class is used to draw to the display device. The Pen class is used to draw lines and curves while the classes derived from Brush are used to fill the interiors of the shapes.

There are also few structures like Point, Color, Rectangle and Size which are used to specify the details of an object which can be of more than one value. For example, by using a Point structure, the co-ordinates of a control (Button1) to be 10 pixels from the upper-left corner of the form in which it resides can be specified as below:

Button1.Location = new Point (10, 10);
Following can be the steps to draw a line or any two-dimensional figure in a Windows Form using .Net classes:

• Creating a Graphics object by means of calling the System.Windows.Forms.Control.CreateGraphics method.

• Creating the Pen object and to specify the color and width in pixels.

• Draw a line or any shape by calling the Graphics member methods and by using the Pen instance created. Some of the methods of Graphics class are DrawEllipse, DrawImage, DrawLine, DrawPie, DrawPolygon, etc. Each of these members is overloaded with different methods through which the figure can be drawn.
Following are the steps to draw solid shape filled with color:

• Create a Graphics object by calling the System.Windows.Forms.Control.CreateGraphics method.

• Create a Brush object and specify the filling pattern and color (by choosing the required derived class of Brush class).

• Call the required Fill method of Brush class and then the Draw method.

Bitmap

A bitmap is an array of bits that specify the color of each pixel in a rectangular array of pixels. The number of bits devoted to an individual pixel determines the number of colors that can be assigned to that pixel. For example, if each pixel is represented by 4 bits, then a given pixel can be assigned one of 16 different colors (2^4 = 16).

Aspose.Drawing for .NET lets you create a bitmap from scratch or open from an existing file that can further be edited. The following code create an arc:




Chart

A chart can operate in bound or unbound mode. In unbound mode, you can manually create and position series points. In bound mode, a chart or an individual series visualizes data from its data source. An example is add series points at runtime.




## TA6.
### Explain in simple terms how to get device coordinates from world coordinates
World coordinates World coordinates are the coordinates used to model a particular graphic world and are the coordinates you pass to methods in the .NET Framework.
Device coordinates Device coordinates are the coordinates used by the physical device being drawn on, such as a screen or sheet of paper.

References:
[https://www.dotnet-guide.com/working-with-graphics-in-net.html](https://www.dotnet-guide.com/working-with-graphics-in-net.html)
[https://learn.microsoft.com/en-us/dotnet/desktop/winforms/advanced/types-of-coordinate-systems?view=netframeworkdesktop-4.8](https://learn.microsoft.com/en-us/dotnet/desktop/winforms/advanced/types-of-coordinate-systems?view=netframeworkdesktop-4.8)
