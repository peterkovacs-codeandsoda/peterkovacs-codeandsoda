<style>
  .page-header {
    background-image: none;
  }
</style>

# Procedural Generation

## 1. Programming Like God - Ingredients
- THE Creator
- a set of rules
- (run)Time to evolve

## 2. Procedural Content Generation
- runtime creation of data using an algorithm
- solve hardware limitations
- solve software limitations
- solve design limitations

## 3. Brief History of PCG
- 1952: Alan Turing love letter generator
- 1980: Akalabeth (generation with seed)
- 1980: Rouge (ancestor of rougelike genre)
![Rouge](https://upload.wikimedia.org/wikipedia/commons/0/0c/Rogue_Screenshot.png)

- 1985: The Sentinel (10k levels stored in 48KB)
- 1985: Elite
- 1995: Diablo (random dungeon layout, random item generation)
- 2002: PCG based asset generator - SpeedTree
- 2006: Dwarf's Fortress - The state-of-the art fantasy PCG based game (weather, biome, geological distribution of materials, plate tectonics, wind and water erosion; full history, world population, races, cities; poetry, monsters, animals, events, cities, etc.)
![Dwarf's Fortress](https://cdn.arstechnica.net/wp-content/uploads/2013/04/thatdude-df-aboveground-640x385.png)

- 2008: Spelunky
![Spelunky](https://cdn.akamai.steamstatic.com/steam/apps/239350/ss_1aa942dee4ecb1dee9ea01933b83bd9129c19e8f.1920x1080.jpg)

- 2009: Minecraft - 140M monthly players, $3 billion revenue (Dawn of the modern era of PCG)
![Minecraft](https://i.ytimg.com/vi/IAWVwpZQFMk/maxresdefault.jpg)

## 4. Modern PCG
- runtime random level generation (Minecraft, Spelunky, Diablo)
- design of level content (used in design phase, not visible in final products)
- instancing in-game entities (Left for Dead, Pjueh)
- user mediated content (X-COM, Spore)
- dynamic systems (S.T.A.L.K.E.R. - 1k non-scripted characters)
- procedural puzzles and plot generation (Apophenia, Mount and Blade)

## 5. Cutting-Edge PCG
- experience-driven: player experience as input
- search-based: evolutionary content
- procedurally artistic-content: visual art, music, poetry, architectures
- PG gameplay

## 6. PCG in Practice
- mazes
<br/>
![mazes](https://cdn1.epicgames.com/ue/product/Screenshot/Algorithms-1920x1080-e05da6c961f3c4c6f72a761cc965c09b.png)

- cellular automata
<br/>
![cellular automata](https://upload.wikimedia.org/wikipedia/commons/e/e2/One-d-cellular-automate-rule-30.gif)

- L-System
<br/>
![L-System](https://www.csh.rit.edu/~aidan/PortfolioAssets/Trees.png)

- diamond-square algorithm
<br/>
![diamond-square algorithm](https://upload.wikimedia.org/wikipedia/commons/f/f7/-PLASMA-ColorCycling.Gif)

- dungeons
  - Voronoi-Delaunay triangulation
  - rain-drop
- fire propagation
- artificial life
- fluid dynamics
- reaction-diffusion system
<br/>
![reaction-diffusion system](https://www.karlsims.com/rd-4examples.png)

- music (Hidden Markov Models)

## 7. Extreme PCG
- Elite Dangerous (400 billion [10<sup>9</sup>] star systems; without PCG: ~1KB/star system -> 400TB)
<br/>
![Elite Dangerous](https://i.ytimg.com/vi/Omzs4ui9RpI/maxresdefault.jpg)

- The Lord of the Rings: MASSIVE -> crowd and fight generation
<br/>
![The Lord of the Rings](https://i.stack.imgur.com/VQ8ge.jpg)

- No Man's Sky: 18 quintillion [10<sup>18</sup>] planets
<br/>
![No Man's Sky](https://staticg.sportskeeda.com/editor/2022/04/e48f2-16506657911274-1920.jpg)
