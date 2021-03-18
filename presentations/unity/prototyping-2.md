<style>
  .page-header {
    background-image: none;
  }
</style>

# Unity - The Practical Way
## 1. Prototyping | Part 2 (In Practice)

### 1.1. How to Start the Project
- Identify the time limit
- Identify the resource
- Identify the goals
- Identify the scope
- Identify the technology stack

### 1.2. Project Design Document
- Try to cover all identified items
- [See](https://github.com/peterkovacs-codeandsoda/project-andromeda/blob/main/Assets/Documents/Project%20Andromeda%20-%20Project%20Design%20Document.pdf)

## 2. Technical Perspective

### 2.1. Project First Steps
- Create project - *Project Andromeda*
- [Add version control](https://github.com/peterkovacs-codeandsoda/project-andromeda)
- Setup local
  - Select framework (Unity 2020.2)
  - Select archetype to fulfill most of the technical dependencies (Mobile 2D template)
  - Add extra dependencies now or later on
  - Setup build (local Android)
    - select JDK
    - select SDK & NDK
  - Add basic logical structure
    - Assets/Animations
    - Assets/Audio
    - Assets/Documents
    - Assets/Editor
    - Assets/Prefabs
    - Assets/Scenes
    - Assets/Scripts
    - Assets/Sprites
- Configure necessary settings. TODO
  - Peformance specific settings
  - Platform specific requirements like asset comperssion, etc.
- Build & Run

### 2.2. Introduce Primitives
- Follow the Design Document prioritized task list
- Create a skeleton/wireframe with most basic or null(stub) functionality
- Focus on minimal working feature
- Avoid any extra feature/util/something which is not covered by the task

### 2.3. Review Primitives
- Build & Run
- Review

### 2.4. Refine Primitives
- Fine tune only the current feature

### 2.5. GOTO: 2.2
- Pick the next feature and follow [Section 2.2](#22-introduce-primitives)

### 2.6. Feature Complete?
- In the meantime compare the current functionality with the Design Document, and create the "Features" Document
- Review it frequently and check if the initial goals
  - Achieved
  - Can be achieved
  - Need to change
