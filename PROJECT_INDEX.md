# VR Testing Project - Index

## Project Overview
Unity VR project for testing and development of VR interactions using XR Interaction Toolkit, XR Hands, and OpenXR.

**Unity Version:** 6000.3.2f1 (a9779f353c9b)

## Key Packages & Dependencies

### Core XR Packages
- **com.unity.xr.interaction.toolkit** (3.3.0) - Core VR interaction system
- **com.unity.xr.hands** (1.7.2) - Hand tracking support
- **com.unity.xr.openxr** (1.16.0) - OpenXR runtime support
- **com.unity.xr.androidxr-openxr** (1.1.0) - Android XR support
- **com.unity.xr.arfoundation** (6.3.1) - AR Foundation
- **com.unity.xr.core-utils** (2.5.3) - XR utility functions
- **com.unity.xr.management** (4.5.3) - XR management system

### Rendering & Graphics
- **com.unity.render-pipelines.universal** (17.3.0) - Universal Render Pipeline (URP)
- **com.unity.shadergraph** - Shader Graph support

### Input & UI
- **com.unity.inputsystem** (1.17.0) - New Input System
- **com.unity.ugui** - Unity UI system
- **TextMesh Pro** - Advanced text rendering

### Development Tools
- **com.unity.ide.rider** (3.0.38) - JetBrains Rider integration
- **com.unity.feature.development** (1.0.2) - Development features
- **com.unity.learn.iet-framework** (5.0.2) - Interactive tutorials
- **com.unity.testtools.codecoverage** - Code coverage tools

## Project Structure

```
VRTesting123/
├── Assets/
│   ├── MyProject/              # Custom project assets
│   │   ├── Prefabs/           # Custom prefabs
│   │   └── Scenes/            # Custom scenes
│   ├── Samples/               # Package samples
│   │   ├── XR Hands/          # Hand tracking samples
│   │   └── XR Interaction Toolkit/  # Interaction samples
│   ├── Scenes/                # Main scene files
│   ├── Settings/              # Project configuration
│   ├── VRTemplateAssets/      # VR template assets
│   ├── TextMesh Pro/          # TextMesh Pro resources
│   ├── XR/                    # XR configuration
│   └── XRI/                   # XR Interaction settings
├── ProjectSettings/            # Unity project settings
├── Packages/                  # Package manifests
└── Library/                   # Unity cache (generated)
```

## Scenes

### Main Scenes
- **Assets/Scenes/BasicScene.unity** - Basic VR scene with grid
- **Assets/Scenes/SampleScene.unity** - Sample scene with lighting
- **Assets/MyProject/Scenes/BasicScene 1.unity** - Custom basic scene
- **Assets/MyProject/Scenes/SampleScene 1.unity** - Custom sample scene

### Scene Templates
- **BasicScene.scenetemplate** - Template for basic scenes
- **SampleScene.scenetemplate** - Template for sample scenes

## Scripts Index

### VRTemplateAssets Scripts
Located in `Assets/VRTemplateAssets/Scripts/`

#### Interaction & UI
- **StepManager.cs** - Controls steps in coaching cards with step navigation
- **Callout.cs** - Displays world and controller tooltips with gaze interaction
- **CalloutGazeController.cs** - Controls callout gaze behavior
- **BooleanToggleVisualsController.cs** - Manages boolean toggle visual states

#### Interaction Components
- **XRKnob.cs** - Knob interaction component
- **XRPokeFollowAffordanceFill.cs** - Poke interaction affordance fill
- **RayAttachModifier.cs** - Modifies ray attach behavior
- **LaunchProjectile.cs** - Launches projectiles with forward force
- **Rotator.cs** - Rotation component

#### Hand Tracking
- **HandSubsystemManager.cs** - Manages hand tracking subsystem

#### Media & Effects
- **VideoPlayerRenderTexture.cs** - Video player with render texture
- **VideoTimeScrubControl.cs** - Video timeline scrubbing control

#### Utilities
- **BezierCurve.cs** - Bezier curve implementation
- **AnchorVisuals.cs** - Anchor visualization
- **DestroyObject.cs** - Object destruction utility

### XR Interaction Toolkit Samples
Located in `Assets/Samples/XR Interaction Toolkit/3.3.0/`

#### Starter Assets
- **DynamicMoveProvider.cs** - Dynamic movement provider for locomotion
- **ControllerInputActionManager.cs** - Manages controller input actions
- **ControllerAnimator.cs** - Controller animation system
- **GazeInputManager.cs** - Gaze-based input management
- **ClimbTeleportDestinationIndicator.cs** - Climbing teleport indicator
- **ObjectSpawner.cs** - Spawns objects in VR
- **MaterialPipelineHandler.cs** - Handles material pipeline
- **PermissionsManager.cs** - Manages VR permissions
- **PlatformUnderstanding.cs** - Platform understanding features
- **RotationAxisLockGrabTransformer.cs** - Axis-locked rotation transformer
- **TeleportVolumeAnchorAffordanceStateLink.cs** - Teleport volume affordance
- **ToggleColorToggler.cs** - Color toggle component
- **ToggleComponentZone.cs** - Component toggle zone
- **DestroySelf.cs** - Self-destruction utility

#### Hands Interaction Demo
- **HandsDemoSceneAssets/Scripts/**
  - **TransformSync.cs** - Synchronizes transforms
  - **ToggleGameObject.cs** - Toggles game objects
  - **PokeBlendShapeAnimator.cs** - Poke-based blend shape animation
- **Scripts/**
  - **Vector3ScaleAffordanceReceiver.cs** - Vector3 scale affordance
  - **ValueDerivedButtonReader.cs** - Value-derived button input
  - **ReleaseThresholdButtonReader.cs** - Release threshold button
  - **LocalPositionOffsetAffordanceReceiver.cs** - Position offset affordance
  - **PokeGestureDetector.cs** - Detects poke gestures
  - **HideObjectWhenInteractorBlocked.cs** - Hides objects when blocked
  - **PinchPointFollow.cs** - Pinch point following
  - **HandsOneEuroFilterPostProcessor.cs** - One-euro filter for hands
  - **OneEuroFilterVector3.cs** - Vector3 one-euro filter
  - **MetaSystemGestureDetector.cs** - Meta system gesture detection

#### Demo Scene Assets
- **MultiAnchorTeleportReticle.cs** - Multi-anchor teleport reticle
- **IncrementUIText.cs** - UI text increment utility

### XR Hands Samples
Located in `Assets/Samples/XR Hands/1.7.1/HandVisualizer/`

- **HandVisualizer.cs** - Visualizes hand tracking data
- **JointVisualizer.cs** - Visualizes hand joints
- **HandProcessor.cs** - Processes hand tracking data
- **MaterialPipelineHandler.cs** - Handles materials for hand visualization

## Prefabs

### Custom Prefabs
- **Assets/MyProject/Prefabs/XR Origin Hands (XR Rig).prefab** - XR rig with hand tracking

### VR Template Prefabs
Located in `Assets/VRTemplateAssets/Prefabs/` (30 prefabs)
- Various VR interaction prefabs
- UI components
- Interaction objects

## Assets Organization

### VRTemplateAssets
- **Audio/** - Button hover and click sounds
- **Fonts/Inter/** - Inter font family
- **Graphics/** - Graphics settings and lighting
- **Materials/** - 44 material files with textures
- **Models/** - 20 FBX models
- **Prefabs/** - 30 prefab files
- **Scripts/** - 15 C# scripts
- **Shaders/** - Custom shaders
- **Sprites/** - 29 sprite images
- **Themes/** - UI theme assets
- **Tutorial/** - Tutorial assets
- **Videos/** - Video assets

### Settings
- **Project Configuration/** - URP settings, quality presets, scene templates
- **XR Settings/** - XR configuration and loaders
- **XRI Settings/** - XR Interaction Toolkit settings

## Key Features

### VR Interaction
- Hand tracking support (XR Hands)
- Controller-based interactions
- Gaze-based interactions
- Poke interactions
- Grab and manipulation
- Teleportation system

### Rendering
- Universal Render Pipeline (URP)
- Custom shaders via Shader Graph
- TextMesh Pro for advanced text

### Input System
- New Input System integration
- Controller input management
- Gaze input support

### Development Tools
- Interactive tutorials framework
- Code coverage support
- Rider IDE integration

## Configuration Files

### Project Settings
- **ProjectVersion.txt** - Unity version (6000.3.2f1)
- **Packages/manifest.json** - Package dependencies
- **Packages/packages-lock.json** - Locked package versions

### XR Configuration
- **Assets/XR/XRGeneralSettingsPerBuildTarget.asset** - XR general settings
- **Assets/XR/Loaders/** - XR loader configurations
- **Assets/XR/Settings/** - XR-specific settings
- **Assets/XRI/Settings/** - XR Interaction Toolkit settings

## Build Targets

### Supported Platforms
- Android (AndroidXR)
- Standalone (Windows/Mac/Linux)
- OpenXR compatible devices

### Quality Presets
- Performance URP Config
- Quality URP Config
- Platform-specific presets (Android, Standalone)

## Notes

- This project uses Unity 6000.3.2f1 (Unity 6)
- Primary VR runtime: OpenXR
- Render pipeline: Universal Render Pipeline (URP)
- Input system: New Input System
- Hand tracking: XR Hands package
- Interaction framework: XR Interaction Toolkit 3.3.0

---

*Last indexed: Generated automatically*
*Project path: C:\Users\qavi9\VRTesting123*

