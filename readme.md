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

## 4.4

> Adding Tracking target for HMD (Now Param: z = -1.93)

> Trying Blend Legs part with previous parts, However Foot Ik reacts wierd

	* 	Use 3ds max reconstruct Animation (So many works)

	*	However OL Haku's Heels won't move

	*	Temporaily change to Uniform Haku Instead

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

</details>

## 4.5

> Finish Haku Office Animator: Leg Layer

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

</details>

## 4.6

> Setup Haku Office Animator: UpperBody Layer

> Setup Randomly Leg Motion Script

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

</details>

## 4.7

> Setup Simple grab object controll

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

* UpperBody Randome motion script not finished

* Wall Collider needs to be fit exact space more

* Floor Collider needs to be fit exact space more

* Gravity: Due to the scene is two big, acts like moon

	* Shrink the scene

	* Override single scene gravity settings

* The place of rose should be adjusted

* The Scale of Camera Rig Should be adjusted

</details>

## 4.8

> Fix Gravity Bug

	* Gravity is propotion to scale 

	* Wierd AddForce after realeasing grab object is because I rotated [CameraRig]

> Update Simple give gift interaction

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 4.9

> Update Basic Lunch Scene

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.0

> Update Hurt Effect in Minecraft, Time countdown, etc.

> Update Game Control of Minecraft Scene

> Update Simple Whole Game Control

> Confirmed use Uniform Haku Instead of OL Haku

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.1

> Update Controller details

> I forgot what I've done :(

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.2

> Update Tutorial change image solution(hit.point to uv)

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.3

> ScreenFadeOut when changing scene (now only attached on Minecraft)

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.5

> Merged from ProjectHaku_P_Version5.4

> Construct Full Dropping gift script in Office Scene(All Gifts & after drop & detect drop with headLookController)

> Construct simple upper body animator (However random play script are not finished yet)

> Construct Planes that able to teleport

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished // almost done

* The scale of room props should be adjusted

</details>

## 5.6

> Finished Construct upper body animator

> Add Special Areas For haku to peek

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Camera needs to higher?

* The scale of room props should be adjusted

</details>


## 5.8

> Merged from ProjectHaku_Y_Version5.8

> Finished Basic Crab Scene (including Morph Controll & revised anim, however not baked physics)

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.0

> Finished Crape and crab Lunch Scene

> Not quite sure waht updated in this version


<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.2 ~ 6.2.8

> experiment with revised animations

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.4

> Revised Animations and fixing wierd bug when fast entering giving gift's collider, causing haku look at you while her hands still typing (Update: Ver 6.5 Not Fixed?)

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.5

> Add Basic Wedding Scene

> Spawn Camera on specific point by substract the placement between CameraRig & Camera(eye), However it works strange on office scene

> add experimental scene: Office Before Lunch

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.6.5

> Adjust BeforeLunchScene without physics effects on animation, a.k.a. broke meshes

> .5 is for haven't clean up experimental animations

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.7

> clean up experimental animations

> Adjust BeforeLunchScene

	裙子用bake，彎腰時破圖

	頭髮用MMD4Mecanim 的 Bullet Physics + MMDRigidbody 的 Cube

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md


</details>

## 6.8

> Add Scene: Opening 

> Minecraft 全部串接 (計時倒數、GameStart/Over Canvas、creeper dying effects)，只缺ipad控制

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.9

> Add Tutorial Control in Scene:Minecraft

> Setting up Scene:Before Lunch

> Finish concat Scene:BeforeLunch and Scene:Lunch

> Trying setup Ending Scene for more details (Now Add: Canvas anim, camera change position)

> Force Rendering support to dx11 in windows, however MKGlow not fixed?

> Ignore dxd9d in some shaders(Axi) of ArchVizPRO

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.0

> Finished Scene:BadEnding

> Construct Basic scene controll of Scene:GoodEnding, need testing and finish it with HMD on

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.1

> Merge with Project_M_ver6.5, Adjust Scene:Office prop's scale

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.2

> Finished Scene:GoodEnding (Not checked in VR)

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>


## 7.3

> Finished Scene:GoodEnding & Scene:BadEnding & Scene:Opening, Not including art details

> Add Scripting Control to bgm fadeIn/Out

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.4

> Finished Bgm Controlling

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.5

> FadeOut Bgm:EndingGoodWait

> 調整Minecraft Count Canvas

> 修正Office物理bug(果然是因為SpecialAreacapusle，調整physical detection layer 修正)

> 全部的bgm、音量再調整、Office Recorder

> 加入Lunch Ipad

> 修正SpawnAtPoint Bug: 因為CameraEye 和 CameraRig本身的Scale的引響(將CameraRig Scele 調成1解決，不過因此 Scene:Office 東西位置需要再微調)

> 修正 修正SpawnAtPoint Bug 之後地板會閃爍：拿掉 PlaneRefection就可以了(可能是之前改DXD9的關係)

> 修正 Minecraft CleanUp 沒有兩隻手把都啟用的bug

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.6

> Adjust Skirt

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.7

> LunchScene, EndingScene * 2 材質、光照完成！

	註記：無法看見蠟燭是因為跟背後玻璃的transparent相衝?

> Fix goodEnding CleanUp Bug

> Fix goodEnding SpawnAtPoint Bug

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.8

> Update Hint in Scene:Office

> Update Dialog Sprite in Scene:BeforeLunch & adjust time for changing scene

> Update Eaten effects on crape & crab(Add Donut)


<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Should add: Haku eating morph and SFXs

* Scene:Lunch LaserPointer Bug

* More less-important details are in todo.md

</details>

## 7.9

> Adjust Haku's scale in whole game

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Should add: Haku eating morph and SFXs

* Scene:Lunch LaserPointer Bug

* More less-important details are in todo.md

</details>

## 8.0

> 修正 Vive Tutorial ReleaseObj 時給予velocity, augularVelocity 的問題(應該要用local座標系的速度、角速度)

	所以在此之後Camera可以Rotate了

> 建立API: 固定出生點視角 (根據 Start 時頭盔位置計算CameraRig轉動量，並根據旋轉之後位置重新指定位置)

> 尚未套用到Office以外的場景(最需要的應該是BeforeLunch)

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Should add: Haku eating morph and SFXs

* Scene:Lunch LaserPointer Bug

* More less-important details are in todo.md

</details>

## 8.1 ~ 8.4

> 因為未詳細紀錄更新紀錄，所以直接整合在一起

> 紀錄上次更新API細節: 固定出生點視角 修正
	
	兩種做法：

	一為根據Camera轉動場景，在生成位置 但是這樣就無法static (舊的作法) // 不好

	二為根據位置計算CameraRig的轉動位移跟位置位移

> 修正新API之後 Ending 場景切換 Camera 位置

	因為轉動之後位移量不再是直接用加的，不過GoodEnding並未做視角控制，沿用舊版

> 初步 Bake 中，效果還好，但是

	光線在天花板處有明顯分界 // 應該是因為point light + 半圓燈罩? 正常嗎?

	沒有陰影的感覺 也沒有樹葉陰影的感覺

> 建立完整第0場景，修正移動到MenuBg的Bug

	因為下面的Plane 在手把的 TeleportMask中

	強迫完成教學的設計模式 (但是無法處理喜歡亂搞的玩家)

> 加入 GoodEnding 觀眾

> 加入Office Judge 禮物時轉頭

> 修正 Office 給東西動畫的bug (因為 Update UpperBodyMotion使用 IEnumerator，所以控制城拿東西後馬上被 Assign 回 Keyboard了)

> 修正複數Bug

	* 修正 Lunch LaserPointer Bug

	* 調整 Minecraft Canvas位置

	* Office 撿不到東西 // 沒問題啊?

	* Lunch 要離Haku進一點

	* Minecraft場景拿不到Ipad // 修改擺放位置

	* 調整 BeforeLunch Bgm 音量到 0.3 // 原本的兩倍

	* 修正BadEnding Haku表情 
	
	* Office表情慢一點點 // 因為加入轉頭

	* Haku頭髮Shader透明? // 因為貼圖本身那邊有alpha = 255的狀況，change MainTex to HairNT

	*  Office Keyboard 音效 // 不過沒有fadeIn, Out, 沒有很fit手指動作

> 註記：

	加頭髮 > 小穿越

	裙子物理沒有考慮到左右腳切換

	Idle -> take東西會小小穿越裙子 // 先不處理!

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

# 8.5 ~ 8.6

* 加入教學

* 加入 Minecraft Haku + ID

* 午餐音效等入

* 根據使用者回饋做了以下調整(以及修正bug)：

		Opening 教學場景 Canvas位置調整

		放寬ipad 中間頁面切換

		提示有的劍不能砍 -> 劍data Canvas

		天花板避免順移 -> 不過還是有無法避免的狀況

		午餐新增對話框 "那我們回去吧!" "你要吃嗎 我喂你"

		午餐Crape 位置 // 不調整

		Adjust 午餐Face Collider // 避免瀏海穿越到臉中

		拿掉 午餐胸前collider // 雖然說對側邊長瀏海有幫助，但是似乎對於後面馬尾影響過大

		Office Haku馬尾有點怪 (不過 BeforeLunch 不會? // 目前暫時拿掉，不過會不會是因為Dynamic Bone?

		Frame 位置調整 // 拿掉 Collider

		快速按下去留聲機會怪怪的? // 做relay 切換

		Office 頭髮穿透 // 重新調整椅子位置 Scale

		Office Haku 補償光 ++

		Ending固定在視角? // 暫不考慮

		修改Ending Canvas: 請在他身邊看著他

		Haku Wedding 太慢 // 把音樂fadeOut 割成 IEnumerator

		不放觀眾 // 暫時拿掉，有人反應很令人分心?

		ipad Coliider怪怪的? // 因為射線射到手把Controller，目前把cube size改成 (.7, .7, .7)

		修正 部分 Office 不應為 Static 的物件

		修正 GoodEnding / BadEnding SpawnPoint Bug

		加入 EndingScene 箭頭提示要看的方向 // 有點醜?

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* More less-important details are in todo.md

</details>

# 8.7

* 根據使用者回饋做了以下調整(以及修正bug)：

		 教學說明改成 "按下兩側的箭頭"

		 最後一頁 Hover

		 Minecraft 傳送門

		 拿起來才消失 劍Canvas

		 Minecraft fallback 回第一版地板

		 Tray 打光  //維持原樣

		 教學說明改成 "把禮物親手交給她"

		 修正 Office // 現在也會有RectileNo

		 Rectile Red warning // 原來是忘了assign texture

		 Opening Scene 加入 "試著移動看看" "試著抓取Ipad"

		 教學字體統一到 華康竹風體(P)

		 Minecraft放到最後多一頁 "PS 有些劍不能拿"

		 Office 時間長一點 // 180sec

		 Haku 電腦的圖, 自己電腦的圖

		 Frame 提示

		 咳嗽聲 自己吃的聲音 太小聲  咳嗽換回原本的版本, maleHamu pitch = 1.23

		 Lunch Loop 回去時考慮暫停Animator 跟 hamu音效

		 GoodEnding 光影閃爍  Haku身後的柱子  原因是因為realtime光，已拿掉

		 分數bug  Lunch IncScore 放在 Update

		 Office 送東西 Collider 偵測附上手把的雙重保險?  類似 Sword isGrabed的方式

		 午餐椅子的collider

		 苦力怕被擊退

		 修正 HurtCapsule 不自然的shader結果 // WorkAround

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* 以下不確定是否採納與修正：

		* Minecraft Canvas 此把劍無法傷害苦力怕

		* BeforeLunch Hair Collider修正

		* 晃很久苦力怕bug

		* Rectile bug?

		* 拿起東西的機制

* More less-important details are in todo.md

</details>

# 8.8

* 根據使用者回饋做了以下調整(以及修正bug)：

		 辦公室提示改成送其中一個禮物後消失

		 修改 Lunch Haku 肩膀動畫幅度

* 在 Minecraft 放入陀螺

* 修正 GoodEnding 中 Haku 的光影效果

* 拿掉 Minecraft場景中的布幔 // 在 Realtime 光影下有閃爍問題

* 修改Player Settings(ProjectName, Icon, Cursor)

* 調整 Lunch SFX 平衡

* 將Spinning Top 加上髮絲紋的法線貼圖

* 些微修正午餐頭髮的物理，但是依舊會抖動


<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* 以下不確定是否採納與修正：

		* Minecraft Canvas 此把劍無法傷害苦力怕

		* BeforeLunch Hair Collider修正

		* 晃很久苦力怕bug

		* Rectile bug?

		* 拿起東西的機制

* More less-important details are in todo.md

</details>

# 8.9 ~ 9.0

* 修正 MKGlow Shader Error // 只是忘了上Glow貼圖?

* 導入新系統：Eye Raycast // Office 拿掉 Mune, yarashi Threshold 設成 150

* 根據使用者回饋做了以下調整(以及修正bug)：

		 * BeforeOffice/Office 桌子邊修正 // 弄新的Plane替代

		* 拿掉 Cursor (炸掉惹)

		* Office Desktop Props Scale 跑掉了 // 拿掉書

		* 修正 Office 筆筒位置

		* Office 天花板燈有點空虛 // 放 Point Light, 用 range + culling mask, 但是還是會有Distance問題

		*  Office Donut 位置上來一點點

		* Office Keyboard 聲音調小

		* BeforeOffice 陀螺應該要轉 // 直接拿掉陀螺

		* Ending要把 Keyboard 播放 cut 掉 // 直接volume Fade 到 0

		* Minecraft 陀螺位置

		* BadEnding BGM 有點小聲 // 調成 0.6

		* BadEnding Haku的腳要上面一點

		* Opening 沒有 RectileNo 效果? // 現在有了

		* Opening 教學 .5f 的 Delay // .3f更直覺，但是容易點太快

		* 修正 Minecraft 場景有時候拿不出劍 // 因為 CameraCollider, 用 Collision Layer 解決

		* 修正 Minecraft 場景 Hurt Effect Bug

		* 修正 GoodEnding Rectile Offset 太小

<details>
<summary>Bugs require Fix:</summary>

* More less-important details are in todo.md

</details>


# 9.1

* 裙子動畫修正

<details>
<summary>Bugs require Fix:</summary>

* More less-important details are in todo.md

</details>

# 9.2

* 修正Office 在手收回去時用丟的送禮物的bug 以及 同時拿兩個禮物靠近，一個送她另一個前後進去Collider的bug

<details>
<summary>Bugs require Fix:</summary>

* Minecraft 武器快速換手會有音樂沒有撥放的bug

* More less-important details are in todo.md

</details>

# 9.3

* 修正Office Keyboard 位置

* Build 參數： 
	
	Demo 版 -> Office 時間 90秒， score > 5 Ending

	Release 版 -> Office 時間 150秒， score > 65 Ending

<details>
<summary>Bugs require Fix:</summary>

* Minecraft 武器快速換手會有音樂沒有撥放的bug

* More less-important details are in todo.md

</details>

# 9.4

* 增加 AlterEnding (Not Achievable Ending)

<details>
<summary>Bugs require Fix:</summary>

* Minecraft 武器快速換手會有音樂沒有撥放的bug

* More less-important details are in todo.md

</details>

# 9.5

* 修正Haku 褲襪貼圖

<details>
<summary>Bugs require Fix:</summary>

* Minecraft 武器快速換手會有音樂沒有撥放的bug

* More less-important details are in todo.md

</details>

# ~ 9.8
* 加入 Haku Nade

* 修正遊玩參數

<details>
<summary>Bugs require Fix:</summary>

* Minecraft 武器快速換手會有音樂沒有撥放的bug

* More less-important details are in todo.md

</details>

# 9.9 (Final)

* 專案 Clean up

<details>
<summary>Bugs require Fix:</summary>

* Minecraft 武器快速換手會有音樂沒有撥放的bug

* More less-important details are in todo.md

</details>

# 10.0 ~ 11.1 (Project Haku II)

## Opening 場景

* 小幅度修正光影，柔和一點點點 (我也忘了我到底有沒有調過啦)

## Minecraft 場景

* 修正 Minecraft 特殊行為 造成的 bug
	
		* 特殊行為: 在目前 Trigger 為按住情況下，另一手把靠近按下Trigger，接著再放開目前Trigger 的行為)

		* 修正 Bug: 9.9 以前 Minecraft 武器快速換手會有音樂沒有撥放的bug

		* 修正 Bug: 小機率因此無法砍傷怪物的bug

* 修正 Minecraft 劍 拿否砍傷怪物的設計

		* 修正前：只有鑽石劍可以攻擊, 使用劍上Canvas 的 攻擊力 暗示這一點

		* 修正後: 所有劍都可以攻擊

		* 然而這樣使用鑽石劍的風險更大，因此在計算分數上採有倍率制，Canvas 亦顯示倍率

		* 鑽石劍倍率: 2 倍，其他的劍: 1 倍

		* 拿掉 Minecraft 場景 Ipad 最後一頁的教學圖片 ("並不是所有劍都能傷到怪物喔")

* 延遲進入傳送門之後 開始遊戲的時間

		* 修改前：直接開始遊戲 + 跑 GameStart UI 動畫

		* 修改後：跑 GameStart UI 動畫，動畫結束後幾秒 (用 yield 實作) 才開始遊戲

* 更改苦力怕重生位置，重生點數量從 8 個 減少到 6 個，另外調整位置離重生點比較遠，避免進入傳送門後有機率馬上遭遇怪物

* 調整 Minecraft 遊玩時間

		* 修改前：30 秒

		* 修改後：45 秒

## BeforeLunchOffice 場景

OLD

![](./img/old3.png)
![](./img/old2.png)
![](./img/old1.png)

NEW

![](./img/new3.png)
![](./img/new2.png)
![](./img/new1.png)

* 加入燈泡 + 很微量的 Bloom，雖然到 Bloom 微量到燈泡不太有 glow 的效果，但是考慮到 Bloom Luminance Threshold 不好調，其他東西太亮，算是做一個取捨

* 降低 天花板 emission
		
		* 修改前: 2

		* 修改後: 1.5， Enable Camera HDR

		* 拿掉修補用的 Area Light

* 光源設置，修改前:
    <details>
    <summary>
        展開
    </summary>

    * 三個大範圍的點光源 (高Range) 照亮環境

                Color = (255, 255, 255)
                Baked
                Range: 10
                Intensity = .96
                Bounce Intensity = 1
                Soft Shadow (Holy ShXt，我當初到底在想甚麼)

            * 三個設置在燈罩底下的 Spotlight

                Rotation = (90, 0, 0)
                Color = (255, 255, 255)
                Baked
                Angle = 14.38
                Spot Angle = 30			
                Intensity = 1
                Bounce Intensity = 1

            * 三個補充牆壁暗處的 Area Light 

                Rotation = (-90, 0, 0)
                width = 24.45219
                hieght = 0.6878968
                Color = (255, 255, 255)
                Bounce Intensity = 1

            * 主要平行光  (向房內照射)
                Rotation = (-43.375, -33.975, 43.441)
                Color = (224, 236, 188)
                Baked
                Intensity = 0.6
                Bounce Intensity = 1
                Soft Shadow

            * 次要平行光 (向房內照射)

                Color = (255, 255, 255)
                Realtime
                Bounce Intensity = 1
                No Shadow

            * Haku 補償平行光

            * 一個 Reflection Probe 設置在場景中央

            * 若干個 Light Probe Group

            * Enviornment Lightning 參數設置:

                Ambient Source: Skybox

                Ambient Intensity: 0.5

                Ambient GI: Baked

                Reflection Source: Custom, Reflection-Probe 0

                Reflection Intensity: 0.291

                Reflection Bounces: 3

            * GI 參數設置:

                Baked Resolution: 40

                Baked Padding: 2

                Altas size: 512
    </details>

* 光源設置，修改後: 

    <details>
    <summary>
        展開
    </summary>

            * 三個大範圍的點光源 (高Range) 照亮環境

                Color = (255, 255, 255)
                Baked
                Range: 1
                Intensity = 2
                Bounce Intensity = 1
                Soft Shadow (Holy ShXt，我當初到底在想甚麼)

            * 主要平行光  (向房內照射)
                Rotation = (-59.549, -65.979, 70.86)
                Color = (255, 255, 255)
                Baked
                Intensity = 0.8
                Bounce Intensity = 1.2
                No Shadow

            * 陰影平行光 (向房內照射)
                
                Rotation = (-70.945, 26.115, -18.694)			
                Color = (255, 255, 255)
                Realtime
                Intensity = Bounce Intensity = 1
                Soft Shadow, Low Res, Strength = 0.6

            * 補償平行光 (向房外內照射)
                
                Rotation = (140.36, -87.98999, 50.067)
                Color = (255, 255, 255)
                Realtime
                Intensity = .84
                Bounce Intensity = 1
                No Shadow		

            * Haku 補償平行光

            * 一個 Reflection Probe 設置在花瓶桌前

                // 玻璃的Reflection Probe 設置 為 Simple 模式，並且 Override Anchor 到 目標 Reflection Probe 的 Transform

                Position = (-10.58, -17.18, 13.81)
                Scale = (5, 5, 5)
                Realtime, Refresh On Awake
                Box Size = (4.665749, 7.8, 11.66156)
                Box Offset = (2.332874, 1.192093e-07, 0.5307815)
                Resolution = 128
            
            * 一個 Reflection Probe 設置在鏡子前

                // 鏡子的Reflection Probe 設置 為 Simple 模式，並且 Override Anchor 到 目標 Reflection Probe 的 Transform

                Position = (-0.49, -33.53, 10.75)
                Scale = (5, 5, 5)
                Realtime, Refresh On Awake
                Box Size = (10.34, 7.8, 15.55)
                Box Offset = (0.8, 0, 0)
                Resolution = 512

            * 若干個 Light Probe Group

            * Enviornment Lightning 參數設置:

                Ambient Source: Skybox

                Ambient Intensity: 0.5

                Ambient GI: Baked

                Reflection Source: Custom, Reflection-Probe 0

                Reflection Intensity: 0.291

                Reflection Bounces: 3

            * GI 參數設置:

                Baked Resolution: 40

                Baked Padding: 2

                Compressed

                Ambient Occulusion
                    Max Distance = 2
                    Indirect = 2
                    Direct = 1

                Final Gather
                    Ray count = 256
                    Denoising

                Altas size: 512

    </details>

* 其它的 畫框玻璃物件 反射應該會有點錯誤，因為 只有兩個 Reflection Probe 可以 Blend (缺少一個最大的 Probe 涵蓋全景)，不過因為角度不明顯，因此不另外修正

* 兩個 Reflection Probe 的 大小 在反射後有點小怪，不過套用 Box Projection 後好像還是有點怪，有可能是 Reflection 在 Realtime 本身就有點全部正確；當然也有可能是更精緻設計的 Reflection Probe 可以修正這個問題

* Haku 的 文字 第一個從 "(看著你)" 改為 "(盯~)"

* Haku 頭髮的物理模擬調整為 Bullet Physics 2.83

* Haku 頭髮的物理模擬 執行續 調整為 Single Thread (比較 Stable 一點)，不過依舊會有看到後才開始計算物理的問題 (有可能是這個計算考慮到 view 的關係)

## Lunch 場景

* 拿掉四周牆壁，加回原始模型就有的欄杆，調整欄杆到比較不反光，也針對新的欄杆加上 Collider

* 微調地板貼圖，分辨率小幅度提升

* 調整咳嗽音效，現在咳嗽音效有3個，來源為 Youtube 影片的調音版本 和 日常 露營時噎到的調音版本

* 主角吃東西的 男生 Hamu 改為 吃東西(吃冰塊) 的音樂特效，比較考慮到女性玩家

* 手動修正周圍場景的建築物 (面數上沒有減非常多，但是 Set Passes 減少了部分，fps 數得以提升)

## Office 場景

* 遊玩時間調整為 120 秒

* 光影配置同 BeforeLunchOffice，惟 陰影平行光 的角度不同

		* 刻意設置不同來表現時間的推移

		* Office: Rotation = (-70.945, 26.115, -18.694)

* 調整 Haku 的 椅子 位置(避免裙子穿透 與 頭髮物理) & Collider

		* 調整前: Box Collider

		* 調整後: Mesh Collider, Mesh = 用 Blender Limited Dissolve 減面後的模型

* Haku 頭髮的物理模擬調整為 Bullet Physics 2.83

* Haku 頭髮的物理模擬 執行續 調整為 Single Thread (比較 Stable 一點)，不過依舊會有看到後才開始計算物理的問題 (有可能是這個計算考慮到 view 的關係)

* GI 設定好像 Custom Reflection 的 Cubemap 跑掉了，不過原本會用這個的就是陀螺，考慮到周圍有另一個可以 Blend 的 Reflection Probe 跟 陀螺本身的法向量比較亂，應該是沒有太大影響

* 千萬不要升專案版本，即使只是從 5.5.2 f1 升級 5.5.4 f1 也會讓物理變的相當不穩定

* 調整自己 iMac 的圖片，為後來的 MHH Scene 提供簡單的連結性

* 調整窗邊 與 花瓶桌子 的 metalic，不再像上一層亮光漆 (強烈懷疑以前的我看到有附 Specular 貼圖就很高興的把強度調到滿...)

* 加入吊燈燈泡 (有簡單的 Emission，不過感覺這邊的 Emission 對 GI 影響甚小，因為 Post Processing 沒有開多大的 Bloom 所以也沒有很 glow，不過我認為這是可以取捨的)

* 否決高對比 (Contrast, Saturation) 的 Post Processing，不開 Post Processing 以追求比較自然的光影效果

## BadEnding

* Ending [B]

* 加入 一堆人 (Beta) 拍手，拍手用 Random 決定 Animation

* 最後面的 Ending 字樣 從 "Thanks for playing!" 修改為 "Thanks for playing...?"

* 最後面加入 Canvas 瞬間消失 + 聲音的效果

## ChurchFailedScene

* 加入新的場景，目的為帶過 失敗 ~ 挑戰 的過程

* Canvas 彼此之間 Fading 的時間並不是 固定的，平均而言有些 4 秒有些 5 秒，基本上配合音樂

* 音樂部分挑選 Soul Sacrifice 的 Hope And Future On The Same Page, 所幸音樂的段落分名剪起來 Mix 的不錯

* 如果提早放棄 (結束)， 音樂會在 4 秒內 volume 降為 0

* 再三確認，留意手把可以選擇的時間並沒有完全契合 Canvas 出現的時間，然而這部分不會影響非常大 (我努力說服自己中，不要太急著按就好)

* 如果放棄，關閉遊戲

* 如果不放棄，降下 Ipad 並進到 MHHScene

## MHHScene

* 加入新的場景，目的為挑戰雌火龍

* 從 Project MHH 延伸而來，然而沿用的部分主要有

		* 80% 鬥祭場

		* 怪物 AI 的基本框架 (後來整個重構)

		* 玩家血量 & 碰撞判定

		* 怪物攻擊判定

* 加入新要素:

		* 針對 VR 的操作方式

		* 右手持劍，左手使用魔法 or 盾

		* 針對 VR 的 UI 設計 (HP, MG, SK, LV)

		* 兩種魔法: 火焰魔法 (固定 CD), 增益魔法 (非線性增長CD時間)

		* 最終階增益魔法開啟 雙劍 & 特殊組合

* 重構怪物的攻擊判定

		* 全部改用 Animation Event 來控制 Coliider Index

		* 如上述，拿掉充滿各種 Magic Number 的 Coroutine

		* 調整 Two Feet Stomp 的 Collide 設定

		* 加入 Flip Attack 的攻擊

		* HowlWhenAir 加入音效 Event

* 拿掉原先 顯示 手或是手把 的 設計，基本上看不到 Controller 的模型

* 調整怪物 Collider 後比較精準，不像以前莫名其妙就死掉了

		* 雖然說以前的比較讓你有絕望感

		* 但是怕會被別人認為是 "很糞" 而不是 "很難"

		* 暫時還是用新版的攻擊判定

* 記得所有的劍 Tag 不要設為 MonsterHitBox

* 修正若干碰撞判定 判定到 MonsterHitBox 以外 Tag 的 Collider 判定

* 利用 Blender 切出眼皮 拉 BlendShape，不過因為有點難對其骨頭的位置，所以目前設置為 Idle 時表現不錯，Idle 以外會小跑掉

* 修正火焰 Prefab 預設就有個角度的Offset (TMD 害我一直de不出沒辦法瞄準的 Bug)

* 如果輸了，到 MHHFailedScene

* 如果贏了，到 OneMoreChanceScene

* Post Processing:
	
		* Bloom:

			Intensity = 1.2

			Threshold = 0.98

		* Color Grading: 
		
			Tone Mapper: None

			Post Exposure = 0.4

## OneMoreChanceScene

* 加入新的場景，目的為跑提示 + 回到原始開頭

* GlobalManager.AdjustThreshold() 調整分數限制，使得 Ending 可能

## MHHFailedScene

* 加入新的場景，目的為讓你重新挑戰

* Yes -> MHHScene

* No  -> Ending [E], goto SpecialOpening + setup Salt

* 後面擺了三個大 Ipad 充當額外提示

## GoodEnding

* Ending [A]

* 加入 PP, 主要是 Bloom & Tone Mapping

* 微調 Haku 補償光 與 花朵的補償光

* Setup Salt

## SpecialOpening

* 加入新的場景，目的為提示到了盡頭

* 對 Opening BGM 調音，大概只有處理前一分鐘的內容 (但是正常遊玩大概只會有30~40秒的遊玩過程)

* 配合音樂客制化調整 Kino.Glitch 的時間點

## ClearOpening

* 加入新的場景，目的為開頭教學 + 些許福利

* 4 個 Haku 除了 Pointing 以外都沒有開啟 頭髮的物理模擬

* 用 Box Collider 取代 Plane Collider 避免 Ipad 穿透問題

* GlobalManager.AdjustThreshold() 調整分數限制，使得 Ending 可能

## 其它

* 流程上重新調整，遊玩時間變長

* 大部分 Canvas Dynamic pixels per unit 調成 800，讓字小一點閱讀比較舒適

* 整體專案品質設定

		* 關閉 8x MSAA

		* 關閉大部分 Anti-Aliasing 設定

		* 嘗試過 Post-processing 的 FXAA 和 TAA， FXAA 效果不明顯明顯吃效能，TAA 很糟糕

* 專案導入 Project MHH 內容

* 不再採用 Resources/ 的存法 (Build 出來超過 4G)

* 專案 Clean up

* 2 代預告片重新錄製 1代預告片的部分內容 (來套上新的 GI 效果) + 多了 40 秒左右的片段

* Meta Salt 的設計
