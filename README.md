# NormCoreXR
An Oculus Quest multiplayer Unity 2019.3 URP template which uses Unity XR and NormCore packagaes

## Description
---

This is a template project which comes integrated with Unity XR and NormCore for quickly deploying multiplayer prototypes for VR devices. 

Using XR makes it possible to deploy across the different VR platforms.

[XR](https://docs.unity3d.com/Manual/XR.html)

NormCore makes it super easy and quick to setup multiplayer experiences. 

[Getting started](https://normcore.io/documentation)

## Instructions
---

This project contains a `MainPrefab` which contains the NormCore `Realtime + VR Player` game object and the Unity XR room scale `XR Rig` . This automagically handles all the networking and to test it you can quickly build to to your required platform.

I have also added the functionality to grab objects provided that they already have a collider and the `XRGrabInteractable` components. 

Drop this prefab in any scene to setup the VR networking.

**NOTE:** Do not forget to sign in to NormCore and copy paste the application id to `Realtime + VR Player`. Refer to the documentation for more details.

[Adding AR/VR Avatars & Voice Chat](https://normcore.io/documentation/guides/adding-vr-ar-avatars.html)

Once the application ID is added, fill in the details under *Player* in the project settings. Add in the package name and you will be able to build and test the project.

## Package List
---

Here are the list of packages inside the project

- NormCore 1.0.0
- Oculus XR Plugin 1.2.0
- XR Interaction Toolkit - 0.9.4 *preview*
- Universal Render Pipeline - 7.4.1
