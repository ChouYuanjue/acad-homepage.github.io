---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am studying for a master's degree in mathematics at Mellon College of Science, Carnegie Mellon University at present.

My research interests include algebraic geometry, category theory and some basic mathematical branches. I am committed to providing a friendly introduction to higher mathematics to non-majors. I have published several papers (informally) <a href='https://scholar.google.com/citations?user=EfVwYVwAAAAJ'><img src="https://img.shields.io/badge/citations-33-blue"></a>).

# 📜 Notes

<style type="text/css">
h4.course {
    font-weight: normal;
    margin-top: 0.3em;
    margin-bottom: 0em;
}

.note-additional {
    color: #444;
}

.extras {
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

.unavailable, .extras a {
    display: inline-block;

    padding: 0.1em;
    margin-top: 0.2em;
    margin-bottom: 0.2em;

    text-align: center;

    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    flex-basis: 20%;
    flex-grow: 0;
}
.unavailable {
    color: #888;
}

@media only screen and (max-width: 600px) and (min-width: 400px) {
    .unavailable, .extras a {
        flex-basis: 20%;
    }
    .extras a.long {
        flex-basis: 40%;
    }
    .extras {
        flex-wrap: wrap;
    }
}
@media only screen and (max-width: 400px) {
    .unavailable, .extras a {
        flex-basis: 33%;
    }
    .extras {
        flex-wrap: wrap;
    }
</style>

Below are the notes I took during my spare time. None of this is formal or official. Note that the notes are not reliable indicators for what was lectured in my year.It can even be said that they have nothing to do with each other. Some mistakes will be unavoidable.

<div class='extras'>
<a href='/note/N-20210204.pdf'>N-20210204</a><a href='/note/N-20210206.pdf'>N-20210206</a><a href='/note/N-20210207.pdf'>N-20210207</a><a href='/note/N-20210804.pdf'>N-20210804</a><a href='/note/N-20210806.pdf'>N-20210806</a>
<a href='/note/N-20220131.pdf'>N-20220131</a><a href='/note/N-20220315.pdf'>N-20220315</a><a href='/note/N-20220319.pdf'>N-20220319</a><a href='/note/N-20220320.pdf'>N-20220320</a>
<a href='/note/N-20220321.pdf'>N-20220321</a><a href='/note/N-20220323.pdf'>N-20220323</a><a href='/note/N-20220405.pdf'>N-20220405</a>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div class="badge">YH-DIE</div><img src='images/IMG_20220406_124238.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[The Mappping of the Main Functions and Different Variations of YH-DIE](/yhdie-oup.pdf)
- YH-DIE must have continuity . Given the basic algebraic clusters of homogeneous configurations,we can get the basic three equations:
![](http://i.upmath.me/svg/%5Cbegin%7Barray%7D%7Bl%7D%0A%09%09%7B%5Cmathop%7B%5Cint%7D%5Cnolimits_%7B0%7D%5Cnolimits%5E%7B%7Bx%7D_%7Bi%7D%7D%7B%5Cfrac%7B%7BG%7D%5Cleft(%7B%7Bx%7D_%7Bi%7D%5Cmathrm%7B%2C%7Ds%7D%5Cright)%7D%7B%7B%5Cleft(%7B%7Bx%7D_%7Bi%7D%5Cmathrm%7B%7B-%7D%7D%7Bs%7D%7D%5Cright)%7D%5E%7B%5Cmathit%7B%5Calpha%7D%7D%7D%5Cmathrm%7B%5Cvarphi%7D%5Cleft(%7Bs%7D%5Cright)%7Bds%7D%7D%5Cmathrm%7B%7B%3D%7D%7D%7Bf%7D%5Cleft(%7B%7Bx%7D_%7Bi%7D%7D%5Cright)%7D%5C%20%3B%5C%0A%09%09%7B%5Cfrac%7B%5Cmathrm%7B%5Cpartial%7D%7D%7B%5Cmathrm%7B%5Cpartial%7D%7Bx%7D_%7Bi%7D%7D%5Cleft(%7B%5Cfrac%7B%7B%5Cmathrm%7B%5Cpartial%7D%7D_%7B%7Bx%7D_%7Bi%7D%7DG%7D%7B%5Csqrt%7B%7B1%7D%5Cmathrm%7B%7B%2B%7D%7D%7B%5Cleft%7C%7B%5Cmathrm%7B%5Cnabla%7D%7BG%7D%7D%5Cright%7C%7D%5E%7B2%7D%7D%7D%7D%5Cright)%5Cmathrm%7B%7B%3D%7D%7D%7B0%7D%7D%5C%20%3B%20%5C%0A%09%09%7B%7Bi%7D%5Cmathrm%7B%7B%3D%7D%7D%5Cmathop%7B%5Csum%7D%5Climits_%7B%7Bx%7D_%7Bi%7D%5Cmathrm%7B%7B%3D%7D%7D%7B1%7D%7D%5Climits%5E%7B%5Cmathrm%7B%5Cinfty%7D%7D%7B%5Carccos%5Chspace%7B0.33em%7D%5Cmathrm%7B%5Cvarphi%7D%5Cleft(%7B%7Bx%7D_%7Bi%7D%7D%5Cright)%7D%5Cmathrm%7B%7B%3D%7D%7D%7Bf%7D%5Cleft(%7B%5Cfbox%7B%24%7BYuh%7D%24%7D%7D%5Cright)%7D%0A%09%09%5Cend%7Barray%7D)
YH-DIE has become a fusion point and access point in the fields of algebraic geometry and partial differential equations, and its mapping on multidimensional algebraic clusters or manifolds is very special. The minimal surface equation is a special case.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">MPGG</div><img src='images/IMG_20220406_124425.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[MODELS OF PEN-PL GAUSSIAN GAMES IN NON-COOPERATIVECOMMUNICATION](/MPGG-first_draft.pdf)
- Consider non-cooperative pen games where bothplayers act strategically and heavily influence eachother. In spam and malware detection, players exploit randomization to obfuscate malicious data and increase their chances of evading detection at test time. The result shows Pen-PL Games have a probability distribution that approximates a Gaussian distribution according to some probability distribution defined over the respective strategy set. With quadratic cost functions and multivariate Gaussian processes, evolving according to first order autoregressive models, we show that Pen-PL "smooth" curve signaling rules are optimal. Finally, we showthat computing a socially optimal Pen-PL networkplacement is NP-hard and that this result holds forall P-PL-G distributions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">AGT</div><img src='images/pt2022_04_08_12_58_30.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Introduction to Arithmetic Graph Theory](/agt-intro.pdf)
- An introduction to arithmetic graph theory.
ISBN 978-1-6780-9204-7
</div>
</div>

# 📖 Educations
- *2020 - present*, MSc in Mathematical Science, Mellon College of Science at CMU
- *2016 - 2020*, BSc in Mathematics, Nanjing University of Aeronautics and Astronautics

# 📈 Skills
- **Matlab & Mathematica**

I can skillfully solve problems and sort out data through Matlab and MMA,especially Matlab.

- **Python & Lua**

I *used to* be an amateur Python programmer and use it to write basic scripts. I also wrote a Qbot by Lua through [mirai](https://github.com/mamoe/mirai).

- **Russian**

I can speak (подделка) Russian. Социализм с чжунготэсэ хао ва!

# 💬 Invited Talks
- *2022.01*, How we consider a "new" set theory –An introduction to ETCS -*MCS Math*
- *2021.07*, A friendly introduction to Boolean algebra -*Geek College* [\[video\]](https://b23.tv/thMyvm9)
