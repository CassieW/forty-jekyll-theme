---
layout: page
title: Honeywell Experion® PKS - Experion Batch
description: Make Every Batch Golden
image: assets/images/orion.jpg
nav-menu: false
show_tile: false
---

<!-- main -->
<div id="main" class="alt">

<section id="banner" class="style2">
    <div class="inner">
        <span class="image">
            <img src="{{ site.baseurl }}/{{ page.image }}" alt="">
        </span>
        <header class="major">
            <h1>{{ page.title }}</h1>
        </header>
        <div class="content">
            {{ page.description }}
        </div>
    </div>
</section>

<div class="row" style="padding:5em 0em 5em 10em">
	<div class="4u 12u$(medium)" style="border-left:2px solid white">
		<h3>CLIENT</h3>
		<p>ExxonMobil, Boehringer Ingelheim, Chevron …</p>
	</div>
	<div class="4u 12u$(medium)" style="border-left:2px solid white">
		<h3>TYPE</h3>
		<p>Integrated platform and software applications</p>
	</div>
	<div class="4u$ 12u$(medium)" style="border-left:2px solid white">
		<h3>Role</h3>
		<p>Dev, Design support</p>
	</div>
</div>

<!-- one -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Long History, Fresh Start</h2>
		</header>
		<p>Since joining Honeywell at beginning of 2018 fresh out of college, I have been working with Experion Batch team as a software engineer. Working at a multinational conglomerate business, I was not too shocked to see developer comments from 90s’ here and there in our huge code base. In fact, our team still owns some products which are built upon legacy system dated back to 1980s’(learn more about product timeline of Experion PKS). While maintaining the infrastructure by adding modules and extensions may sound like a viable solution from technical perspective, User Experience, on the other hand, is compromised inevitably when it comes to the long drop-down list, rows and rows of window tabs, lack of guidance or feedback… the list goes on.  </p>
		<p>My concern since Day 1 was no news to the team, nor the management and leadership. Focusing on Velocity Product Development, Honeywell is launching a whole new process called Z21, which is going to reduce innovation cycle times in half. Batch team, as one of the pilot projects of Z21, has adopted Agile software development and moreover, modern technologies to build user-centered product. </p>
		<span class="image fit" style="text-align:center;">
		<img src="assets/images/history.svg" alt="Experioin Timeline" />
		<figcaption><i>History of Experion 1970 - present</i></figcaption>
		</span>
	</div>
</section>

<!-- two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Procedure Explorer</h2>
		</header>
		<p>
		Currently in Batch Operations, operators are often “flying blind” not knowing when critical steps are coming up. According to our customer research, throughput is sometimes compromised because operators do not have the time-based visualizations to prepare for upcoming tasks. Knowing what is coming next and when is key to keeping the plant running at maximum efficiency.
		</p>
		<p>
        While the majority of my work in this project is focusing on front-end development, I have certainly picked up a lot of useful design practices through the workshop as well as sync-up sessions with UX designer. At the same time, implementing features for a working product makes me dive deep into every design detail. As the development goes I was able to understand the patterns and principles better, and to come up with questions and feedback to support design.
        </p>
        <div class="row" style="padding:0em 7.5em">
            <div class="4u 12u$(medium)">
                <h3>User Personas</h3>
                <p>
                    <span class="image left"><img src="assets/images/oscar.png" alt="Oscar Operator in Control Room" /></span>
                    <code><b>Oscar Operator</b><br /></code>
                    <code><b>- Control Room Operator</b><br />Works in Control room. Very busy, noisy. Works 12 hour shifts – 4 days on, 5 off.</code>
                </p>
                <p>
                    <span class="image left"><img src="assets/images/samuel.png" alt="Samuel Smart working on Console Station" /></span>
                    <code><b>Samuel Smart</b><br /></code>
                    <code><b>- “Super” Console Operator</b><br />Works in the plant. Ascended to current position from maintenance role due to years of experience.</code>
                </p>
                <p>
                    <span class="image left"><img src="assets/images/stephen.png" alt="Stephen Super supervising an oil plant" /></span>
                    <code><b>Stephen Super</b><br /></code>
                    <code><b>- Shift Supervisor</b><br />Dedicated office, short walk to the control room. Spends a lot of time communicating between Console Operators and Plant Management.</code>
                </p>
            </div>
            <div class="4u 12u$(medium)" style="border-left:2px solid white; padding-bottom:8.3em; margin-bottom:3em">
                <h3>User Environments</h3>
                <p>
                <code><b>Control Room:</b> Multiscreen station equipped with mouse and keyboard input. Operator seated in chair monitoring all screens at same time.</code>
                <br /><br />
                </p>
                <p>
                <br />
                <code><b>In the Plant:</b> Single screen station, sometimes touchscreen. Operator standing near equipment during their shift.</code>
                <br /><br />
                </p>
                <p>
                <br /><br />
                <code><b>On the Go:</b> Mobile tablet in hard case, with touchscreen capability.</code>
                </p>
            </div>
            <div class="4u$ 12u$(medium)" style="border-left:2px solid white; padding-bottom: 26.5em;">
                <h3>Experions Outcomes</h3>
                <blockquote>
                <code><b>Understand the context of my active processes…</b> more easily and clearly.</code>
                </blockquote>
                <blockquote>
                <code><b>Troubleshoot batch process…</b> more efficiently and with less downtime.</code>
                </blockquote>
            </div>
        </div>
        <p>
        After going through iterations of User Needs Analysis, we landed on a lighter-weight web-based application as a reliable solution to help customer achieve their golden batch. Procedure Explorer is an intuitive recipe visualization interface that facilitates seamless workflow to operate and control of batch processes.
        </p>
        <h3>Adaptive Web Design</h3>
        <blockquote>
        "Adaptive design will (theoretically) ensure the best user experience according to whichever circumstances the user is in to interface. As the name suggests, the design adapts to the user’s situational needs and capabilities. As designers, we can show users that we’re in tune with their needs by giving them the right solution without asking for input.
        <br />
        A strength of adaptive design is that it feels more relevant to the modern user experience, whereas responsive design shows a more desktop-centric approach (with the demands of other devices taking a secondary, almost passive place). Let’s take a literal example; if you were driving through a long tunnel, wouldn’t you rather have a GPS screen that adapts to the environment and adjusts its brightness? That context-based performance and usability is reassuring, at the same time confirming that your smart device is smart enough to adapt and be extra useful.”
        </blockquote>
        <p>
        Our users work in complicated, stressful, distracting environments: an oil refinery plant in Texas producing over 5,000 tons of petrochemical products, or a pharmaceutical manufacturing plant in Germany running 2-million-dollar batches per day. Users could be sitting in the control room, multitasking on four separate displays while three different alarms going on in the background. They could be standing in the plant near a mixer equipment, working on a single-screen console station at the 5th hour of 12-hour night shift. They could be running back and forth between control room and the field, with a pen and a notebook in hand to write down parameters to be checked… With Procedure Explorer, our target is to resolve customers’ most concerned pain point – user experience.
        </p>
        <p>
        Once a batch finishes configuration and kicks off running, hundreds of configured parameters and run-time data is generated. To work this massive amount of information into an intuitive visualization without compromising the legibility, it requires us to design adaptively and inclusively on the details:
        </p>
        <div class="row 200%">
            <span class="image fit" style="text-align:center;">
                <img src="assets/images/FullScreenNPopUp.png" alt="Procedure Explorer runs full screen and pop-up" />
                <figcaption><i>Full Screen & Pop-up Window</i></figcaption>
            </span>
            <div class="6u 12u(medium)">
                <span class="image fit" style="text-align:center;">
                        <img src="assets/images/themes.gif" alt="Two color theme applies adaptively to different lighting conditions" />
                        <figcaption><i>Light theme & Dark Theme</i></figcaption>
                </span>
            </div>
            <div class="6u 12u$(medium)">
                <span class="image fit" style="text-align:center;">
                        <img src="assets/images/toggle.gif" alt="Toggle button to switch between description and expressions" />
                        <figcaption><i>Toggle Description & Expression</i></figcaption>
                </span>
            </div>
            <span class="image fit" style="text-align:center;">
                <img src="assets/images/StepNTransition.png" alt="Customized view for each block type" />
                <figcaption><i>Step Block & Transition Block</i></figcaption>
            </span>
        </div>
        <h3>Progressive Disclosure</h3>
        <blockquote>
        "Progressive disclosure defers advanced or rarely used features to a secondary screen, making applications easier to learn and less error-prone."
        </blockquote>
        <p>
        An inevitable dilemma for interaction design:
        </p>
        <ol>
            <li>
            Users want <b>power</b>, features, and enough options to handle all of their special needs. An operator would like to skip all the details and get straight to the error block, while an engineer needs some essential parameters to troubleshoot specific scenario.
            </li>
            <li>
            Users want <b>simplicity</b>; they don't have time to learn a profusion of features in enough depth to select the few that are optimal for their needs. For example, users struggle to find their target in a context menu when it lists more than 10 items, or expands more than two levels - it takes forever for one single action.
            </li>
        </ol>
        <p>
        <i>Progressive disclosure</i> is one of the best ways to satisfy both of these conflicting requirements. It's a simple, yet powerful idea:
        </p>
        <ul>
            <li>
            Initially, show users only a few of the most important options.
            </li>
            <li>
            Offer a larger set of specialized options upon request. Disclose these secondary features only if a user asks for them, meaning that most users can proceed with their tasks without worrying about this added complexity.
            </li>
        </ul>
        <p>As we introduce Procedure Explorer as a user-friendly replacement for functionalities in existing system, progressive disclosure makes the transition happens naturally: with one action users bring up a set of limited functions, they are designed intuitively leading to next level of information, while not overwhelm users with the options.
        </p>
        <div class="row">
            <div class="4u 12u$(medium)">
                <span class="image fit" style="text-align:center;">
                        <img src="assets/images/ProgresssiveDisclosure1.png" alt="Toggle button to switch between description and expressions" />
                        <figcaption><i>
                        Combining existing Chart View with Tree View, a hierarchy structure optimized for view in depth to quickly locate an element.
                        </i></figcaption>
                </span>
            </div>
            <div class="4u 12u$(medium)">
                <span class="image fit" style="text-align:center;">
                        <img src="assets/images/ProgressiveDisclosure2.gif" alt="Customized view for each block type" />
                        <figcaption><i>
                        Clicking on chart element brings up a table visualization with key parameters, which allows further interaction for in-place instruction, or accessing next level of parameters.
                        </i></figcaption>
                </span>
            </div>
            <div class="4u$ 12u$(medium)">
                <span class="image fit" style="text-align:center;">
                        <img src="assets/images/ProgressiveDisclosure3.png" alt="Toggle button to switch between description and expressions" />
                        <figcaption><i>
                        Call-out dialog gives more details on the chosen element, with access point to other views for more diagnosis information.
                        </i></figcaption>
                </span>
            </div>
        </div>
        <p>A closer look on the workflow running a batch with Procedure Explorer shows the complete three layers of progressive disclosure:</p>
        <span class="image fit" style="text-align:center;">
                <img src="assets/images/demo.gif" alt="Customized view for each block type" />
                <figcaption><i>Procedure Explorer Demo</i></figcaption>
        </span>
    </div>
</section>


</div>