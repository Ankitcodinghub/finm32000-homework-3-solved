# finm32000-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [FINM32000 Homework 3 Solved](https://www.ankitcodinghub.com/product/finm32000-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98417&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FINM32000 Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Assume that the short rate (the instantaneous spot rate of interest) follows the process drt = α(rt, t)dt + β(rt, t)dWt

where Wt is Brownian motion under risk-neutral probabilities. This framework includes models such as the Vasicek and CIR models, which correspond to particular choices of the functions (α, β), but for part (a), let’s leave the α and β as unspecified functions.

(a) Consider an interest rate derivative whose time-T payout has value given by some function F(rT),andwhosetime-tpriceCt satisfiesCt =C(rt,t)forsomepricingfunctionC.

Apply Ito’s rule to find the risk-neutral dynamics of C. Then set its drift equal to rC, to derive a PDE for C(r, t).

Now let’s take a specific choice for the functions α and β. Suppose that the risk-neutral dynamics of r are given by

drt = κ(θ − rt)dt + σdWt,

with parameters κ = 3, θ = 0.05, σ = 0.03. Consider a T = 5-year discount bond (a zero-coupon

bond which pays 1 at maturity T).

(b) Write code to find the time-0 price of bond by applying a standard central-difference explicit

finite difference scheme to the PDE in (a). (Therefore Cnj will be determined by Cj+1, Cj ,

and Cj−1.) n+1

∂r

the usual central difference. Specifically, for those rj such that κ(θ − rj ) 􏰈 0, approximate

</div>
</div>
<div class="layoutArea">
<div class="column">
Complete the code in the file hw3.ipynb.

(c) Also write code to price the bond using an explicit upwind approximation to ∂C instead of

</div>
</div>
<div class="layoutArea">
<div class="column">
∂C(rj,tn+1)usingthepointsCj+1 andCj . Forthoserj suchthatκ(θ−rj)&lt;0,approximate

</div>
</div>
<div class="layoutArea">
<div class="column">
∂r

∂C(r ,t

</div>
<div class="column">
n+1 n+1

) using the points Cj and Cj−1. (For ∂2C, use the usual approximation).

</div>
</div>
<div class="layoutArea">
<div class="column">
∂r j n+1

</div>
<div class="column">
n+1 n+1 ∂r2

</div>
</div>
<div class="layoutArea">
<div class="column">
In (b) and (c), to approximate the PDE’s rC term, use the values of r and C at node (n, j). (As we said in class, node (n + 1, j) would also be a natural choice, but let’s choose n instead of n + 1). At the grid’s upper and lower boundaries rmax and rmin, impose for all t &lt; T the “linearity” boundary conditions

C(rmax, t) = 2C(rmax − ∆r, t) − C(rmax − 2∆r, t) C(rmin, t) = 2C(rmin + ∆r, t) − C(rmin + 2∆r, t)

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
n+1 n+1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(This technique can help in some situations where it is not obvious what boundary conditions to use.) Thus, in each column of the grid, first solve for C in the interior nodes; then deal with the top and bottom nodes.

Now let us do some comparison of the central-difference and upwind schemes.

<ol start="4">
<li>(d) &nbsp;Suppose f : R → R is smooth in some open neighborhood of x. Show that as h → 0,
􏰉􏰉f(x+h)−f(x) ′ 􏰉􏰉 􏰉􏰉f(x+h)−f(x−h) ′ 􏰉􏰉 2

􏰉 h −f (x)􏰉=O(h) and 􏰉 2h −f (x)􏰉=O(h ).

􏰉􏰉􏰉􏰉

using Taylor’s theorem. The O(h) means “some function bounded by a constant times h, near h = 0.” Likewise, O(h2) means “some function bounded by a constant times h2, near h = 0.” Different instances of “O” may mean different functions. The “constants” may depend on x but not h.
</li>
<li>(e) &nbsp;For all part (e) calculations: Use the grid spacings ∆r = 0.01 and ∆t = 0.01. Use rmax = 0.35 and rmin = −0.25 for the upper and lower boundaries of the grid, respectively.
Run a central-difference calculation and an upwind calculation of the bond price for r0 = 0.10. Which is more accurate? The more accurate of the two solutions should agree, to three significant digits, with the true bond price in this model: 0.7661. The less accurate of the two solutions will be very inaccurate.
</li>
<li>(f) &nbsp;Based on your answers to (d) and (e), insert either “greater” or “less” in each blank space in the following rule-of-thumb. No explanation necessary.
Ignoring stability issues and considering only consistency (i.e. “truncation error,” also known as “local discretization error”), the upwind explicit scheme, which uses one-sided spatial differences, discretizes the PDE with accuracy than the standard explicit scheme, which uses central spatial differences.

However, to actually guarantee convergence, the grid spacing must satisfy certain stability constraints. In a PDE exhibiting strong drift, we have just seen that these constraints may allow the upwind scheme freedom in choosing grid spacing, compared to the standard scheme.
</li>
<li>(g) &nbsp;The continuously-compounded yield-to-maturity of a zero-coupon bond with time-t price Pt and nonrandom face value PT to be paid at maturity date T is defined to be
log(PT /Pt)

T−t wherelog,asalwaysforus,denotesnaturallog,andwherePT =1accordingtothisproblem’s assumptions. One way to think of the time-t yield to maturity T is as the time-t expectation

of the average of the instantaneous spot rates from time t to time T.

Find the yield-to-maturity of a 5-year discount bond, in the case that r0 = 0.12, and in the case that r0 = 0.02. (The “good” results from part (e) may be used here. The “bad” results should not be used, unless you want to fix them by modifying the grid spacings).

Why, intuitively, is the yield for r0 = 0.12 smaller than 0.12, whereas the yield for r0 = 0.02 is greater than 0.02?
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Comment: Under these short-rate dynamics, there exist analytic pricing formulas for bonds. So we do not need finite difference methods to value the simple payoff that we have here. But the finite difference scheme can be adjusted to handle contracts for which exact pricing formulas do not exist.

Problem 2

Suppose that a non-dividend-paying stock has dynamics

dSt = rStdt + σ(t)StdWt, (1)

where W is Brownian motion under risk-neutral probabilities, and where the time-dependent but non-random volatility function σ : [0,T] → R is piecewise continuous and sufficiently integrable. L2.13 relates this local volatility function σ to the Black-Scholes implied volatility σimp.

(a) Are the dynamics (1) capable of generating a non-constant (with respect to T ) term-structure of implied volatility? Are they capable of generating an implied volatility skew (non-constant with respect to K)? Explain briefly.

(b) Let S0 = 100 and r = 0.05. At time 0, you observe the prices of at-the-money (this means K = 100) European calls at 0.1-year, 0.2-year, and 0.5-year expiries to be 5.25, 7.25, and 9.5, respectively. First find the Black-Scholes implied volatilities of the three options. Then find (calibrate) a time-varying local volatility function σ : [0, 0.5] → R consistent with these option prices. A step function suffices (but other answers are also acceptable).

(c) Consistently with your local volatility function σ from part (d), find the time-0 price of an at-the-money European call with expiry 0.4. Do not use a tree or finite difference calculation.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
