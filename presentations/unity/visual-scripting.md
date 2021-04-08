<style>
  .page-header {
    background-image: none;
  }
</style>

# Unity - The Practical Way
## 1. Visual Scripting
How to do the "no code" way

### 1.1. Unity Engine
- Have a Scene (Running environment)
- Add GameObjects (Objects/Instances to do things)
- Put some Components on them (Functions/Behaviors)

### 1.2. Unity Engine Mechanism (UEM)
- FPS
- [Physics Engine](https://docs.unity3d.com/2021.1/Documentation/Manual/PhysicsSection.html)
- [Render Engine](https://docs.unity3d.com/2021.1/Documentation/Manual/Graphics.html)
- .NET runtime
- Custom code
- Everything is code

### 1.2.9999. [DOTS - Data Oriented Technology Stack](https://unity.com/dots)
- Core - ECS:
  - [Burst Compiler](https://docs.unity3d.com/2021.1/Documentation/Manual/com.unity.burst.html)
  - [Entities](https://docs.unity3d.com/Packages/com.unity.entities@0.17/manual/index.html)
  - [C# Job System](https://docs.unity3d.com/2021.1/Documentation/Manual/JobSystem.html?_ga=2.86431960.1990378347.1617922025-1026899014.1599206430)
- [Extensions](https://unity.com/dots/packages):
  - Unity Physics
  - Unity Mathematics
  - Havoc Physics
  - Unity NetCode
  - Unity Transport
  - Hybrid Renderer
  - DSPGraph
  - Unity Animation

### 1.3. [Bolt](https://docs.unity3d.com/Packages/com.unity.visualscripting@1.6/manual/index.html)
- Pick everyhing (still code)
- Generate bubbles for all the classes
- Connect visual scripts with UEM
- Sequential flow control
- Scoped variables
- Can construct
- Not able to define

### 2. Milestone 2
- Implement to decrease enemy's health
- Implement to gain gold after kill
- Implement UI updates

### 2.1. Demo
- Have fun
