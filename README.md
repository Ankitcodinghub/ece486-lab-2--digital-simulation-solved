# ece486-lab-2--digital-simulation-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/ece486-lab-2-digital-simulation-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131403&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE486 Lab 2- Digital Simulation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
Scope and Objective

1. Study the dynamic response of 2nd order systems through digital simulation ◼ Implement a transfer function with an all-integer block diagram in Simulink.

◼ Implement a transfer function with State-Space function block in Simulink

2. Gaining insight to control system design through the characteristic responses of the systems

◼ Investigate the effect of an extra zero

◼ Investigate the effect of an extra pole

Introduction

Digital simulation packages are an essential part of control system design. Such packages are used routinely in control system analysis and design. This lab introduces Simulink, the digital simulation package sold with Matlab. Simulink will be used to study the dynamic response of a second order system,

𝐹(𝑠)= 𝑈 𝑌((𝑠𝑠)) = 𝑠2𝑏+1𝑎𝑠1+𝑠𝑏+𝑜𝑎𝑜 (1)

in both block-diagram:

Figure 1: Block Diagram Representation of System with Transfer Function F(s) and state-space forms:

(𝑥𝑥̇̇1)=(−0𝑎 −1𝑎 )(𝑥𝑥12)+(01)𝑢 (2); 𝑦=(𝑏0 𝑏1)(𝑥𝑥12) (3)

2 0 1

together with the effects of an additional pole and an additional zero. The characteristic responses of these systems provide important insights into control system design.

Reading

➢ G. F. Franklin, et al., Feedback Control of Dynamic Systems, 4th, 5th, 6th, 7th or 8th Ed., Sec. 3.5.

Modified from ECE486 Control Systems Lab Manual,

Prelab Exercise

𝑌(𝑠) 25

𝐻(𝑠)=𝑈 (𝑠)=𝑠2 +6𝑠+25

1. Develop an all-integrator block diagram for the transfer function H1(s). What are the damping ratio and natural frequency? What the poles of the system?

2. Simulate the all integrator block diagram using SIMULINK

a) Type simulink in MATLAB command line or click on the Simulink icon as shown

b) Click Blank Model. At the blank SIMULINK library file

c) Double click on the Model Window to open a field and type “integrator” as shown in (I) to select and place the Integrator block. Alternatively, click “Library Bowser”. Search “continuous” to find the Integrator block and drag it to the model browser as illustrated by (II-IV).

d) Repeat the same for other block elements including Gain and Sum (from “Math Operation”).

e) Place a Step block from Source library and To Workspace block from Sink library

Scope block approach as you have learned in Lab 01 to log the data to the workspace too)

g) Label the output of the first integrator y_dot by double-clicking on the line representing the output

h) Double click on the Gain block and set the appropriate values

i) Double click on the Step clock to set the following parameters.

⚫ Step time: 0;

⚫ Initial Value: 0;

⚫ Final Value: 1; ⚫ Sample Time: 0

j) Double click on To Workspace block connect to the output and set the following parameters:

⚫ Variable name: y ⚫ Save format: Array

k) Double click To Workspace block connected to y_dot and set the following parameters:

⚫ Variable name: y_dot;

⚫ Save format: Array

l) Set the simulation parameters by clicking on the Simulation menu and choosing Configuration Parameters, to:

⚫ Stop Time: 3 (chosen to capture the main response)

⚫ Type: Variable-step

⚫ Solver: ode45

⚫ Max Step Size: 0.001(Smaller max step sizes give smoother responses, but take longer to compute)

⚫ Click on Data Import/Export and uncheck the Limit data points to last box.

m) Run the simulation by clicking on the Simulation menu

3) In the MATLAB workspace, you will find three variables: tout, y and y_dot. SIMULINK always saves the time vector as tout. Plot the variable y and y_dot using tout as the time axis.

2 Digital Simulation

j Laboratory Exercise j

Part I: State Space Model of H1(s)

1. Open a new Simulink model.

2. Drag in a State-Space block from the Continuous library.

3. In the Matlab workspace window, set the following variables:

A

4. Double-click on the State-Space block, and set the A, B, C, D parameters to “A”, “B”, “C”, “D” respectively (without the quotes). This causes Simulink to look up the values in the Matlab workspace when the model is run.

5. Open the Sources library and drag a Step block into the model window. Connect the Step block to the input of the State-Space block, and change the parameters to those used in the prelab.

6. Open the Signals Routing library and drag a Demux block into the model window. Connect the State-Space output to the Demux input.

7. Open the Sinks library to find the To Workspace block. Connect each output of the Demux to a separate To Workspace block. Set the variable name of the top To Workspace block to y dot, and the bottom one to y. Make sure both To Workspace blocks are set to an Array type save format (as in the prelab).

8. Set the Simulation Parameters as in the prelab, and run the simulation.

9. Make a plot containing subplots of both y and y dot. Label and print this for your report. Set y1=y, y dot1=y dot, and tout1=tout to save these responses for later.

Part II: Effects of an extra Zero

We will now use the information from Appendix A section IV-c to introduce a zero into the all-integrator block diagram from the prelab. Sketch the block diagram by hand before implementing it in Simulink. This diagram will be similar to Figure 1.

1. Modify your all-integrator block diagram so that the zero in H2(s) is added. Remove the y dot “To Workspace” block. In the block diagram, use variables like “a” or “zeta” for α and ζ; this way you can easily set their values in the Matlab workspace.

2. Notice that the zero is added at s = −αζ, with ζ as found in the prelab. With this ζ, simulate the system with the real part of the zero in various regions. We will rename the variables after each simulation so they are not overwritten.

. ten times further left than the poles (save as y2a and tout2a)

. on the real axis directly between the poles (save as y2b and tout2b)

. halfway between the poles and the origin (save as y2c and tout2c)

. in the right-half plane, with α = −3 (save as y2d and tout2d)

. to see the trend, also try α = −30 (save as y2e and tout2e)

Signal zero location α

y2a

y2b

y2c

y2d

y2e

3. Overlay all these responses along with y1 on a single graph and label appropriately. Print a copy for the report. Note that in general tout2a 6= tout2c; since we are using variable-step integration, Matlab is free to choose which times it evaluates. Remember this; a common mistake is to use the wrong time data when plotting. √

2 Digital Simulation

Part III: Effects of an extra Pole

1. Remove the zero from the model in Part II and add an extra pole instead, as inH3(s). Sketch the block diagram by hand before implementing it in Simulink.

2. The extra pole is added at s = −αζ, with ζ as found in the prelab. With this ζ, simulate the system with the real part of the added pole:

. ten times further left than the poles (save as y3a and tout3a)

. on the real axis directly between the poles (save as y3b and tout3b)

. halfway between the poles and the origin (save as y3c and tout3c)

. We do not want a pole in the right half plane because that is unstable. Try it and see what happens.

Signal pole location α

y3a

y3b

y3c

y3d

3. Overlay all the stable extra pole responses on a single graph and label appropriately. Be sure to include the response y1 from the first portion of the lab.

Print.

] Report ]

I: State Space Model of H1(s)

1. Compare the plots of y dot and y as obtained in Part I of the lab to the plots made in the prelab. Do they appear to come from the same system? Attach the plots to your report, making sure they are clearly labeled.

II: Effects of an extra Zero

1. How are Mp, tr, and ts affected by the location of the zero? Answer this by measuring these values from the Part II plot and tabulating them. Include the values from Part I for comparison. Attach the plot to the end of your report.

2. A zero in the right half plane is called a non-minimum phase zero. What isinteresting about the plot for this case?

3. Take H2(s), set ζ to the value found in the prelab, and separate the numerator terms to make a sum of two fractions. What does each term represent? As α changes, which term dominates? Be sure to consider the limits as α approaches 0 or ∞. What happens when α is negative?

III: Effects of an extra Pole

1. How are Mp, tr, and ts affected by the location of the additional pole? Answer this by measuring these values from the Part III plot and tabulating them. Include the values from Part I for comparison. Attach the plot to the end of your report.

2. Take H3(s), set ζ to the value found in the prelab, do a partial fraction expansion to separate the extra pole from the original system, and then separate the numerator as before. The expansion should look something like:

Solve for k1, k2, and k3 in terms of α. What does each of these three terms represent? How do k1, k2, and k3 change as α changes? Be sure to consider the limits as α approaches 0 or ∞.
