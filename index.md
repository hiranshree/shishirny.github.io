---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

![Alt text](/images/profile.jpg){:style="float: right;margin-left: 0px;margin-top: -20px;"}

[CV](shishir_CV.pdf){:style="float: left;margin-left: 0px;margin-top: -30px;"} <br>
[Google scholar](https://scholar.google.com/citations?user=is0x16gAAAAJ&hl=en){:style="float: left;margin-left: 0px;margin-top: -30px;"} <br>
[AMBER Lab](http://www.bipedalrobotics.com){:style="float: left;margin-left: 0px;margin-top: -30px;"} <br>
<i style="font-size:14px" class="fa">&#xf0e0;</i> <a href="mailto:{{ site.email }}">{{ site.email }} </a> <br>
{% include icon-github.html username=site.github_username %} <br>
{% include icon-twitter.html username=site.twitter_username %}

For email: use letters in perentheses only


# About me

  I am a Postdoctoral scholar working for AMBER Lab in the California Insitute of Technology. I received my Ph.D. degree in Mechanical Engineering (2016) from the Georgia Institute of Technology, M.S. degree in Electrical Engineering (2012) from Texas A&M University. I received my B.Tech. degree in Electrical Engineering (2008) from the National Institute of Technology Karnataka, Surathkal, India. Prior to pursuing Master's degree, I worked as a board designer in Tejas Networks Ltd. Bangalore from 2008-2010. I am interested in nonlinear control, engineering mechanics, hybrid systems and robotics. I am currently working with Dr. Aaron Ames, and we make robots walk.


# My research

 I am currently working on using the Input to State Stability criterion to design robust Control Lyapunov Functions and Control Barrier Functions for hybrid systems (bipedal locomotion in particular). It can be split into three parts a) Reduce an uncertain system into an input/output system. What is considered a natural extension of viewing the functions of the uncertainty (modeling, model parameter, measurement) as inputs to a system, my work consists of reducing this form to ISS Lyapunov (barrier) functions and establishing the ultimate bounds on the outputs of the hybrid system, as functions of input uncertainty. b) Construct Control Lyapunov Functions (CLF) and Control Barrier Functions (CBF), that yield lower ultimate bounds and higher convergence rates to these bounds. c) Demonstrate these control functions by realizing sustainable walking and running experimentally.


