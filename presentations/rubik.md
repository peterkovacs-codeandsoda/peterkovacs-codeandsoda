<style>
.page-header {
  display: none;
}

// THIS IS FOR EVERY ELEMENT
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

// BASIC HTML AND BODY STYLES
html, bodry {
  height: 100%;
  position: relative;
  background-color: #111;
  font-size: 100px;
}

bodry {
  display: flex;
  align-items: center;
  justify-content: center;
  perspective: 4000px;
  perspective-origin: right -150%;
}

// HERE THE FUN BEGINS
.scene {
  position: relative;
  transform-style: preserve-3d;

  .cube {
    position: absolute;
    width: 2em;
    height: 2em;
    transform: translate(-50%, -50%);
    transform-style: preserve-3d;
    animation: rotatete 4s;

    .face {
      position: absolute;
      width: 100%;
      height: 100%;
      background-color: #000;
      border-radius: 4px;
      display: flex;
      flex-wrap: wrap;
      gap: 0.02em;

      * {
        width: 0.65em;
        height: 0.65em;
        border-radius: 4px;
      }

      &.front {
        transform: translateZ(1em);

        * {
          background-color: #009b48;
        }
      }

       &.back {
        transform: translateZ(-1em);

         * {
          background-color: #0046ad;
        }
      }

      &.left {
        transform: rotateY(90deg) translateZ(-1em);

        * {
          background-color: #ff5800;
        }
      }

      &.right {
        transform: rotateY(90deg) translateZ(1em);

        * {
          background-color: #b71234;
        }
      }

      &.top {
        transform: rotateX(90deg) translateZ(1em);

        * {
          background-color: #ffffff;
        }
      }

      &.bottom {
        transform: rotateX(90deg) translateZ(-1em);

        * {
          background-color: #ffd500;
        }
      }
    }
  }
}

@keyframes rotatete {
  100% {
    transform: translate(-50%, -50%) rotateY(360deg)
  }
}
</style>
<div class="bodry">
<div class="scene">
  <div class="cube">
    <div class="face front">
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
    </div>
    <div class="face back">
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
    </div>
    <div class="face left">
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
    </div>
    <div class="face right">
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
    </div>
    <div class="face top">
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
    </div>
    <div class="face bottom">
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
      <div class="cell"></div>
    </div>
  </div>
</div>
</div>



# Rubik's Cube

## 1. History
- Inventor: Ernő Rubik (scrulptor, *real* architect)
- Invented: 1974
- Original name: Magic Cube
- Original colors: white, blue, red, orange, green, yellow


## 2. Pop Culture Icon
- 1980: International debut as Rubik's Cube
- 1980: Toy of the Year - Best Puzzle [Germany, UK, France, US]
- 1981: Game of the Year - Best Puzzle [Finland, Sweden, US]
- 1981: Patrick Bossert - You Can Do the Cube [13 years old wrote an offical solution guide]
- 1982: MOMA NY selected Rubik's Cube into permanent collection

## 3. Some Statistics
- 1980-1983: 200 million cubes sold
- 2021: 450 million cubes sold
- best selling puzzle worldwide
- best selling toy worldwide

## 4. First Rubik's Cube World Championship
- 1982 - Budapest
- 19 countries
- the first official speedcubing championship
- 1st place: Minh Thai [US] - 22.95
- 3rd place: Zoltán Lábas [HU] - 24.49
- 17th place: Piotr Serbenski [PL] - 37.50
- 18th place: Svilen Tenev [BG] - 47.29
- 19th place: Josef Trajber [AT] - 50.16


## 5. Cube Math
-

## 6. Revolution of Speedcubing
- 1997: Jessica Fridrich invented CFOP
- C: Cross
- F: F2L (First 2 layers)
- O: OLL (Orient last layer)
- P: PLL (Permutate last layer)


![CFOP method](https://pbs.twimg.com/media/E6zVXUoVoAMHlSY.jpg)
