<style>
  .page-header {
    background-image: none;
  }
</style>

# Unity - The Practical Way
## 1. How To Mobile - Application Side

### 1.1. Build Setup
- Build Target (Android, iOs)
- Texture Compression -> ASTC; See: [Supported texture compression formats, by platform](https://docs.unity3d.com/Manual/class-TextureImporterOverride.html#supported-formats)
- ETC2 fallback
- Export project -> import into Android Studio as Gradle project
- Build App Bundle -> [aab](https://developer.android.com/platform/technology/app-bundle/) instead of apk
- Run Device -> connected device for testing purposes
- Development Build -> debug symbols + enabled Profiler
- Autoconnect Profiler
- Script Debugging -> allow script debugger to attach remotely
- Scripts Only Build
- Compression Method -> Compress data at Build Time
  - Default - normal ZIP: fast compress, slower decompress
  - LZ4 - fast compress, better app load time; Development Build
  - LZ4HC - high compression, slower compress, even better app load time; Production Build

### 1.2. [Player Settings](https://docs.unity3d.com/Manual/class-PlayerSettingsAndroid.html#Other)
- Metadata (icon, splash, logo, background)
- Resolution & presentation
  - Scaling
  - Rotation
  - Orientation
- Render config
  - Color space
    - Gamma: better overall performance on Mobile
    - Linear: slower, but more natural and realistic visual fidelity
  - Graphics API
    - [Vulkan](https://www.vulkan.org/)
    - OpenGLES3
  - Color Gamut - device capabilities
  - Multithreaded Rendering
  - [Draw Call Batching](https://docs.unity3d.com/Manual/DrawCallBatching.html)
    - Static Batch
    - Dynamic Batch
  - Compute Skinning
  - Graphics Jobs - Vulkan Only
  - Normal Map Encoding
  - Lightmap Encoding
  - Lightmap Streaming
  - Frame Timing Stats
  - Virtual Texturing
  - Shader precision model
  - 360 Stereo Capture
- Vulkan Settings
- Identification
  - app, version, API dependency
- Configuration
  - Scripting Backend
- Publishing
  - Project Keystore
  - Project Key
  - Build
  - Minify
