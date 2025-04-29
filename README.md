# cmpsci403-hw08-discrete-impact-based-contact-simulation-solved
**TO GET THIS SOLUTION VISIT:** [CMPSCI403 HW08-Discrete Impact Based Contact Simulation Solved](https://www.ankitcodinghub.com/product/cmpsci-403-introduction-to-robotics-perception-mechanics-dynamics-and-control-solved-8/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109721&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPSCI403 HW08-Discrete Impact Based Contact Simulation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Figure 1: Double pendulum model.

In this problem, you will extend your previous simulation to include constraints. In this homework, we will add the slippery surface, which makes a friction force depending on the friction coefficient and the normal force. Please include your simulate_pend_HW8.m code in your submission.

1. Given a ground height yc = −1.1 m, complete skeleton the code for the function discrete_impact_contact in simulate_pend_HW8.m. This function should:

• Compute the height of the foot relative to the ground Cy = y − yc.

• Compute the C˙y = y˙.

• If the constraints are not violated (i.e. Cy &gt; 0 or C˙y &gt; 0), then your function should not update q˙.

• If the constraints are violated (i.e. Cy &lt; 0 and C˙y &lt; 0), compute the vertical impulse force,

Fˆc,y = Λc,y(−γC˙y − Jc,yq˙), where Λc,y is the vertical directional operational space mass, γ is the coefficient of restitution, and Jc,y is the vertical directional Jacobian at the contact point.

• Update q˙ using the equation, .

• Using the same procedure, update q˙ by applying tragential impulse force to satisfy a friction cone constraint. Compute the tangential impulse force, Fˆc,x = Λc,x(0 − Jc,xq˙).

• Truncate Fˆc,x if it is outside of friction cone, &gt; µFˆc,y.

• Update q˙ using the equation, q˙ = q˙ + M−1Jc,x&gt; Fˆc,x.

2. Find a proper place to put the update function in the simulation. Does it need to be in dynamics function? Or in the middle of numeric integration?

3. Use the coefficient of resitution γ = 0 and a friction coefficient µ = 0.3 to simulate trajectory tracking for the circle task with ω = 3 rad/s. Provide position and velocity plots of x and y over the interval t = [0s, 10s].

4. Increase µ to 3 and perform another simulation. Describe what changes in this simulation.

1

5. (Optional) Note that this method for enforcing constraints is general to cases beyond contact with the ground. For instance, in reality, this mechanism has a kinematic joint limit that constrains q1. In your code, implement a joint limit constraint to enforce q1 &gt; −0.1 rad.

2
