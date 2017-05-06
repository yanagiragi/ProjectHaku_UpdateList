# Update List


### Version Semantics: 

    Major. Minor. isNotShaderCacheContained (1 if not Contained)

<hr>

## 1.0 
> Add Basic Folder Structures

## 1.1

> Add Basic Wall Collider

> Add One Hinge Joint Door 

> Clear All Props from unityPackage Q512

> Sceen -> non-static

## 1.2 

> trying new space


<details>
<summary>Bugs require Fix:</summary>

* collider fix, 
* hinge joint fix, 
* wall fix

</details>

## 1.3

> fix collider 

> Hinge Joint not fixed yet

> Fill up new space

> Still non-static

<details>
<summary>Bugs require Fix:</summary>
	
* Hinge joint fix
* exit sign for upper cube of door(Maybe Ricgh Text UI will fix it)
* upper cube: Anchor override for two reflection probes with weights
* other area space bug

</details>

## 1.4

> fix room-Boiserie and Room-shelf bug(Shelf separate into two parts)

> Add windows.max for needs of boolean expression when adding windows

<details>
<summary>Bugs require Fix:</summary>
	
* Hinge joint fix
* exit sign for upper cube of door(Maybe Ricgh Text UI will fix it)
* upper cube: Anchor override for two reflection probes with weights
* other area space bug

</details>

## 1.5

> Complete partial office structure

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix
* exit sign for upper cube of door(Maybe Ricgh Text UI will fix it)
* upper cube: Anchor override for two reflection probes with weights
* other area space bug

</details>
	

## 1.6

> Fixed upper cube of the door

> Office Strcture minor Adjust

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>
	
## 1.7

> Add Props: Tray, Mug, KirbyMug, CupCake, Record Player

> Finish Section: Book Shelef of Office

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>

## 1.8

> Add Props: Spinning Top, Golden Laugh

> Try Add Reflection Probe Under top for top's reflection, however result is not good. Depreciated for now.

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>

## 1.9

> Add Props: Creeper Doll, Kirby Doll, Flowers, Mac Keyboard&Mouse

> Adjust Desktop structure

> Almost ready to start bake light

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>

## 2.0

> Adjust Ceiling light

> trying add Fur Shader to Dools, but due to resouce-consuming depreciated.

> trying adjust material of spinning top, however it stay for original mat for now.

> Almost ready to start bake light

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix // May Not Needed? <- if restrict access to other room?

</details>

## 2.1

> Adjust Wall Frames

> Almost ready to start bake light

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix // May Not Needed? <- if restrict access to other room?

* Lack of Office Props on Haku's Desktop

</details>

## 3.0

> Lighting Baked

> Lots of workaround for beautify Scenes

<details>
<summary>Preview</summary>

<img src="img/3.0preview.png">

</details>

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

</details>

## 3.1

> Fix Position of Caffe Table, Console

> Adjust Exposure and Rotation of Skybox

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

</details>

## 4.0 Merged

> Merge Project With M,P Version

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

</details>

## 4.1 

> Note: Compressed With lightmap, ShaderCache, etc.

> Backup of new Lightmap

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

</details>

## 4.2

> Import some of haku animation

> Build up simple demo of HeadLookController, BreathController

> HeadLookHelper is depreciated due to it may cause "The Exorcist"

> Adding Enviornment Compensation Light, Haku Compensation Light (Now Both are Directional Light with different Culling Mask)

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

</details>

## 4.3

> Update Idle State Animation: Blending(Actually additvely blend) Animation of sitting.fbx from mixamo.com, trying syncing with BreathController

> Params:

	*	AvatarMask: Torse & two arms (NO HAND & IK)

	*	BreathController: Duration: 0.78

	*	AnimtaionController: BreathLayer: Additively, weight = 0.15

	*	AnimtaionController: BreathLayer.Delay -> BreathLayer.Breathing: Transition Duration = 0.25, Offset = 0

	*	AnimtaionController: BreathLayer.Breathing: Speed = 1

	*	Animtaion: sitting.fbx: frame 177 - frame 363 + AvatarMask

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

</details>