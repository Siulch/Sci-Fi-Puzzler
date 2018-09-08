# VR Sci Fi Puzzler
Puzzler is a project part of the Vr Developer Nanodegree at Udacity, which is to develop a game for mobile devices based on a puzzle, keeping in mind all the experiences the user could have.

This project is about a puzzle based on a Sci Fi environment where the player starts and moves slowly towards the room where the puzzle is. The player has to memorize the sequence of the batteries that were turned on and repeat it by clicking on the batteries in the correct order, if it is correct it can start again.

###Scene Path
Assets -> Low Poly Flat Sci Fi Assets -> Demo -> Scenes

### Versions Used
- [Unity LTS Release 2017.4.4](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.100.1](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)
- [iTween](https://assetstore.unity.com/packages/tools/animation/itween-84) v2.0.9


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated project.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.100.1, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.
