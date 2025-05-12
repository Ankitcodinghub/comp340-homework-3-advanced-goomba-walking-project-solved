# comp340-homework-3-advanced-goomba-walking-project-solved
**TO GET THIS SOLUTION VISIT:** [COMP340 Homework 3-Advanced Goomba Walking Project Solved](https://www.ankitcodinghub.com/product/comp340-homework-3-advanced-goomba-walking-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91127&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP340 Homework 3-Advanced Goomba Walking Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column">
&nbsp;

Project Description

In this project, you will implement an advanced Goomba walking project. This project will give an animation result where Goomba’s feet are raised while walking. Several frames of the animation are given below.

You will add work on Goomba project that we have done so far during the class. This document assumes that you work on the regular Goomba project, but it is also OK to work on the Paragoomba project.

Project Guideline

Follow the below guideline to write an advanced Goomba project.

Part 0. Setup Programming Environment

<ol>
<li>Download the required file (GoombaAdv.cs) from Blackboard and save it under a folder where you have a Goomba project.</li>
<li>In Visual Studio Code, when you open the folder where you save the GoombaAdv.cs, you should see a group of classes like the below. (If you work based on the Paragoomba project, you will also have ParaGoomba.cs in the group.)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 3

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Open GoombaAdv.cs. You will see that there is a basic structure of GoombaAdv class and GoombaAdv class extends Goomba class. You will complete GoombaAdv.cs by following the below guideline to have the advanced Goomba animation.

Part 1. SetSprite() of GoombaAdv class

<ol>
<li>Inside SetSprite() of GoombaAdv, you will write a code that stores Goomba images to goombaSpriteLeftFoot and goombaSpriteRightFoot.</li>
<li>You can use Goomba images stored in GoombaSprites.txt on Blackboard.</li>
<li>There are two Goomba images in GoombaSprites.txt. Goomba image that raises left foot will be stored to goombaSpriteLeftFoot, and Goomba image that raises right foot will be
stored to goombaSpriteRightFoot.
</li>
<li>Remember how we stored star image to starSprite in Star class and goomba image to
goombaSprite in Goomba class.
</li>
</ol>
Part 2. DrawSprite() overriding

<ol>
<li>Because Goomba’s DrawSprite() displays a single goomba image on a console window, you will override the DrawSprite() in a way that it displays two goomba images one by one (ex. left foot→right foot→left foot→…).</li>
<li>Open Goomba.cs. Add virtual keyword to DrawSprite() (i.e. public virtual void DrawSprite()…).</li>
<li>In GoombaAdv.cs, add override keyword to DrawSprite() (i.e. public override void DrawSprite()…).</li>
<li>In Goomba.cs, change private int posX to protected int posX so that GoombaAdv can use posX freely. (You may need posX in GoombaAdv’s DrawSprite().)</li>
<li>Complete GoombaAdv’s DrawSprite(). In DrawSprite(), you need to write a code that displays two different Goomba images (left-foot image &amp; right-foot image) in order whenever DrawSprite() is called in an animation.

(Don’t forget that your Goomba also should move to right then to left.)</li>
<li>Feel free to add variables and methods in GoombaAdv class. However, you CANNOT add variables and methods in other classes.

*Hint: You may add a variable in GoombaAdv that increases the number whenever DrawSprite()is called (ex. 1→2→3→4 …). Then, when the variable has an odd number and even number, you may display goombaSpriteLeftFoot and goombaSpriteRightFoot, respectively.</li>
</ol>
Part 3. Advanced Goomba animation

<ol>
<li>Open Program.cs. Create an object of GoombAdv class (you can set up the speed value as you want).</li>
<li>Put the GoombaAdv object into gWalk.StartAnimation().</li>
<li>Remember how we put Goomba object (or ParaGoomba object) into
gWalk.StartAnimation().
</li>
<li>Run the advanced Goomba project using dotnet run and enjoy the advanced Goomba
animation!
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
