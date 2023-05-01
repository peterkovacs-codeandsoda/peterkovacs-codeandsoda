<style>
  .page-header {
    background-image: none;
  }


  .comparison-widget {
    display: inline-block;
    max-width: 100%;
    max-height: 100%;
    position: relative;
    overflow: hidden;
    vertical-align: top;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
  }
  .comparison-widget * {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
  }
  .comparison-widget:hover .comparison-separator {
    opacity: 1;
  }
  .comparison-widget:hover .comparison-control {
    opacity: 1;
  }
  .comparison-widget:hover .comparison-control:before,
  .comparison-widget:hover .comparison-control:after {
    opacity: 1;
  }
  .comparison-widget--hidden {
    opacity: 0;
  }
  .comparison-item {
    height: 100%;
    width: 100%;
    background: #FFF;
  }
  .comparison-item--first {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 2;
  }
  .comparison-item__content {
    height: 100%;
    overflow: hidden;
    position: relative;
  }
  .comparison-item__content:hover .comparison-item__label {
    background: #FFF;
  }
  .comparison-item--first .comparison-image {
    width: auto;
    max-width: none;
    position: absolute;
    left: 0;
    top: 0;
  }
  .comparison-item__image {
    display: block;
    max-width: 100%;
    -webkit-user-drag: none;
  }
  .comparison-item--first .comparison-item__label {
    left: 0;
    right: inherit;
  }
  .comparison-item__label {
    padding: 7px 10px;
    position: absolute;
    top: 0;
    right: 0;
    text-transform: uppercase;
    font-family: Verdana, sans-serif;
    font-size: 11px;
    color: #222;
    background: rgba(255, 255, 255, 0.65);
    z-index: 1;
    -webkit-transition: background-color 300ms linear;
    -moz-transition: background-color 300ms linear;
    transition: background-color 300ms linear;
  }
  .comparison-separator {
    width: 2px;
    height: 100%;
    position: absolute;
    right: -1px;
    top: 0;
    z-index: 10;
    background: #FFF;
    cursor: pointer;
    opacity: 0.7;
  }
  .comparison-control {
    width: 12px;
    height: 12px;
    margin-top: -6px;
    margin-left: -6px;
    position: absolute;
    top: 50%;
    left: 50%;
    background: #FFF;
    border-radius: 100%;
    opacity: 0.7;
  }
  .comparison-control:before,
  .comparison-control:after {
    content: '';
    display: block;
    width: 12px;
    height: 20px;
    margin-top: -10px;
    position: absolute;
    top: 50%;
    background: url('arrow.png') 0 0 no-repeat;
  }
  .comparison-control:before {
    left: -15px;
  }
  .comparison-control:after {
    right: -15px;
    background-position: -12px 0px;
  }
  .comparison-control__mask {
    width: 50px;
    height: 40px;
    position: absolute;
    top: -15px;
    left: -18px;
    background: #FFF;
    opacity: 0;
  }


</style>

<script src="assets/vfx/ImageComparison.js"></script>

# Effects in Motion Pictures

## 1. AH (Abbrev Hell)
- CG: computer graphics
- CGI: computer generated imagery
- SFX: special effects
- VFX: visual effects

## 2. Film Production Phases
- Pre-production
- Production
- Post-production

### 2.1. Pre-Production
- concept art
- previs

### 2.2. Production
- analog/digital camera recording

### 2.3. Post-Production
- cut
- VFX

## 3. VFX Companies
- [Industrial Light & Magic](https://www.ilm.com/): *Star Wars: Episode IV - A New Hope*
- [Wētā FX](https://www.wetafx.co.nz/): *The Lord of the Rings: The Fellowship of the Ring*
- [Scanline VFX](https://www.scanlinevfx.com/reels/): *300*
- [Digital Domain](https://digitaldomain.com/): *Titanic*
- [DreamWorks Animation](https://pibfyc.dreamworks.com/?slug=videos&type=page&id=242): *Shrek*
- [Pixar Animation Studios](https://www.pixar.com/feature-films-launch): *Toy Story*
- [Walt Disney Animation Studios](https://disneyanimation.com/): *Mickey Mouse & Friends*

## 4. Who is Adam "MythBusters" Savage?
![Petranaki Arena - Geonosis](images/vfx/Geonosis_arena.jpg)

## 5. Visual Effects
- SFX: on set, physical based
- Motion capture: movement recording
- Matte painting: static landscape/environment
- Animation: digital movement creation
- 3D modeling: virtual actor, digital double
- Rigging: skeletal animation
- Rotoscoping: frame-by-frame cutout
- Chroma key: blue/green screen
- Match Moving: insertion of CG into live-action footage
- Compositing: combining multiple source of visual elements into single image
- Digital Effects: simulations - fire, smoke, water

## 6. Visualization - Pre-Production
- [The Third Floor](https://thethirdfloorinc.com/reels/#highlights)

## 7. Virtual Production
- GOT: [Game of Thrones Virtual Production with Unreal Engine](https://www.unrealengine.com/en-US/spotlights/virtual-production-on-the-battlegrounds-of-game-of-thrones)
- Unreal Engine Virtual Production Flow
![Unreal Engine Virtual Production Flow](images/vfx/ue_virtual_production_flow.jpg)
- ILM: [StageCraft](https://www.ilm.com/stagecraft/)
![StageCraft Mandalorian](https://www.ilm.com/wp-content/uploads/2021/03/StageCraftLED-Mandalorian2.jpg)

## 8. Film Stock
- [Kodak EKTACHROME 5294 - Euphoria S2](https://www.kodak.com/en/motion/blog-post/euphoria)

## 9. Misc Examples
![450k Q-tips as crowd in 'The Phantom Menace'](https://pbs.twimg.com/media/E3uHhYnX0AIgS0p.jpg)
[Blade Runner Opening Scene - Hades landscape](https://youtu.be/nFVcdKa0M9E)
![Blade Runner - Hades landscape 1](https://xos-prod-media.s3.amazonaws.com/media/collection/image/P180583_G294.jpg.1920x1920_q85.jpg?AWSAccessKeyId=AKIA5NFUCQMTFXEBPVO5&Signature=9DXP%2B7yXtECtJCVWzC5p5H8S0Ck%3D&Expires=1683032684)
![Blade Runner - Hades landscape 2](https://acmi-website-media-prod.s3.ap-southeast-2.amazonaws.com/media/original_images/P180575_G286.jpg.1200x1200_q85.jpg)
<div class="js-comparison-container">
  <img class="comparison-image" src="https://www.fxguide.com/wp-content/uploads/2016/05/CAPCW_TTF__TC0903_PLATE-830x437.jpg" alt="">
  <img class="comparison-image" src="https://www.fxguide.com/wp-content/uploads/2016/05/CAPCW_TTF_TC0903_POSTVIS-830x436.jpg" alt="">
</div>
<script>

    document.addEventListener('DOMContentLoaded', domReady);

    function domReady() {
      var imageComparisonCollection = document.querySelectorAll('.js-comparison-container');
      for (var i = 0; i < imageComparisonCollection.length; i++) {
        var imageWidget = imageComparisonCollection[i];
        var images = imageWidget.querySelectorAll('.comparison-image');
        new ImageComparison({
          container: imageWidget,
          startPosition: imageWidget.getAttribute('start-position'),
          data: [
            {
              image: images[0],
              label: 'before'
            },
            {
              image: images[1],
              label: 'after'
            }
          ],
        });
      }
    }
  </script>

## 10. VFX Tools
- Maya, Cinema4D, 3Ds Max, Blender
- ZBrush
- Substance Designer, Substance Painter
- Photoshop
- After Effects
- Houdini
- Nuke
- Unreal Engine, Unity

## 11. Low-Budget Approach - Blender Only
- Ian Hubert - Dynamo Dream Series {[1](https://youtu.be/LsGZ_2RuJ2A),[2](https://youtu.be/xlqhdaLhRVY),[3](https://youtu.be/JM_WPiT6NRQ)}
- [Dynamo Dream Teaser Breakdown](https://youtu.be/FFJ_THGj72U)
