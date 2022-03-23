<style>
/* ==============================================================================================
This copyright notice must be kept untouched in the stylesheet at all times.
The original version of this stylesheet and the associated (x)html
is available at http://www.script-tutorials.com/night-sky-with-twinkling-stars/
Copyright (c) Script Tutorials. All rights reserved.
This stylesheet and the associated (x)html may be modified in any way to fit your requirements.
================================================================================================= */
* {
    margin: 0;
    padding: 0;
}
header {
    background-color:rgba(33, 33, 33, 0.9);
    color:#ffffff;
    display:block;
    font: 14px/1.3 Arial,sans-serif;
    height:50px;
    position:relative;
    z-index:5;
}
h2{
    margin-top: 30px;
    text-align: center;
}
header h2{
    font-size: 22px;
    margin: 0 auto;
    padding: 10px 0;
    width: 80%;
    text-align: center;
}
header a, a:visited {
    text-decoration:none;
    color:#fcfcfc;
}

@keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}
@-webkit-keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}
@-moz-keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}
@-ms-keyframes move-twink-back {
    from {background-position:0 0;}
    to {background-position:-10000px 5000px;}
}

@keyframes move-clouds-back {
    from {background-position:0 0;}
    to {background-position:10000px 0;}
}
@-webkit-keyframes move-clouds-back {
    from {background-position:0 0;}
    to {background-position:10000px 0;}
}
@-moz-keyframes move-clouds-back {
    from {background-position:0 0;}
    to {background-position:10000px 0;}
}
@-ms-keyframes move-clouds-back {
    from {background-position: 0;}
    to {background-position:10000px 0;}
}

.stars, .twinkling {
  position:absolute;
  top:0;
  left:0;
  right:0;
  bottom:0;
  width:100%;
  height:300px;
  display:block;
  padding-bottom:300px;
}

.stars {
  background:#000 url(images/stars.png) repeat top center;
  z-index:0;
}

.twinkling{
  background:transparent url(images/twinkling.png) repeat top center;
  z-index:1;

  -moz-animation:move-twink-back 200s linear infinite;
  -ms-animation:move-twink-back 200s linear infinite;
  -o-animation:move-twink-back 200s linear infinite;
  -webkit-animation:move-twink-back 200s linear infinite;
  animation:move-twink-back 200s linear infinite;
}

.clouds{
    background:transparent url(images/clouds.png) repeat top center;
    z-index:3;

  -moz-animation:move-clouds-back 200s linear infinite;
  -ms-animation:move-clouds-back 200s linear infinite;
  -o-animation:move-clouds-back 200s linear infinite;
  -webkit-animation:move-clouds-back 200s linear infinite;
  animation:move-clouds-back 200s linear infinite;
}
</style>
<div class="stars"></div>
<div class="twinkling"></div>

# Black Holes

![Milky Way Panorama](https://upload.wikimedia.org/wikipedia/commons/9/9e/Milky_Way_Arch.jpg)

## 0. Prepare for the big moment

![Crab Nebula](https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/Crab_Nebula.jpg/375px-Crab_Nebula.jpg)

- 1054: SN 1054 - Crab Nebula
- 1676: First measure the speed of light
- 1783: definition of dark star - escape velocity > speed of light

## 1. Relativity

- Special Relativity (1905)
- General Relativity (1915)

### 1.1. Special Relativity Foundations

- Inertial frame of reference (with no acceleration)
- Speed of light is absolute/invariant

### 1.2. Special Relativity Consequences

- E=mc2
- Time dilation
- 2D quantified spacetime (double light cone)
- (it doesn't care about gravity)

![Light cone](https://upload.wikimedia.org/wikipedia/commons/1/16/World_line.svg)

### 1.3. General Relativity Foundations

- 3D quantified spacetime
- it really cares about gravity

### 1.4. General Relativity Consequences

- Equivalence Principle Experiments:
  - Philoponus (6th century): two balls with different weights fall the same speed
  - Newton (~1680): period of pendulum with different masses but identical length
  - David Scott (1971): drop feather and hammer on the Moon
- Gravitational Lensing
- Gravitational Waves
- BLACK HOLES (FINALLY...)

## 2. Paradox - The Fuel of Physics

- Newton's First Law: Uniform Motion
  - No Motion (No Force)
  - Constant Speed
- Paradox: jump off the roof
  - No Force (but I accelerate)
- Solution: warped spacetime (3D)
- Explain:
  - turn off gravity:
    - floating a straight line
  ![gravity-off](images/bh-1.png)
  - turn on gravity: gravity wraps spacetime
    - fall to the ground (as expected)
    - time ticks slower on the ground than on the roof
  ![gravity-on](images/bh-2.png)

## 3. Solution of the General Relativity (1916)

- Schwarzschild found his radius
- BLACK HOLES (FINALLY AGAIN...)

![Schwarzschild radius](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Black_hole_details.svg/220px-Black_hole_details.svg.png)

## 4. Bald Black Holes

- No-hair Theorem
- Three properties:
  - mass
  - electric charge
  - angular momentum
- Physics meme exists

![No-hair black hole](https://www.hollywoodreporter.com/wp-content/uploads/2011/10/doh_a.jpg?w=681&h=383&crop=1)

## 5. Observe Indirectly

- intense light coming from accretion disk
  - ISCO (Innermost Stable Circular Orbit)
    - ISCO > R: accretion disk spin the same direction as the black hole
    - ISCO = 3R: the black hole is not rotating
    - ISCO < 9R: accretion disk spin the inverse direction as the black hole
- SMBH affecting near stars
- Gravitational Lensing
- Gravitational Waves
  - LIGO
  - VIRGO
- Take a photo

## 6. Nobel Prize
- Penrose 1978?
- 2017 LIGO
- 2020

## 9999. References
