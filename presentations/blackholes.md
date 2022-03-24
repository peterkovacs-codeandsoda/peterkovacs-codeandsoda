<style>
.page-header {
  display: none;
}
/* ==============================================================================================
This copyright notice must be kept untouched in the stylesheet at all times.
The original version of this stylesheet and the associated (x)html
is available at http://www.script-tutorials.com/night-sky-with-twinkling-stars/
Copyright (c) Script Tutorials. All rights reserved.
This stylesheet and the associated (x)html may be modified in any way to fit your requirements.
================================================================================================= */

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
}

.stars {
  background:#000 url(images/stars.png) repeat top center;
  background-attachment: fixed;
  z-index:0;
}

.twinkling{
  background:transparent url(images/twinkling.png) repeat top center;
  background-attachment: fixed;
  z-index:1;

  -moz-animation:move-twink-back 200s linear infinite;
  -ms-animation:move-twink-back 200s linear infinite;
  -o-animation:move-twink-back 200s linear infinite;
  -webkit-animation:move-twink-back 200s linear infinite;
  animation:move-twink-back 200s linear infinite;
}

.main-content {
  margin-top: 300px;
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

## 5. Black Hole Behaviour

![Black Hole](https://cdn.mos.cms.futurecdn.net/56HmHbttAgfKELwqmqLRLc-1024-80.jpg.webp)

- Physical property
  - Micro: mass of the Moon with ~0.1mm radius
  - Stellar: 10 x mass of the Sun with 30km radius
  - Intermediate-mass: 1000 x  mass of the Sun with 1000 km radius (Earth radius: 6378km)
  - Supermassive: 100000 to 10 billion x  mass of the Sun with 0.001-400 AU (Astronomical unit: Sun Earth distance: 150 million km)
- Singularity
  - Spaghettification

![Spaghettification](https://upload.wikimedia.org/wikipedia/commons/f/ff/Spaghettification_%28from_NASA%27s_Imagine_the_Universe%21%29.png)

- ISCO
- Photonsphere
- Ergosphere
- Event Horizon

![Ergosphere](https://deepstash.com/_next/image?url=https%3A%2F%2Fd1dfxfqogsjixt.cloudfront.net%2F92268-1620913049.png&w=1920&q=75)

## 6. Observe Indirectly

- intense light coming from accretion disk
  - ISCO (Innermost Stable Circular Orbit)
    - ISCO > R: accretion disk spin the same direction as the black hole
    - ISCO = 3R: the black hole is not rotating
    - ISCO < 9R: accretion disk spin the inverse direction as the black hole

![Intense accretion disk](https://www.nasa.gov/sites/default/files/cygx1_ill.jpg)
![Milky way's SMBH jet](https://www.nasa.gov/sites/default/files/thumbnails/image/hubble_mwayjet_diagram.jpg)
- SMBH affecting near stars

[Stars orbiting around supermassive black hole at the center of the Milky Way](https://upload.wikimedia.org/wikipedia/commons/7/71/Simulation_of_the_orbits_of_stars_around_the_black_hole_at_the_centre_of_the_Milky_Way.webm)
- Gravitational Lensing

![Gravitational Lensing](https://upload.wikimedia.org/wikipedia/commons/0/03/Black_hole_lensing_web.gif)
![Artistic Gravitational Lensing](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/20190410l.tif/lossy-page1-1200px-20190410l.tif.jpg)
- Gravitational Waves
  - LIGO

  ![LIGO](https://www.ligo.caltech.edu/system/media_files/binaries/271/original/Dual_detectors_with_arrow_and_stns_labeled.jpg?1453424757)
  - VIRGO

  ![VIRGO](https://upload.wikimedia.org/wikipedia/commons/5/55/Virgo_aerial_view_01.jpg)
- Take a photo

![First black hole photo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Black_hole_-_Messier_87_crop_max_res.jpg/360px-Black_hole_-_Messier_87_crop_max_res.jpg)
- Hawking radiation

## 7. Nobel Prize
- 2017: LIGO
- 2020: Penrose, Ghez, Genzel

## 8. Paradox Again
- general relativity and quantum mechanics fight against each other
- quantum mechanics doesn't allow information loss in the system, so what happens in the black hole?

## 9. References
- [Simple example about the general relativity](https://vis.sciencemag.org/generalrelativity/)
- [AtomCsill presentation about the black holes](https://youtu.be/rToQgaiMy4M)
- [Nobel Prize 2017](https://www.nobelprize.org/prizes/physics/2017/summary/)
- [Nobel Prize 2020](https://www.nobelprize.org/prizes/physics/2020/summary/)
- [LIGO](https://www.ligo.caltech.edu/)
- [VIRGO](https://www.virgo-gw.eu/)
- [Cygnus X-1](https://en.wikipedia.org/wiki/Cygnus_X-1)
- [03.2022. - Black Holes may have quantum hair?](https://www.livescience.com/black-hole-quantum-hair)
- [Black Holes - Wikipedia](https://en.wikipedia.org/wiki/Black_hole)
- [Spaghettification - Wikipedia](https://en.wikipedia.org/wiki/Spaghettification)
