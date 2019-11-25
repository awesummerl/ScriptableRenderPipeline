## NOTE: We have migrated reported issues to FogBugz. You can only log further issues via the Unity bug tracker. To see how, read [this](https://unity3d.com/unity/qa/bug-reporting).

# Unity Scriptable Render Pipeline
The Scriptable Render Pipeline (SRP) is a new Unity feature in active development. SRP has been designed to give artists and developers the tools they need to create modern, high-fidelity graphics in Unity. Including a built-in Lightweight Render Pipeline for use on all platforms, and a High Definition Render Pipeline (HDRP) for use on compute shader compatible platforms. These features are available in Unity 2018.1+.

We are committed to an open and transparent development process, and as such you are welcome to take a look around if you are really curious.

Detailed documentation is being added here: [Wiki](https://github.com/Unity-Technologies/ScriptableRenderPipeline/wiki)

This feature is currently in preview. Some features may change or be removed before we move to a full release.  

[Lightweight Pipeline Blogpost](https://blogs.unity3d.com/2018/02/21/the-lightweight-render-pipeline-optimizing-real-time-performance/)

[High Definition Pipeline Blogpost](https://blogs.unity3d.com/2018/03/16/the-high-definition-render-pipeline-focused-on-visual-quality/)

[The High Definition Render Pipeline: Getting Started Guide for Artists](https://blogs.unity3d.com/2018/09/24/the-high-definition-render-pipeline-getting-started-guide-for-artists/)

### Package CI Summary

Package Name | Latest CI Status
------------ | ---------
com.unity.render-pipelines.core | [![](https://badge-proxy.cds.internal.unity3d.com/95fc0a37-8067-48e3-ad10-abca1ce43dc5)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.core/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/fc79e112-aa09-4c50-a324-efbb9bf9865a)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.core/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/74b65e22-f1c3-4b3a-a6e9-6c1528314bc4)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.core/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/2a7cb55e-1260-4b0c-87b8-99a90b13f68d)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.core/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/90be70c3-cd3c-4275-940c-8ca0262fb711) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/73c999ed-fd64-4df1-a6b8-77df8cbfe50f)
com.unity.render-pipelines.universal | [![](https://badge-proxy.cds.internal.unity3d.com/3fa6c209-3f11-43cf-a2de-1e930d91ea9e)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.universal/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/a597f590-141e-4c31-a85a-ded682388833)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.universal/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/2eaeea22-a937-4476-ac4b-6071378be1ba)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.universal/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/09f1ad19-33fe-4ce8-9b42-b186b4b3cc82)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.universal/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/5a632a87-cc88-4414-be12-394dfeb934df) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/28dfd57b-54d1-45ca-80d3-94d96dbbcfd0)
com.unity.render-pipelines.high-definition | [![](https://badge-proxy.cds.internal.unity3d.com/8917cf06-a703-4484-ba2c-5660a8622fd1)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/6dba0915-7a8e-4427-90ba-0caadc947530)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/d3ed9e4b-d9c4-4401-b952-ed5808aafe44)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/ba16f6d2-169b-4968-b9df-3e03abd9ae57)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/b7d3bcae-9ad8-4375-a683-1b907828137f) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/1ef3d7d0-cea1-4955-9276-e34c0952afbb)
com.unity.render-pipelines.high-definition-config | [![](https://badge-proxy.cds.internal.unity3d.com/f2a846ff-fd47-44aa-bdb5-3f3ca2aad416)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition-config/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/fd2c38b4-303f-4a41-a096-affba6812d3e)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition-config/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/ab12a6a1-17e5-478f-9916-7cfe77f2dbbb)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition-config/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/05e87aea-8e47-44f6-ac20-3764cb9bf8a0)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.high-definition-config/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/59fd14b1-3fc2-49e4-bf24-950f1482323f) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/d0fb96fc-6ff8-45a8-a317-ec19f30894cc)
com.unity.shadergraph | [![](https://badge-proxy.cds.internal.unity3d.com/8edb24f0-154e-41d5-b358-b3f4a612dba9)](https://badges.cds.internal.unity3d.com/packages/com.unity.shadergraph/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/2fb4f72b-fca1-4d95-8c3d-2e165ab7b1ed)](https://badges.cds.internal.unity3d.com/packages/com.unity.shadergraph/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/7e1ee3c6-0477-4076-a2af-3376ead10421)](https://badges.cds.internal.unity3d.com/packages/com.unity.shadergraph/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/4037069a-b945-4364-b398-b351d31637a9)](https://badges.cds.internal.unity3d.com/packages/com.unity.shadergraph/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/e2171d56-50c8-4803-964c-a63dcc728355) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/30fe71f1-5838-4bf9-84eb-26a42320e4a2)
com.unity.visualeffectgraph | [![](https://badge-proxy.cds.internal.unity3d.com/f56c4415-9b08-4a46-aeba-21c628f53f99)](https://badges.cds.internal.unity3d.com/packages/com.unity.visualeffectgraph/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/62ba81b5-1353-4662-a766-fc047853ab8c)](https://badges.cds.internal.unity3d.com/packages/com.unity.visualeffectgraph/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/c10f50c2-2a79-4d0a-a763-54dcb40d027f)](https://badges.cds.internal.unity3d.com/packages/com.unity.visualeffectgraph/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/3038865c-1465-4949-8cd3-d8c0b90b6106)](https://badges.cds.internal.unity3d.com/packages/com.unity.visualeffectgraph/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/59b6ec9b-c477-4767-82ba-d2390e70cede) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/ae2fb4f5-43dc-4ad2-8c94-7190dbcdc132)
com.unity.render-pipelines.lightweight | [![](https://badge-proxy.cds.internal.unity3d.com/2c5734ae-2f1e-4a09-bbad-66cd22934a0c)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.lightweight/build-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/d9b60fcb-2884-4753-acbe-8e613b85b0cf)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.lightweight/dependencies-info?branch=automation%2Fpackage-badges) [![](https://badge-proxy.cds.internal.unity3d.com/7e4aae95-2a9a-471c-a5f8-e8faf3675454)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.lightweight/dependants-info) [![](https://badge-proxy.cds.internal.unity3d.com/89a2cb3a-b36d-4d74-b7fe-c8584264cafb)](https://badges.cds.internal.unity3d.com/packages/com.unity.render-pipelines.lightweight/warnings-info?branch=automation%2Fpackage-badges) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/679931b4-d19f-4788-90af-be45f40f3a11) ![ReleaseBadge](https://badge-proxy.cds.internal.unity3d.com/a11f872a-60e4-4a16-a3f7-4ac888bcd879)

## How to use the latest version
__Note: The Master branch is our current development branch and may not work on the latest publicly available version of Unity. To determine which version of SRP you should use with your version of Unity, go to Package Manager (Window > Package Manager > Show Preview Packages) to see what versions of SRP are available for your version of Unity Editor. Then you can search the Tags tab of the Branch dropdown in the SRP GitHub for that tag number.__

__Regarding package number, we have adopted those numbers
Unity binaries 2019.1 is compatible with 5.x version
Unity binaries 2019.2 is compatible with 6.x version
Unity binaries 2019.3 is compatible with 7.x version
Unity binaries 2020.1 is compatible with 8.x version__

To use the latest version of the SRP, follow the instructions below:

This repository consists of a folder that should be cloned outside the Assets\ folder of your Unity project. We recommend creating a new project to test SRP. Do not clone this repo into an existing project unless you want to break it, or unless you are updating to a newer version of the SRP repo.

After cloning you will need to edit your project's `packages.json` file (in either `UnityPackageManager/` or `Packages/`) to point to the SRP submodules you wish to use. See: https://github.com/Unity-Technologies/ScriptableRenderPipeline/blob/master/TestProjects/HDRP_Tests/Packages/manifest.json

This will link your project to the specific version of SRP you have cloned.

You can use the GitHub desktop app to clone the latest version of the SRP repo or you can use GitHub console commands.

### To clone the repo using the GitHub Desktop App:
1. Open the GitHub Desktop App and click __Clone a Repository__.
2. Click the __URL__ tab in the __Clone a Repository__ window
3. Enter the following URL: https://github.com/Unity-Technologies/ScriptableRenderPipeline
4. Click the __Choose…__ button to navigate to your project’s base folder.
5. Click the __Clone__ button.

After the repo has been cloned you will need to run the following console commands from the ScriptableRenderPipeline folder:

```
> git checkout Unity-2018.1.0b2 (or the latest tag)

```
### To download the repo using console commands:
Enter the following commands in your console application of choice:  

```
> cd <Path to your Unity project>
> git clone https://github.com/Unity-Technologies/ScriptableRenderPipeline
> cd ScriptableRenderPipeline
> git checkout Unity-2018.1.0b2 (or the latest tag)

```
## Scriptable Render Pipeline Assets
The Scriptable Render Pipeline Asset controls the global rendering quality settings of your project and creates the rendering pipeline instance. The rendering pipeline instance contains intermediate resources and the render loop implementation.

You can create multiple Pipeline Assets to store settings for different built platforms or for different testing environments. 

To create a Render Pipeline Asset: 

1. In the Project window, navigate to a directory outside of the Scriptable Render Pipeline Folder, then right click in the Project window and select ___Create > Render Pipeline >  High Definition or Lightweight > Render Pipeline/Pipeline Asset.___
2. Navigate to ___Edit > Project Settings > Graphics___ and add the Render Pipeline Asset you created to the __Render Pipeline Settings__ field to use it in your project. 

Note: Always store your new Render Pipeline Asset outside of the Scriptable Render Pipeline folder. This ensures that your settings are not lost when merging new changes from the SRP repo.


## Using the High Definition Render Pipeline (HDRP) or the Lightweight Pipeline

### Using HDRP

To use HDRP you must edit your project’s __Player__ and __Graphics__ settings as follows:

1. Navigate to ___Edit > Project Settings > Player___ and set the color space of your project to Linear by selecting __Linear__ from the __Color Space__ dropdown. HDRP does not support Gamma lighting.
2. In the Project window, navigate to a directory outside of the Scriptable Render Pipeline Folder, then right in click the Project window and select ___Create > Render Pipeline >  High Definition > Render Pipeline.___
3. Navigate to ___Edit > Project Settings > Graphics___ and add the High Definition Render Pipeline Asset you created to the __Render Pipeline Settings__ field.

Note: Always store your High Definition Render Pipeline Asset outside of the Scriptable Render Pipeline folder. This ensures that your HDRP settings are not lost when merging new changes from the SRP repo.

### Using Lightweight Pipeline
To use the Lightweight Pipeline you must edit your project’s __Graphics__ settings as follows:

1. In the Project window, navigate to a directory outside of the Scriptable Render Pipeline Folder, then right click in the Project window and select ___Create > Render Pipeline >  Lightweight > Pipeline Asset.___
2. Navigate to ___Edit > Project Settings > Graphics___ and add the Lightweight Render Pipeline Asset you created to the __Render Pipeline Settings__ field.

Note: Always store your new Render Pipeline Asset outside of the Scriptable Render Pipeline folder. This ensures that your Lightweight settings are not lost when merging new changes from the SRP repo.

## Sample Scenes in ScriptableRenderPipelineData

If you want some sample scenes to use with SRP, you can find them at the [ScriptableRenderPipelineData GitHub repository](https://github.com/Unity-Technologies/ScriptableRenderPipelineData).

Clone the repo into your project's Assets\ folder.

Previous iterations of the ScriptableRenderPipeline repo owned this sample scene data, in case you noticed it before, and wondered where it went.
