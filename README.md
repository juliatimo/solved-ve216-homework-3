Download Link: https://assignmentchef.com/product/solved-ve216-homework-3
<br>
<strong>Problems:</strong>

<ol>

 <li>[5]A set of signals {<em>ϕ<sub>k</sub></em>(<em>t</em>)} is called <strong>orthogonal </strong>over the interval (a,b) iff the <strong>inner product </strong>of each pair of distinct signals in the set is zero:</li>

</ol>

where <em>ϕ</em><sup>∗</sup><em><sub>k </sub></em>is the complex conjugate of <em>ϕ<sub>k </sub></em>and <em>α </em>= 0̸ . Show that the set of complex exponentials {<em>e<sup>jω</sup></em><sup>0<em>kt </em></sup>: <em>k </em>= 0<em>,</em>±1<em>,</em>±2<em>,…</em>} is orthogonal on any interval over a period <em>T</em><sub>0</sub>, where.

<ol start="2">

 <li>[5] We know that for a CT period signal <em>x</em>(<em>t</em>) with, and its Fourier series can be represented as,</li>

</ol>

Show that it can also be expressed in real form as,

Where,

<ol start="3">

 <li>[5]Find the Fourier series coefficients <em>a</em><sup>′</sup><em><sub>k</sub>s </em>of <em>x</em>(<em>t</em>) = sin(3<em>πt</em>) + cos(4<em>πt</em>)</li>

 <li>[6]Find the Fourier series representations of the following signals. Express your answer in a real form.</li>

</ol>

(c) The signal illustrated below,

<em>x</em>(<em>t</em>)

−1         0          1          2          3          4                       <em>t</em>

Figure 1: HW3-4(c) 5. [6] Let <em>x</em>(<em>t</em>) be a period signal whose Fourier series coefficient are

Use Fourier series properties to answer the following questions:

<ul>

 <li>Is <em>x</em>(<em>t</em>) real?</li>

 <li>Is <em>x</em>(<em>t</em>) even?</li>

 <li>Is <em>dx</em>(<em>t</em>)<em>/dt </em>even?</li>

</ul>

<ol start="6">

 <li>[10]Based on the results obtained in question 4(a)(b)(c), use MATLAB to plot the Fourier series representations. For the summation in the FS, since we can not go infinite, just choose a <em>k </em>that is large enough.</li>

 <li>[4] A continuous-time signal <em>x</em>(<em>t</em>) with period <em>T </em>is said to be odd harmonic if in its Fourier series representation</li>

</ol>

<em>a<sub>k </sub></em>= 0 for every even integer k.

<ul>

 <li>Show that if <em>x</em>(<em>t</em>) is odd harmonic, then</li>

 <li>Show that if <em>x</em>(<em>t</em>) satisfies the relation in (a), then it s odd harmonic.</li>

</ul>

<ol start="8">

 <li>[4] In Problem 4(c), we see that the Fourier Series expansion of the ”periodical exponential” signal is given by <em>S<sub>N</sub></em>(<em>t</em>), where <em>x</em>(<em>t</em>) = <em>S<sub>N</sub></em>(<em>t</em>) when <em>N </em>→ ∞.

  <ul>

   <li>Now, instead of plotting <em>x</em>(<em>t</em>) using a <em>N </em>”large enough”, we would like to plot the ”intermediate steps”. Specifically, please use Matlab to plot <em>S<sub>N</sub></em>(<em>t</em>) with <em>N </em>= 5<em>,</em>10<em>,</em>15<em>,</em>19 for <em>t </em>∈ [0<em>.</em>5<em>,</em>4<em>.</em>5]. Interpret what you see from the graphs.</li>

   <li>We notice that the <em>x</em>(<em>t</em>) = <em>S<sub>N</sub></em>(<em>t</em>) above is not ”strict” in the sense that <em>x</em>(<em>t</em>) has some discontinuities where its value is undefined, while <em>S<sub>N</sub></em>(<em>t</em>) is always continuous even when <em>N </em>→ ∞. Use Matlab to calculate <em>S<sub>N</sub></em>(0) and <em>S<sub>N</sub></em>(1) for the <em>N </em>values in (a). Then make an educated guess for the values of <em>S<sub>N</sub></em>(0) and <em>S<sub>N</sub></em>(1) when <em>N </em>→ ∞.</li>

  </ul></li>

 <li>(a) [2] The signal <em>x</em>(<em>t</em>) is illustrated below, using the differentiation property to calculate Fourier series. Be cautious about the DC component of <em>x</em>(<em>t</em>) when you differentiate it.

  <ul>

   <li>[2] Using Fourier series properties, find the Fourier coefficients</li>

  </ul></li>

</ol>

Also calculate the values for <em>d</em><sub>2 </sub>and <em>d</em>−3. (<em>x</em>(<em>t</em>) is the same as (a))

<ul>

 <li>[2] Using Fourier series properties, find the Fourier series expansion of <em>y</em>(<em>t</em>) = 4<em>x</em>(<em>t/</em>3 − 2) + 5.</li>

</ul>

<ol start="10">

 <li>[18] Consider a casual LTI system realized by the RLC circuit shown below. <em>x</em>(<em>t</em>) is the voltage input (V) and y(t) is the voltage (V) across the capacitor.</li>

</ol>

Figure 3: HW3-10

<ul>

 <li>Find the differential equation relating <em>x</em>(<em>t</em>) and <em>y</em>(<em>t</em>).</li>

 <li>Find the system’s response to <em>x</em>(<em>t</em>) = <em>e<sup>jωt</sup></em>, where <em>ω </em>is arbitrary.</li>

 <li>Write out the system’s transfer function <em>H</em>(<em>s</em>).</li>

 <li>Calculate the magnitude of the system’s frequency response |H(<em>jω</em>)| and plot it as a function of <em>ω</em>.</li>

 <li>Use Matlab freqs to generate the exact same plot as part (d). Note that you want to plot the output argument of freqs because directly calling freqs with no output arguments will 1. give two figures; 2. plot both the magnitude and phase response in its default log scale. Besides, be sure to specify an appropriate range for the third input argument of freqs using linspace.</li>

 <li>Find the Fourier series expansion (in complex exponential form) for <em>x</em>(<em>t</em>) = 1 + sin(<em>t</em>) + sin(4<em>t</em>) and plot its power density spectrum (by using stem).</li>

 <li>Use <em>x</em>(<em>t</em>) as an example to verify Parseval’s relation. You may want to use Matlab/Mathematica to calculate (integrate) the power of <em>x</em>(<em>t</em>).</li>

 <li>Find the systems output <em>y</em>(<em>t</em>) due to <em>x</em>(<em>t</em>). Plot the power density spectrum of <em>y</em>(<em>t</em>).</li>

 <li>Compare <em>x</em>(<em>t</em>) and <em>y</em>(<em>t</em>) and their PDS’s. What frequency component of the <em>x</em>(<em>t</em>) is attenuated? Is this RLC circuit a lowpass/highpass/bandpass/bandstop filter?</li>

</ul>

<ol start="11">

 <li>[5] Consider a continues-time ideal lowpass filter <em>S </em>whose frequency response is</li>

</ol>

When the input to this filter is a signal <em>x</em>(<em>t</em>) with fundamental period <em>T </em>= <em>π/</em>6 and Fourier series coefficients <em>a<sub>k</sub></em>, it is found that

<em>x</em>(<em>t</em>) −→ <em>y</em>(<em>t</em>) = <em>x</em>(<em>t</em>)

For what value of <em>k </em>it is guaranteed that <em>a<sub>k </sub></em>must be zero?

<ol start="12">

 <li>[6] The Bessel lowpass filter is a widely-used analog linear filter.

  <ul>

   <li>Make a specific Bessel filter by using Matlab command [num, den] = besself(5,1e4), where the two vectors num and den are the filter’s transfer function’s coefficients on the numerator and denominator, respectively. Plot the filter’s magnitude response from 0 to 20000 rad/s using freqs.</li>

   <li>Use Matlab gensig to generate a square wave with period 0.002 seconds, duration 1 second, and sampling every 10<sup>−4 </sup> Plot an appropriate portion of the generated signal with axis command.</li>

   <li>Use Matlab tf and lsim to simulate the response (output) of the filter to the square wave. Plot your output signal with the same axis range as (b). Compare your input and output. As you can see, the ”corners” of the square wave are all ”filtered”, implying that these corners actually correspond to the high-frequency components of the signal. This also makes sense intuitively as the corners are where the signal change ”abruptly”.</li>

  </ul></li>

 <li>[5] Assume <em>x</em>(<em>t</em>) is a periodic CT signal with period <em>T</em>. Its Fourier series coefficients <em>a<sub>k </sub></em>also have a period <em>N</em>. Show that there exist a periodic sequence <em>g</em>[<em>n</em>], so that <em>x</em>(<em>t</em>) is represented by</li>

</ol>

<em>.</em>

This means any <em>x</em>(<em>t</em>) with such property actually looks more like a discrete-time signal. This problem shows that typical periodic CT signals will have non-periodic Fourier coefficients.

<ol start="14">

 <li>[5] A distortion present in all amplifiers is in some form of nonlinearity. Nonlinearities introduce additional frequency components, transferring some of the signal power from the fundamental frequency component to higher harmonics. This is called <strong>harmonic distortion</strong>. The quality of an amplifier is (in part) judged by how small its <strong>total harmonic distortion (THD) </strong>is, defined by:</li>

</ol>

THD =  · 100% = [1 − ] · 100%<em>. </em>power in DC &amp; harmonics power in fundamental total power        total power

Consider the following model for an amplifier:

<em>y</em>(<em>t</em>) = 7[<em>x</em>(<em>t</em>) + <em>bx</em><sup>5</sup>(<em>t</em>)]<em>,</em>

where <em>b </em>= 0<em>.</em>10. (This is not a great amplifier.) Find the THD for this amplifier, when the input signal is <em>x</em>(<em>t</em>) = sin(3<em>t</em>).

<ol start="15">

 <li>[6] Let</li>

</ol>

be a periodic signal with fundamental period <em>N </em>= 10 and Fourier series coefficients <em>a<sub>k</sub></em>. Also, let

<em>g</em>[<em>n</em>] = <em>x</em>[<em>n</em>] − <em>x</em>[<em>n </em>− 1]<em>.</em>

<ul>

 <li>Draw the graph of signal <em>g</em>[<em>n</em>], and determine the fundamental period of <em>g</em>[<em>n</em>].</li>

 <li>Determine the Fourier series coefficients of <em>g</em>[<em>n</em>].</li>

 <li>Using the Fourier series coefficients of <em>g</em>[<em>n</em>], determine <em>a<sub>k </sub></em>for <em>k </em>= 0.̸ 16. [4] Consider the following three continuous-time signals:</li>

</ul>

<em>x</em>(<em>t</em>) = cos(4<em>πt</em>) <em>y</em>(<em>t</em>) = sin(4<em>πt</em>) <em>z</em>(<em>t</em>) = <em>x</em>(<em>t</em>)<em>y</em>(<em>t</em>)

<ul>

 <li>Determine the Fourier series coefficients of <em>x</em>(<em>t</em>).</li>

 <li>Determine the Fourier series coefficients of <em>y</em>(<em>t</em>).</li>

 <li>Use the results of parts (a) and (b), along with the multiplication property of the continuous-time Fourier series, to determine the Fourier series coefficients of <em>z</em>(<em>t</em>) = <em>x</em>(<em>t</em>)<em>y</em>(<em>t</em>).</li>

 <li>Determine the Fourier series coefficients of <em>z</em>(<em>t</em>) through direct expansion of <em>z</em>(<em>t</em>) in trigonometric form, and compare your result with that of part(c).</li>

</ul>