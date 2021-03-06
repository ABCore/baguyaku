---
layout: gl
permalink: /GlitchList/
---

<!--
- [物理的バグ(Physics-Related Glitches)](#物理的バグphysics-related-glitches)
- [ヨッシー関係のバグ(Yoshi-Related Glitches)](#ヨッシー関係のバグyoshi-related-glitches)
- [アイテムとオブジェクトのバグ(Item and Object Glitches)](#アイテムとオブジェクトのバグitem-and-object-glitches)
- [雑多なバグ(Miscellaneous Glitches)](#雑多なバグmiscellaneous-glitches)
- [ロックとクラッシュ(Locks and Crashes)](#ロックとクラッシュlocks-and-crashes)

# Physics-Related Glitches  
-->
# 物理的バグ(Physics-Related Glitches)  

<!--
__(Mario and controls)__  
-->
__マリオと操作(Mario and controls)__  

<!--
_70 recorded glitches, 64 of which are useful_  
-->
_70個(64個有用)_  

<!--
* If Mario becomes surrounded by blocks and touches the ground, he will be crushed and die. However, avoiding touching the ground can be done in a number of ways, such as by flying before Mario gets surrounded, or swimming upwards. [Video](https://www.youtube.com/watch?v=oxUGDQCccF4)
-->
* マリオがブロックに囲まれまま地面に足がつくと、圧死する。しかし、飛行状態や上方向に泳ぐなどの地面に足がつかない方法で圧死を避けられる。[Video](https://www.youtube.com/watch?v=oxUGDQCccF4)

<!--
* If Mario is far enough inside a solid tile, he will be pushed leftward by it. Oddly, Layer 2 does will not do this, and instead Mario will be able to freely walk around (though unable to jump).
-->
* マリオがソリッドタイルにめり込んでいる時、左方向に押される。ただし、レイヤー2ではそうならず、ジャンプはできないが自由に走り回れる。

<!--
* If Mario is big and stands up or jumps in a one-tile space, he may be pushed through the floor. Also works if Mario lands on Yoshi, and can even occur while Mario is small if he gets stuck in a turnblock during the jump.
-->
* デカマリオが1タイル分の空間で立つと同時にジャンプすると、下向きに押され床抜けする。これはマリオがヨッシーに乗った時や、チビマリオが回転中のクルクルブロックに重なって、回転し終えた瞬間ジャンプしたときにも起こる。

<!--
* If Layer 2 or Layer 3 are active in a level, standing Mario up in a one-tile space with blocks on the same layer both above and below him will cause him to sink slightly into the block, as opposed to being pushed left like normal. Often this will cause him to fall through the ground without the need to jump.
-->
* レイヤー2・3レベルで、同じレイヤーのブロックが上下に配置された1タイルの隙間でデカマリオが立つと、通常左に押されるのとは対称的に、マリオがブロックの中で震える。この状態では、ジャンプしなくても床抜けすることがある。

<!--
* Smashola: Doing the above through turnblocks while caped and spinjumping may cause Mario to "warp" his way downward very quickly. [Video](https://youtu.be/oyJ7ZTz3HMw)
-->
* スマッシュオラ：マントマリオがスピンジャンプでクルクルブロックの中を掘り進む時、ワープしたかのように極めて早く下移動することがある。[Video](https://youtu.be/oyJ7ZTz3HMw)

<!--
* Walljump: With enough speed, Mario can land on the corners of blocks for a frame - even if they're part of a wall - and jump off of it. As an alternative, this frame can also be used to enter doors or pipes, even if they don't normally have ground. [More info](http://smwc.me/617858) - [Video](https://www.youtube.com/watch?v=yp3Z6d81sX4) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=8815)
-->
* 壁ジャンプ：十分な速度で壁にぶつかると、ブロックの角に1Fだけ乗ることができ、この瞬間にジャンプが可能。ジャンプの変わりに、地面でない所では通常入れないドアや土管に入ることもできる。[More info](http://smwc.me/617858) - [Video](https://www.youtube.com/watch?v=yp3Z6d81sX4) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=8815)

<!--
* Mario can enter a pipe even if his head is the only part touching it.
-->
* マリオの頭部が土管の一部に触れてさえいれば、入ることが可能。

<!--
* Jumping on the first frame after coming out of an upwards pipe will let Mario jump without triggering the effects of the block he came out on top of (including Munchers).
-->
* 上向き土管用の動きで出てきて、行動できる最初のFにジャンプすると、足がつくことになる（ブラパを含めた）ブロックの効果が作用しない。

<!--
* Slope clip: Mario can pass through the corners of slope tiles so long as he is moving upward as he crosses it. [More info](http://smwc.me/617858) - [Video](https://www.youtube.com/watch?v=OmU8Vd5-QYM) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=8816)
-->
* 坂抜け：上昇中のマリオが坂タイルの角を横切ると、坂を通り抜けられる。[More info](http://smwc.me/617858) - [Video](https://www.youtube.com/watch?v=OmU8Vd5-QYM) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=8816)

<!--
* Clipping into an upside-down slope will force Mario on top of it. This can also force him inside blocks, killing him. [Video](https://youtu.be/GxBuYS_DQfc?t=10m50s)
-->
* マリオが天地逆さの坂にめり込むと、坂によって下方向に押される。これにより、マリオがブロック内に押し込まれ、圧死することがある。[Video](https://youtu.be/GxBuYS_DQfc?t=10m50s)

<!--
* Clipping into the bottom corner of a block that is on a ledge may cause Mario to be forced on top of the ledge, killing him inside the block.
-->
* 下に足場があるブロックの底の角にめり込むと、足場に乗り上げブロックの中で圧死する。

<!--
* If Mario hits the vertical screen barrier while walking up a slope, he will fall through the slope. [Video](https://youtu.be/MySZ8yYvb-w?t=38s)
-->
* 画面上部の判定が取られる境界上の坂を登ろうとすると、坂をすり抜けて落ちる。[Video](https://youtu.be/MySZ8yYvb-w?t=38s)

<!--
* Mario will "stick" to the vertical screen barrier when jumping; he won't fall down until his speed actually becomes positive, but he can't rise higher either. [Video](https://twitter.com/Kaizoman666/status/905846914674982912)
-->
* ジャンプ中のマリオは、画面上部境界より上に行けず、境界にくっつく。上速度を持つ間、落ちはしないが、高くもならない。[Video](https://twitter.com/Kaizoman666/status/905846914674982912)

<!--
* Corner clip: With enough speed, Mario can "enter" the corner of a block in order to pass through it. If he's small or ducking, though, he may be crushed. [Mo](http://smwc.me/617858)[re](http://www.smwcentral.net/?p=viewthread&t=72714) [info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#CornerClip)
-->
* 角抜け：十分速い速度でブロックの角に突っ込むと、そのまま抜ける時がある。もしチビマリオだったりしゃがんでいると、圧死する。[Mo](http://smwc.me/617858)[re](http://www.smwcentral.net/?p=viewthread&t=72714) [info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#CornerClip)

<!--
* If Mario is big, you can also force him into inner corners where a leftside wall and ceiling meet. If the corner is non-solid, he can go through without dying.
-->
* デカマリオなら、壁の左上角を抜けることもできる。もし角が非ソリッドタイルなら、死なずに済む。

<!--
* If Mario is ducking when he enters certain states (climbing, balloon), then he will still retain his reduced hitbox size, despite what the graphics for these states suggest. He'll also still be ducking once he exits those states.
-->
* マリオがしゃがんでいる最中、何かを掴んだりPバルーンなど特定の状態になると、マリオはその状態における表示が描写されるが、実際の当たり判定はしゃがんだ範囲となる。状態が解除されると、当たり判定は通常に戻る。

<!--
* If Mario grows from a powerup while in certain phases (climbing, Lakitu cloud) and his head ends up inside a ceiling, he'll be pushed leftward, even through solid blocks.
-->
* 何かを掴んでいたりジュゲムの雲に乗っているなどの特定の状況で、マリオの頭が天井に触れている時にパワーアップすると、左向きに押されてソリッドブロックも貫通する。

<!--
* If Mario has 99 lives and he gets a life through any means, his life counter will briefly increase past 99 for a frame. Exiting a level on that frame (via start+select or a screen side exit) will then display a glitched value for his life counter on the overworld. Entering a new level will fix it, however.
-->
* 残機が99の時に残機を1増やすと、1Fだけ残機が99を越えて値が増える。そのFにステージを出る（Start+Select/画面横出口）と、OW上での残機表示がバグる。これは新しいレベルに入ると治る。

<!--
* It's possible to completely prevent any sprite from spawning so long as the spawn region of the screen can be passed over it (a distance of just over 16 pixels). Because the spawn routine only runs every other frame, this means that you can have up to three frames to do this (the last frame of which can be gotten from pausing the game breifly to realign the frame counter). Two verified methods of doing so are using a rope mechanism to drag Mario during those frame, and using a fast-spinning revolving platform. If moving fast enough, it may also be possible without the use of any sprites. [More info](http://tasvideos.org/forum/viewtopic.php?p=464958#464958)
-->
* スクリーンのスプライトを出現させる領域（16ピクセルほどの狭さ）をスキップすることでスプライトの出現を完全に防ぐことができる。スプライト出現のルーチンが1Fおきに呼び出されるので、ポーズでフレームカウンターを調整による1Fとおまけ1F（More infoに詳細）が得られるから、このバグは最大3F連続して起こせる。確認済みで有用な2つの方法があり、ロープでマリオをそのフレームの内に加速させること、あるいは高速で回転する足場を使うことである。スピードが十分あればスプライトの援助なしでもバグが発生することはある。[More info](http://tasvideos.org/forum/viewtopic.php?p=464958#464958)

<!--
* If vertical scrolling is enabled in a level, you can prevent the screen from scrolling by jumping off of the ground the frame that Mario lands on it.
-->
* 縦スクロールができるレベルで、マリオの足が地に着くFにジャンプし続けると、縦スクロールしない。

<!--
* While being "stuck" by a noteblock, Mario can enter solid blocks, though he'll be crushed. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8815)
-->
* 音符ブロックにくっついてる間、横にあるソリッドブロックにめり込めるが、押し潰される。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8815)

<!--
* Mario can stick to a row of noteblocks without bouncing off of them if he runs across them at the right speed.
-->
* 横に並んだ音符ブロック列に適切な速さで突っ込むと、跳ねずに通り過ぎることができる。

<!--
* If Mario is moving fast enough (x-speed of 64-80), then Mario will be unable to jump. Any faster and his jump height will also be significantly higher than usual. [Gif](https://imgur.com/VrqY93y) - [Video](https://youtu.be/SYTSgrhPsgg?t=26m43s)
-->
* マリオのX速度が64-80のとき、ジャンプできない。これより速い速度のときは、通常より高いジャンプが可能。[Gif](https://imgur.com/VrqY93y) - [Video](https://youtu.be/SYTSgrhPsgg?t=26m43s)

<!--
* Mario can spinjump off of noteblocks if you press A on the frame that he actually bounces off.
-->
* 音符ブロックで跳ねるFにAを押すと、スピンジャンプで跳ねることができる。

<!--
* The top tile of tileset-specific lava can be used to push Mario into blocks. Interestingly, if Mario is big, it can also be used send him all the way through solid walls or solid floors without being crushed.
-->
* 洞窟溶岩の一番上のタイルはマリオをブロックの中に押し込む作用がある。デカマリオのとき、圧死せずに壁や地面を抜けられる。

<!--
* The left and right edges of tileset-specific lava are solid.
-->
* 洞窟溶岩の右側と左側はソリッド。

<!--
* Mario can swim in standard object lava so long as he doesn't swim too far into the top of the tile.
-->
* 洞窟溶岩はそのタイルの下側を泳げる。

<!--
* Mario's P-meter will not decrease while in water.
-->
* Pメーターは水中にいる間、減少しない。

<!--
* Layer 2 will not reset Mario's Y speed when he stands on it; this means, if you walk off of a Layer 2 platform, Mario will start falling much faster than he normally would.
-->
* レイヤー2はマリオのY速度をリセットしない。つまり、レイヤー2の足場から落下し始めると、通常より早い速度で落下し始める。

<!--
* When scrolling the screen, Mario will not interact with solid blocks; this can be used to pass through solid Layer 2 blocks if the horizontal scroll setting for them is set to something other than constant.
-->
* 画面をLRスクロールする時、マリオはソリッドブロックと相互作用しない。これにより、レイヤー2の横スクロール設定がConstant以外に設定されている時、レイヤー2のソリッドブロックを横から貫通できる。

<!--
* Mario can survive a few blocks under the bottom of levels.
-->
* Mario can survive a few blocks under the bottom of levels.

<!--
* Changing between powerups while Mario is offscreen will cause his transformation animation to be skipped. [Fix](http://www.smwcentral.net/?p=section&a=details&id=5780)
-->
* 画面外でパワーアップしたとき、変身アニメーションがスキップされる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=5780)

<!--
* Net punching while climbing can kill sprites other than the Climbing Net Koopas; the only requirement is that Mario and the sprite be on opposite sides of the fence, even if the sprite isn't actually "climbing" it.
-->
* 金網パンチは金網ノコノコ以外のスプライトも倒すことができる。これをするのに必要な条件は、マリオとスプライトが金網の反対側にいることである。

<!--
* Net punching will destroy extended sprites regardless of what side of the fence they're on.
-->
* 金網の裏表に関係なく、拡張スプライトは金網パンチで消える。

<!--
* Net punching can also hit blocks. When in front of the fence, the hitbox is to the top right of Mario; when behind it, it's to the top left.
-->
* 金網パンチはブロックを叩くことができる。マリオが金網の表にいる時、判定はマリオの右上に出現するが、裏側の場合は左上。

<!--
* The capespin timer isn't cleared inbetween rooms, so capespinning prior to entering a door/pipe will cause Mario to start the next room with a capespin. Normally this isn't very useful, but one advantage is that it applies to even diagonal pipes, which normally don't allow input for a brief period after being fired. Additionally, it can be used to enter and exit pipes while facing the opposite direction you normally would.
-->
* マント回転タイマーはルーム簡で保持される。マント回転しながらドアや土管に入ると、移動後に回転を再開する。通常これはあまり役に立たないが、発射後入力を受け付けない斜め土管からの出現時に使うことができる。さらに、土管の出入りの時に通常と逆を向くことが可能になる。

<!--
* When Layer 2 or Layer 3 is scrolling and has interaction, the relative Layer 2 position ($7E0026) gets added to capespins to handle interaction with between them. Normally, this resets back to Mario when it goes back to handle sprites and Layer 1, but if the game is frozen (via $9D), this doesn't happen, and the relative position keeps gets added repeatedly. This causes the cape hitbox  axis of Layer 2/3's movement during the freeze, hitting any blocks or sprites along the way. [More info](http://smwc.me/1228582)
-->
* When Layer 2 or Layer 3 is scrolling and has interaction, the relative Layer 2 position ($7E0026) gets added to capespins to handle interaction with between them. Normally, this resets back to Mario when it goes back to handle sprites and Layer 1, but if the game is frozen (via $9D), this doesn't happen, and the relative position keeps gets added repeatedly. This causes the cape hitbox  axis of Layer 2/3's movement during the freeze, hitting any blocks or sprites along the way. [More info](http://smwc.me/1228582)

<!--
* Mario can turn while flying by pressing X or Y to capespin.
-->
* 飛行中、XorY入力のマント回転で方向転換できる。

<!--
* Fast diving: Mario's flying "frame" will increase or decrease every time a direction is tapped, allowing his speed to increase faster than simply holding it down. With this in mind, you can rapidly press one direction to dive quickly or build big air faster.
-->
* ファストダイビング：飛行中、進行方向への入力で毎F速度が増減する。単純な押しっぱではなく、調整して入力することで、通常より早く最速になることができる。また、1F毎に進行方向へ入力すると、早くダイブの姿勢になり、ビッグエアを得られる。

<!--
* Air cancel: You can cancel an air catch through a number of ways, including spinning around, hitting a ceiling, or reversing your speed. If you manage to do this, it can be used to decrease the height given by an air catch (useful for tight passages), or it can be used to catch air while maintaining big air.
-->
* エアキャンセル(上昇キャンセル)：マント回転・天井に当たる・速度を反転させるなどのいくつかの方法で、上昇をキャンセルできる。エアによる上昇の抑制（狭い通路で有用）、ビッグエアの保持に使える。

<!--
* Infinite air catch: Based off the above, you can catch big air with a low X speed, use <+B to slow Mario down, and then reverse his speed to cancel the catch. This will give him a significant Y-speed boost while maintaining big air, which can then be repeated an infinite number of times. [More](http://smwc.me/617858) [info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#PerpetualAirCatch)
-->
* ∞エアキャッチ(無限上昇)：上記に基づくと、小さいX速度でビッグエアを得られ、<+Bを使ってX速度を小さくし、X速度を反転させると上昇キャンセルができる。この操作は大きいY加速を得つつも、ビッグエアを保持でき、さらに何回でも繰り返すことができる。[More](http://smwc.me/617858) [info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#PerpetualAirCatch)

<!--
* Mario can "stick" to ceilings if he catches air close enough to it. Simple hold the opposite direction to Mario's direction and he won't start to fall downward. Big air can also be maintained through this glitch.
-->
* 天井近くでエアをキャッチしたとき、天井に貼り付ける。単純にマリオの逆方向を入力すれば、落ちることはない。このバグをしている最中、ビッグエアは保持され続ける。

<!--
* Mario can regain flight after letting go of X or Y by pressing it again while he is moving downward and his takeoff meter (7E149F) is greater than 2.
-->
* Mario can regain flight after letting go of X or Y by pressing it again while he is moving downward and his takeoff meter (7E149F) is greater than 2.
-テイクオフメータ(7E149F)が3以上・XorYを押している・Y速度が負を満たすとき、再飛行が可能。

<!--
* If Mario is flying and takes a screen exit, he can regain flight in the next room in the same was described above.
-->
* 上記を満たしていれば、ルーム移動してからでも再飛行できる。

<!--
* Mario will not lose flight while climbing, nor after collecting a P-balloon, so long as he doesn't touch the ground. It should be noted that, in either case, Mario retains the extra hit from flight even while in that state.
-->
* バルーン状態やツタ・金網・ロープを掴んでいる間、飛行は維持される。ただし、バルーン状態で地面に触れたら飛行は解除される。飛行を維持している時に敵に当たると、バルーン状態や掴んでいる状態は維持したまま、飛行が解除される。

<!--
* Pressing both left and right at the same time while flying will act as if Mario is pressing just left, but will not affect his X speed.
-->
* 飛行中に左右同時押しをすると、<をおした時と同じ行動をとるが、X速度は変化する。

<!--
* L+R glitch: Holding down both the left and right directions at the same time while Mario has either a P-balloon or Lakitu cloud will boost Mario rightward at higher speeds than normal, even allowing him to force his way through solid objects without dying. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8771)
-->
* LRバグ(左右同時押し)：バルーン状態か雲に乗っている間に、左右同時押しをすると、右向きに通常より速い速度で進む。このとき圧死せず、ソリッドオブジェクトを通り抜けられる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8771)

<!--
* The timer for the P-balloon continues to decrement even while the game is frozen with $9D.
-->
* Pバルーンのタイマーは、$9Dでフリーズしている間も減り続ける。

<!--
* If Mario is holding a P-balloon and its slot is overwritten, by another sprite coming out of a block or by Yoshi swallowing it, then the P-balloon animation will remain forever and the player won't be able to control Mario, causing pratically a softlock. This can be avoided if Mario gets hurt, dies or touches a goal tape, for instance. [Video](https://youtu.be/aiJ4dDPdIQU?t=980)
-->
* バルーン状態のときにブロックからのスプライトの出現やYなどによってPバルーンのスロットが上書きされると、Pパルーンのアニメーションが維持され、プレイヤーはマリオを操作できなくなる。この状態は、ダメージをくらったり、死んだり、ゴールバーにふれると即座に解除される。[Video](https://youtu.be/aiJ4dDPdIQU?t=980)

<!--  
* The item in the item box can be released even while the game is frozen with $9D.
-->
* アイテムボックスのアイテムは、$9Dでフリーズしていても出すことができる。

<!--
* Shooting a fireball at a moving conveyor belt or rope slope will warp the fireball five blocks upward if the slope is moving downward, and ten blocks upward if it is moving upward. The opposite height changes will occur if the fireball hits the slope while moving downward in parallel with it.
-->
* ファイアを動くコンベアor動くロープ坂に当てると、上方にワープする。下向きに動く坂だと5ブロック分、上向きに動く坂だと10ブロック分ワープする。下向きに動く坂の場合、時々全く異なる所にワープする。

<!--
* Fireballs can pass through the corners formed by two diagonally placed blocks.
-->
* ファイアは斜めに配置された2つのブロック間を通過できる。

<!--
* Fireballs and silver P-switches can't kill sprites in slot #A or #B.
-->
* ファイアと銀Pは、スロット#Aor#Bのスプライトを倒すことができない。

<!--
* Mario can kill many sprites that would normally be unkillable by sliding into them, often resulting in a glitched death sprite. Similarly, you can also get some glitched sprites with star power, capespins, and quake sprites as well.
-->
* マント滑りで普通に殺せないスプライトを殺すことができ、表示がバグるスプライトもある。スター・マント回転・揺れスプライトでも似たことが可能。

<!--
* Grabbing a vine/fence or collecting a P-balloon while in the sliding state will cause the state to persist, meaning any sprites you touch will be instantly killed. The effect will end if you move horizontally in midair while not holding onto the fence. [Video](https://www.youtube.com/watch?v=puNUhG2j9Qg)
-->
* 坂滑り状態でツタや金網を掴んだりPバルーンを取ると、坂滑りが保持され、マリオに触れたスプライトは瞬殺される。この状態は金網などを掴んでいない時、空中で水平方向に移動すると解除される。[Video](https://www.youtube.com/watch?v=puNUhG2j9Qg)

<!--
* Killing a sprite by sliding into it will set the counter for the number of sprites Mario has killed with a star to 1. [Fix](http://www.smwcentral.net/?p=section&a=details&id=12574)
-->
* 坂滑りでスプライトを倒すと、スターのキルカウンターが1にセットされる。 [Fix](http://www.smwcentral.net/?p=section&a=details&id=12574)

<!--
* While the star power timer normally decrements once every four frames, freezing the game (via $9D) on a frame the timer is meant to decrement will cause it to decrease every frame while the game is paused.
-->
* スタータイマーは通常4F毎に1減少する。減少するFに（＄9Dで）フリーズさせると、フリーズ中、毎Fタイマー値が減っていく。

<!--
* The star's kill counter only resets if you come in contact with a sprite that uses default interaction while Mario doesn't have star power. This means you can start building the counter with one star, let it run out, then grab a second star to continue building the counter. [Fix](http://www.smwcentral.net/?p=section&a=details&id=12574)
-->
* スターのキルカウンターはスター状態に関わらない方法でスプライトと接触した時にのみ、リセットされる。1つ目のスターを使いきってから、2つ目をとれば、カウンターを引き継げる。 [Fix](http://www.smwcentral.net/?p=section&a=details&id=12574)

<!--
* Mario may be killed if he spinjumps on two sprites at the same time. [Fix](http://www.smwcentral.net/?p=section&a=details&id=6700)
-->
* 2体以上重なったスプライトでスピンジャンプをすると、ダメージをくらうことがある。 [Fix](http://www.smwcentral.net/?p=section&a=details&id=6700)

<!--
* Destroying a sprite via spinjump will stop Mario's vertical movement. Because Parakoopas and Super Koopas can be bounced off of even with an upwards Y speed, it's possible to reduce the height of a jump to as little as a few pixels using them.
-->
* スピンジャンプでスプライトを倒すと、垂直方向の動きがなくなる。パタパタとマントガメはマリオが上昇中でも踏めるので、ジャンプの高さを数ピクセルにまで抑えることが可能。

<!--
* If Mario's Y position is 14 pixels higher than a sprite in midair on the frame before Mario touches the ground, interacting with said sprite on the same frame he lands will cause him to bounce off the sprite as if he actually landed on top of it. Notably, this can be used to turn a spinjump into a normal jump. [Video](https://twitter.com/Kaizoman666/status/869397277370142720)
-->
* マリオが地面に着地する前のFに、マリオのY位置が空中のスプライトより14ピクセル以上高い時、着地と同時にスプライトに触れると、そのスプライトを踏める。スピンでこれを行うと、通常のジャンプのように跳ねる。[Video](https://twitter.com/Kaizoman666/status/869397277370142720)

<!--
* If Mario is big, ducking on the frame just before he turns upright after wall-running will cause him to clip into the wall.
-->
* 壁走り中のデカマリオが角で体を起こすFにしゃがむと、壁にめり込む。

<!--
* Mario can survive being crushed by the Layer 3 smashers by alternating A and B every frame.
-->
* レイヤー3の大木に潰されても、1F毎にA・Bを交互に押せば圧死しない。

<!--
* Mario will "stick" to the bottom of the Layer 3 smashers, making him fall slower if he touches them as they're poking out of the ceiling.
-->
* レイヤー3の大木より遅い速度で落下すれば、地面に着地するまで大木の底にくっつける。

<!--
* Mario can fly through Layer 3 smashers if he either dives into them at the right angle or gets pushed into them.
-->
* 右向きに突っ込むか押し込まれていれば、レイヤー3の大木の中で飛行していられる。

---

<!--
* Screen-scrolling while the Yoshi's House smoke sprite is onscreen will cause it to glitch out.
-->
* 画面内にあるヨッシーの家の煙スプライトは、スクロールするとバグる。

<!--
* Alternating directions every other frame while swimming with an item will cause Mario to appear as if he's holding the item on his back.
-->
* 水中で1F毎に左右を押すと、マリオがアイテムを尻に挟んでいるかのように見える。

<!--
* Touching a damaging object (e.g. muncher, spike) while swimming upward will glitch Mario's shrinking animation. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8753)
-->
* 水中で上昇中にダメージオブジェクト(ブラパ・トゲ)に触れると、マリオのチビ化アニメーションがバグる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8753)

<!--
* Capespinning or shooting a fireball while running up a wall will cause Mario to stop animating briefly. The abilities will also still behave as if he were horizontal.
-->
* 壁走り中にマント回転やファイアを出すと、走るアニメーションが止まる。これらの効果は、水平時と同じように作用する。

<!--
* Mario will decelerate significantly slower when sliding up a left-facing very steep slope than when he directly runs at it. This also happens with right-facing very steep slopes, though to a much lesser degree.
-->
* マリオは左向きのとても急な坂を坂滑りで登る時、減速具合が歩いて登る時より緩やかになる。右向きでも同様のことが起こるが、程度が小さい。

<!--
* If Mario finishes a capespin during the goal walk, the cape's hitbox will persist even after the spin at whatever position he stopped at.
-->
* マント回転しながらゴールバーを切ると、マント回転の当たり判定がゴールした瞬間の位置に存在し続ける。

<!-- 
* Capespinning below a horizontal level makes the cape try to hit the next row of blocks in the next screen. If a block is high enough in the next screen, then it can get hit. [Video](https://www.youtube.com/watch?v=ZAwkqZ8vjnI)
-->
* 水平レベルのマント回転は、次の画面の次の行に当たり判定を生じさせられる。ブロックが次の画面の十分高い位置にあるときに、叩ける。 [Video](https://www.youtube.com/watch?v=ZAwkqZ8vjnI)

---
---

<!--
# Yoshi-Related Glitches
-->
# ヨッシー関係のバグ(Yoshi-Related Glitches)

<!--
__(things requiring Yoshi)__  
-->
__ヨッシーを必要とする物事(things requiring Yoshi)__  

<!--
_148 recorded glitches, 127 of which are useful_
-->
_148個(127個有用)_  

<!--
* After mounting Yoshi, Mario can not be hit by enemies for a few frames. Only works with certain sprites, however. [More info](http://smwc.me/649544)
-->
* Yに乗った直後の数F、敵に触れてもヒットしない。ただし、一部のスプライトは例外でヒットする。[More info](http://smwc.me/649544)

<!--
* Keys and P-switches can still hit blocks while stuck to Yoshi's tongue.
-->
* Yの舌で掴んでいる鍵とスイッチでブロックを叩ける。

<!--
* Shells, throwblocks, and Goombas can still hit other sprites while stuck to Yoshi's tongue, so long as the sprite it's hitting is in a lower slot.
-->
* 甲羅・ブルブルブロック・クリボンをYの舌で掴んだ時、それらは下位スロットの別スプライトにヒットする。

<!--
* Spinjumping onto Yoshi will allow Mario to break turnblocks as if he is still spinjumping. If he has a cape, it'll also add the effects of the spinning cape as well.
-->
* マリオがデカの時にスピンジャンプでYに乗ると、クルクルブロックを壊せる。マント状態であるなら、マント回転の判定も追加される。

<!--
* You can grab items on Yoshi by landing on Yoshi and grabbing the item on the same frame. If the item is not a springboard, however, it must be in a lower sprite slot than Yoshi.
-->
* Yに乗ると同時にアイテムを持つと、アイテムを持ちながらYに乗れる。ジャンプ台以外でやる場合、アイテムはヨッシーより低いスプライトスロットである必要がある。

<!--
* If Mario grabs a shell, throwblock, or goomba on Yoshi, he'll be knocked off almost immediately as if Yoshi took damage. Note that this will not occur if the sprite is eat-canceled.
-->
* 甲羅・ブルブルブロック・クリボンを持ちながらYに乗ると、ダメージをくらったかのようにすぐ降りてしまう。ただし、これは食べキャンされたスプライトでやると起こらない。

<!--
* If Mario is running in the same direction as a shell while riding Yoshi, he can pass slightly inside the shell from behind without taking damage from it, until either the shell turns around or he passes far enough inside that he's considered to be in front of the shell.
-->
* Yに騎乗中、甲羅と同じ方向に走っていると、甲羅に後ろから少し重なってもダメージを受けることなく走り続けられる。これは甲羅が反転したり、マリオが甲羅の前に行きすぎない限り行える。

<!--
* Yoshi's fireballs can be destroyed by a capespin mostly regardless of the vertical between them and Mario; the only thing that generally matters is his horizontal distance from them.
-->
* ヨッシーの吐く火は、マリオの高さとずれていてもマント回転で大抵消せる。殆どの場合、水平距離のみ近ければ良い。

<!--
* Yoshi has an unusual hitbox that makes all standard clipping glitches have a significantly lower speed requirement. [More info](http://smwc.me/1025243)
-->
* Yは独自の当たり判定を持っていて、全てのクリッピングバグが通常必要とされる速度より小さい速度で可能。[More info](http://smwc.me/1025243)

<!--
* If Mario clips far enough into a wall and dismounts Yoshi there, the game may consider Yoshi to actually be inside the wall, causing him to climb up it. [Video](https://www.youtube.com/watch?v=5Nwcggojnds)
-->
* マリオが壁に十分めり込んだ状態でYを降りると、Yは壁の中にいると判定され上昇していく。 [Video](https://www.youtube.com/watch?v=5Nwcggojnds)

<!--
* If Mario is riding Yoshi in water while big, you can clip into the right side of blocks occasionally by just swimming into them.
-->
* 水中・デカの状態でYに乗っていると、ブロックに右側からめり込むことができる。

<!--
* While riding Yoshi, Mario can clip upwards through solid blocks by landing on an item near it.
-->
* Yに乗っている間、アイテムに乗り上げることでソリッドブロックを上向きに抜けられる。

<!--
* If a Yoshi is one tile below the top of a ledge, Mario can land on him if he clips far enough into the top of the block while Yoshi is bouncing upward.
-->
* Yが1タイル分下に位置していても、Yが一番跳ねた時ならば、床を貫通してYに乗ることができる。

<!--
* Landing on Yoshi at the right angle next to a solid block may clip Mario inside the block.
-->
* ブロックの隣にYがいる状態で、Yがいる方のブロックの角に着地すると、ブロックにめり込める。

<!--
* Landing on Yoshi while he's inside a springboard and immediately dismounting him will allow Mario to pick up the springboard.
-->
* J台に重なったYに乗ってすぐにAを押すと、J台を持ってYを乗り捨てられる。

<!--
* Jumping at the right angle onto a message box or light switch while riding Yoshi will "suck" Mario on top of the box, even if there is a solid block on top of it. He also won't be able to be crushed while on top of it, though you won't be able to get out otherwise.
-->
* Jumping at the right angle onto a message box or light switch while riding Yoshi will "suck" Mario on top of the box, even if there is a solid block on top of it. He also won't be able to be crushed while on top of it, though you won't be able to get out otherwise.

<!--
* If Yoshi ends up inside a block while Mario is riding him, you will be unable to move out of the block without jumping.
-->
* Yに乗っていながらブロックにめり込むと、ジャンプしない限りブロックから出られない。

<!--
* If Yoshi ends up inside a block without Mario riding him, he will "climb" the blocks upward until he reaches an empty block. This can occur as a result of growing Baby Yoshi inside the block, spawning a block on top of Yoshi, or clipping four pixels into the block and dismounting. [Video](https://youtu.be/5Nwcggojnds)
-->
* マリオに乗られていないYがブロック内部にいると、ブロックのないところまでブロックを登って行く。これは、ブロック内でチビYが成長したり、Yが4ピクセル以上ブロックにめり込んだ状態で乗り捨てられると起こる。[Video](https://youtu.be/5Nwcggojnds)

<!--
* If Mario is riding Yoshi, on the ground, and inside a solid tile, then for a few frames after jumping off Yoshi, Mario can jump a second time as if he were on the ground. This will not cancel a spinjump, instead just making the jump go higher.
-->
* マリオが地面に立ってYに乗ってソリッドブロックにはまったままYをスピンで乗り捨てて、数FのうちにBを押すと通常より高い乗り捨てが行える。

<!--
* Yoshi's swallow timer while he has a sprite in his mouth normally decreases once every frame. Freezing the game (via $9D) on one of the decrementing frames, however, will cause the timer to decrease every frame while the game is frozen.
-->
* Yの飲み込みタイマーは通常1F毎に減少する。減少するFに($9Dで）フリーズするとフリーズ中、タイマーは毎F減っていく。

<!--
* After eating enough berries, you can delay Yoshi's "laying" animation by not touching the ground for more than a frame. If you throw Yoshi in a hole before he lays it, the next-spawned Yoshi will lay it instead.
-->
* Yが十分な個数の木の実を食べたあと、1Fより長く地面に足を付けないことで、産卵を遅らせることが可能。産卵する前にYを穴に落としたら、次に現れるYが変わりに産卵する。

<!--
* The egg Yoshi lays can be used to hit blocks.
-->
* Yが産んだ卵でブロックを叩ける。

<!--
* While Yoshi is laying an egg, Mario won't interact with solid blocks, but solid sprites will still push him to the side during those frames. This can result in Mario being pushed into a wall with only a single sprite.
-->
* Yが産卵している間、マリははソリッドブロックと作用しないが、ソリッドスプライトはマリオを押す。これにより、マリオはスプライト1つで壁の中に押し込まれる。

<!--
* Similar to the above, while Yoshi is eating a berry, Mario won't interact with solid blocks, but solid sprites will still push him to the side during those frames. [Video](https://twitter.com/Kaizoman666/status/1054431665546842113)
-->
* 上記と同様に、Yが木の実を食べている間も、マリオはソリッドブロックと作用しないが、ソリッドスプライトとは作用する。[Video](https://twitter.com/Kaizoman666/status/1054431665546842113)

<!--
* If Yoshi eats a powerup as it's rising from a block, Mario will not actually be given any powerups.
-->
* ブロックから出てくる最中のパワーアップアイテムをYで食べると、パワーアップできない。

<!--
* Spinjumping onto Yoshi and then dismounting him the frame Mario lands will cause Mario to spinjump off of Yoshi, yet have the height of a regular jump off of him.
-->
* スピンジャンプでYに乗ると同時に降りると、スピンジャンプのままYを降りられ、通常より高く跳ねる。

<!--
* Yoshi's Y speed isn't cleared when mounted, nor when knocked off by enemies (though it is cleared if you press A to actually dismount). This can be used to manipulate his fall speed.
-->
* マリオが乗っている間、YのY速度は初期化されない。敵に当たった時も同様。初期化されるのはA入力で普通に降りた時である。これを利用すればYの落下速度を調整できる。

<!--
* Dismounting Yoshi on the frame he gets damaged will cause Mario to gain invincibility frames as normal without Yoshi running away.
-->
* ダメージを受けるFにYを降りると、Yが走ることなくマリオが無敵状態になる。

<!--
* If you land onto Yoshi after gaining flight without touching the ground, you can continue to fly while riding him, though the controls will be a bit strange.
-->
* 飛行状態でYに乗り、地に足をつけなければ、Yに乗ったまま飛行し続けられる。ただし、操作方法が通常と異なる。

<!--
* Yoshi can make a powerup count as two powerups if Mario grabs the powerup while it is stuck to Yoshi's tongue.
-->
* Yの舌で掴んでるパワーアップアイテムをマリオが取ることで、そのパワーアップアイテムを2回取得できる。

<!--
* Non-carryable sprites that get eaten by Yoshi are actually erased one frame prior to his tongue fully retracting, allowing you to pick up a second sprite if Yoshi's head passes by it. One well-known use of this is for quickly eating Pokey segments.
-->
* 持ち運べないスプライトがYに食べられる時、舌が完全に引っ込む1F前にそのスプライトは消える。その際、Yの頭が別のスプライトと重なっていれば、2番目のスプライトを舌で掴むことができる。よく知られた例として、サンボの高速食いがある。

<!--
* If Yoshi is despawned with a sprite in his mouth, that sprite will persist despite no longer "existing". It's impossible to despawn the sprite in this state, so the slot essentially becomes useless.
-->
* Yがスプライトを咥えたまま消えると、そのスプライトは現存しないが残り続ける。その状態のスプライトは消すことができず、スプライトがいたスロットは実質的に使えなくなる。

<!--
* If a sprite on Yoshi's tongue despawns before it is pulled into his mouth, the game will register that sprite as having been eaten, but will still respawn the original sprite. This can also be abused with shells to turn a single shell into many, or in a similar manner with powerups.
-->
* Yの舌につかまれたスプライトが咥えられる前に消えると、そのスプライトは食べられたと認識されるが、元のスプライトが再出現する。これを使えば、一つの甲羅を複数に増やせたり、同じパワーアップアイテムを複数回取得できる。

<!--
* Yoshi's tongue will have unusual interacting when crossing screen borders. When crossing offscreen, it will loop to the opposite side of the screen, allowing you to pick up items on the other side. When crossing onscreen, it will "compress" toward Yoshi. An interesting advantage of this is that jumping off Yoshi when it's compressed will let Mario grab the sprite as he's jumping off. Doing this at the bottom of the screen can potentially cause the sprite to register as having despawned before Mario grabs it, allowing you to duplicate the sprite.
-->
* Yの舌がスクリーンの両端を超えると変な効果がある。スクリーン外の場合は舌がスクリーンの反対側にループしてそこにあるスプライトを掴める。スクリーン内の場合は舌が圧縮されて舌が掴んでいるスプライトをマリオが下りた途端にすぐつかめたりする効果がある。ちなみにこれが画面の下端で発生したら、スプライトはマリオが持つ前に消えた状態に移行するためスプライトを複製することがある。

<!--
* Yoshi's tongue will have unusual interaction when Yoshi's body OAM is completely offscreen. Regardless of the direction he faces, the actual hitbox will occasionally be stretched far to the right in the same fashion as in the layer switch glitch.
-->
* Yの胴体のOAMが完全に画面外だと舌に変な接触判定がおかしくなる。向いている方向に関係なく、レイヤー変更バグと同じように実際の当たり判定が遥か右側に伸ばされることがたまにある。

<!--
* It's possible to duplicate sprites that remain on Yoshi's mouth by using the previous glitch to catch it while Mario kicks the sprite, in such a way that it reaches the despawn region. After that, the sprite will be in Yoshi's mouth and reappear in original position within the level. This technique can also be done if Mario jumps off Yoshi while he releases the tongue and goes offscreen with the sprite.
-->
* マリオがスプライトの消える領域まで蹴ったスプライトを前のバグを使ってYの舌でキャッチすると、スプライトを複製することができる。これによってスプライトがYに咥えられていると同時に元の出現位置にも再出現する。Yの舌を出してスプライトが画面外にいくようにYを乗り捨てて行うことも出来る。

<!--
* It's possible to duplicate sprites near a level entrance by sacrificing Yoshi. Because the spawn region when entering a level (-60 to +A0) is larger than the despawn region for sprites (usually -40 to +30), a sprite can be spawned in a slot and then immediately despawned, entering its index for the sprite load status table to $161A in the process. If Mario enters the level riding a Yoshi that then takes the sprite's slot, that Yoshi will inherit that loading index due to it not being reset during level load. If you then despawn that Yoshi, the game will think it's okay to respawn the original sprite... even if that original sprite is already on-screen, or has even already been permanently killed.
-->
* レベルに入ったときにYに騎乗しているとYを犠牲にしてスプライトを複製することができる。レベルに入ったときのスプライトの出現領域（-60から+A0）は消滅領域（大体-40から+30）より広いため、スプライトが出現したらすぐに消滅させられて、sprite load status tableへのインデックスを$161Aに登録できる。sprite load status tableへのインデックスはレベルのロードの際リセットされないため、Yに乗ったままレベルがロードされてYが消滅したスプライトの枠を乗っ取れば、インデックスも一緒に引き継ぐ。結果として、そのYが消滅したら元のスプライトがまだ画面上に存在しても、あるいはすでに倒されていても、改めて出現可能になる。

<!--
* Invisi-Yoshi: Spawning more than one Yoshi onscreen will cause all Yoshis other than the one in the **lowest** sprite slot to turn invisible and have unusual interaction. [Video](https://youtu.be/uXUHCyOL-AM)
-->
* 透明Y：レベル内でYを複数匹出すと、スロット番号が一番小さいY以外が透明化する。透明Yは普通とは異なる挙動を示す。[Video](https://youtu.be/uXUHCyOL-AM)

<!--
* Dismounting an invisi-Yoshi will cause Mario to warp to whatever its Y-position was when he mounted it. It should be noted that Invisi-Yoshi can still move for a few frames after jumping on him, and can also be sent running if touched with a thrown shell, meaning its Y-position (and where Mario warps) can be changed. Should also be noted that invisi-Yoshi can be landed on mid-fall.
-->
* 透明Yを降りると、透明Yに乗った位置のY座標に瞬間移動する。降りた時、透明Yを少し動かすことが可能。透明Yに敵スプライトが当たると走りだす。これらを利用して透明YのY座標を変えられる。また、落下中の透明Yに乗ることも可能。

<!--
* If Mario is riding a visible Yoshi when a second Yoshi hatches, Mario will be riding an Invisi-Yoshi but will retain his riding animation and will keep Yoshi's hitbox. He also won't be able to take damage from most enemies.
-->
* 可視Yに乗ってから2匹目のYが孵化すると、Yに乗っているアニメーションのまま、当たり判定のある透明Yに乗っていることになる。この透明Yはほとんどの敵からダメージを受けない。

<!--
* Dismounting a visible Yoshi in a level with more than one Yoshi spawned when entering the death zone underneath the level will cause Mario to warp to the next visible Yoshi's Y-position, and will receive the same effects described in the previous glitch. However, unlike the previous glitch, Mario will be unable to jump off this Yoshi.
-->
* 透明Yに乗ってから可視Yに乗り、デスゾーンで可視Yを乗り捨てると、透明Yの高さにワープし、前述のバグと同じことが起こる。ただしこの方法だと、透明Yから降りることができなくなる。

<!--
* While Mario is in the state described by the previous two glitches, Yoshi's will be unable to despawn from the level. This mean, if a Yoshi falls off the bottom of the level, it will not be despawned by the death zone, and will instead loop vertically all the way around the level. It should be noted, though, that it takes about 18 minutes for Yoshi to complete this loop.
-->
* 前2つのバグを起こすと、Yをそのレベルから消すことができない。つまり、Yを画面下に落とし、デスゾーンに侵入してもYは消えない。また、垂直方向はループするため、Yは18分ほどかけて落とし始めた時の同じ高さ(Y座標)に戻ってくる。

<!--
* When Mario is in the aforementioned "riding Yoshi" state, getting hit by a cluster or extended sprite will release Mario from the state, and will cause the visible Yoshi to start running. If he was riding an invisi-Yoshi at the time, he will still be riding that Yoshi. It's also worth noting that the visible will always start running at a slower speed than normal when hit by those sprite types.
-->
* -マリオが前述のY騎乗状態である時、クラスターか拡張スプライトに触れることで騎乗状態を解除して乗っている状態になり、可視Yが走りだす。これらのスプライトに触れる時、別の透明Yにも乗っていると透明Yに騎乗したまま。また、可視Yは通常より遅く走る。

<!--
* When there's more than one Yoshi spawned in a level, the eggs laid after eating enough berries will spawn at the Yoshi in the **highest** sprite slot. Because the visible Yoshi is always the **lowest** slot, this means it will end up laid by an invisi-Yoshi.
-->
* 同レベルに複数体のYが読み込まれている時、木の実を10個食べて生まれる卵はスロットが一番大きいYから出てくる。可視Yは常に低いスロットなので、産卵するのは全て透明Y。

<!--
* Killing the visible Yoshi will cause the next invisi-Yoshi to become visable; if Mario is riding this Yoshi, it will appear one tile below him, allowing him to fall through the ground. Also, if Mario is climbing when the Invisi-Yoshi becomes visible, he'll continue to climb despite riding Yoshi at the same time.
-->
* 可視Yを殺すと、次の透明Yが可視化する。もし透明Yに乗っている時に可視Yが消えると、透明Yがマリオの1タイル下に可視化して出現し、床ぬけができる。何かを掴んでいる状態でこれが起こると、掴んだままYに騎乗している状態になる。

<!--
* If the visible Yoshi is killed while it has an item in its mouth, the next visible Yoshi will spawn with a nonexistant null sprite in its mouth. When spat out, "nothing" will come out of Yoshi's mouth. [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#NullSprites)
-->
* 可視Yが口に何かを含んだ状態で死ぬと、次の可視Yは存在しないヌルスプライトを口に含んだ状態で出現する。それを吐き出しても、Yの口からは何も出てこない。[More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#NullSprites)

<!--
* Double-Tongue Glitch: If Yoshi spits out his tongue on the frame Mario transforms from a powerup, Yoshi will stick out his tongue twice, regardless of if he swallows anything. As an alternative, this glitch can also occur when taking damage while riding Yoshi without getting knocked off (by munchers/spikes, Wigglers, Dino Rhinos, etc.), in the next level after entering a vertical pipe (by sticking it out the frame Mario enters the pipe), or when Yoshi lays an egg. [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#NullSprites) - [Video](https://youtu.be/1SGfYkXoGjg?t=8m37s) - [Fix](https://www.smwcentral.net/?p=nmap&m=smwrom&u=0#01F0BA)
-->
* 舌2回出しバグ・二枚舌バグ：$9DでフリーズするFに舌を出すと、舌を2回出す。1回目に何かを咥えても2回出る。[More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#NullSprites) - [Video](https://youtu.be/1SGfYkXoGjg?t=8m37s) - [Fix](https://www.smwcentral.net/?p=nmap&m=smwrom&u=0#01F0BA)

<!--
* If Yoshi swallows a sprite on the first tongue of the above glitch and nothing on the second, he will end up with a null sprite in his mouth.
-->
* 上記のバグで、1回目の舌でスプライトを咥え、2回目の舌で何も咥えなかった場合、口の中はヌルスプライトになる。

<!--
* When doing the double tongue method of creating a null sprite, any sprite grabbed by the first tongue will no longer respawn, as if it was destroyed.
-->
* 上記の方法でヌルスプライトを作る時、1回目の舌で掴まれたスプライトはリスポンされることはない。

<!--
* If $019D (part of the stack) is a value from 00 to 0C and Yoshi has a null sprite in his mouth, then Yoshi will get wings or be able to stomp the ground based on $16F5 (score sprite high X position). You can manipulate this value at any time, allowing Yoshi to freely swap out powers.
-->
* $019D（スタックの一部）が00から0Cまでの値でヌルスプライトを含んだYは$16F5（スコアスプライトのhigh X position）の値次第で羽を生やしたり砂煙を起こしたりできる。$16F5はいつでも簡単に操ることができるためYの能力は自由に切り替えられる。

<!--
* If $019D (part of the stack) is the value 80 and Yoshi has a null sprite in his mouth, then Yoshi will act as having a key in his mouth and will be able to activate keyholes. [Video](https://youtu.be/ymxwjRuN-VQ)
-->
* $019D（スタックの一部）の値が80でYがヌルスプライトを咥えてる状態では、鍵をくわえているように動作する。したがって、鍵穴に反応させることが可能。[Video](https://youtu.be/ymxwjRuN-VQ)

<!--
* Powerup incrementation: Spitting out a null sprite while on a brown revolving platform will cause unintended effects; one common effect is increasing Mario's powerup status, even past the standard values. Collecting powerups in these additional sprites can have a number of differing effects, from crashing the game to giving you a goal sprite. [More info](http://tasvideos.org/forum/viewtopic.php?p=250970&sid=4b6fef50ca81972d546c027211b3d597#250970) - [Effects](http://pastebin.com/JKQ6iApB) - [Goal item data](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning) - [Video](https://youtu.be/zQFseooBPl0)
-->
* Powerup incrementation：ヌルスプライトを回転する茶色足場の上で吐くと、意図されない効果が発生する。効果の一つとして、マリオのパワーアップ状態の標準値を無視した加算がある。参照の追加スプライトをパワーアップとして取得すると、様々な効果があり、クラッシュしたりゴール玉をストックできたりする。[More info](http://tasvideos.org/forum/viewtopic.php?p=250970&sid=4b6fef50ca81972d546c027211b3d597#250970) - [Effects](http://pastebin.com/JKQ6iApB) - [Goal item data](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning) - [Video](https://youtu.be/zQFseooBPl0)

<!--
* Spitting out a null sprite as Mario mounts on Yoshi and lands on a Rotating gray platform whose slot is higher than Yoshi's causes a similar effect of the previous glitch. However, it corrupts $15E9 (Sprite index for the current sprite that is being processed). Therefore, the game can process the main sprite loop with an index much higher than #$0B, as high as #$7E depending on Yoshi's position. This can have innumerous effects, because every sprite table is read/written incorrectly during this frame. [Video](https://www.youtube.com/watch?v=052UZbhIgtI)
-->
* マリオがYに騎乗しながら回転する灰色足場スプライトに乗っているときにヌルスプライトを吐くと、前述のバグと似たような効果が生じる。$15E9（現在処理しているスプライトのインデックス）が破損し、メインスプライトのループが#$7Eなどの#$0Bより大きい値で実行される。これはYの位置に依存する。このFにそれぞれのスプライトテーブルがに不正に読み書きされるため、多数の効果がある。 [Video](https://www.youtube.com/watch?v=052UZbhIgtI)

<!--  
* The previous glitch can be used to corrupt $00CE, the pointer to level's sprite data. With correct values, we can spawn most sprites in the level based on the current joypad values, for example. [Video](https://www.youtube.com/watch?v=hOgU3Je7pjE)
 -->
* 前のバグでレベルのスプライトデータへのポインターである$CEを乱すことができる。例えば、コントローラーのボタン状態によってスプライトを出現させるように設定できる。[Video](https://www.youtube.com/watch?v=hOgU3Je7pjE)

<!--
* Null sprite overload: Spitting out a null sprite will glitch certain sprites' properties. Slot #3 will usually lose ground interaction, and slot #1 will usually either become burnable or change its interaction completely. [Mo](http://tasvideos.org/forum/viewtopic.php?p=250970#250970)[re](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#NullSprites) [info](https://youtu.be/g25UHjarSCY)
-->
* ヌルスプライトオーバーロード：ヌルスプライトを吐き出すと特定のスプライトの性質が変化する。スロット#3は地面判定がなくなり、スロット#1はファイアでコイン化するようになったり相互作用が完全に変化したりする。[Mo](http://tasvideos.org/forum/viewtopic.php?p=250970#250970)[re](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#NullSprites) [info](https://youtu.be/g25UHjarSCY)

<!--
* Burning a Yoshi (via overload) on the frame Yoshi's tongue timer ($14A3) is equal to #$0C will cause the coin spawned by burning him to turn into a sprite berry.
-->
* Yの舌タイマー（$14A3）が$0CであるFに（オーバーロードを使って）Yを燃やすと、コインが木の実スプライトに変化する。

<!--
* Unstepping a sprite: Hitting a sprite and swallowing it before it fully disappears will reset it to its initial state.
-->
* Unstepping a sprite：倒したり、飲み込んだりして、スプライトが完全に消える瞬間にそのスプライトは最初の状態にリセットされる。

<!--
* Swallowing a springboard at the same time Yoshi is bouncing off it will give him a large boost while bringing the spring with him. This boost can be extended by holding up and/or B, and can even go through solid blocks. It will also give the springboard a slightly glitched graphic when spat back out. [Video](https://www.youtube.com/watch?v=WOMcX1pycWo) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=4319)
-->
* ジャンプ台をYが咥えると同時に乗ると、咥えきるまでの間、上方向にブーストを得る。このブーストは上かB入力で大きくすることができ、ソリッドブロックを抜けられる。ジャンプ台を吐き出すと、表示が縮んだままで出てくる。[Video](https://www.youtube.com/watch?v=WOMcX1pycWo) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=4319)

<!--
* Eat-canceling an item: If Mario is hit off of Yoshi while an item is stuck to Yoshi's tongue, that item will be dropped off of it while retaining any properties it had while stuck to the tongue. This can allow for a variety of effects, including causing sprites to lose (some) vertical object interaction, moving normally immovable sprites, and more. [Video](https://youtu.be/1SGfYkXoGjg?t=8m05s)
-->
* 食べキャン：Yが舌でスプライトを掴んでいる最中に攻撃をくらうと、スプライトは舌で掴まれている状態を保持したまま、Yが咥える・食べる動作を中断(食べキャン)する。これにより、スプライトは通常とは異なる挙動を示し、オブジェクトに対する垂直方向の相互作用が失われたりする。食べキャンによって普通動かせないスプライトを動かすことができる。[Video](https://youtu.be/1SGfYkXoGjg?t=8m05s)

<!--
* If Yoshi has an item on his tongue and you jump off of him as he is about to despawn, the item on Yoshi's tongue will be eat-canceled and warp to Mario's position as he jumps, allowing him to pick up carriable items or doublegrab powerups (shells are an exception; Yoshi will instead bounce off of it). It will also be counted as a new sprite, meaning the original one will respawn as well. Note that Yoshi has to despawn before the sprite for this to work, as it's still stuck to his tongue until then.
-->
* アイテムを舌で掴んでいる状態のYを画面下で消えように乗り捨てると、アイテムは食べキャンされ、マリオのジャンプする位置に瞬間移動してくる。持ち運べるアイテムなら掴むことができ、パワーアップアイテムなら2個取得することになる。甲羅は例外で、Yが甲羅を踏んで跳ねる。瞬間移動したアイテムは新しいスプライトとして認識され、元のスプライトは再度出現する。


<!--
* Not only does an eat-canceled sprite lose damage interaction with Yoshi, its entire slot does as well, until the next time Yoshi sticks out his tongue.
-->
* 食べキャンされたスプライトはYとの当たり判定がなくなるだけでなく、再びYが舌を出すまで、食べキャンされたスプライトのいたスロットとの判定がなくなったままになる。

<!--
* Eat-canceled sprites won't interact with sprites in a higher slot than them.
-->
* 食べキャンしたスプライトはそれより大きいスロットにあるスプライトと作用しなくなくなる。

<!--
* If a shell is eat-canceled, the shell will fall through the ground when kicked. Additionally, eat-canceled shells won't knock Mario off of Yoshi, and can also be doublegrabbed without destroying each other.
-->
* 食べキャンされた甲羅を蹴ると地面を通りぬけ、Yに乗ったマリオも素通りする（が、Yの足に反応して踏まれる）。食べキャンされた甲羅同士は相互作用しないので、2個持ちができる。

<!--
* If a key is eat-canceled, sticking it in just below an inner corner will allow Mario to walk on the key through solid blocks, regardless of his powerup status. This can also be done with springboards, though Mario will be unable to pass all of the way through before being crushed.
-->
* If a key is eat-canceled, sticking it in just below an inner corner will allow Mario to walk on the key through solid blocks, regardless of his powerup status. This can also be done with springboards, though Mario will be unable to pass all of the way through before being crushed.

<!--
* If any carriable sprite is eat-canceled, throwing it upward while it's in a wall will cause it to slowly sink downward. It can still hit blocks as it's sinking.
-->
* 食べキャンされた持ち運べるスプライトを壁の中で上向きに投げると、ゆっくり沈んでいく。沈んでいく最中ブロックを叩く。

<!--
* Item swap: Mario can briefly create a null sprite on Yoshi's tongue by destroying or despawning a sprite while it is stuck to it (it should be noted that burning a sprite and collecting its coin, as well as grabbing a Koopa on Yoshi's tongue as it jumps into a shell, are both valid methods). Doing so will cause the next sprite to spawn in the null sprite's slot to warp to Yoshi's tongue. This can be used for a variety of effects, such as messing with sprites that change properties based on position, since this glitch essentially changes a sprite's spawn position. [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#ItemSwap)
-->
* アイテムスワップ：舌で掴まれているスプライトを倒すか消すことで、Yの舌の上にヌルスプライトは簡単に作ることができる。スプライトをファイアや銀Pなどでコインにして取ったり、甲羅に入るノコノコを舌で捕まえたりして行える。これを行うと、ヌルスプライトのスロットに次にスポンされるスプライトがYの舌にワープする。これにより、様々な現象を起こすことができ、スプライトの座標に基づいて性質を変えるといったこともできる。このバグのために、スプライトのスポンポジションを変える必要が出てくる。[More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#ItemSwap)

<!--
* Certain sprites have the "give powerup when eaten" flag set despite not being powerups, most notable of which being the Chucks. Depending on Mario's powerup status, using item swap to eat these sprites will give Mario odd sprites in the item box. Two particularly well-known uses are getting a goal sphere from a Clappin' Chuck when Mario has a fireflower, and getting a Lakitu cloud from Chargin' Chucks when small. [More info](http://smwspeedruns.com/index.php/Orb) - [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)
-->
* 特定のスプライトはパワーアップアイテムではないが、食べるとパワーアップするフラグが設定されている。アイテムスワップを使ってスプライトを食べると、マリオのパワーアップ状態に依存して変なスプライトをアイテムボックスに送ることができる。マリオがファイアの状態でその場で跳ねるブルを食べるとゴール玉が得られ、チビの状態でブルを食べるとジュゲムの雲が得られる。[More info](http://smwspeedruns.com/index.php/Orb) - [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)

<!--
* You can "store" an item swap on an Invisi-Yoshi's tongue by sticking a sprite onto a visible Yoshi's tongue before it's replaced by another Yoshi. When the invisible Yoshi becomes visible again, Yoshi's tongue will spawn with it and grab whatever sprite happens to be in the same slot as the one that you stuck to it before.
-->
* Yの舌でスプライトを掴んでいる時に、別のYを出現させて騎乗中のYを透明Yに変身させると、アイテムスワップをストアできる。透明化したYが可視化すると、掴んでいたスプライトを同じスロットにスポンさせ、ストアする前のように舌で掴む。

<!--
* If there is no sprite currently in the slot stored to the Invisi-Yoshi's tongue, then it will instead spawn a copy of the last sprite in the slot. Since this counts as a new sprite, it can be used to duplicate any sprite.
-->
* アイテムスワップがストアされた時のスプライトが現在存在しない場合、そのスプライトのスロットに最後に読み込まれたスプライトを代わりにコピーとしてスポンさせる。これは新しいスプライトとして認識されるので、あらゆるスプライトをダブらせることができる。

<!--
* If a sprite is stored to invisi-Yoshi's tongue, spitting out the visible Yoshi's tongue a few frames before it despawns will cause a second tongue to spawn on Invisi-Yoshi, resulting in a null sprite.
-->
* 可視Yが透明化する直前数Fの間に舌を出すと、2度目の舌が透明Yから出現し、それで掴まれたスプライトはヌルスプライトになる。

<!--
* After item swapping, sprites can then be eat-canceled off of Yoshi's tongue. Certain sprites that are never meant to be edible by Yoshi can create some unusual glitches as a result.
-->
* アイテムスワップ後、スプライトはYの舌で食べキャンされる。特定のスプライトはYで食べられなくなり、結果としていくつかのバグを引き起こす。

<!--
* If Yoshi starts to sink in lava while a sprite is stuck to his tongue, and that sprite is then destroyed, Yoshi will have a null sprite on his tongue and be able to perform an item swap. A difference between this and the normal item swap, however, is that the sprite will remain stuck to Yoshi's tongue while he's sinking, which can be combined with Yoshi's tongue interaction on screen borders to create a few interesting effects. The sprite will also be automatically eat-canceled when Yoshi disappears.
-->
* スプライトを舌で掴んでいるYが溶岩に沈んでいる最中にそのスプライトを消すと、アイテムスワップを行えるヌルスプライトを舌に作ることができる。これは通常のアイテムスワップと異なり、Yが沈んでいる最中、スプライトは舌に固定されたままとなる。これを画面の境界上で行うと、おもしろい現象を数個発生させられる。Yが完全に消えた時、スプライトは自動的に食べキャンされる。

<!--
* If a Yoshi is sinking in lava and another Yoshi is registered on his tongue (by getting a sprite on his tongue, despawning it, then spawning Yoshi in the same slot), and Yoshi is set to hatch an egg from berries, then standing on the ground so that this egg is spawned will freeze sprites as normal (through $9D) but Mario will still be able to move around.
-->
* 1匹目のYが溶岩に沈んでいき、（適当なスプライトを舌に絡めてから消し、同じスロットに新たなYを出現させるなどして）別のYが1匹目のYの舌に登録されて、Yが木の実によって産卵できる状態の時に、産卵するために着地するとスプライトは($9Dで)フリーズするが、マリオは通常通り動ける。[Movie](https://www.youtube.com/watch?v=wZK3xB6KHkE)

<!--
* When spawning a Yoshi from a block while another Yoshi is sinking in lava, Mario will still be able to move around during the new Yoshi's hatching animation. However, $9D will still be set (freezing other sprites in place), meaning any glitches resulting from it can still occur in this time.
-->
* Yが溶岩に沈んでいる最中に別のYをブロックから出現させると、孵化アニメーション中に乗り回すことができる。$9Dはセットされ、他のスプライトはフリーズしているので、$9Dを用いるバグを引き起こせる。

<!--
* Priority swap: If all sprite slots in division 1 are filled, then prioritized sprites such as the goal sprite will have to replace another sprite in order to spawn, and the sprite it replaces can manipulated by abusing priority through sprite permanence. In simple terms, priority sprites will replace the **highest** non-permanent sprite slot if all of them are filled. If that sprite happens to be stuck to Yoshi's tongue when the priority sprite spawns, the priority sprite will actually warp to Yoshi's tongue, even if it's a stationary sprite like a goal tape. [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#ItemSwap)
-->
* 優先スワップ：もし分割1の全てのスロットが埋まっていて、ゴールバーなどの他のスプライトと置き換わる優先スプライトが出現する時、どのような状態であれ、優先権によりスプライトが置き換わる。簡単に言えば、全てのスロットが埋まっている時に、優先スプライトが一番IDの大きい非残存スプライトのスロットと置き換わる。もしそのスプライトがYの舌上にあるときに置換が起こると、優先スプライトはゴールバーであれ、Yの舌上に出現する。[More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#ItemSwap)

<!--
* Eat-canceling a goal tape will set its max height to wherever it was dropped, which can lead to some strange side effects. That game still registers its original position as the actual sprite, so touching the goal tape below what would normally be the 1 star mark will actually give a glitched number of bonus stars, even greater than 50.
-->
* 食べキャンしたゴールバーはドロップされた瞬間、最も高い位置にセットされ、いくつか変な現象を引き起こす。ゲームはゴールバーの元の位置を実際の位置として認識するので、通常の場合にボーナススターが1得られるゴールバーの位置に触れると、ボーナススターの値がバグって50以上にもなる。

<!--
* If you item swap a sprite that uses extra bits (e.g. the goal tape) when Yoshi is in a higher slot than it, the sprite's extra bits will be modified. The game normally stores the extra bits with the sprite's high Y spawn position (in the format %----EE-Y) before correcting it in the sprite's initilization code; if Yoshi's tongue's code runs before the sprite's does, it will instead use the high Y position from the tongue, affecting the extra bits in the process. NOTE: this glitch will NOT work in hacks that use custom sprites, due to using a specialized table for extra bits. [More Info](http://pastebin.com/XBqrVHyH)
-->
* Yがより大きい番号のスロットにいてextra bitsを使うスプライト（例えばゴールバー）をアイテムスワップすると、extra bitsが変更される。これはextra bitsは普段スプライトのhigh Y positionと一緒に（%—-EE-Yのフォーマットで）一旦保存されてから、スプライト初期化コードであるべき場所に移されるためで、つまりスプライトのコードよりもYの舌の処理が起動すると代わりに舌のhigh Y positioが使用されてextra bitsに影響が出る。カスタムスプライトを使うハックではextra bitsに特別な情報に保存するからこのバグは起こらない。[More Info](http://pastebin.com/XBqrVHyH)

<!--
* Yoshification: For one frame after Yoshi despawns, the game will still manage his sprite slot as a Yoshi for one frame afterwards. If a new sprite spawns into his slot on that frame, then there can be a huge variety of effects based on how that new sprite uses its RAM tables that were previously managed by Yoshi. For instance, if it sets $C2 to 01 to spawn (which Yoshi uses as a "mounted" flag), then the game will think Mario is riding that sprite like a Yoshi and warp it to his position. Furthermore, when Mario goes to another room or level, he will suddenly spawn on a new Yoshi (who receives its palette and graphics page from whatever sprite was swapped). [More info](https://www.youtube.com/watch?v=2fLOZrQzDnQ)
-->
* ヨッシー化（Yoshification）：Yが消滅した直後の1Fは、そのスプライトスロットがYとして処理され続ける。このF内に別のスプライトが同じスロットに出現したら、そのスプライトが以前Yに支配されているRAMをどう使用するかによってありとあらゆる作用が発現する。例えば、Yが「乗られている」フラグとして使う$C2をスプライトが出現するために01に設定すると、スプライトがYのように乗られているとされてマリオの位置に瞬間移動させられる。また、別のレベルに移行するとマリオがスワップされたアイテムのパレットとグラフィックページを持つ新しいYに乗ったままレベルに入る。[More info](https://www.youtube.com/watch?v=2fLOZrQzDnQ)

<!--
* Stunning a sprite: If Mario spits out a sprite while its stun timer is set, it will spawn an extra sprite once its stun timer hits zero. While this is intended for sprites like the Koopa shell, it works for other sprites, as well. For example, P-switches can spawn a fish if Yoshi spits it out when it turns into a smoke cloud. [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#StunnedSprites) - [Video](https://youtu.be/1SGfYkXoGjg?t=11m04s)
-->
* スタンバグ（Stunning a sprite）：スタンタイマーがセットされたスプライトを吐くと、スタンタイマーが0になる時に新たなスプライトが出現する。吐き出されたスプライトは甲羅のように振る舞い、別のスプライトに作用する。例えば、Pスイッチが煙に変わる時にYがPを吐き出すと、Pスイッチからプクプクが出るような感じ。[More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#StunnedSprites) - [Video](https://youtu.be/1SGfYkXoGjg?t=11m04s)

<!--
* Spitting out a stunned Koopa shell on the frame its stun timer is about to run out will cause the Koopa spawned by it to be sent flying as if it were knocked out of the shell.
-->
* スタンタイマーが0になるFに甲羅を吐くと、裸ノコノコが甲羅から飛び出るように口から放たれる。

<!--
* Phase pointer manipulation: When a carryable sprite "normalizes" ($1558 reaches 01), $C2 for the sprite will be set equal to the value of $1540 rounded up to the nearest odd number. Because many sprites use $C2 as a phase pointer, this can cause garbage code to run, resulting in a large variety of possible effects. Although only a few sprites use $1558 naturally (such as the Pitchin' Chuck), it can also be set by having a sprite sink in lava and then using Yoshi to spit out the sprite shortly thereafter. [More info](http://tasvideos.org/forum/viewtopic.php?p=476091#476091)
-->
* 段階ポインター操作（Phase pointer manipulation）：持ち運べるスプライトが「通常段階」に戻る（つまり$1558が01に達する）と$C2が奇数まで切り上げた$1540の値に設定される。$C2を段階ポインターとして使うスプライトが多いため、これによってゴミコードに移ってあらゆる作用が発現する。$1558を通常の動作で使うスプライト（例えば野球ボールを投げるブル）は少ないが、溶岩に沈んでいくスプライトをYに吐かせることでも行える。[More info](http://tasvideos.org/forum/viewtopic.php?p=476091#476091)

<!--
* Yoshi can "store" a sprite slot in his mouth, but it gets a bit complicated. First, do the double tongue glitch and pick up a carriable sprite with the first tongue. Then, with the second tongue, pick up the sprite you want to stun, but eat-cancel it before Yoshi swallows it. As a result, Yoshi will have the second sprite slot "in" his mouth, but other sprites can still spawn in that slot and will function as normal. Yoshi can then spit out that sprite (resulting in a glitched version of it), or swallow it (resulting in the sprite vanishing).
-->
* Yはスプライトスロットを口にストアすることができるが、少々手間取る。舌2度出しバグで、1度目の舌で持ち運べるスプライトを掴み、2度目の舌でスタンしたいスプライトをつかんでから食べキャンする。結果的に、Yは2度目の舌で掴んだスプライトをスロットを口の中に保持するが、他のスプライトはそのスロットに読み込まれ通常通り動く。Yは咥えたスプライトをバグったスプライトとして吐き出すか、飲み込んで消失させられる。

<!--
* With the above glitch, you can also stun sprites that are normally unstunnable. You just have activate the sprite slot's stun timer and then spit it out of Yoshi's mouth while the timer is active. This can create a variety of effects, most notably a [Koopa Kid from a sliding blue Koopa](https://youtu.be/1SGfYkXoGjg?t=14m01s), a [goal tape (at x=0,y=0) from a Pokey](https://www.youtube.com/watch?v=dfn94RSdJr0), a [keyhole from a Dino Rhino](https://www.youtube.com/watch?v=ASE9ZXp_gdw), and a [Reznor from horizontally-swimming fishes](https://youtu.be/hboxJ_z-P7E?t=1m49s). [Video](http://youtu.be/GIA0xg0ZWuo) - [More Info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#StunnedSprites) - [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)
-->
* 上記のバグで、通常スタンしないスプライトをスタンさせられる。そのスプライトのスロットのスタンタイマーは稼働させることができ、タイマーが作動している最中に吐き出すこともできる。これで様々な現象を作り出せる。[スライディングしている青ノコノコからコクッパ](https://youtu.be/1SGfYkXoGjg?t=14m01s)・[サンボからゴールバー(x=0, y=0)](https://www.youtube.com/watch?v=dfn94RSdJr0)・[コライタから鍵穴](https://www.youtube.com/watch?v=ASE9ZXp_gdw)・[横に泳ぐプクプクからブイブイ](https://youtu.be/hboxJ_z-P7E?t=1m49s)などがある。[Video](http://youtu.be/GIA0xg0ZWuo) - [More Info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#StunnedSprites) - [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)

<!--
* When spit out of Yoshi's mouth, stored sprites begin acting like a shell, yet still retain the object interaction of the original sprite. This leads to some odd block interactions for certain sprites, such as Pokeys (five tiles higher) or Piranha Plants (one tile lower), and even affects block duplication for these sprites.
-->
* Yの口からストアされたスプライトを吐くと、甲羅のような働きをするスプライトが出てくるが、オブジェクトとの相互作用が元のスプライトのままである。これにより、一部のスプライトはブロックに対して変な相互作用を持つ。例えば、そのスプライトでブロックを叩くと、サンボが元の場合は5タイル分高い位置、パックンが元の場合は1タイル分低い位置にブロックが増殖される。

<!--
* Spitting out a stored sprite when its stun timer is nearly 0 will cause the sprite spawned from it to act as if it was spat out of Yoshi's mouth. For most sprites, this will make the sprite kickable as if it were a flopping fish, but it can have some odd additional effects on certain sprites.
-->
* ストアされたスプライトをスタンタイマーが0近くの時に吐き出すと、新しいスプライトが吹っ飛んで出てくる。大抵のスプライトは地上のプクプクのように蹴ることができるが、一部のスプライトは奇妙な効果がある。

<!--
* If a sprite gives special properties to Yoshi when in his mouth (e.g. blue or yellow shells/Koopas), then storing that sprite in Yoshi's mouth via the stun glitch will also inherit those properties to Yoshi until either the sprite gets overwritten or Yoshi swallows the storage. In the case of wings, the wing graphic will also not show up, nor will the flight sounds play.
-->
* Yに特性を与えるスプライト（青・黄色の甲羅/ノコノコ）が口の中にあって、スタンバグを通してそれらをストアすると、スプライトは上書きされるか、Yが飲み込むまで特性は引き継がれる。翼の場合、表示が見えなくなり飛ぶ音は再生されない。

<!--
* If Yoshi has a sprite stored in his mouth, and a Yoshi egg spawns into that sprite slot, then spitting out the egg on the same frame it spawns in will cause it to hatch with a green Koopa rather than a baby Yoshi. [Video](https://cdn.discordapp.com/attachments/167412470862970881/470363716613832734/koopinha-egg_00000.gif)
-->
* Yがスプライトを含んでいる間その枠に卵が出現した、ちょうどそのFの内に卵を吐くと、チビYの代わりに裸緑ノコノコが孵る。[Video](https://cdn.discordapp.com/attachments/167412470862970881/470363716613832734/koopinha-egg_00000.gif)

<!--
* If you kill a Yoshi and then spawn a second one, the new one will inherit the first one's "state" (sticking tongue out, laying an egg, etc.) that it had when it died.
-->
* Yが死んで、次のYがスポンされると、新しいYは前のYが死んだ時の（舌や卵などの）状態を受け継ぐ。

<!--
* If Yoshi has a key in its mouth, dying while riding will still let Mario enter any keyholes he passes on his way down.
-->
* 鍵を咥えているYに乗ったまま死に、死亡モーション中に鍵穴と重なれば鍵ゴールができる。

<!--
* If a keyhole is in a higher slot than a key, grabbing the key while it's stuck to Yoshi's tongue will allow the tongue to activate keyholes (even through walls). An easy method of doing this is by storing the key's slot to an invisi-Yoshi's tongue.
-->
* 鍵穴が鍵より大きいスロットにある時、Yの舌に掴まれている鍵をマリオが掴むと鍵穴に反応させられる。透明Yの舌で鍵のスロットをストアさせれば、簡単に行える。

<!--
* The previous glitch can be combined with the tongue behaviour when Yoshi is offscreen to the right, allowing the activation of distant keyholes. [Gif](https://i.imgur.com/UlCXq1h.gif)
-->
* 前述のバグは画面右外のYにおける舌の挙動と組み合わせられ、離れた位置にある鍵穴を作用させられる。[Gif](https://i.imgur.com/UlCXq1h.gif)

<!--
* Hitting a goal tape while a shell is stuck to Yoshi's tongue will make Yoshi act like he has a yellow shell in his mouth during the walk, regardless of what color the shell actually was.
-->
* Yが舌で甲羅を掴んでいる最中にゴールバーに触れると、黄色甲羅を咥えたような状態になる。甲羅の色は何色でもよい。

<!--
* If Yoshi has the stomp power from yellow shells and he lands on Layer 2, the smoke and quake sprites will not scroll with Layer 2 and will instead spawn at the position it would be at were Layer 2 not scrolling. This occurs both horizontally and vertically.
-->
* Yが黄色甲羅を含んでいる時に出せる砂煙と揺れは、レイヤー2オブジェクに着地する場合、レイヤー2のスクロールしていない設定位置で発生する。これは垂直方向でも水平方向でも起こる。

<!--
* The quake sprite from Yoshi's stomp power can wrap around the screen from left to right if Mario lands directly next to the screen barrier. [More info](http://smwc.me/1409196)
-->
* 黄色甲羅を咥えたYの着地時に出る砂煙は、画面横境界近くで発生すると画面左から画面右に瞬間移動する。[More info](http://smwc.me/1409196)

<!--
* If Yoshi eats a powerup as Mario dies, Mario will "revive" and bounce upward. The speed given varies depending on how far Mario is into the death animation when Yoshi swallows it.
-->
* マリオが死ぬと同時にYがパワーアップアイテムを食べると、マリオは飛び上がって復活する。上昇時の速さはマリオの死亡アニメーションに依存する。

<!--
* If the above is done when the time limit for the level reaches 0, the timer will also stay at 0 as if it was set to such when Mario entered the level.
-->
* 上記のバグを時間切れによる死で行うと、時間は0のままになる。その後、そのレベルでは元々時間が0に設定されていたように動作する。

<!--
* If Yoshi swallows a hundreth coin as Mario is dying, the game will register Mario as dying but will not decrease the life counter. This can be used to "survive" a game over; the game will still show the game over screen, but Mario will reappear on the overworld as normal.
-->
* マリオが死んでいる最中にYが100枚目のコインを取得すると、マリオは死んだと見なされるが、残機は減らない。これを使えば、ゲームオーバーの画面が表示されてから、OWに戻ることができる。

<!--
* Layer Switch Glitch: If Yoshi eats a powerup and transforms Mario as he is entering a pipe, Mario will stop entering the pipe and several different effects will occur. Mario will go behind Layer 1 and no longer interact with any sprites except Yoshi and platforms, and his climbing graphic will be glitched. Yoshi will be stuck in his "turning" frame, and while his tongue will still be able to interact with things, it will be invisible and he will be unable to duck. Thirdly, certain sprites which were not burnable before will become burnable, such as Yoshi, sprite coins, powerups, and the goal tape. The opposite is also true, with enemies such as Koopas and shells becoming unburnable. It should be noted that Mario can end up on an invincible Yoshi if he burns Yoshi while he's riding it.
-->
* レイヤー変更：マリオが土管に入っていく最中、Yがパワーアップアイテムを食べてマリオが変身すると、土管に入る動作が中断され、いくつかバグが引き起こされる。マリオはレイヤー1の後ろに表示され、接触判定のあるスプライトがYとプラットフォームのみとなり、金網等を掴んでいる時の表示がバグる。Yはマリオが変身した時の表示で固定されるが、舌は通常と同様に他スプライトを掴んだりできる。また、Yの舌は表示が透明になり、Yは舌を出す時に身をかがめなくなる。三番目に、特定のスプライトが不燃性から可燃性に変化する。例えば、Y・スプライトコイン・パワーアップアイテム・ゴールバーがある。逆に、ノコノコや甲羅といったスプライトがファイアでコインに変わらなくなる。乗っている最中にYをファイアでコインに変えると、無敵Yに騎乗できる。Yが2匹いるときにレイヤー変更をしてから、可視Yに乗ると同時にファイアを当ててコインにすると、無敵Yに乗った状態になる。

<!--
* If the layer switch glitch is done, Yoshi's tongue will interact strangely with other sprites at some frames, when the camera X position changes 16 pixels. Regardless of the direction that Yoshi faces, the tongue actual hitbox will be stretched to his right.
-->
* レイヤー変更状態の時、カメラのX位置が16ピクセル変わるFにおいて、Yの舌は他スプライトとの判定がおかしくなる。Yの向きに関係なく、舌の当たり判定が右側に発生する。

<!--
* If Mario is holding an item when he switches layers, the item will become stuck to Mario and he will be unable to let go of it, even if Y and X are released (this also means Yoshi can not be ridden). In addition, if Mario goes to another room, this item will be taken to that room as well, even if he enters through a door; it will appear at whatever position it was at when Mario exited the previous room.
-->
* アイテムを持ちながらレイヤー変更を行うと、アイテムがマリオに張り付いたままになる。XYを離してもアイテムは離れないため、Yに乗れなくなる。ルーム移動すると、持っていたアイテムは移動先に運ばれる。土管の出入りだけでなく、ドアでの移動でも起こり、アイテムの出現位置はドアに入ったときのマリオの座標に準拠する。

<!--
* If the layer switch glitch is done frame-perfect, Mario will retain sprite interaction and sprites will retain their correct properties, but Yoshi will still glitch and still go behind layers and have glitchy interaction while being ridden. In addition, in this state, if Mario picks up an item, it will be stuck to him as described above.
-->
* レイヤー変更を土管に入るFに行うと、マリオはスプライトとの接触判定を残したままで、スプライトは通常通り動く。Yのみレイヤー1の後ろに表示され、マリオが乗ると通常と異なる判定を持つ。この状態でマリオがアイテムを持つと、アイテムは手前側に表示されたまま、上記のように張り付く。

<!--
* If Mario is riding Yoshi as he comes out of a pipe downward, holding up will allow Mario to re-enter the pipe immediately.
-->
* マリオがYに乗った状態で下向き土管から出てくる時、上を押していれば土管にすぐ入り直すことができる。

<!--
* If Mario is riding Yoshi while big as he comes out of a pipe downward, and there is ground two tiles below the pipe, dismounting Yoshi on the first frame the player gains control will drop Yoshi into the ground.
-->
* マリオがデカでYに乗った状態で下向き土管から出てくるとき、地面が土管から2マス下にあれば、操作可能になるFにYを降りると、Yは地面を貫通して落ちる。

<!--
* Dismounting Yoshi repeatedly against a ceiling will let Mario move horizontally (albeit slowly) without moving vertically. This can be used to clip into upside-down slopes.
-->
* Yに乗った状態で、天井近くでA連打することで、垂直方向には移動せず、ゆっくりだが水平方向に移動できる。これを使って、天井の逆さ坂にめり込める。

<!--
* Riding a Yoshi into a Mode 7 battle will cause Mario's ground interaction to be one tile higher than it should be. In the Iggy and Larry battles, this doesn't cause any major problems, but in Roy's, Luwig's, Morton's, and Bowser's rooms, Mario will fall through the ground and die if he doesn't jump off.
-->
* モード7バトルにおいてYにに乗ると、マリオの地面との関係が表示より1タイル高くなる。イギー・ラリーのマップでは特に問題はないが、ロイ・ルドウィッグ・モートン・クッパのルームでは、Yから降りないと地面を素通りして落下する。

<!--
* When Yoshi eat-cancels a Pokey segment, its Y speed constantly increases, causing it to "bounce" if its dropped from a height of y=11 or higher. Yoshi can then eat this bouncing segment infinitely without it actually disappearing, and because it counts as a separate sprite, Mario can turn one Pokey into five individual sprites. Additionally, the segment slowly rises upward at a rate of 8 pixels per bounce, and after about two hours, it'll disappear from looping around the screen.
-->
* Yで（y=11以上にいる）サンボの体節を食べキャンすると、それのY速度が繰り返し上昇し、バウンドする。体節が消えるまで、何度でもYで食べることができ、それは独立したスプライトとして認識される。サンボ1匹から5個の体節に分けられる。体節はバウンドするたびに8ピクセルずつ上昇し、画面から消えても2時間ほどするとループして戻ってくる。

<!--
* If Yoshi's tongue comes into contact with part of a pokey while sprite slots are filled, then that part of the Pokey will just completely vanish without being counted as stuck to Yoshi's tongue. This allows Yoshi to very quickly erase the Pokey, as every frame his tongue is in contact with it will cause another segment to disappear.
-->
* スプライトスロットが埋まっている時に、Yの舌がサンボの一部に触れると、その部分はYの舌に掴まれることなく即座に消える。Yの舌は毎Fサンボの一部を消せるので、素早くサンボ全体を消すことができる。

<!--
* Holding both left and right at the same time while riding Yoshi will cause him to continously turn back and forth while moving rightward.
-->
* Yに乗っている最中に左右同時押しをすると、Yが前と後ろをと交互に振り向きながら右方向に移動していく。

<!--
* While riding Yoshi, Mario can slide up slopes by holding down and pressing left/right. This will also allow Yoshi to travel across purple triangles without bouncing upward.
-->
* Yに乗っていると、下と左右のどちらかを押すことで坂を登ることができる。これを使うと、ピンクの三角ブロックの上を跳ねずに移動できる。

<!--
* If Mario jumps off of Yoshi while he is eating Yoshi wings, Mario will still fly up to the Yoshi wings room without a Yoshi.
-->
* Yが翼を食べた時に乗り捨てていると、Yなしでマリオが上昇してYの翼ステージに移動する。

<!--
* While in the Yoshi wings room, opening Yoshi's mouth (to stick his tongue out, spit out an item, etc.) will cause his wings to temporarily disappear; you can't fly during that period, but you'll fall faster.
-->
* Yの翼ステージ内で、舌を出したりスプライトを吐き出したりして口を開けると、その間は翼が消える。落下速度は通常より速い。

<!--
* Taking Yoshi wings or obtaining a bonus game in a room that only uses secondary exits will take Mario to a glitched exit in the bonus game room rather than the room it's supposed to go to. Lunar Magic fixes this by default.
-->
* Secondary exitしかないレベルでYの翼を取ったりかボーナスゲームに行くと、正常な行先ではなくバグったボーナスゲームに移動してしまう。Lunar Magicはこのバグを自動的に修正する。

<!--
* If Mario is riding on a Yoshi that has a blue shell in its mouth and he slides off of a sprite platform, you'll be unable to control Mario's horizontal movement until he hits something and stops. [Video](https://www.youtube.com/watch?v=v2RjbDKKhVQ)
-->
* 青甲羅を咥えているYに乗っている最中、プラットフォームスプライトから滑り落ちると、何かにぶつかって止まるまで水平方向に操作できなくなる。[Video](https://www.youtube.com/watch?v=v2RjbDKKhVQ)

<!--
* When Yoshi has wings from a blue shell and the current level has some form of vertical scrolling enabled, the screen will always scroll upwards to Mario, even if he's not actually riding the Yoshi. This means it'll even scroll up to Mario if he only lands on the ground for a frame, which it normally doesn't do. This effect also persists if Yoshi despawns with the blue shell in his mouth, and will continue until a new Yoshi spawns or a new level is loaded.
-->
* レベルが垂直方向にスクロールができる設定で、Yが青甲羅を咥えて翼が生えている時、マリオがYに乗っていなくても、マリオに合わせて画面はスクロールする。つまり、マリオが地面に1Fしか足をつけない場合、通常はスクロールしないのにスクロールするようになる。これは青甲羅を咥えたYが消えるか、次の新しいYがスポンするか、新しいレベルが読み込まれるまで続く。

<!--
* If Invisi-Yoshi exists in a level, swallowing a blue shell with the visible Yoshi will allow flight but will not display wings or play the flight sound effect, nor will the screen automatically follow him vertically.
-->
* 透明Yが存在するレベルで可視Yが甲羅を咥えると、翼は表示されず、飛行音もなくなる。上記のバグについて、画面はマリオに合わせたスクロールではなくなる。

<!--
* If Mario is the "riding Yoshi" state on an Invisi-Yoshi and the visible Yoshi has a shell in its mouth, then the Invisi-Yoshi will receive the effects of that shell as well.
-->
* 可視Yが甲羅を咥えていると、各甲羅の効果が騎乗状態の透明Yにも出る。

<!--
* Landing on Yoshi counts as bouncing on a sprite. Jump off Yoshi enough without touching the ground and the next enemy you hit can give you a 1-up. [Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#01ED6D)
-->
* Yに乗ることは、スプライトを踏んだとしてカウントされる。Yに乗った瞬間AでYを離れることを繰り返してから、スプライトを踏むと1upできる。[Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#01ED6D)

<!--
* If Yoshi's tongue stops touching a berry after it gets stuck to his tongue/mouth (either by turning or ducking), the berry will be eat-canceled as a permanent sprite. This can also be done by baby Yoshi by turning on the frame he comes in contact with the berry, or by passing the berry while he's in the process of eating another sprite.
-->
* 方向転換やかがんだりし、一度触れた木の実からYの舌か口をずらすと、木の実が残存スプライトとして食べキャンされる。これはチビYが木の実と接触する同Fに振り向いたり、別のスプライトを食べている最中に木の実を通過することなどにより起こせる。

<!--
* If Yoshi runs into a berry on the same frame his tongue picks it up, the game will give two coins.
-->
* 木の実を食べる同Fに舌を出すと、コインを2枚得られる。

<!--
* You can "store" a berry to Yoshi's tongue by picking up a berry with Yoshi's mouth, but canceling it by sticking out Yoshi's tongue and turning away. You can tell if it was done correctly if the berry doesn't turn into a sprite, but the game still freezes for a frame as if Yoshi ate it. As a result, the next sprite Yoshi swallows will add to his berry count, and can be repeated on a single berry indefinitely. A small additional side effect is that any sprite berries will inherit the palette of the stored berry until it is used. [Video](http://youtu.be/Ses6MZfwpTg)
-->
* Yの口で木の実をピックアップすることで、Yの舌に木の実をストアできるが、Yの舌を出して振り向くことで飲み込むことをキャンセルできる。完璧にこれを行うと、木の実はスプライトに変わらないが、Yが実際に木の実を食べたかのようにフリーズする。結果として、Yが次にスプライトを食べると、木の実カウントが増加する。これは1つの木の実で何度でも行える。他の小さな変わった効果として、スプライト状態になった木の実は木の実がストアされるまで使われていたパレットを引き継ぐ。[Video](http://youtu.be/Ses6MZfwpTg)

<!--
* If Yoshi has a null sprite in his mouth, passing his mouth by a berry will cause him to store the berry to the null sprite (giving him a berry when he swallows). During certain frames of the swallowing animation, you can also actually eat the berry instantaneously as opposed to storing it.
-->
* Yがヌルスプライトを含んだまま口を木の実に重ねると、木の実がヌルスプライトに保存される。（つまり、それを飲み込むときに木の実として加算される。）飲み込むアニメーション中、木の実を保存せず一気に飲み込むFがある。

<!--
*  If a berry is located at the very bottom of a subscreen, then picking up the berry with Yoshi's mouth while he's ducking with his tongue out will cause the berry to register as eaten without actually clearing the tile. This can then be repeated infinitely.
-->
* 木の実がサブスクリーンの下端にある場合、Yがそれを舌を出したまま口で直接飲むと、木の実自体が消されずに「飲まれた」かのように加算される。これは何度でも繰り返せる。

<!--
* As with the cape, Yoshi's tongue below horizontal level will try to swallow berry tiles in the next row of blocks in the next screen. If a berry is high enough in the next screen, then it can be grabbed by the tongue.
-->
* As with the cape, Yoshi's tongue below horizontal level will try to swallow berry tiles in the next row of blocks in the next screen. If a berry is high enough in the next screen, then it can be grabbed by the tongue.

<!--
* Berries don't work correctly in vertical levels; they will treat the level data as if it were still in a horizontal format, which results in them not working at all past the top two screens of the level, and even on those screens the interaction point and actual berry will be disconnected, resulting in Yoshi eating berries out of nowhere (leaving behind a green bush tile in its place). [Fix](https://www.smwcentral.net/?p=section&a=details&id=15543)
-->
* 縦レベルの木の実は、正常に動作しない。木の実が横レベルのフォーマットとして扱われることが原因である。食べられたとしても、表示とYが食べる位置は異なる。[Fix](https://www.smwcentral.net/?p=section&a=details&id=15543)

<!--
* When Yoshi eats a berry by running into it, the game will adjust Mario and Yoshi's position slightly during the freeeze to center him on the block. If the berry is placed close enough to a slope, this can be used to clip them into the slope.
-->
* 移動しながらYが木の実を食べる時、ゲームはフリーズの間に発生するマリオとYの座標のズレを調整しようとし、ブロックにめり込むことがある。坂道に設置された木の実を使って、坂抜けすることもできる。

<!--
* Dismounting Yoshi while he's eating a berry will cause Mario to normal jump off instead of spinjump, despite still giving an X and Y speed as if he spinjumped.
-->
* Yが直接木の実を食べている最中にYを降りると、スピンではなく通常のジャンプになる。ただし、X速度・Y速度はスピンの時と同じとなる。

<!--
* In the Japanese version of SMW, Yoshi is able to eat the jumping dolphins. This is not possible in any other release.
-->
* 日本語版でのみ、Yは跳ねるイルカを食べられる。

<!--
* If a Baby Yoshi and adult Yoshi are spawned in the same level, Yoshi's head graphics will glitch and the game will have some strange effects. One effect in particular is that berries will not actually be eaten when Yoshi's head touches them; the game will keep registering him as eating it, but it will never disappear, letting you get an infinite number of berries.
-->
* YとチビYが同じレベルにスポンされると、Yの頭がバグる。影響の1つとして、Yの頭が木の実に触れても、木の実がなくならない。つまり、木の実を無限に食べられる。

<!--
* If both Baby Yoshi and Yoshi eat the same item, Yoshi can still spit out the item, but it will have glitched properties. Strange effects can also occur from two Baby Yoshis eating the same items. This can additionally be used to create a null sprite.
-->
* チビYとYが同時にアイテムを食べると、Yはそれを吐き出せるが、そのアイテムの性質が変化する。2匹のチビYが同時に同じアイテムを食べると、ヌルスプライトが生成される。

<!--
* If Baby Yoshi swallows multiple enemies consecutively, the game may register him swallowing an extra non-existant sprite; this can be used to grow a Baby Yoshi with only three sprites.
-->
* チビYが連続して敵を食べると、ゲームは存在しないスプライトを食べたと認識することがある。これにより、チビYをスプライト3体で成長させることができる。

<!--
* While Baby Yoshi is swallowing a shell, it's actually just temporarily moved to the background rather than having sprite interaction disabled. This means you can use it to kill climbing Net Koopas behind a net from the in front of it.
-->
* チビYに咥えられている最中の甲羅は、一時的にスプライトと相互作用しない背景に移動する。これを使うことで、マリオは表にいながらネットの裏側にいる網ノコノコを倒すことができる。

<!--
* If Baby Yoshi grows as he is eating a sprite, that sprite will be eat-canceled. This can also result as a side effect of eating multiple sprites consecutively, meaning, although you need at least three sprites for it, the last sprite may not actually be eaten.
-->
* チビYがスプライトを食べている最中に成長すると、そのスプライトは食べキャンされる。複数のスプライトを連続して食べ、成長させるには少なくとも3体必要だが、最後のスプライトが実際には食べられてない。

<!--
* If Baby Yoshi swallows a non-permanent sprite while far enough offscreen, the sprite will despawn as he is eating it. This will allow said sprite to be allowed to respawn even though it was used to feed Yoshi, making it possible to grow him with just a single enemy. Additionally, this effect can be used to item swap.
-->
* チビYが残存スプライトでないスプライトを十分画面外で食べると、そのスプライトは食べられている最中に消える。そのスプライトは再読込でリスポンするので、1匹の敵スプライトでチビYを成長させることができる。これはアイテムスワップにも使える。

<!--
* If Baby Yoshi grows close enough to a ceiling and Mario lands on the Yoshi while it's still next to it, Mario can jump straight off of Yoshi and through the ceiling (regardless of his size). Alternatively, you can be forced far enough into the ceiling such that Mario can clip through corners where the ceiling and left wall meet, retaining Yoshi in the process.
-->
* チビYが天井近くで成長してそれにマリオが乗れる時、（マリオのパワーアップに依存せず）乗った瞬間に乗り捨てることで天井抜けができる。また、天井近くのYで乗り降りを繰り返すことにより、左に進んでいき、左壁があるならば天井の角にめり込める。

<!--
* Spawning a throwblock will briefly set the high byte of its X position as the value at the address $(95 + sprite slot) for a frame. If a Baby Yoshi is at the same position within that screen, it will actually register the block and swallow it.
-->
* ブルブルブロックを持つと、それのX座標の上位バイトが1フレームだけアドレス$(95 + sprite slot)に代入される。もしチビYがブルブルブロックと画面が整数倍ずれた位置に存在すると、そのブルブルブロックを食べる。

<!--
* Baby Yoshi can swallow sprites as they're rising out of a block. If thrown at the right angle, Baby Yoshi can even hit a block and eat the sprite that comes out of it in a single throw.
-->
* チビYはブロックから出てくる最中のスプライトを食べることが可能。適切な向きでチビYを投げると、ブロックに当たると同時にスプライトを食べる。

<!--
* If a level has a no-Yoshi entrance and Mario dies in the level with a Yoshi, he'll keep the Yoshi when he exits to the overworld.
-->
* Yが入れないレベルでYに乗って死ぬと、OWにYを持ち越せる。

<!--
* If a level has a no-Yoshi entrance and Mario enters the level with a Yoshi, then mounts a new Yoshi in the level and dismounts him, he'll lose the Yoshi on the overworld as well. Beating the level without dismounting this new Yoshi will simply replace the original with it.
-->
* Yが入れないレベルにYに乗って入場し、レベル内で新しいYに乗ってから降りると、OWのYがいなくなる。新しく乗ったYから降りずにクリアすると、OWのYは新しいYに置換される。

---

<!--
* Mounting Yoshi on the same frame Mario takes damage will cause the game to register the damage without knocking Mario off Yoshi. This can be used to kill Mario while still riding the Yoshi.
-->
* Yに乗るにFにダメージを受けると、Yから降ろされることなくダメージ判定が起こる。これにより、Yに乗ったままマリオを殺せる。

<!--
* Mario can still get knocked off of Yoshi by sprites while in the sliding state, unless the sprite's clipping position is more than 13 pixels below Yoshi's when they make contact.
-->
* Yに乗ったまま滑っている状態でも、接触するスプライトの位置が14ピクセル以上Yのより下ではない限り、Yから落とされることは可能である。

<!--
* Having a Yoshi on the same screen as a Podoboo will glitch Yoshi's head graphics. His body can also be glitched by the splash created by lava.
-->
* Yとバブルが同じ画面内に存在すると、Yの頭の表示がバグる。マグマの飛沫が表示されると、Yの体の表示がバグる。

<!--
* When riding Yoshi, Mario will not interact with the bottom tile of a Banzai Bill.
-->
* Yに乗っていると、マグナムキラーの一番下のタイルの部分との当たり判定がなくなる。

<!--
* While turning on Yoshi, one of Mario's feet is non-existant and can be seen through.
-->
* Yに乗っている間、マリオの片足は表示されていない。

<!--
* Mario can still be knocked off of Yoshi by a Boo ceiling even when he has a star.
-->
* マリオはスター状態であっても、Yに乗っている状態で天井テレサに当たると、Yを降ろさせられる。

<!--
* While Yoshi is laying an egg, you can press X or Y repeatedly while riding him to play his tongue sound.
-->
* 乗っているYが産卵している間にXYを連打すると、その分舌を出す効果音がずれて再生される。

<!--
* Attempting to spinjump off Yoshi on the frame he lays an egg will cause the spinjump sound to play, but Mario won't actually dismount.
-->
* Yが産卵するFにスピンジャンプを試みても、スピンジャンプの音は再生されるが、Yからは降りられない。

<!--
* If you stick out Yoshi's tongue before Mario hits a goal tape, you can duck or stand up during the walk animation as long as it's out.
-->
* ヨッシーの舌が出ている最中にマリオがゴールバーに触れると、舌が出ている間はYをしゃがませたりできる。

<!--
* Yoshi can still duck or even spit out sprites during any period where the game is temporarily frozen from $9D (including keyholes).
-->
* Yは（鍵穴を含む）$9Dでゲームが一時的にフリーズしている間、しゃがんだりスプライトを吐き出すことができる。

<!--
* When spawning multiple Yoshis, the newest Yoshi will hatch twice as fast as the last-hatched Yoshi.
-->
* Yを複数出すと、一番新しいYが2倍速で孵化する。

<!--
* Taking damage on the same frame Yoshi hatches will cause Mario's shrinking animation to speed up.
-->
* Yが孵化する同Fにダメージを受けると、マリオの縮むアニメーションが早くなる。

<!--
* If Mario dies on the same frame Yoshi hatches, the game will continue to function as Mario is dying, rather than freezing as normal. This can lead to some strange effects such as Mario freezing mid-fall, remounting Yoshi even as he dies, or dying a second time due to an enemy or time up.
-->
* Yが孵化する同Fに死ぬと、ゲームはフリーズしないで通常通りに動きつつ、死亡アニメーションが続行される。これはいくつか変な現象が発生し、死亡落下中Yに乗り降りができたり、敵に当たる・タイムアップなどで2度死ねる。

<!--
* Yoshi's tongue turns invisible while entering a pipe, but will still pull sprites around. However, it will behave strangely as a result of the tongue not actually being drawn.
-->
* Yの舌を出しながら土管に入ると、舌の表示が透明に変わり、舌は判定位置が狂いながらもスプライトを掴める。

<!--
* If Mario dies on Yoshi while Yoshi has his tongue out, Yoshi's head may briefly loop to the top of the screen when they fall off the bottom of the level.
-->
* マリオが舌を出しているYに乗りながら死に、レベルの底に落ちていくと、Yの頭の表示が少し画面上部にループする。

<!--
* Yoshi can lick the brown revolving platform by sticking his tongue out to the right side of its base. It won't actually do anything besides make a noise, though.
-->
* 茶色の回転足場の付け根の右側をYの舌で舐めることができる。効果は音が鳴るだけ。

<!--
* Yoshi can lick the side-exit-enabled sprite by licking the center of the screen, three tiles from the bottom. It won't actually do anything besides make a noise, though.
-->
* 画面の下端より3タイルほど上、画面の中央辺りにヨッシーの舌を当てることでside-exit-enabledスプライトを舐めることができる。効果は音が鳴るだけ。

<!--
* If Yoshi eats the directional coin sprite, the music will never change back.
-->
* Yがコントロールコインを食べると、音楽が戻らなくなる。

<!--
* Occasionally, eat-canceled berries may take the place of powerup graphics.
-->
* 時々、食べキャンされた木の実のグラがパワーアップアイテムに入れ替わる。

<!--
* Collecting a green berry after the music speeds up from time running out will increase the timer while keeping the music at its speed; the effect can then be repeated indefinitely. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4938)
-->
* 緑色の木の実を使って、タイムを100以上から99以下に何度もすると、その度に音楽が早くなっていく。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4938)

<!--
* If Yoshi's head eats a green berry while Yoshi is ducking and sticking out his tongue, his head's graphic will glitch slightly.
-->
* 緑の木の実を食べる時に舌を出すと、Yの頭の表示がバグる。

<!--
* If Baby Yoshi is eating a sprite offscreen, turning while carrying an item in a higher slot than him will cause the sprite's tilemap to mess up.
-->
* チビYが画面外でスプライトを飲み込んでいる間、そのYよりスロット番号の大きいアイテムを持ちながら向きを変えるとスプライトのタイルマップが化ける。

---
---

<!--
# Item and Object Glitches
-->
# アイテムとオブジェクトのバグ(Item and Object Glitches)

<!--
__(Carryables and blocks)__  
-->
__持ち運べるアイテムとブロック(Carryables and blocks)__  

<!--
_118 recorded glitches, 104 of which are useful_
-->
_118個(104個有用)_  

<!--
* Items can get stuck in walls, and will spasm while inside.
-->
* アイテムは壁の中に押しこむことができ、壁中のアイテムは痙攣する。

<!--
* Items stuck in walls can be moved around by scrolling the screen on the right frames.
-->
* 壁中で痙攣しているアイテムは、$9Dでフリーズする度にずれていく。正確なFで行えば、任意の方向にずらしていける。

<!--
* Items can be forced through solid blocks by entering it far enough before releasing. [Video](https://www.youtube.com/watch?v=YkyZZiAAR2o)
-->
* アイテムをソリッドブロックに充分めり込ませて離すと、貫通させられる。[Video](https://www.youtube.com/watch?v=YkyZZiAAR2o)

<!--
* If an object is tossed high enough off the top of the screen, it will despawn.
-->
* If an object is tossed high enough off the top of the screen, it will despawn.

<!--
* Items will not interact with blocks if they are 8 or more pixels offscreen on the left side or 12 or more pixels offscreen on the right. When even a pixel offscreen on the left, the hit animation will also not appear.
-->
* アイテムは左側が8ピクセル以上または右側が12ピクセル以上画面外にあるブロックに作用しない。ブロックの左側が少しでも画面外にあると、ヒットアニメーションが表示されない。

<!--
* Items can fall through slope corners if they're moving fast enough at the right angle. Shells can also do this occasionally just by riding up the slope.
-->
* 充分な速度で移動している最中にアイテムを坂の角で離すと、通り抜けることがある。甲羅の場合、通り抜けずに坂の上に乗り上げることがある。

<!--
* Taking a pipe exit to a normal entrance while holding onto an item will cause Mario to release the item upon entering the level, spawning it at whatever position the pipe exit was in the previous one.
-->
* アイテムを持ったまま土管に入り、出口が土管でないレベルに移動すると、土管に入り終わった時の座標にアイテムが出現する。

<!--
* Double-grabbing: Mario can pick up two items at once if they're the right distance apart. Due to oddities in the way springboards are handled, you can grab more sprites at the same time if at least one of them is a springboard. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4252)
-->
* 2個持ち：適度に離れた2つのアイテムを一度に持つことができる。ジャンプ台は他のアイテムと性質が異なるため、ジャンプ台複数個とジャンプ台以外のアイテム（多くて2個）で同時持ちできる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4252)

<!--
* Although shells, throwblocks, Goombas, and Bob-ombs usually kill each other when doublegrabbed (unless they're eat-canceled), they can safely be held together if Mario enters a pipe at the same time. They will kill each other on exit, however.
-->
* 甲羅・ブルブルブロック・クリボン・ボム兵などを食べキャンされていない2つで同時持ちしようとすると、相殺するが、同時持ちするFに土管入ると、相殺を防ぐことができる。しかし、結局移動後に相殺する。

<!--
* Shells, throwblocks, Goombas, and Bob-ombs can actually overlap without killing each other, so long as they have zero Y speed and aren't in a carried/kicked state. The easiest way to do this is by placing one on top of a tile, then dropping the other into the tile so it gets pushed on top. Once overlapping, the sprite in the lower slot can be recovered by grabbing it while facing away from the other sprite.
-->
* 甲羅・ブルブルブロック・クリボン・ボム兵はY速度が0かつ持たれたり蹴られている状態でなければ、相殺せずに重なることができる。片方を1タイル上に乗せて、もう一方をそのタイルに押し込んで持ち上がらせることで、簡単に行える。一度重なっても、下位スロットのスプライトはもう片方のスプライトの反対側から掴むことで取ることができる。

<!--
* Items can also be carried while Mario has a P-balloon by grabbing both on the same frame.
-->
* Pバルーンとアイテムに同時に触れると、風船状態でアイテムを持ち運べる。

<!--
* Items can be carried while climbing, sliding, or flying by simply grabbing the item without getting off, jumping, or stopping flight. Note that the one exception to this rule is the moving rope mechanism, which Mario will fall off of when grabbing an item. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4252)
-->
* ツタや金網を掴んでいる最中、坂を滑っている最中、飛行中などにアイテムに掴むと、動作を続けながら持ち運べる。動くロープ中にアイテムをとると、アイテムを掴みロープを離す。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4252)

<!--
* Carried sprites won't actually flip to the other sides of nets with Mario, but the game will still let him hold it through the fence.
-->
* 持ち運ばれているスプライトはマリオと一緒に金網の裏側に行くことはないが、掴まれたままである。

<!--
* Items can be released while flying without stopping flight by letting go of Y for a single frame some time after catching air.
-->
* 物持ち飛行中、上昇後の数F間の1FだけX(Y)を離すと、アイテムを離して飛行を維持できる。

<!--
* If Mario gets between two solid carryable sprites and a wall, he will be pushed into the wall and be crushed. If you're big, it's also possible to spinjump through the floor before he dies.
-->
* マリオが2つの持ち運べるソリッドスプライトと壁に挟まれると、壁に押し込まれ潰される。もしマリオがデカなら、死ぬ前にスピンジャンプをすることで床抜けができる。

<!--
* Mario can jump through ceilings while big if he stands on two solid carryable sprites while they are close enough to said ceiling. Alternatively, you can use Yoshi and a single solid sprite for the same effect. This can also be done while small and with just a single key or springboard if they are moving upward toward the ceiling as Mario lands on it.
-->
* 2つの持ち運べるソリッドスプライトが天井に充分近い位置で、それの上にマリオが乗っている時、ジャンプで天井を抜けられる。Yに乗っていれば、1つのソリッドスプライトでもできる。天井近くまで上昇する鍵かジャンプ台に乗ることでも行える。

<!--
* If Mario is big, landing on a key close to the ceiling will cause his head to enter the ceiling enough to push Mario leftward, even through solid walls.
-->
* マリオがデカで、天井に近い高さにある鍵に乗ると、頭が天井に入りマリオが左向きに押される。

<!--
* Mario can enter through doors and pipes while he is standing on any solid sprite.
-->
* ソリッドスプライトに乗っている間、ドアと土管に入ることができる。

<!--
* Any of the solid carryable sprites are able to damage a Pokey on the frame they are thrown.
-->
* どの持ち運べるソリッドスプライトでも、投げるFはサンボにダメージを与えられる。

<!--
* Keyjump: Mario can land on and jump off of a key while it is in midair. Note that if the key is falling too fast, this glitch may not be possible. [Video](https://youtu.be/V9447JWXzaU)
-->
* 鍵ジャンプ：マリオは宙に浮いている鍵に乗り、持ってジャンプできる。鍵の落下速度が大きいと、できなくなる。[Video](https://youtu.be/V9447JWXzaU)

<!--
* If two keys are spawned at the same time, only the key in the **lowest** sprite slot will be able to interact with keyholes.
-->
* 2つ以上の鍵がスポンしている場合、鍵穴に反応するのはスロットIDが一番小さい鍵のみ。

<!--
* If Mario is standing on two keys at the same time, he will be unable to jump until he gets off of one.
-->
* 重なっている2つの鍵の上に立つと、ジャンプができなくなる。

<!--
* Mario is unable to walk in a one-tile space below keys, even if he's small or ducking.
-->
* 鍵の1タイル下のスペースは、マリオがチビでもしゃがんでも通り抜けられない。

<!--
* P-switch jump: Mario can land on and jump off of a P-switch on the first frame he hits the top of it. [Video](https://www.youtube.com/watch?v=ThUu-lWmuiQ) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=4330)
-->
* Pジャンプ：Pスイッチを踏むFにジャンプできる。[Video](https://www.youtube.com/watch?v=ThUu-lWmuiQ) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=4330)

<!--
* Carrying a silver P-switch through a pipe will make it act like a blue P-switch in the next room. Note that if another sprite in a lower slot is doublegrabbed on top of the silver P-switch, this glitch will not take effect. [Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#02AC18)
-->
* 銀Pスイッチを持って土管でルーム移動すると、効果が青Pスイッチに変化する。銀Pスイッチより下位のスロットのスプライトと2個持ちして土管移動すると、このバグは起こらない。[Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#02AC18)

<!--
* If a pressed P-switch despawns before it disappears in a cloud of smoke, then the switch will respawn as if it was not pressed.
-->
* 潰れたPが煙になって消える前に、画面下などで潰れた状態のまま消すと、潰れてないPが再び出現する。

<!--
* Mario will still bounce off of a springboard even if it moves out from beneath him.
-->
* ジャンプ台に一度乗れば、マリオはジャンプ台から離れてもジャンプする。

<!--
* Springboards will disable Mario's interaction with both blocks and sprites while he is stuck on it, allowing him to fall through corners or platform sprites. You can also be pushed through ceilings due to this, if Mario throws up a springboard and is able to land on it as it is rising. This can most easily be done in any 2-3 tile high space. [Video](https://www.youtube.com/watch?v=8u0aCd83jso)
-->
* ジャンプ台に乗っている間、マリオはブロック・スプライトを貫通できる。足場スプライトを通り抜けたり、ブロックの角にめり込めたりする。もし投げ上げたジャンプ台に乗ることができたら、マリオもジャンプ台と共に上昇する。これは高さ2-3マスが一番やりやすい。[Video](https://www.youtube.com/watch?v=8u0aCd83jso)

<!--
* If Mario is big and standing up, he'll be unable to jump through the bottoms of springboards. If he's small, ducking, or riding Yoshi, however, this won't happen.
-->
* マリオがデカの時、ジャンプ台を通過することができない。チビ・しゃがんでいる・Yに乗っている時は通過できる。

<!--
* Sprites do not clear the miscellaneous table at $15AC on initialization, which results in it being carried by sprites if they occupy the same sprite slot. Most sprites don't use $15AC for anything noticeable, but notably, shells don't interact with the sides of blocks when set, which means you can prevent a shell from being "pushed aside" on spawn if it's spawning inside a solid block (see [this video](https://cdn.discordapp.com/attachments/167412470862970881/482284837659607041/turn_timer_transfer.gif)). Note: Fixed by default by all sprite tools.
-->
* スプライトの初期化ルーチンで$15ACは無視されるから、同じスロットに出現するスプライトが既存の値をそのまま引き継ぐ。$15ACを目立つようなことで利用するスプライトは稀だが、甲羅でこれが設定されているとブロックの側面と相互作用しないからソリッドブロックの中に出現する甲羅が横に押しのけられることを防げる（[Video](https://cdn.discordapp.com/attachments/167412470862970881/482284837659607041/turn_timer_transfer.gif)参照）。全てのspritetoolはデフォルト設定でこのバグを修正する。

<!--
* If a shell is spinning in a one-tile space, it will become invincible to all quake sprites (including capespins, Yoshi stomps, and hit blocks) until it exits the space.
-->
* 甲羅が1タイル分のスペースで回転している場合、全ての揺れスプライト（マント・Yの砂煙・ブロック）に反応しなくなる。

<!--
* If a carryable sprite touches lava for only a single frame (e.g. by throwing the sprite upwards on that frame), it will resulting in $1558 being set for the sprite without killing it. This can have a number of effects on the sprite depending on how it uses $1558; for instance, a Koopa shell will suddenly have a Koopa inside it. On the frame a shell touches the lava, Mario can also bounce off of or be damaged by it as if it were a normal Koopa, as well.
-->
* 持ち運べるスプライトを洞窟の溶岩に（触れたFに上投げするなどして）1Fだけ触れさせると、スプライトは死なずに$1558がセットされる。スプライトの$1558をどう使うかに寄って、様々な現象が起こる。例えば、甲羅が洞窟の溶岩に触れると、中身がセットされて通常のノコノコに戻る。

<!--
* You can perform the above glitch with other carryable sprites by getting said sprite in slot #1 and overloading it. This will have some odd effects on the sprites when they're reset, such giving a key wings or changing a P-switch into a gold switch (acts like a blue switch, though).
-->
* 他の持ち運べるスプライトもスロット1にロードしてから上書きすることで前のバグを実行できる。これによってリセットされるスプライトにさまざまな奇妙な副作用がある。例えば、鍵に羽が生えたり、Pスイッチが黄色になったり（ただし機能に変化なし）することがある。

<!--
* Mario can throw a shell up even as a Koopa is entering it, allowing him to effectively move Koopas throughout the level. Note that red and blue shells will invert their speed when the Koopa actually spawns. Similarly, if Yoshi eats a shell as a Koopa is entering it, spitting it out before its stun timer hits zero will still have the Koopa jump out of it.
-->
* ノコノコが甲羅に入ろうとしている間も甲羅を上投げできる。これはノコノコを移動させる有用な方法になる。赤と青の甲羅の場合はノコノコに変身したとき横速度が反転する。また、Yがノコノコの入ろうとしている甲羅を食べてそのスタンタイマーがゼロになる前に吐きだすと、ノコノコは何もなかったかのように甲羅から出てくる。

<!--
* If you restun a shell with a Koopa inside (by way of capespin/block hit/etc) just as the Koopa jumps out, the shell will end up restunning with another Koopa still inside, resulting in two Koopas overall.
-->
* 中身入りの甲羅からノコノコが飛び出ると同時に（マント回転やブロックなどで）甲羅を攻撃すると、甲羅は別のノコノコを内部に生じさせて跳ね上がる。結果として2体のノコノコが生じる。

<!--
* Portable disco shell: If a Koopa enters a shell, releasing or throwing the shell upward on the frame the Koopa would normally appear will cause the Koopa to disappear and retain its shell form. If the Koopa that entered it was yellow, though, then throwing this shell will turn it into a disco shell.
-->
* 持ち運び無敵甲羅：裸ノコノコが甲羅に入って、当たり判定が発生するFにその甲羅を上投げすると、中のノコノコが消え、甲羅は元の状態のままとなる。ただし、黄色甲羅でこれを行ってから横投げしたり蹴ったりすると、無敵甲羅になる。

<!--
* Repeating the portable disco shell glitch with the same shell 255 times will cause the next yellow Koopa to enter the shell to get rejected immediately from it as if it were knocked out of the shell.
-->
* 持ち運び無敵甲羅のバグを255回繰り返した後、次の裸黄ノコノコがその甲羅に入ろうとすると、即座に甲羅から吹っ飛んで出てくる。

<!--
* If another Koopa (other than a yellow one) enters the portable disco shell, the Koopa that is created will basically act like a normal yellow Koopa, but will act like a disco shell when bounced on. This Koopa can also be turned back into a portable disco shell by capespinning it. This new disco shell is unique in that it can be stopped at any time with a capespin, rather than being destroyed like a normal disco shell would. [Video](https://youtu.be/cN2d57Y6p8A)
-->
* 黄色以外の裸ノコノコが持ち運べる無敵甲羅に入ると、通常の黄ノコノコのように行動する。特殊な点は踏んだ時に、無敵甲羅を踏んだようにマリオが跳ねる。このノコノコはマントの回転を当てると、持ち運びできる甲羅になり、この甲羅が無敵状態になってもマントの回転で止めることができる。[Video](https://youtu.be/cN2d57Y6p8A)

<!--
* Capespinning the special disco shell described above can also give a few unused colors of shells, such as gold, grey, brown, sky blue, teal, or pink. These colors will either act like a blue or yellow shell when eaten by Yoshi or when a Koopa enters them.
-->
* 無敵甲羅をマントの回転で止めると、通常使われない色の甲羅にできる。例えば、金・茶・空・青緑・桃色がある。これらの色の甲羅をYが咥えたり、ノコノコが入ると、青色か黄色の甲羅として動作する。

<!--
* If a blue Koopa kicks a portable disco shell (thereby activating it), the speed of the shell will be much greater than it normally moves at.
-->
* 裸青ノコノコが持ち運べる無敵甲羅を蹴ると、無敵甲羅の速度が通常より大きくなる。

<!--
* If a Koopa tries to flip over a shell in a higher slot than it, it will usually be killed by the shell in the process.
-->
* 裸ノコノコが自分よりスロットIDの大きい甲羅をひっくり返すとき、通常その過程で自滅する。

<!--
* Blue Koopas can catch thrown Bob-Ombs, but only when they're either in a lower slot or on the ground on the frame they register interaction. However, the Koopa won't slide or stop the Bob-Omb's movement, causing it to be kicked from inside or behind the Koopa. It can even fly straight through him or make him turn around to face it.
-->
* 裸青ノコノコは投げつけられたボム兵を、スロット番号がより小さいか当たりを判定するFに地面に足をついていたら、受け止めることができる。なお、ノコノコが滑らせられたりボム兵の動きを止めたりするわけではないため、蹴るときはボム兵の位置がノコノコと重なっているか後ろにある。たまにボム兵はノコノコをすり抜けたり、すり抜けざまにノコノコの向きを変えさせたりすることがある。

<!--
* When catching a dropped throwblock, blue Koopas won't clear the throwblock's X speed, which can cause it to bounce inside the Koopa. If it bounces far enough, it can actually kill the Koopa after it kicks it.
-->
* 下入力しながら手放されたブルブルブロックは青ノコノコによってX速度をリセットされず、青ノコノコを貫通する。十分な速度で行えば、青ノコノコは自分の後ろにあるブルブルブロックを蹴り、自分で死ぬ。

<!--
* If a shell bounces far enough into a blue Koopa, the Koopa will be killed by the shell as soon as it kicks it. This can also be forced by screenscrolling as the Koopa is catching the shell.
-->
* 甲羅が青ノコノコに十分めり込んでいると、青ノコノコは甲羅を蹴った直後に甲羅で死ぬ。これはノコノコが甲羅をキャッチしている最中、画面スクロールによっても引き起こされる。

<!--
* If a shell is registered by a blue Koopa but does not actually stop (due to bouncing off of a wall or otherwise), then the Koopa will be "dragged" along with the shell until the shell is either stopped or despawns.
-->
* 裸青ノコノコが動いている甲羅を一度捉えると、甲羅が止まるか消えるまで、ノコノコは甲羅に押されてスライドする。

<!--
* If Mario grabs a shell that a blue Koopa is about to kick, and then lets go or throws it upwards before the Koopa kicks, the shell will still be kicked by the Koopa even if it's not actually touching it.
-->
* 裸青ノコノコが蹴ろうとしている甲羅は動かせ、蹴られるFに掴んだり横投げなどをしていなければ、ノコノコは甲羅が離れていたとしても蹴る。

<!--
* Screen scrolling as a blue Koopa catches a shell that has a Koopa inside will cause the Koopa to be flung out of the shell.
-->
* 青ノコノコが中身入り甲羅をキャッチしている時に画面スクロールすると、中身が飛び出てくる。

<!--
* While any Koopa is in their kicking animation (including to flip a shell over), they will not be affected by gravity and won't move with the layer they're standing on. When on a scrolling Layer 2, this can cause them to end up inside the layer, as well.
-->
* 全てのノコノコは甲羅を蹴る（ひっくり返すのも含む）アニメーション中、重力と自分が立っているレイヤーの移動を無理する。レイヤー2のスクロール中にこれが起こると、めりこむことがある。

<!--
* If a blue Koopa and a dropped carryable item have opposite "facing" directions ($157C), then the item will warp in front of the blue Koopa when it touches it, regardless of their relative positions to each other. Note that the "facing" direction of a carryable sprite is not the direction it's actually moving in; instead, it's the last horizontal direction the sprite was moving in when in a non-carryable status (alternatively, it can be inverted by bumping off a wall).
-->
* 裸青ノコノコと手から離れた持ち運べるアイテムの「向き」（$157C）が逆の時、アイテムが裸青ノコノコに触れられると互いの位置の差にも拘わらず裸青ノコノコの前に瞬間移動させられる。持ち運べるスプライトの「向き」は実際に動いている方向に関係なく、持ち運べる状態に入る直前動いていた水平的な方向である。また、この値はスプライトが壁から跳ね返されたら反転する。

<!--
* If a thrown Koopa/Buzzy Beetle shell (or stunned Spiny/Yellow Parakoopa) is caught by a blue Koopa and Mario grabs said shell from it before it is kicked, then when the shell returns to normal status (i.e. a normal Koopa/beetle), the sprite will immediately die when touched. [Vid](https://twitter.com/nathanisbored1/status/910402559994503168)[eos](https://twitter.com/Kaizoman666/status/910549944704077824)
-->
* 投げられたノコノコやメット（/スタンしたトゲメット/黄色パタパタ)が青ノコノコにキャッチされ、蹴られる前にマリオが掴み、それから通常の状態（普通のノコノコ/メット等）に戻してから触れると、そのスプライトは即死する。[Vid](https://twitter.com/nathanisbored1/status/910402559994503168)[eos](https://twitter.com/Kaizoman666/status/910549944704077824)

<!--
* Yellow Koopas will jump as if a shell was thrown at them so long as a shell is thrown in close proximity to them, even if it's being thrown away from them or bouncing off of a wall.
-->
* 黄ノコノコはとても近い距離で甲羅が投げられてもジャンプする。壁で反射した甲羅でもジャンプする。

<!--
* Yellow Koopas will also jump if any other carriable sprite is thrown next to them, so long as they are in close enough proximity on the frame the sprite is thrown.
-->
* 黄色ノコノコは近くで他の持ち運べるスプライトが投げられるとジャンプする。

<!--
* If you capespin or bounce a shell that a yellow Koopa enters before it turns into a disco shell, then the Koopa will instead change colors to whatever color the shell is.
-->
* 黄ノコノコが甲羅に入り無敵甲羅に変わる前に、マントの回転を当てたり甲羅を跳ねさせると、ノコノコは甲羅の色に変化する。

<!--
* Shells will ignore the bottoms of blocks while they are spinning.
-->
* 動いている甲羅は、ブロックの底部に接触判定を持たない。

<!--
* Carrying a buzzy beetle shell or a shell that has a Koopa inside it through a pipe will cause the Koopa/Beetle to never emerge from the shell. Note that if a sprite in a higher slot is doublegrabbed on top of the shell, this glitch will not take effect.
-->
* メットやノコノコが入った甲羅を持って土管移動すると、ただの甲羅の状態のままになる。もし甲羅よりスロットIDが大きいスプライトと2個持ちして移動したら、このバグは発生しない。

<!--
* Throwing a Goomba upwards as Mario is colliding with a wall may cause it to warp upwards several tiles.
-->
* クリボンを壁に密着して上投げすると、数タイル分上に瞬間移動することがある。

<!--
* Landing on a Goomba, Bob-Omb, or Koopa while flying will squish it with a glitched graphic rather than the regular actions they take.
-->
* クリボン・ボム兵・ノコノコを飛行中に踏み潰すと、通常とは異なるバグった表示になる。

<!--
* Shells, throwblocks, Goombas, and Bob-ombs can destroy sprites that would normally be undestroyable (e.g. Thwomps, Thwimps) so long as they are in a higher sprite slot than the sprite.
-->
* 甲羅・ブルブルブロック・クリボン・ボム兵は通常倒せないスプライト(ドッスンやコトン)などであっても、スプライトIDがそれらより大きいと倒すことができる。

<!--
* Dropping or kicking a shell or Goomba on the frame that an enemy is about to collide with it will destroy the other sprite without destroying the shell/goomba, and will give 1000 points as if they actually had collided.
-->
* 甲羅・クリボンを離す・蹴ることを敵に接触するFに行うと、甲羅・クリボンを死なせずに敵を倒すことができる。これを行うと、ぶつけた時のように1000点入る。

<!--
* Flying ? blocks will destroy shells, Bob-Ombs, Goombas, and throwblocks if Mario runs into the block while holding them.
-->
* 飛んでいる？ブロックは掴んでいる甲羅・ボム兵・クリボン・ブルブルブロックで触れると叩ける。

<!--
* Throwing a carryable sprite at a flying ? block will zero its Y speed upon hitting it. Alternatively, its X speed will be zeroed if it is thrown up at the block. And if it's dropped on top of the block, it will fall through while still hitting the block.
-->
* 持ち運べるスプライトを飛んでいる？ブロックに当てるとY速度またはX速度が0になる。スプライトがブロックの上に落下すると、ブロックに引っかかかりながら落ちていく。

<!--
* Flying ? blocks will invert the X speed of throwblocks when hit, essentially bouncing the block back in the previous direction, rather than making them break.
-->
* 飛んでいる？ブロックにブルブルブロックを当てると、壊れることなくX速度が反転する。

<!--
* The bottom of flying ? blocks are also treated the same as the sides of it, meaning the X speed of sprites thrown upward at it will still invert.
-->
* 飛んでいる？ブロックの底面は側面と同様に扱われており、下からスプライトが当たると、X速度が反転する。

<!--
* If Mario collects a star while holding an item that would normally be destroyed by star power, that item will not be destroyed unless Mario lets go of it and touches it again.
-->
* スターを取ってからアイテムを掴もうとすると、スター状態のためアイテムは倒される。事前にアイテムを掴んでいる状態でスターを取れば、アイテムを離さない限りアイテムは倒されない。

<!--
* Mario can pick up a throwblock on the same frame he jumps off of it.
-->
* ブルブルブロックの上でジャンプすると同時にそれを掴むことができる。

<!--
* Dropping a throwblock just as it's about to disappear will extend its timer a short time.
-->
* 掴んでいるブルブルブロックが消えるFに放すと、消えるまでの時間が少し追加される。

<!--
* If sprite slots 0-9 are filled, Mario will be unable to pick up throwblocks.
-->
* スプライトスロット#0-#9が埋まっていたら、ブルブルブロックを新しく掴めない。

<!--
* Throwblocks will bounce backward when thrown at a very steep vertical slope. You can even make it bounce back and forth infinitely if you throw it between two of them.
-->
* ブルブルブロックはとても急な坂にぶつかると、逆向きに跳ね返る。向かい合わせにもとても急な坂があれば、ずっと反射させられる。

<!--
* Landing on the very top of a very steep slope for a frame will boost Mario's speed, allowing him to get up to 51 speed without a cape. Normally, the slope would slow Mario to 32 when going down it.
-->
* とても急な坂の頂上に乗るとマリオを加速させられ、マントなしで速度51にすることが可能である。通常は速度32まで減速させられる。

<!--
* Mario can spinjump off of throwblocks after they're thrown.
-->
* 投げたブルブルブロックをスピンで踏むことができる。

<!--
* Mario can spinjump off of throwblocks on the frame they shatter from hitting a block.
-->
* ブルブルブロックがブロックにあたって粉々になるFにスピンで踏むことができる。

<!--
* Mario can spinjump off of throwblocks on the frame they turn into a cloud puff from their timer running out.
-->
* ブルブルブロックが時間切れで雲になるFにスピンで踏むことができる。

<!--
* Carrying a throwblock, Goomba, or Bob-omb through a pipe will make it never run out of time. However, if you double grab the sprite with another sprite in a higher slot, this glitch will not take effect.
-->
* ブルブルブロックを持って土管を通ると、時間経過で消滅しなくなる。クリボンだと復活しなくなり、ボム兵は爆発しなくなる。ただし、スロットIDが高位の別のスプライトと2個持ちしていると、このバグは発生しない。

<!--
* Horizontally kicking a Goomba, Bob-omb, or Mechakoopa will reset their stun timer; this can also cause the Bob-omb to change palettes if you kick it while it's flashing.
-->
* クリボン・ボム兵・メカクッパを横に蹴るとスタンタイマーがリセットされる。光っているボム兵を蹴れば、カラーパレットを変えることができる。

<!--
* Releasing a Bob-omb, or kicking it upward, at the last frame before exploding will also reset its stun time, but to a lower value of 0x40; it also triggers the explosion sound.
-->
* ボム兵が爆発する直前のFに離したり上に蹴り上げると、スタンタイマーがリセットされて下位の値が0x40になる。これによって爆発音が鳴る。

<!--
* It's possible to bounce off Bob-ombs, Goombs, and Mechakoopas a frame before their stun timers run out. This is most notable with Bob-ombs, since you can't normally bounce off them again after they're stunned for the first time.
-->
* スタンタイマーが0になる直前のFにボム兵・クリボウ・メカクッパを踏むことができる。特にボム兵は一度停止状態になると普通は踏めなくなるので、注目に値する。

<!--
* When Mario grabs a sprite, its X and Y speed doesn't get reset; this instead happens when he throws or drops it. However, sprites that hop out of Mario's hands on their own, such as Goombas, Buzzy Beetles, or MechaKoopas, don't get their speeds reset. One use of this is allowing Mario to bounce off the sprite in mid-air without needing to let go of it.
-->
* マリオがスプライトを掴むとき、それのXY速度はリセットされない。これはマリオがスプライトを蹴るか離した時には生じないが、マリオの手からひとりでに離れるスプライト（クリボン・メット・メカクッパ）では有用であり、空中でスプライトを離さなくても踏むことができる。

<!--
* For a few frames after being thrown, a Goomba will destroy other sprites without being destroyed as well.
-->
* 投げられてから数Fの間のクリボンは、死なずに敵を倒せる。

<!--
* Explosions from Bob-ombs can still be spinjumped on, as well as capespinned and killed. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4693)
-->
* ボム兵の爆発でスピンジャンプすることができる。この爆発はマントの回転で倒せる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4693)

<!--
* Explosions from Bob-ombs won't disappear as long as they are offscreen, beyond the despawn region. This can make them occupy a slot persistently.
-->
* ボム兵の爆発は消滅領域を超えたスクリーン外で発生すると、時間経過で消滅しない。つまり、永久にスロットを占領することになる。

<!--
* Mechakoopas will pass through the bottoms of solid blocks while active. In other words, you can just throw it up as it's about to reactivate to send it through the roof.
-->
* メカクッパが動いているときはソリッドブロックの底面を無視する。つまり、再稼働するときにメカクッパを上投げすると、ソリッドブロックを貫通していく。

<!--
* Hittable blocks will always bounce sprites away from Mario when hit, regardless of which side of the block Mario is actually on.
-->
* 叩けるブロックは常にスプライトをマリオから遠ざける向きに飛ばす。これはマリオがブロックに対してどちら側にいるかは関係ない。

<!--
* Hitting a block twice within its activation frames will cause it to dispense two items.
-->
* ブロックがアクティブである間に2度叩くと、中身が2回でる。

<!--
* Capespinning a block at the same time that the game is frozen (via $9D) will cause the block to dispense multiple items, usually filling up every sprite slot available.
-->
* ゲームが（$9Dで）フリーズしている時、マント回転でブロックを叩くと、スプライトスロットが埋まりきるまで中身が出てくる。

<!--
* Block duplication: Throwing an item into a hittable block in the right spot will cause it to "duplicate" the tile to an adjacent block, either horizontally, upward, or diagonally upward. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4387) - [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#DuplicatingBlocks) - [Video](https://youtu.be/1SGfYkXoGjg?t=41s)
-->
* ブロック増殖：投げられるアイテムを上投げでブロックの特定の位置に当てると、横・上・斜め上のいずれかのタイルにブロックが複製される。 [Fix](http://www.smwcentral.net/?p=section&a=details&id=4387) - [More info](http://tasvideos.org/GameResources/SNES/SuperMarioWorld.html#DuplicatingBlocks) - [Video](https://youtu.be/1SGfYkXoGjg?t=41s)

<!--
* In levels with a scrolling Layer 2, it's also possible to duplicate downward or even two blocks downward.
-->
* レイヤー2がスクロールするレベル内では、レイヤー2のブロックを下方向に増殖できる。2タイル下にも可能。

<!--
* Duplicating a block into a Yoshi coin and then grabbing the Yoshi coin will turn the block into tile 125; this tile has the potential of spawning a key, Yoshi wings, P-balloon, or shell. Note that if the block you duplicated was a turnblock, you'll have to wait for it to stop turning before collecting the coin. [Video](https://youtu.be/1SGfYkXoGjg?t=4m25s)
-->
* ドラゴンコインの下部を上書きするようにブロック増殖してから、ドラゴンコインの上部をとると、下部がタイル125番になる。このタイルはX座標によって鍵・Yの羽・Pバルーン・甲羅を出す。クルクルブロックでこれを行う場合、コインを取るのはクルクルブロックの回転が止まってから。 [Video](https://youtu.be/1SGfYkXoGjg?t=4m25s)

<!--
* Block factory: Items can be forced into corners or walls and get stuck inside. If one of the blocks it's stuck between happens to be a hittable block, it's possible that it will create a situation in which the block is rapidly duplicated until the sprite despawns or is removed.
-->
* ブロック工場（高速増殖）：アイテムは壁の内部などに押し込めることが可能。壁の中等で痙攣しているアイテムがブロックを叩いた時、ブロックが高速で増殖され続けることがある。一度増殖されると、アイテムがそこから消えるまで増殖は止まらない。

<!--
* The above can have a few strange effects on other hittable blocks; bounce sprites may get overwritten so that the blocks turn into an invisible solid block, or they won't spawn for a frame and will dispense two items at once, or won't spawn at all and can dispense an item without being registered as hit. If a noteblock's bounce sprite gets overwritten while you're bouncing on it, Mario will also fall through it. These effects can also be created without block factory by spawning more than four bounce sprites before any of their animations finish.
-->
* 高速増殖中に別のブロックを叩くと通常と異なる挙動になる。ブロックが透明になったり、アイテムが2個同時に出てきたり、ブロックをアイテムで叩いても当たったことにならないことがある。音符ブロックを上から踏んでいる時に透明化すると、マリオが音符ブロックを貫通して下にすり抜ける。これらの挙動は高速増殖中でなくても、4つ以上のブロックが叩かれて跳ねているアニメーションの最中に行ってもできる。

<!--
* Mario can fall through the top of block factories regardless of the block being duplicated, and can pass through it in either direction.
-->
* 高速増殖中のブロックの上部分を通り抜けることができる。そこから左右に通り抜けられる。

<!--
* When throwing a carryable sprite upwards, if the sprite registers itself as hitting both the bottom of one block and the side of another at the same time, neither will actually be activated by the hit. This can be done not only at the inner corner between two blocks, but even on an entirely flat ceiling (by throwing the sprite so it enters the ceiling enough to touch the side of an adjacent block).
-->
* 上向きに投げられたスプライトがブロックの下ともう1つのブロックの側面に同時に当たると、両方のブロックに当たらなかったとされる。ブロック間の隅っこに投げつけることではもちろん、側面に当たるように十分にめり込ませれば平面の天井でもこのバグを発生させることができる。

<!--
* Tile 125's shell will only actually come out if an adjacent block knocks it upward.
-->
* タイル125番の甲羅は隣接したブロックが叩かれると出現する。

<!--
* Mario can still hit blocks while moving downward, so long as he enters the lower corner of the block enough.
-->
* マリオは落下しながらでもブロックの下の角に十分近い軌道を通れば、ブロックを叩ける。

<!--
* If a block overwrites a rotating turnblock (e.g. by vine, duplication, etc.), then the turnblock will reappear once it stops rotating.
-->
* 回転しているクルクルブロックをツタやブロック増殖などで上書きしても、回転が止まるFにクルクルブロックが再出現する。

<!--
* Turnblocks can be copied from Layer 1 to Layer 2 or vice-versa by interupting their bounce sprite (even during the rotating animation) with one from a block on the destination layer.
-->
* クルクルブロックが叩かれてバウンススプライトが消えないうちに（回るアニメーションが始まっていたとしても）、別のレイヤーにあるブロックでバウンススプライトを出現させると、前者のスプライトが中断されてブロックが後者のレイヤーにコピーされる。

<!--
* If there is a coin on top of a block when Mario hits it, the coin will become a solid, invisible block. [Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#029347)
-->
* コインが上にあるブロックを叩くと、コインの所が透明なソリッドブロックになる。 [Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#029347)

<!--
* If a coin is placed 16 screens away from a block and one tile higher than it, then bouncing off the top or side of this block (e.g. with noteblocks or the side-bounce turnblock) will give Mario a coin and create an invisible solid block on top. This occurs regardless of which side of the blocks the coins are actually on. However, the exact position of the coin needed for the glitch may vary depending on what screen it is on.
-->
* コインが（音符ブロックや側面から触れるとバウンドするクルクルブロックなどの）ブロックから16画面離れて1タイル高い位置に配置されているとき、ブロックの上面か側面でバウンドすると、コインを1枚得られ、ブロックの1タイル上に透明なソリッドブロックが生成される。

<!--
* Hitting a block that uses bounce sprites in multiple directions (such as the all-way noteblock) on two sides at once will generate multiple bounce sprites even though there should only be one.
-->
* 複数の方向にバウンススプライトを発生させるブロック（全方向に反応する音符ブロックなど）の左右両方の側面を同時に叩くと、バウンススプライトが複数個発生する。

<!--
* If the sprite in the **lowest** filled sprite slot with object interaction is inside one of tiles 021-024 or 121-124, then all tiles outside of the level will register as the corresponding tile on Map16 page 0. They won't actually become solid when hit, but they will block Mario from below and spawn any related sprites. Notably, capespinning will briefly interrupt this effect.
-->
* If the sprite in the **lowest** filled sprite slot with object interaction is inside one of tiles 021-024 or 121-124, then all tiles outside of the level will register as the corresponding tile on Map16 page 0. They won't actually become solid when hit, but they will block Mario from below and spawn any related sprites. Notably, capespinning will briefly interrupt this effect.

<!--
* Mario can pass through invisible coinblocks or noteblocks without hitting them as long as he is being pushed upward by anything other than a jump, including keys, platform sprites, ropes, or another layer.
-->
* 透明なコインブロック・音符ブロックはジャンプ以外の方法で下から通過すれば反応しない。鍵・足場になるスプライト・ロープ・別レイヤーの足場などの方法がある。

<!--
* Bonus game coinblocks will always register a correct hit if a shell, Goomba, or Bob-omb is knocked into it by a capespin or bounced by another block.
-->
* ボーナスゲームのコインブロックは甲羅・クリボン・ボム兵をマント回転か別のブロックのバウンドで当てたら、必ず○になる。

<!--
* In a bonus game room, hitting a coinblock that isn't in one of the positions used by the original bonus game may cause additional brown blocks to spawn.
-->
* ボーナスルームで、正しい位置に配置されてないコインブロックをたたくと、複数のプンプンブロックが出現することがある。

<!--
* If a coinblock is placed within the top 4 rows of the bonus room, it will cause Mario to immitate a P-balloon when hit, except the P-balloon neither wears off nor can be controlled; Mario will only move with whatever inertia he had when the block was hit.
-->
* ボーナスルームで画面上から4タイル以内の高さに配置されたコインブロックを叩くと、マリオがPバルーンをとったかのような挙動をする。ただし操作は不可能。マリオはブロックを叩いた時の速度で慣性移動する。

<!--
* If a coinblock is placed within the bottom 4 rows of a bonus room, it will cause Mario's graphics to severely mess up when hit, as well as make him lose interaction with sprites.
-->
* ボーナスルームで画面下から4タイル以内に配置されたコインブロックを叩くと、マリオの表示がひどくバグり、またスプライトとの接触判定がなくなる。

<!--
* All multi-coinblocks function using the same timer to determine whether they continue giving coins or turn into a used block. This means hitting one, waiting a bit, and then hitting another will immediately turn it into a used block; the original one, meanwhile, will restart the timer when hit again rather than doing the same. Notably, double-hitting a single block can cause that timer to reset without turning any blocks into brown blocks.
-->
* 全ての複数コインブロックは、同じタイマー($7E186B )を使用している。いずれかのブロックが叩かれると、タイマーが00からFFになり1F毎に1減少し、値が01になるまではブロックを叩けばコインがでる。01になってブロックを叩くとそのブロックがプンプンブロックに変化し、値は00になる。1つのブロックを同時に２回叩くと、プンプンブロックにならずにタイマーをリセットできる。

<!--
* Releasing an item from the item box will cause it to continue cycling vertically throughout the level until Mario collects it. Its interaction will even loop every two horizontal screens as well, so you can grab even if you can't see it.
-->
* Releasing an item from the item box will cause it to continue cycling vertically throughout the level until Mario collects it. Its interaction will even loop every two horizontal screens as well, so you can grab even if you can't see it.

<!--
* In vertical levels, permanent sprites will loop around vertically around the level. It takes about 400 in-game seconds for the sprite to make a complete loop, though. They can potentially also loop horizontally in horizontal levels, too, but only if they don't fall off the bottom of the screen.
-->
* 縦ステージでは、残存スプライトは垂直方向にループしている。一周するのにTIME400ほどかかる。横ステージでもスプライトが画面下に落ちなければ、水平方向でループする。

<!--
* In certain levels, objects will fall slower when off the top of the level, as if they are in water. The cause is unknown, but sprite buoyancy is likely related.
-->
* 一部のレベルでは、画面上部ではオブジェクトが浮力を持ったかのようにゆっくり落ちる。原因は不明。

---

<!--
* Finishing a boss battle while holding a carryable sprite will cause the sprite to disappear, but Mario will continue to act like he's holding it.
-->
* ボス戦が終わるときに持ち運べるアイテムを掴んでいると、スプライトは消えるが、マリオは掴んだ表示のままとなる。

<!--
* If you're standing on something after a boss battle ends, Mario will continue to stand there even if he shouldn't normally. For example, walljumping, P-switchjumping, keyjumping, or grabbing a throwblock all work, even though normally Mario would fall.
-->
* ボスバトルが終わるFに通常立てない場所立っていると、マリオはそこに立ち続ける。例えば、壁・Pスイッチ・鍵の上がある。終わる瞬間に足場のブルブルブロックを持ってジャンプできるが、マリオは落ちる。

<!--
* The game will register a bubble as being hit for every frame that a shell or throwblock touches it.
-->
* 泡に甲羅・ブルブルブロックを当てると、毎Fヒットする。

<!--
* If a Koopa starts to jump into a shell while in the water and exits the water midway through the jump, the animation won't line up and it'll end up walking slightly further than it should.
-->
* 水中にいる裸ノコノコが甲羅に入ろうとぴょんとジャンプしてる最中に水中から出ると、アニメーションがずれてしまって目的地より少し歩きすぎてしまう。

<!--
* If a shell, throwblock, Goomba or Bob-omb hit the very top of a Pokey's head, Pokey's head won't actually be hit, but a head graphics will still fall down.
-->
* 甲羅・ブルブルブロック・クリボン・ボム兵をサンボの頭に当てると、倒せるわけではないが、頭のグラフィックが落ちていく。

<!--
* If sprite buoyancy is enabled in a level, grabbing a throwblock will show the water splash graphic regardless of if it's actually in water.
-->
* スプライトの浮力があるレベルでブルブルブロックを掴むと、水中でなくても水しぶきの表示が発生する。

<!--
* When swimming with a carryable sprite in a level with sprite buoyancy, pressing against a wall will cause the game to think the sprite has exited the water and will display a splash graphic. Likewise, turning away from the wall will cause the game to treat it as entering the water again, also displaying one.
-->
* スプライトの浮力があるレベルで持ち運べるスプライトを、壁に押し付けたり反転させたりする度に水しぶきが表示される。これはスプライトが水中に出入りしていると認識されるため。

<!--
* Grabbing an item on the frame Mario enters a pipe will cause him to enter the pipe without turning. You can also occasionally exit the pipe backward, as well.
-->
* マリオが土管に入るFにアイテムを掴むと、振り返らずに土管に入っていく。

<!--
* Releasing of a pressed P-switch off the right side edge of a level will cause its graphics to briefly loop to the left side of the screen.
-->
* 潰れたPスイッチが画面右にあると、画面左にループして表示される。

<!--
* Turning while holding a Mechakoopa will cause Mario's head to disappear briefly.
-->
* メカクッパを持って振り返る間、マリオの頭部の表示が消える。

<!--
* Hitting a block above the screen will cause it to dispense whatever is inside and stop giving items like usual, but its graphics won't change.
-->
* Hitting a block above the screen will cause it to dispense whatever is inside and stop giving items like usual, but its graphics won't change.

<!--
* Hitting a block off the sides of the screen will cause it to not register being hit.
-->
* 画面横の外のブロックを叩いても、叩いたと認識されない。

<!--
* Freezing the game (via $9D) on the frame a Yoshi egg lands on solid ground will cause its graphics to glitch briefly. [Gifs](https://imgur.com/a/R4lOF)
-->
* Yが産んだ卵がソリッドな地面につくFに（$9Dで）フリーズすると、卵の表示がバグる。[Gifs](https://imgur.com/a/R4lOF)

<!--
* Bringing a carryable sprite into a Mode 7 boss room will cause the graphics to glitch.
-->
* 持ち運べるスプライトをモード7のボス部屋に持ち込むとグラフィックがバグる。

---
---

<!--
# Miscellaneous Glitches
-->
# 雑多なバグ(Miscellaneous Glitches)

<!--
__(Sprites, objects, and levels in-of themselves)__ 
-->
__スプライト・オブジェクト・レベル(Sprites, objects, and levels in-of themselves)__  

<!--
_280 recorded glitches, 180 of which are useful._
-->
_280個(180個有用)_  

<!--
* Sprites will "slide" with inertia across tiles 1D8-1FF. It should be noted that this means if the sprite hits 0 speed while on one of the blocks, it will be unable to move at all unless Mario causes it to. Because the bottom tile of tileset-specific lava is also included in the range mentioned above, sprites can pass through it without being destroyed; only the top of the lava will actually kill it.
-->
* スプライトはタイル1D8-1FF上を通るとき慣性移動する。スプライトが速さが0でこれらのタイル上にいるとき、マリオが何かするまでスプライトは動けない。特定のタイルセット用の溶岩の底タイルは上記の効果を持つため、スプライトは死なずに慣性移動する。スプライトが死ぬのは溶岩の上面タイルだけ。

<!--
* If enough sprites are close enough together, they can push each other off of or through blocks.
-->
* 複数のスプライトが密集して存在すると、それぞれが押し合ってブロックにめりこんだり貫通したりする。

<!--
* Quake sprites can be overwritten by spawning more than 4 within a very short time. Because they don't actually destroy sprites until a few frames after spawning, this can actually prevent them from interacting entirely. As an alternative, spitting out a null sprite will also overwrite slot 2.
-->
* 揺れスプライトは短時間に4体以上出現すると上書きされる。揺れスプライトは出現後数Fはスプライトを倒さないので、これを利用することで揺れを完全に妨げることができる。代わりとして、ヌルスプライトを吐くとスロット2が上書きされる。

<!--
* Screen scrolling on the frame that Mario touches a shell-less Koopa (other than blue) will cause him to kick and kill it.
-->
* LRスクロールするFにマリオが青色でない裸ノコノコに触れると、蹴り殺す。

<!--
* Freezing the game (via $9D) on the frame that a shell-less red or blue Koopa touches the corner of a block will cause it to fall downward past that corner.
-->
* 裸の赤・青ノコノコがブロックの角に触れる時、($9Dで)フリーズさせるとノコノコが角で振り返らず落下する。

<!--
* Koopas standing on a conveyor platform will continue to be moved while the game is frozen (via $9D).
-->
* （$9Dで）フリーズさせている間、動く足場に乗っているノコノコが動き続ける。

<!--
* If Mario knocks a Koopa out of its shell, lets it re-enter, and then knocks it out once more, the game will register that Koopa as a new sprite. This means, if the shell is then despawned, the Koopa will respawn, even if the shell-less Koopa you knocked out isn't. This means you can get an infinite number of shell-less Koopas from a single Koopa.
-->
* ノコノコを甲羅から出して再び入れて、もう一度出すと、出てきた裸ノコノコは新しいスプライトとして認識される。つまり、甲羅を倒さず消すとノコノコが再び現れる。これを利用すれば、裸ノコノコを一体のノコノコから何体でも出現させられる。

<!--
* If a Koopa has just entered a Koopa shell, setting $15D0 (flag for being on Yoshi's tongue) for a sprite in the same slot the Koopa was in will cause the Koopa inside the shell to vanish without actually emerging.
-->
* 裸ノコノコが甲羅が入りノコノコになる前に、裸ノコノコと同じスロット同じスロットのスプライトの$15D0（Yの舌上にあるかのフラグ）がセットされると、甲羅内部のノコノコが消える。

<!--
* If a shell-less Koopa is jumping into a shell, and that shell despawns and is replaced by any other sprite overlapping with the Koopa, then the Koopa will enter the sprite and set two misc addresses for the sprite ($1558 to #$10, $160E to the ID of the Koopa). This can cause various effects depending on the sprite. [More Info](http://pastebin.com/ga1DUtmh) - [Video](https://youtu.be/Gj88xkSiAXI)
-->
* 裸ノコノコが甲羅に入ろうとジャンプしている最中、甲羅が消えて裸ノコノコとかち合う位置に別のスプライトが読み込まれると、裸ノコノコがそのスプライトに入り、スプライトの2つのアドレス（$1558に#$10、$160EにノコノコのID）がセットされる。これはスプライトによって幾つか変な効果を引き起こす。[More Info](http://pastebin.com/ga1DUtmh) - [Video](https://youtu.be/Gj88xkSiAXI)

<!--
* Koopas sliding from being knocked out of a shell will clear their X speed and temporarily reset their animation graphic if the game freezes with $9D.
-->
* 甲羅から飛び出たノコノコは$9Dでフリーズさせると、X速度が0になり、フリーズ中は表示がリセットされる。

<!--
* Sliding blue Koopas will only register the top of solid blocks; they'll pass right through the sides and bottom.
-->
* 滑る青ノコノコはソリッドブロックの上面しか認識しない。ソリッドブロックの左右と底面は素通りする。

<!--
* During the brief period after a Sliding Blue Koopa comes to a stop (before it starts walking as a normal Blue Koopa), it will no longer update it's position or interact with blocks, so removing the ground from below it will cause it to just float in midair for a bit.
-->
* 滑る青ノコノコが止まってから通常の青ノコノコとして歩き始めるまで、位置やブロックとの相互作用を更新しないので、僅かな時間地面がなくても空中に浮く。

<!--
* Sliding Blue Koopas will constantly bounce when trying to slide upwards on a slope.
-->
* 滑る青ノコノコは坂を登っていく時、跳ねながら登っていく。

<!--
* If a blue Koopa is prepared to kick a sprite, and that sprite despawns and is replaced by another carryable sprite (i.e. in sprite status 9) within horizontal proximity of the blue Koopa, then the blue Koopa will kick that instead. If not a shell, this also sets that sprite's stun timer. [Vi](https://youtu.be/RNdl6zkoC00)[de](https://youtu.be/HjLO7A6NYX8)[os](https://youtu.be/JBvdsC9TFRE)
-->
* 青ノコノコがスプライトを蹴る準備できた時に、そのスプライトが消えて、青ノコノコに近い水平位置の別の持ち運べるスプライトに置換されると、青ノコノコは代わりにそのスプライトを蹴る。甲羅ではない場合、スプライトのスタンタイマーがセットされる。[Vi](https://youtu.be/RNdl6zkoC00)[de](https://youtu.be/HjLO7A6NYX8)[os](https://youtu.be/JBvdsC9TFRE)

<!--
* Screen scrolling while a yellow Koopa is jumping will allow it to pass through solid blocks on the way up.
-->
* 黄色ノコノコがジャンプするときに、LRスクロールをするとソリッドブロックを下から上に通り抜ける。

<!--
* Yellow Koopas can still jump over shells while sliding. Combine this with the fact that sliding Koopas don't register the bottom of blocks, and you have a way to move a yellow Koopa upward through solid tiles.
-->
* 黄色ノコノコは動いている甲羅が近づくとジャンプする。これを上記のバグと組み合わせれば、黄色ノコノコをソリッドブロックを数タイル分上方向に上抜けさせられる。

<!--
* The net-climbing Koopas will only actually hit small Mario if his feet are touching them. This means Mario can just hang off the bottom of the net to avoid them.
-->
* 金網ノコノコとチビマリオが当たるのは、マリオが金網ノコノコの足に触れたとき。金網の下端にぶら下がることで、金網ノコノコを避けられる。

<!--
* Green net-climbing Koopas will not despawn off the top of the screen in vertical levels, essentially being treated as a permanent sprite. They'll still despawn below the screen, however.
-->
* 金網に捕まる緑ノコノコは縦ステージにおいて、画面上で消失せず残存スプライトとして扱われるが、画面下で消える。

<!--
* It's possible to jump off the climbing net door during a few frames before it actually starts turning after being hit. Mario will still switch layers despite no longer being on the sprite, and grabbing onto something (even off the gate) will cause him to still be pulled around. Unfortunately, he still interacts with objects during it.
-->
* 回転金網を叩いてから数Fはスプライトが作動してマリオが奥側に行くまでの猶予が有り、その間にジャンプすることが可能。スプライトに重なっていない位置でも、何かに掴んでいなくても奥側に行くことになるが、地形に依存し、オブジェクトとは相互作用し続ける。

<!--
* Getting pushed off the net gate sprite by a solid sprite (including two carriable sprites) right at the start of its rotation will cause Mario's X speed to rapidly start increasing in that direction. This will continue as long as he holds a net, eventually overflowing his speed and rebounding unless he lets go. [Video](https://twitter.com/Kaizoman666/status/755102882345656321)
-->
* 回転金網が回転を始める時に、（2つの持ち運べるスプライトを含む）ソリッドスプライトによってマリオが押し出されると、押し出されるX方向に急加速される。この加速は金網を掴んでいる間発生し続け、離さなければ速度がオーバーフローし、逆方向に跳ね飛ばされる。[Video](https://twitter.com/Kaizoman666/status/755102882345656321)

<!--
* The net gate boost described above can also be gotten without items, by jumping off the gate just before it starts turning and then grabbing another fence further to the side. This boost is less significant, however.
-->
* 上記の回転金網による加速はアイテムなしでも可能。回転が始まる前にジャンプして、回転軸の反対側にある金網に掴まればできる。しかし、この方法の加速は上記に比べ小さい。

<!--
* Feathers will not despawn offscreen unless they are falling. By way of an item swap, it is even possible to turn a falling feather into a permanent, still one.
-->
* 羽は画面下に落ちない限り消えない。落ちる羽であってもアイテムスワップによって残存スプライトにできる。

<!--
* Touching an invisible mushroom on the frame Mario's speed inverts will cause it to fly in the opposite directly than it normally would.
-->
* マリオの移動速度が反転するFで跳ねるキノコを出現させるスプライトに触れると、キノコの向きは通常の逆になる。

<!--
* Stars push themselves far enough through blocks before bouncing off of them that Mario can collect a star through a corner between two blocks.
-->
* スターは跳ねる力が強く、ブロック中に存在すると登っていく。マリオは斜めに配置されたブロックの窪みからスターをとることができる。

<!--
* The roulette item sprite will still change while the game is frozen with $9D.
-->
* ルーレットアイテムスプライトはゲームが$9Dでフリーズしている最中も変化する。

<!--
* The block containing a roulette sprite doesn't actually have to be hit in order for it to start rising out. Instead, a nearby block, capespin, net punch, or Yoshi stomp will suffice, so long as their quake sprite comes into contact with the roulette sprite.
-->
* ルーレットアイテムスプライトは、近くのブロックが叩かれたり、マント回転・金網パンチ・Yの砂煙などの揺れスプライトに反応して出る。

<!--
* The roulette sprite won't interact with the sides or bottoms of solid blocks for a brief period of time after being spawned out of its block, causing it to bounce up on top of them if it does hit any blocks.
-->
* ルーレットアイテムスプライトがブロックから出現した直後少しの間ソリッドブロックの側面と底との相互作用を無視するので上まで跳ねてしまう。

<!--
* Spawning a Bullet Bill shooter on the far left edge of a level will not only cause it to not actually spawn, but also create a shell-less green Koopa at [0,0] in every available sprite slot.
-->
* Spawning a Bullet Bill shooter on the far left edge of a level will not only cause it to not actually spawn, but also create a shell-less green Koopa at [0,0] in every available sprite slot.

<!--
* Messages from a message box or display message sprite will erase whatever Layer 3 the level had; this includes water or smashers.
-->
* メッセージブロックかメッセージを表示するスプライトによってメッセージが表示されると、水や大木などのレイヤー3レベルが消える。

<!--
* If Layer 3 water is replaced by a message box, the water will still have interaction at the bottom of the level.
-->
* レイヤー3の水がメッセージボックスで消されても、画面下のわずかな部分だけ水が残る。

<!--
* Hitting a message box and then taking a screen exit will display that message in the next room instead.
-->
* メッセージブロックを叩いてからマップ移動すると、移動先でメッセージが表示させられる。

<!--
* Mario can land on the right corner of a message box or light switch for a frame in manner similar to walljumping, but without the speed requirement.
-->
* 壁ジャンプをする時のように、メッセージボックス・ライトブロックの角に1Fだけ乗ることができる。ただし速さは不要。

<!--
* Being pushed inside a solid sprite (e.g. message box, turnblock bridge, Hammer Bro platform, Bowser statue...) will cause Mario to warp to the nearest side, even through solid blocks. If the camera moves sharply, this may also cause the newly loaded columns of Map16 to have glitched graphics until they're reloaded. Possible ways of doing this include being pushed in by another sprite, jumping fast enough, or wallrunning via a purple triangle.
-->
* マリオが実体のあるスプライト（例えばメッセージブロック・クルクルブロックで出来た橋・アッパレの足場・クッパ像など）の中に強制的に押し込まれると、ソリッドブロックを貫通してでも一番近い側面に瞬間移動する。これによってカメラが飛ぶと、新しくロードされるMap16の縦の列はグラフィックが読み込みなおされるまで化けることがある。バグの実行は、別のスプライトに押し込まれることや、高速でジャンプすることや、ピンクの三角ブロックによって壁走りすることなどの方法がある。

<!--
* When being 'warped' by a solid sprite, it's possible to completely pass the screen's spawn region over a sprite, preventing that sprite from spawning at all.
-->
* スプライトの押し出しなどによる瞬間移動によって、スプライトの読み込み位置を完全に素通りすると、スプライトが出現しない。

<!--
* Hitting a message box that isn't set to contain a message box will cause it to instead load the Yellow Switch Palace message. If $1DF5 is non-zero, the level will automatically end and activate the Yellow Switch shortly after the message box appears; else, exiting the level by any other means (dying, goal tape, start+select, etc.) will achieve the same effect, although this will not count as beating the level. This is fixed by default by Lunar Magic. [Video](https://www.youtube.com/watch?v=EFjXb-xhWAg)
-->
* メッセージがセットされていないメッセージボックスを叩くと、黄色スイッチ宮殿のメッセージが代わりに読み込まれる。もし$1DF5の値が0以外だと、メッセージボックスが短時間出現した後、レベルが自動で終わり、黄色ブロックがONになる。値が0だと、死んだりゴールしたりスタート+セレクトなどの方法でレベルを終えた後、同様の効果が得られる。これによりレベルをクリアしたことにはならない。この挙動はLMにデフォルトで修正される。[Video](https://www.youtube.com/watch?v=EFjXb-xhWAg)

<!--
* For a brief period of time after hitting a flying ? block (even if it's been already "hit"), sprites can pass through it.
-->
* 飛んでいる？ブロックが叩かれた後少しの間（既に叩かれていたとしても）、スプライトはブロックをすり抜ける。

<!--
* If Mario touches the bottom of a solid sprite while the sprite is either touching the top border of the visible screen from above or crossing it, he will be warped to its nearest side, with the same effects as the above. This glitch works even if the screen is scrolling.
-->
* 画面の上端と上から接しているか交わっているソリッドスプライトの下にマリオが触れると前のバグと同じように一番近い側面に瞬間移動する。画面がスクロール中でも可。

<!--
* As an exception to the above glitch, if a turnblock bridge is crossing the top of the visible screen and Mario's body is onscreen, he will not interact with the bottom or sides of the bridge rather than being warped to its side. In addition, if he is moving downward while touching the bridge, he will be warped on top of it; this effect can be used with vertically extending turnblock bridges to warp Mario upward, even through solid blocks.
-->
* 前のバグの例外として、左右に伸びるクルクルブロックは画面の上端と交わってマリオの身体が画面内にあってバグを実行すると、側面に移動しない。また、左右に伸びるクルクルブロックに触れたときマリオが下の方に移動中だと左右に伸びるクルクルブロックの上に瞬間移動する。上下左右に伸びるクルクルブロックの場合はマリオを上にソリッドブロックをすり抜けて移動させる方法になる。

<!--
* If a turnblock bridge is touching (but not crossing) the top of the vertical screen border from below, Mario will not interact with the top or sides of it.
-->
* 上部が画面上にある縦に伸びたクルクルブロックは、上部と側部の接触判定を持たない。

<!--
* Turnblock bridges can push Mario into and through solid blocks if it expands while he is standing on it.
-->
* 上下方向に伸びるクルクルブロックは、それに乗っているマリオをソリッドブロックの中に押しこめる。

<!--
* Activating the unused orange platform (sprite 5E) will also activate flying turnblock platforms. However, they'll move in the oppose direction that they're supposed to, and will horizontally move very slowly. If the flying turnblock platform is already activated when the unused orange platform is landed on, the turnblock platform will suddenly slow down horizontally.
-->
* 使われていないオレンジ足場(5E)を作動させると、翼の生えた灰色足場(C1)も作動し始めるが、本来進む方向とは逆に進み、横速度がとてもゆっくりになる。灰色足場が作動中にオレンジ足場を作動させると、横速度が急にゆっくりになる。

<!--
* When more than two flying turnblock platforms are activated at once, they don't always move in the directions Lunar Magic claims they'll go. The directions each platform will move in also varies depending on which platform you land on; sometimes they even all move in one direction, even if they're not meant to. The game even gets confused when reversing the directions of the platforms; they don't always change direction when they're supposed to.
-->
* 飛ぶ足場を2つ以上同時に稼働させても、一概にLMの指定する方向に動き出さない。向きは足場のどれに乗るかに影響を受ける。たまに指定されてもいないのに全部が同じ方向に動き出すことさえある。足場が向きを変えるときも同じようなバグがある。つまり、指定通りに向きが変わらないことがある。

<!--
* Landing on multiple moving platform sprites at the same time will cause their effects on Mario's position to stack. This means if Mario lands on two platforms moving right, he'll slide across them to the right.
-->
* 複数の動いている足場スプライトに同時に乗った時、マリオはそれぞれのスプライトの作用を受ける。例えば、マリオが右方向に動く2つの足場スプライトに乗ると、マリオは右方向に滑っていく。

<!--
* Any non-solid solid block will be overwritten when a tile-replacing sprite passes over it (e.g. vine, mushroom scale, growing/shrinking pipe, etc.). This includes ropes, ledges, and rotating turnblocks (however, the latter will return to a turnblock after its spin timer runs out).
-->
* ソリッドブロックでないタイルは全て、ツタ・キノコ足場・伸び縮みする土管などのタイルを上書きするスプライトによって上書きされる。足場や回り続けるクルクルブロックなども含む。ただし叩いたクルクルブロックを上書きしても、クルクルブロックで再上書きされる。

<!--
* When a vine sprite is spawned, it will always overwrite the block directly above it with a vine, even if it's a solid block.
-->
* ツタ生成スプライトが出現したとき、そのスプライトの1マス上はソリッドブロックであっても上書きされる。

<!--
* The creating/eating block will immediately stop its path when another creating/eating block is spawned. It will resume movement when another brown block is touched.
-->
* 動くプンプンブロックは別のプンプンブロックが読み込まれるとすぐに動きを停止する。オブジェクトのプンプンブロックが踏まれると動きを再開する。

<!--
* If a block is hit and bounces as the creating/eating path block sprite is about to eat it, it will be skipped over without being eaten.
-->
* 動くプンプンブロックがブロックを通る直前に、そのブロックを叩いて跳ねさせると、上書きされない。

<!--
* The eating path block sprite can skip over empty tiles without disappearing if there is a solid block in the tile to the right of it.
-->
* 動くプンプンブロックは空きタイルを、そのタイルの右側にソリッドブロックが配置されていれば、消えることなく通り抜けることができる。

<!--
* The eating path block sprite makes some unusual decisions when path finding. When given a choice of up or down, it will fly diagonally downward to the right at high speed (eventually latching back onto a block 16 tiles right and 11 tiles down). A choice between left and up/down will result in it going right (making it disappear unless the previous glitch is used). A choice between up, right, and down will send it downward, but will briefly accelerate as it changes direction; if this occurs 4 times, the block will shoot downwards until it despawns. A choice of up, left, and right will move it slowly downward and to the right, before correcting itself and taking the right path. Finally, a choice of all four directions will send it flying diagonally upward to the right at a very high speed. [Video](https://youtu.be/GIN1To_Nwqg)
-->
* 動くプンプンブロックは与えられた経路によって変な動きをしたりする。上下なら高速で斜め右下に吹っ飛ぶ（16タイル右11タイル下にブロックがあると、それに反応し後退する）。上下左なら、右に進む（上下のバグを使わない限り消える）。上下右なら下に1タイル素早く進む。これが4回起こると、画面下に向かって落ちていく。上左右ならゆっくり右下に進む。上下左右なら高速で右上に吹っ飛ぶ。 [Video](https://youtu.be/GIN1To_Nwqg)

<!--
* The eating path block sprite makes even unusual decisions when given the choice between paths on Layer 1 and Layer 2. Most setups will send the block flying in some direction.
-->
* 動くプンプンブロックはレイヤー1とレイヤー2のブロックが進む方向にある時、普通でない動きをする。大抵は吹っ飛ぶ。

<!--
* If a block gets hit as an eating path block sprite passes over it, the block will respawn after the bounce sprite animation is finished, even though the path block should have deleted it. Notable in that it can cause the eating path sprite to backtrack.
-->
* 動くプンプンブロックが通過する時ブロックが叩かれると、バウンススプライトのアニメーションが終わってから、そのブロックが再出現する。動くプンプンブロックはそれを認識して引き返すことがある。

<!--
* Plantaporting: If there is a wall springboard at either y=12 or y=13, falling in a pit directly beneath it will warp Mario on top of it.
-->
* プランタポーティング:緑のバネがY座標12・13に配置してあるとき、バネの下の辺りに落ちると、マリオがバネの位置に瞬間移動する。

<!--
* If a wall springboard is crossing the edge of the screen, its interaction will loop to the other side. In order for it to work, however, the base sphere of it has to be fully onscreen.
-->
* 緑のバネが画面端にかぶっている時、判定が逆側の画面端にループする。本来の判定の部分も正常に機能する。

<!--
* Mario can not be crushed by solid blocks while he is standing on a wall springboard. This can be used to drop him through solid blocks or through ceilings.
-->
* 緑のバネに乗っているときは、ソリッドブロックの中で圧死しない。これを利用してソリッドブロックや床や天井を抜けられる。

<!--
* Similar to the plantaporting, if a Wiggler is placed at y=13 or any position above, Mario can bounce off of it by falling into a pit directly beneath.
-->
* y=13以上の高さに配置されたハナチャンの下の位置に落ちると、マリオはハナチャンを踏むことできる。

<!--
* Landing on a Wiggler as its head is turning on a corner can cause it to become stuck on the corner, or occasionally will fall off the edge. If it's on a ledge, it will always fall down.
-->
* 崖で反転する瞬間のハナチャンを踏むと、ハナチャンが崖の位置で固定されたり崖から落ちることがある。

<!--
* Although Mario can not be killed by the segments of a falling Wiggler, each of them can still be jumped on.
-->
* 落下中のハナチャンの胴体に触れてもマリオは死なず、踏むことはできる。

<!--
* Wigglers can't be killed by a Bob-omb being bumped into them, but will still turn around when touching one. This can be used to push a Wiggler off the edge of a ledge or into walls.
-->
* ハナチャンはマリオに押し出されたボム兵に触れても死なず、向きを変える。これを使うことで、ハナチャンを崖から落としたり、壁に押し込めることができる。

<!--
* If a Wiggler gets pushed inside a block, it will either be pushed into the ground (if on top of a ledge) or shot 33 tiles into the air (if on top of a solid block), ignoring all solid tiles in the way.
-->
*ハナチャンはブロック中に押し込まれると、ソリッドブロック以外の上にいる場合は床下に抜ける。ソリッドブロックの上にいる場合は33タイル上に間のソリッドブロックを素通りして急上昇する。

<!--
* Certain sprites will hurt Mario directly even if he's riding Yoshi, rather than knocking him off. These include Wigglers, Dino Torch flames, Fishin Boo's flame, and Mega Moles.
-->
* 一部のスプライトはYに乗っているマリオをYから降ろさせずに直接ダメージを与える。ハナチャンやチビライタの炎、スプークの炎やインディなど。

<!--
* Mario can still be hurt by a Wiggler's segments or a Dino Torch's flames even while the corresponding sprite is on Yoshi's tongue. In fact, combined with the above glitch, Mario can be hurt by the sprite on Yoshi's tongue even while he's still riding Yoshi.
-->
* ハナチャンやチビライタはYの舌につかまっていても、マリオはハナチャンの断片やチビライタの炎からダメージを食らうことができる。上記のバグと組み合わせて、Yに騎乗したまま、舌で掴んだスプライトによって直接ダメージを食らうことができる。

<!--
* Wigglers can be killed by star power if the Wiggler is onscreen and Mario is offscreen one screen above it.
-->
* マリオがスター状態でハナチャンが画面内にいるとき、マリオがハナチャンより1画面分上の画面外の位置にいくとハナチャンを倒せる。

<!--
* While on the backside of a fence, Mario will still interact with: wall springboards, the Fishin' Boo's flame, the Dino Torch's flame, and Wigglers.
-->
* マリオが金網の裏にいても、緑のバネ・スプークの炎・チビライタの炎・ハナチャンなどと接触判定をもつ。

<!--
* If a sprite is on top of a growing/shrinking pipe as it is expanding, the sprite will end up stuck inside.
-->
* スプライトが伸び縮みする土管の上にいると、伸びた時内部に固定される。

<!--
* Killing a growing/shrinking pipe (by using a null sprite to mess with its properties) will cause it to act strangely; it will still try to act like normal and spawn pipe tiles, but it'll move horizontally at the same time. If Mario strays too far from it, it'll stop its normal functionality and fall off the bottom of the screen.
-->
* ヌルスプライトを用いた性質変更で伸び縮みする土管を倒すと、奇妙な動作をする。通常と同じように土管タイルをスポンしようとするが、土管は水平方向に移動する。もしマリオが土管から離れすぎると、土管は伸び縮みは止め、画面下に落ちる。

<!--
* Mushroom scales and growing/shrinking pipes will overwrite any tiles they pass over, regardless of whether they are solid or not.
-->
* きのこ足場と伸び縮みする土管はソリッドであろうとなかろうと、あらゆるタイルを上書きする。

<!--
* Mushroom scales will "lock" their position every 8 tiles.
-->
* きのこ足場は8タイル毎にロックされる。

<!--
* Flying red coins can be burned.
-->
* 飛んでいる赤コインは可燃性。

<!--
* Burning a Lakitu with a fireball rather than jumping on him will cause its cloud to never disappear.
-->
* 雲に乗っているジュゲムをファイアで燃やすと、マリオが乗るまで雲は消えない。

<!--
* If a priority swap replaces Lakitu, its cloud will never disappear.
-->
* スプライト優先度によるスロット上書きでジュゲムを消すと、雲が消えなくなる。

<!--
* Pressing both A and B at the same time while riding in a Lakitu cloud will cause Mario to spinjump out of it.
-->
* 雲に乗っている時に、同時にABを押すとスピンジャンプをして雲から出る。

<!--
* Pressing both up and down at the same time while in a Lakitu cloud will cause Mario to duck while moving upward. If you press up against a ceiling and then release down, Mario will get his head stuck in the ceiling and be pushed leftward.
-->
* 雲に乗っている時に、上下を同時押しすると、マリオがしゃがみながら上昇していく。デカでこれをして、天井にくっついてからボタンを離すと、頭が天井にめりこみ、マリオが左に押されていく。

<!--
* Landing in a Lakitu cloud on the same frame that Mario would enter a wall far enough to walljump will push Mario inside and through the wall.
-->
* 壁にひっかかれる速度で雲に乗ると、壁を貫通できる。

<!--
* Lakitu's Cloud will not despawn offscreen, so it can loop across the level in any direction.
-->
* 雲は画面外で消えないため、そのレベル内でどの方向でもループする。

<!--
* Since Lakitu and his cloud are separate sprites, having enough slots filled will cause only the Lakitu to spawn. Instead of flying around and throwing spinies, though, he'll just float in midair.
-->
* 雲に乗っているジュゲムは2つのスプライトに分けられている。出現するときに2スロット余っていないと、ジュゲムのみが位置が固定された状態で出現する。

<!--
* Killing a Lakitu with a capespin, quake sprite, or net punch will cause whatever sprite is in slot 9 to have its stun timer set to 31.
-->
* ジュゲムをマント回転・揺れスプライト・金網パンチなどで倒すと、スロット#9のスタンタイマーが31に設定される。

<!--
* If Lakitu spawns without its cloud, killing it by jumping on top of it will cause whatever sprite is in slot 0 to have its stun timer set to 31. If Lakitu has already spawned previously in the level, it will instead stun whatever slot Lakitu's cloud was last in.
-->
* ジュゲムが雲なしに出現した時、ジャンプで踏んで倒すと、スロット#0のスタンタイマーが31にセットされる。もしそのレベル内で既に別のジュゲムが出現していた場合、雲が最後にあったスロットのスタンタイマーがセットされる。

<!--
* Mario can still collect the Fishin' Lakitu's 1-up while dying. [Fix](http://www.smwcentral.net/?p=section&a=details&id=6108)
-->
* マリオは死亡中にジュゲムが吊るしている1upをとることができる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=6108)

<!--
* Lakitus will run into issues if there is more than one cloud spawned at a time. Both clouds will end up spawning spinies, while the Lakitu will only actually be present in the one with a higher slot. Killing the Lakitu will only destroy the cloud he was originally meant to spawn in, rather than the one he's actually in. [Video](https://twitter.com/Kaizoman666/status/824102759377104896)
-->
* アッパレはアッパレ用の足場スプライトが同時に2つ以上存在するとバグを引き起こす。ハンマーと当たり判定は元の足場にくっついたままだが、アッパレの表示はスロットが小さい方に付随する。アッパレの有無に関わらず、どちらの足場スプライトを叩いてしまえばアッパレを倒せる。[Video](https://twitter.com/Kaizoman666/status/824102759377104896)

<!--
* Hammer Bros. will run into issues if there is more than one flying platform spawned at a time. The hammers and sprite hitbox will remain attached to the original platform, but the Bro's graphics will end up on the platform with the lowest sprite slot. Hitting any platform will kill the Hammer Bro, regardless of whether he is on it or not.
-->
* アッパレはアッパレ用の足場スプライトが同時に2つ以上存在するとバグを引き起こす。ハンマーと当たり判定は元の足場にくっついたままだが、アッパレの表示はスロットが小さい方に付随する。アッパレの有無に関わらず、どちらの足場スプライトを叩けばアッパレを倒せる。

<!--
* Hammer Bros will start throwing hammers while they are sinking in lava. [Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#02DA60)
-->
* アッパレは溶岩に沈んでる最中、ハンマーを投げる。[Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#02DA60)

<!--
* Hitting a Hammer Bro. platform and then moving it (via sprite slot storage and spitting it out) before the hit animation finishes will cause its movement pattern to change, potentially making it travel extremely high upwards at a very high speed. [Video](https://www.youtube.com/watch?v=N7u-WvMZDv4)
-->
* アッパレの足場を叩いて、叩かれたアニメーションが終わらない内に（スプライトスロットに保存して吐き出すことで）別の位置に移転させると、その移動パターンが変わる。例えば超高速で上がることがある。[Video](https://www.youtube.com/watch?v=N7u-WvMZDv4)

<!--
* If a Podoboo's spawn position is exactly 22 tiles above the lava it ends up in, when the Podoboo jumps out, it will end up jumping significantly higher than it should (approximately 34 tiles above the spawn position).
-->
* バブルの配置座標が溶岩から丁度22タイル上の時にバブルが飛び上がると、本来の位置より高く（出現位置から約34タイル上）まで上昇する。

<!--
* Freezing the game (via $9D) while the Falling Spike is falling will cause its Y speed to reset.
-->
* $9Dでフリーズさせると落下する棘のY速度がリセットされる。

<!--
* The Falling Spike sprite doesn't actually interact with Mario until it starts to fall.
-->
* 落下する棘は落下を始めるまでマリオとの判定がない。

<!-- 
* If a room has the castle candle flame cluster sprite, then whatever the last sprite loaded into slot 3 was will appear in the room in state 7 (swallowed by Yoshi). If no sprite has spawned into slot 3 yet, then it will have sprite ID 0 (shell-less green Koopa).
-->
* 城の蝋燭炎のクラスタースプライト（クラスタースプライト05）が出現すると、最後に第3スロットに保存されたスプライトが状態7（ヨッシーに含まれている）で出現する。第3スロットがずっと空きだった場合、登場するスプライトのIDは0（裸緑ノコノコ）になる。

<!--
* The Mario proximity detection routine for sprites (e.g. for Thwomps, falling spikes, Yoshi eggs, etc) loop across the screen borders.
-->
* マリオが近づくと反応するスプライト（ドッスン・落下する棘・ヨッシーの卵など）の判定は画面端でループする。

<!--
* Thwomps will only interact with blocks that their left side touches.
-->
* ドッスンは左側にあるブロックにしか反応しない。

<!--
* When Thwomps hit a very steep slope, they shift slightly to the side.
-->
* ドッスンはとても急な坂に着地すると、少し横にずれる。

<!--
* Thwomps will lock their position every 16 tiles, preventing them from rising back up if they fall too far. Similarly, a Thwomp can get pushed up above its spawn position if it lands on a slope or a slightly offset Layer 2, which will cause it to rise up to the next lock position instead.
-->
* ドッスンは固定位置を16タイル毎に更新する。坂や動くレイヤー2に着地し、ドッスンが出現位置より上にずらされると、次の固定位置まで上昇していく。

<!--
* While rising back to their original position, Thwomps will ignore any blocks in the way.
-->
* ドッスンは元の高さに戻るとき、道中にあるブロックを無視する。

<!--
* Thwimps can jump through corners where two solid blocks touch diagonally.
-->
* コトンは斜めに配置された2つのソリッドブロックの間を抜けられる。

<!--
* If a Thwimp jumps into a wall, it will lodge itself into the side of the wall to land on it.
-->
* コトンの軌道に壁があると、壁に着地する。

<!--
* Mario can pass through the bottom half of the grey castle block sprite so long as he has no upwards Y speed. As a side effect, it also won't force small Mario or a ducking big Mario into walls.
-->
* 城の灰色の左右に動く足場スプライトの下半分はマリオの上向きY速度がない場合素通りできる。

<!--
* Hitting the grey castle block sprite from below when $C2 is 0 (where the block will be stationary before moving left) will cause it to immediately start moving left.
-->
* 城の灰色の左右に動く足場スプライトを$C2が0のとき（64往復後の静止状態）に叩くと、即座に左に動き始める。

<!--
* Mario can fit between two Wooden Spike sprites without being hurt, even if they're directly next to each other.
-->
* マリオは隣接した上下移動する木のトゲの間をダメージを受けずにめり込むことができる。

<!--
* Mario doesn't actually have to be touching the spike part of a wooden spike to take damage; the entire interior will hurt him.
-->
* マリオは上下移動する木のトゲのトゲ部分に触れてもダメージは受けない。木のトゲの内部に触れるとダメージをくらう。

<!--
* Mario can vertically pass through a Wooden Spike sprite without being pushed out, so long as he enters them directly through the top/bottom (but he will take damage in the process).
-->
* マリオは上下移動する木のトゲを上下どちらの方向にでも貫通して移動できる。ただし基本的にはダメージをくらう。

<!--
* The Hopping flame's remnants normally don't hurt Mario when they're flickering, but freezing the game (via $9D) will still cause him to get hurt by them.
-->
* バウンドファイアの火の粉は点滅を開始すると、普通はマリオにダメージを与えないが、$9Dでフリーズするとダメージを与える。

<!--
* The Sumo Bro's lightning will continue falling even if the game is frozen by $9D. During a screen scroll, it will not interact with solid objects during that time either.
-->
* K.K.の雷は$9Dでフリーズしている間も落下し続ける。フリーズ中、雷はソリッドオブジェクトとの判定を持たない。

<!--
* The Sumo Bro's lightning will infinitely loop vertically until they hit a block. Will takes some time to fall, though.
-->
* K.K.の雷はソリッドオブジェクトに当たるまで、垂直方向でループし続ける。

<!--
* If the first division is filled, the flames from Sumo Bro's lightning will spawn in strange positions.
-->
* スプライトスロットの分割1が埋まっていると、K.K.の雷による炎が通常と異なる位置に出現する。

<!--
* The Sumo Bro's flames may occasionally borrow graphics from other onscreen sprites. If the sprite is in slot 0, it will often actually warp to the position to the flame. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4242)
-->
* K.K.の雷による炎は時折、画面内の別スプライトから表示を借りる。もしそのスプライトがスロット0ならば、表示だけではなくスプライト本体も炎の位置に瞬間移動する。 [Fix](http://www.smwcentral.net/?p=section&a=details&id=4242)

<!--
* If a Sumo Bro walks off a ledge, it will fly in that direction until it lands on something. This can also lodge it into walls.
-->
* K.K.が崖を踏み外すと、足場にたどり着くまで滑空する。壁にめり込むこともある。

<!--
* Touching one of the three-platform sprite on the frame it spawns (by scrolling the screen all the way over and sticking to the side of the screen) will cause Mario to be warped leftward. This will send him through solid blocks, as well as still leave him with the ability to jump. [Vid](http://i.imgur.com/4SXCGtL.gif)[eos](https://twitter.com/Kaizoman666/status/805900722680328192)
-->
* 回転する3つの足場スプライトが読み込まれるFに（画面をスクロールしたりして画面を片方に寄せるなどして）それに触れると、マリオが左方向に瞬間移動する。ソリッドブロックを貫通し、ジャンプできる状態で瞬間移動する。[Vid](http://i.imgur.com/4SXCGtL.gif)[eos](https://twitter.com/Kaizoman666/status/805900722680328192)

<!--
* Freezing the game with $9D on the frame one of the middle three flames from the Sumo Bros' lightning spawns will cause all of the other flames to spawn at once, and additionally may spawn a few extra ones as well. Of note, one of these extra flames can spawn 12 tiles to the right of where the lightning originally hit. [More info](http://smwc.me/1237494)
-->
* K.K.の雷の中心三本の炎が発生するFで$9Dでフリーズさせると、全ての炎が同時に出現し、さらにもう数本追加で出現する。余剰炎の一本は雷が発火した地点から12タイル右に生成される。[More info](http://smwc.me/1237494)

<!--
* When touching a revolving brown platform without actually being on it, some timers will decrease twice as fast. These include $1490 (star power timer), $18AC (Yoshi swallow timer), $18AE (waiting to stick Yoshi's tongue out timer), and $151C (Yoshi's tongue extension distance).
-->
* When touching a revolving brown platform without actually being on it, some timers will decrease twice as fast. These include $1490 (star power timer), $18AC (Yoshi swallow timer), $18AE (waiting to stick Yoshi's tongue out timer), and $151C (Yoshi's tongue extension distance).

<!--
* Mario can pass through any solid blocks while riding a revolving brown platform, though he'll still be pushed left and killed if he ends up fully surrounded.
-->
* マリオは回転する茶色足場に乗ってる間はあらゆるソリッドブロックの中を通り抜けられるが、四方の接触判定があると、左に押され圧死する。

<!--
* Jumping on a dolphin as it is rising quickly may cause Mario to fall through it. Though less useful, this can also occur with revolving brown platforms.
-->
* イルカが上昇している時にジャンプをすると、イルカを通り抜けて落ちることができる。意味は無いが、回転する茶色足場でも可能。

<!--
* In certain levels, dolphins will treat the area offscreen above the level as water, which in turn causes them to jump infinitely upwards until they eventually loop and despawn at the bottom.
-->
* 一部のレベルでは画面上がイルカにとって水中判定になっており、画面下にループし消えるまで、画面上でジャンプし続ける。

<!--
* Once a dolphin touches lava, its timer to jump will be set. As soon as that timer runs out, the dolphin will perform the jump, even if it's no longer actually in water.
-->
* イルカは一回溶岩に触れると、ジャンプするタイマーがセットされる。そのタイマーが0になると、水中でなくてもジャンプをする。

<!--
* Skull rafts can travel through solid blocks, as they only acknowledge the tops of blocks.
-->
* ドクロリフトはソリッドブロックの上も移動する。

<!--
* If a skull raft encounters a left facing very steep slope, it will get stuck and become unable to progress. Running onto the raft in this state can potentially clip Mario through the slope, as well.
-->
* ドクロリフトがとても急な坂にぶち当たると、坂にはまって進まなくなる。この状態のドクロ足場に走って乗ると、坂を抜けられることがある。

<!--
* Torpedo Teds and Fishbones will still act like they're alive when killed; you can still be hurt by it or spinjump off of it. You can't kill it a second time, though, unless you have a star. [Fix](http://www.smwcentral.net/?p=section&a=details&id=11522)
-->
* トーピードとフィッシュボーンは一度倒されても、生きているように行動し続ける。一度倒してもスピンジャンプしたりダメージを受けたりする。通常は一度しか倒せないが、スターであれば何度でも倒せる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=11522)

<!--
* Stomping on a Dry Bones that stays on ledges on the the frame it turns around at the edge of the ledge will cause it to fall off the ledge.
-->
* カロンを崖で振り向くFに踏むと、カロンが崖から落ちる。

<!--
* Normally, Mario isn't able to jump through the bottom of a moving ghost house hole (due to it being a pixel too high). Clipping through the ceiling through any method (including just simply spinjumping off Yoshi) will push him far enough in, though.
-->
* 普段ならお化け屋敷の動く穴が1ピクセルほど高いためマリオは下から上がれないが、天井に嵌まるような動き方（例えばYをスピンジャンプで降りるなど）では通れる。

<!--
* The moving Ghost House hole sprite will allow Mario (and other sprites) to fall through any solid block as long as he is touching it, not just through the blocks it actually covers. When riding Yoshi, his hitbox is large enough to pass through a tile as far as three blocks below the sprite.
-->
* お化け屋敷の動く穴が素通りさせるソリッドブロックはスプライトが直接触れているのだけでなく、マリオがスプライトに接触している限りあらゆるブロックが対象である。Yに騎乗している当たり判定だと穴の3タイルほど下にあるブロックまですり抜けられる。

<!--
* Certain sprites will not pass through moving Ghost House holes. [List](https://pastebin.com/Gvgea42u)
-->
* 特定のスプライトはお化け屋敷の動く穴を通り抜けない。[List](https://pastebin.com/Gvgea42u)

<!--
* If a moving ghost house hole is despawned while Mario is interacting with it ($185C has a non-zero value), the flag that makes Mario pass through objects won't be cleared, and you'll pass through all objects in the level as a result. This will not be corrected until a new ghost house hole spawns in the same slot as the original.
-->
* お化け屋敷の動く穴がマリオと触れている間（$185Cが0以外の値の時）に消えると、そのフラグの値が変化しなくなる。フラグの値が0以外の時、マリオはオブジェクトとの判定がなくなる。これはお化け屋敷の動く穴が消えたのと同じスロットに新たに出現するまで治らない。

<!--
* If a moving ghost house hole is despawned while any sprite is interacting with it ($15DC has a non-zero value), the flag that makes the sprite pass through objects won't be cleared, and the sprite will pass through all objects in the level as a result (however, other sprites will still interact with it). This will not be corrected until a new ghost house hole spawns in the same slot as the original.
-->
* お化け屋敷の動く穴がスプライトと触れている間（$15DCが0以外の値の時）に消えると、そのフラグの値が変化しなくなる。フラグの値が0以外の時、そのスプライトはオブジェクトとの判定がなくなる。これはお化け屋敷の動く穴が消えたのと同じスロットに新たに出現するまで治らない。

<!--
* If Mario is pushed off of a moving rope mechanism by a block, the game will continue to think he is in front of the sprite and will let him grab onto and jump off of the rope as if it is still there. However, this effect will be broken if he passes in front of another rope sprite, unless he is holding an item. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8784)
-->
* 月歩:マリオがロープを掴んでいる最中、プロックに押されると、マリオは常にそのスプライトの前にいると認識されるようになり、どこにいてもそこにロープがあるように掴んでりジャンプしたりできる。この効果は別のロープスプライトの前にアイテムを持ってない状態で、通りかからない限り解除されない。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8784)

<!--
* As an alternative to the above, the "climb anywhere" rope mechanism glitch can also be activated by grabbing onto the very far edge of a rope mechanism (so that Mario immediately falls off) at the same time he interacts with the side of a block, even if the mechanism isn't moving directly into said block. [Video](https://cdn.discordapp.com/attachments/167412470862970881/462505481898950676/smw-climbing-glitch-new_00000.gif)
-->
* 上記のバグはロープスプライトの掴んだ瞬間離れてしまうような端っこを掴むと同時にブロックの側面に触れることでも起こすことができる。これはロープスプライトがブロックの方向に動かない場合でも行える。[Video](https://cdn.discordapp.com/attachments/167412470862970881/462505481898950676/smw-climbing-glitch-new_00000.gif)

<!--
* When climbing upward on a moving rope mechanism, Mario will not interact with the tops of blocks. This can be used to enter solid blocks when the mechanism moving downward or falling.
-->
* ロープを掴んで上向きに登ると、マリオはブロックの上面との判定を持たない。ロープスプライトが下向きに移動中か落下中になら、ソリッドブロックにめり込める。

<!--
* If you press up in front of a moving rope mechanism for a single frame or land on the ground while holding it, Mario will be "pulled" by the rope even though he isn't holding it. This can also be used to retain a spinjump when jumping off of the rope. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8785)
-->
* マリオが地面に足がついた状態でロープの前で1Fだけ上入力をすると、掴んでいないのにロープに引っ張られる。またスピンジャンプ中に1Fだけ上とAかBを入力をすると、スピンを維持したまま再びジャンプする。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8785)

<!--
* Mario can be slightly offset while riding on a moving rope mechanism if he grabs on and holds the direction opposite to the direction the rope is in (though offsetting vertically without a block to assist Mario is only possible while big). This can let Mario fit in gaps that normally would not be possible while riding the rope.
-->
* ロープに掴まっているとき、マリオがロープの動いている方向の逆に動き続けることで少しだけ位置がずれることはある。（しかし、垂直にずれるのはブロックを頼りにしなければデカの場合だけ可能。）これによって普通に掴んでいたら通れない隙間を通れるようになることがある。

<!--
* If a line-guided sprite hits either tile 096-099 or a tile on Map16 page P with position X such that P & (0x80 >> (X % 8)) != 0 while falling, the tile will end up acting like whatever the last lineguide tile the sprite touched was. Then, one of two things will happen. If the sprite hits the block where the "start" of that rope tile is, it will latch on and function as it normally would if it were actually a guide. Otherwise, the sprite will end up warping vertically, with the distance depending on the sprite and certain conditions (specifically, how addresses $08 and $0A were modified prior to $01D938). For most of the sprites, this occurs in the OAM write routine making it difficult to manipulate, but for the Grinder and Fuzzy it's instead based on the Mario proximity routine, where it'll warp to the top of the subscreen Mario is on so long as he's within a 10x12 space around the sprite (though this space also repeats every 16 tiles in any direction).
-->
* If a line-guided sprite hits either tile 096-099 or a tile on Map16 page P with position X such that P & (0x80 >> (X % 8)) != 0 while falling, the tile will end up acting like whatever the last lineguide tile the sprite touched was. Then, one of two things will happen. If the sprite hits the block where the "start" of that rope tile is, it will latch on and function as it normally would if it were actually a guide. Otherwise, the sprite will end up warping vertically, with the distance depending on the sprite and certain conditions (specifically, how addresses $08 and $0A were modified prior to $01D938). For most of the sprites, this occurs in the OAM write routine making it difficult to manipulate, but for the Grinder and Fuzzy it's instead based on the Mario proximity routine, where it'll warp to the top of the subscreen Mario is on so long as he's within a 10x12 space around the sprite (though this space also repeats every 16 tiles in any direction).

<!--
* Pressing left and right at the same time will cause the directional coins to, oddly, move upwards.
-->
* 同時に左右入力をすると、コントロールコインは上方向に進む。

<!--
* The directional coin sprite does not become solid if a P-switch is pressed, even though its graphics do. This can cause Mario to be crushed by the blocks it creates, since he doesn't get pushed out of the way. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8751)
-->
* コントロールコインは青Pが押されて茶色ブロック表示になっても、ソリッドにはならない。コントロールコインはマリオを外に押し出されないので、マリオは圧死することができる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8751)

<!--
* The directional coin sprite will immediately terminate if the game is frozen (via $9D) on a frame it's set to generate a coin.
-->
* コントロールコインはコインを生成するFに（$9Dで）ゲームがフリーズすると消える。

<!--
* In Layer 2 and Layer 3 levels, the directional coin sprite will act strangely with Layer 1 tiles. When touching the side or bottom of a tile, it will completely overwrite the tile without stopping. If touching the tile from above, however, it will interact with the block, but will not terminate like it normally does. With solid tiles, this causes the trail to become "stuck" as it tries to move down into the tile but is forced on top of it. This extends to conveyors, which will push the trail to the side, although the sprite will not spawn coins while being moved and will remain stuck even after falling off the end. A similar result occurs for very steep slopes, although on right-facing slopes, it will briefly become un-stuck as it's pushed down. Very steep slopes are also special in that approaching their 'lower' tile from the side will still cause the sprite to get stuck, although it won't even move down the slope.
-->
* レイヤー2・3レベルでは、コントロールコインはレイヤー1タイルとの判定がおかしくなる。タイルの下から触れると、止まらずにコインで完全に上書きする。タイルに上から触れるとブロックとの判定を持つが、通常とは違って消えない。タイルがソリッドならば、くっついてるように位置が固定される。これはコンベアでも起こり、スプライトはコンベアの進行方向に徐々にずれていくが、コインを生成しない。端まで行くと動かせないまま下に進んでいく。近いことが右を向いたとても急な坂でも起こるが、頂点のタイル(1CC)に当たる度にと固定状態が短時間だけ解除される。とても急な坂の頂点ではないタイルに触れると、操作できないまま坂に沿って移動していく。

<!--
* Mario can bounce off of Rexes while walking up slopes, regardless of how steep the slope is.
-->
* 傾斜によらず坂を登っているドラボンに対面する方向から突っ込んだら踏める。

<!--
* The sea urchin sprites have a tendency to not work correctly with slopes, and occasionally will get stuck inside them, unable to move. The very steep slopes can also cause the urchins to start moving twice as fast as they normally do, and can sometimes cause them to move diagonally instead of in a straight direction.
-->
* ウニラは坂に対して正常に作動せず、内側に引きこまれ抜け出せなくなることがある。とても急な坂の場合、ウニラが2倍の速さで動いたり、斜め方向に動いたりする。

<!--
* Rip van Fish can force their way through the sides of blocks if they swim into it for long enough.
-->
* グースカはブロックの横にめり込んでいく。時間をかければ、ブロックを貫通させられる。

<!--
* Rip Van Fish completely ignores Layer 2, even if sprites are set to interact with it.
-->
* スプライトがレイヤー2と反応する設定のとき、グースカはレイヤー2を完全に無視する。

<!--
* When flopping out of water, the standard fish sprites have a small chance of clipping inside a block upon hitting its side. This will cause the fish to either climb up the wall or clip straight through it.
-->
* ばたついているプクプクがブロックの側面に衝突すると低い確率で嵌まることがある。その後はブロックの上に登ったりブロックの向こう側まですり抜けることがある。

<!--
* All underwater enemies other than basic fish will still act as if they're in water even when they're not; the only difference is that they'll sink downward as they move around.
-->
* 普段水中にいる敵は普通のプクプクを除いて水を出ても、動いている間だんだん位置が下がること以外その行動に変化はない。

<!--
* If a Whistling Chuck that wakes up fish is hit by a shell in a lower sprite slot on the frame he starts whistling, then he will summon Super Koopas as well. [Video](https://youtu.be/E6MGW_yNyi8)
-->
* 口笛を吹くブルが口笛を吹くFに下位のスロットのスプライトで倒すと、マントノコノコが現れるようになる。[Video](https://youtu.be/E6MGW_yNyi8)

<!--
* When smashing through blocks, Chargin' Chucks will only check the bottom block of a wall; this means that the block on top will be broken, regardless of what type of block it actually is.
-->
* 走るブルは上下2ブロックを破壊するが、チェックするのは下のブロックのみ。つまり下が破壊できるブロックなら、上のタイルは何であれ一緒に破壊できる。

<!--
* For 30 frames after the Clappin' Chuck claps, it won't be killable by capespins or quake sprites.
-->
* その場で跳ねるブルが跳ねた後30Fは、マント回転などの揺れスプライトなどによって倒されない。

<!--
* Jumping Bowser statues and Ninjis are able to jump through solid blocks. [Fix (Ninji)](http://www.smwcentral.net/?p=section&a=details&id=8786)
-->
* ジャンプするクッパ石像とハックンはソリッドブロックを貫通してジャンプしていく。[Fix (Ninji)](http://www.smwcentral.net/?p=section&a=details&id=8786)

<!--
* You can prevent a Bowser statue's fireball from being fired by freezing the game (via $9D) during it's spawn frames.
-->
* クッパ石像が炎を吐くFに$9Dでフリーズしていると、炎を吐かない。

<!--
* If a normal Bowser Statue is hit from below, it'll start shooting fireballs.
-->
* ただのクッパ石像を下から叩くと、炎を出すようになる。

<!--
* Hitting the Boo Block from below when it's semi-solid will cause it to immediately become fully solid.
-->
* ブロックに変身するテレサが半分ブロックになっている時に下から叩くと、即座にブロックに変身し終える。

<!--
* Boo rings have two slots for their data, but the first slot of data will only be used by the first boo ring spawned; all others will use the second slot. Since two rings can be spawned at a time, this causes the data from any two rings spawned more than six tiles apart after the first one to overlap. This means, if they're rotating in the same direction, the resulting ring will move at double speed. If they're in opposite directions, it'll instead be completely motionless.
-->
* ぐるぐるテレサのデータを司るスロットは2つあるが、その1つ目を使えるのは先に出現するぐるぐるテレサに限られている。ぐるぐるテレサは同時に2つ存在できるため、第1ぐるぐるテレサ以降出現する、タイル6つ以上離れた第2ぐるぐるテレサのデータがかぶってしまう。その場合、回転の方向が同じだと後者の回る速度が2倍になり、方向が逆だと後者の速度がゼロになる。

<!--
* If a sprite is in slot #0 while a Boo ceiling generator is active, the game will warp the sprite around the level, as if it were one of the ghosts that make up the ceiling.
-->
* 天井テレサジェネレーターが動作している状態では、スロット#0にあるスプライトが天井テレサの出現位置に瞬間移動する。

<!--
* The reappearing Boo generator will only interact with Mario on the screen the ghosts actually because visible; this mean if you travel more than a screen before they disappear, he can swim straight through them.
-->
* 出たり消えたりを繰り返すテレサは画面内に出現したテレサのみマリオと判定を持つ。つまり、テレサが消える前にマリオが1画面以上移動すると、テレサを素通りできる。

<!--
* The Big Boo Boss can be hurt by any carriable sprite, though for springboards it will only do so on the first frame it is released.
-->
* ボスレテサはすべての持ち運べるスプライトでダメージを与えられる。ジャンプ台は離したFしか判定がない。

<!--
* All large 64x64 sprites, such as Banzai Bills, Big Boos, green gas bubbles, and even Bowser, will lose interaction with Mario if they pass even a pixel past the left border of the level.
-->
* 全ての64*64の大きいスプライト、マグナムキラー・アトミックテレサ・緑の大きなガス球・クッパなどは1ピクセルでも画面左にあると、マリオとの判定がなくなる。

<!--
* When entering a room of a level, sprites will spawn facing where Mario was when he exited in the previous room, causing them to move in different directions depending on where he was. Notably, this also applies to the No-Yoshi entrance cutscenes. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4560)
-->
* マリオがレベルに入った時、スプライトはマリオが直前の部屋でいた位置を向く。マリオがいた場所次第で、スプライトを異なる方向に進む。ヨッシーを降りる入場シーンでもこれは発生する。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4560)

<!--
* Each item memory bit covers an entire vertical column (or horizontal row in vertical levels) within a subscreen. This means that, if item memory is enabled, setting the bit for a block (e.g. a coin, 1-up block, Yoshi coin, etc.) will also affect all of the other blocks in the subscreen's column/row once the level is reloaded.
-->
* アイテム記憶のビットはそれぞれサブスクリーンの縦の列を1つ管理する（垂直レベルの場合は横の列）。つまり、アイテム記憶をONに設定すればブロック（例えばコイン・1-upブロック・ドラゴンコインなど）のビットをオンにセットして、同じレベルに移動するとそのサブスクリーンの同じ列にあるブロック全てが影響される。

<!--
* When a coin is collected and permanently erased from a level, reloading the room will replace the spot the coin filled with whatever block was placed "below" it in Z-order. The same occurs with Yoshi coins, and collecting all five of them will permanently erase the coins even if item memory is untracked.
-->
* コインがマリオに取られてそのレベルから恒久的に取り除かれた後、レベルを再読み込みすると、コインのあった位置にコインより下のZオーダーに設置されていたブロックが出現する。同様のことはドラゴンコインでも発生する。

<!--
* If a Yoshi coin is placed across a screen border, collecting it will cause the coin to graphically glitch and give Mario either constant supply of lives or coins, with the level of effect varying based on his Y position within the coin. It will also erase the two tiles 14 blocks below it, looping to the next screen if necessary. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8774)
-->
* TBL（Top-Bottom-Line:LMでF2押して見える線）にまたがって配置されたドラゴンコインをとると、色々なことが起きる。コインの表示がばぐり、残機かコインが増え、コインの14タイル下（次ページにループする）が空になる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8774)

<!--
* Certain sprites, such as P-switches, will not sink in tileset-specific lava, instead landing on top of it as if it were a solid tiles. Fireballs are also included in this list, and will bounce across the top of the lava.
-->
* Pスイッチなどの特定のスプライトは、ソリッドタイルの上にあるかのように洞窟溶岩に沈まない。ファイアもこれに当てはまり、溶岩の上で跳ねる。

<!--
* Sprites will not sink in sloped tileset-specific lava tiles. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4199)
-->
* スプライトは坂の溶岩タイルに沈まない。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4199)

<!--
* Under the right conditions, a room of a level will act like normal, but all the sprites in the room will act like they're in water. [Video and more info](https://youtu.be/_MMlw8A3RiY)
-->
* リンク先の条件下では、スプライトが水中にいるように動く。[Video and more info](https://youtu.be/_MMlw8A3RiY)

<!--
* Oddly, Sunken Ghost Ship (level 018) is hardcoded to not reset the "boss beaten" flag. As a result, beating a boss in the level will cause a few strange effects in the next level Mario enters, so long as the overworld isn't reloaded in-between. One effect is that Mario will freeze in place after hitting a goal tape or sphere rather than doing a goal walk, as if a boss had beaten. A stranger effect, however, is that Yoshi will use incorrect animation frames and will behave particularly oddly. [More](https://pastebin.com/XkB8cyg0) [info](http://pastebin.com/YnNEuvYE)
-->
* ラムネ海溝の沈没船（レベル018）はハードコードされており、ボス撃破フラグがリセットされないようになっている。このレベルでボスを倒すと、OWが再読込されない限り、マリオが次に入ったレベルで幾つか奇妙な効果が引き起こされる。マリオがゴールバーやゴール玉に触れると歩かず、ボスを倒したときのようにその場でマリオが静止する。他には、ヨッシーのアニメーションが正しくないものになり、挙動もおかしくなる。[More](https://pastebin.com/XkB8cyg0) [info](http://pastebin.com/YnNEuvYE)

<!--
* Purple triangles will not work correctly in Layer 2 levels; while running sideways, Mario will not be given Layer 1 interaction, causing him to be warped straight downward. Shells may also not be flung correctly. They can work if Layer 1 and 2 overlap, however.
-->
* レイヤー2レベルでは、三角ブロックが正常に作動しない。マリオが三角ブロックで壁走りをしようとすると、真下にワープする。甲羅は三角ブロックで跳ねなくなる。これらはレイヤー1と2が重なっていると正常に作動するようになる。

<!--
* While wallrunning, Mario will ignore the standard function of whatever he is running up, so long as it is solid some of the time. This means he can run up munchers, any kind of ledge or slope, tile-set specific lava, noteblocks, and even other purple triangles. This effect also lasts for a frame after he reorients at the top, allowing him to jump normally. Additionally, he will also run through any blocks that aren't always solid on his way up the wall, including upside-down slopes, standard lava, and water.
-->
* 壁走り中、マリオはオブジェクトの通常の性質を無理することがある。ブラパ・全ての種類の坂・特定の溶岩・音符ブロック・三角ブロックも壁走りできる。この効果は頂点でマリオが水平になる前の斜めっている最中まで続く。走行中、天地逆さの坂・水・溶岩などのソリッドではないあらゆるブロックを貫通できる。

<!--
* Mario will "stick" to any platform sprites while wallrunning, slowing him down to the speed of the platform until it passes by. One notable use of this is that it even applies to the animation at the end of a wall where Mario reorients himself, but his horizontal speed will remain unaffected, which can cause him to clip into the tiles in the next column over. It should be noted that this works with the solid platform sprites as well, but only if Mario enters at a position where he doesn't get warped out of it. [Video](https://cdn.discordapp.com/attachments/167412470862970881/462945193574793216/tes27.gif)
-->
* 壁走りしている間マリオが足場スプライトに触れたら、垂直位置が足場スプライトに固定され、足場スプライトが壁を離れるまで取れない。水平の位置に影響がないため、マリオが壁の上で斜めになっている状態でバグが起動すると地面に嵌まることがある。これはソリッドの足場スプライトにマリオが瞬間移動しないように突っ込んで行うこともできる。

<!--
* If Mario starts trying to run up a purple triangle without a wall next to it, he will sometimes move upwards more than he should. If there's a solid block two tiles above the purple triangle, he can pass far enough into it such that jumping will send him straight through. Similarly, if there's a solid block one tile in front of the triangle, he can be pushed into that instead.
-->
* 隣に壁がない三角ブロックで走り上がろうとすると、まるで壁があるかのように1マス分空中を駆け上がる時がある。三角ブロックの2マス上にソリッドブロックがある時、前述の駆け上がりでソリッドブロックにめり込んだ時にジャンプすると、天井抜けができる。同様に1マス上にソリッドブロックがあると、それの中に押し込められる。

<!--
* Dying in a bonus game will produce a glitched GAME OVER message. In addition, the next time Mario enters the level he came from, he will spawn at the midpoint.
-->
* ルーレットステージで死ぬとGAME OVERの表示がバグり、再びそのステージに入ると中間位置から開始される。

<!--
* Trying to take a screen exit in a Yoshi wings room will reset the room.
-->
* Yの翼ステージ内でレベル移動すると、再びYの翼ステージになる。

<!--
* If you hit a goal tape in a Yoshi wings room and are given a bonus game, the game will reset the Yoshi wings room rather than sending you to the bonus game room or overworld. If you touch a goal tape again after this happens, the goal walk will be skipped and the room will be immediately reset.
-->
* Yの翼ステージでゴールバーを切り100スター貯めると、Yの翼ステージを再び開始する。この状況で再びゴールバーを切ると、瞬間的に再びYの翼ステージが開始する。

<!--
* During the goal walk, the screen freezes in place. If you scroll the screen left before the walk begins, Mario will end up running into the right-side screen barrier, stopping him earlier than normal. If screen exits are enabled, he'll end up even walking offscreen (and consequently exiting to the overworld) despite not technically being the edge of a level.
-->
* ゴール後の歩いている最中、画面はある地点でフリーズする。もし画面を充分左にスクロールさせていると、最終的にマリオは画面の右端にぶつかる。もしSide ExitがONで普通では画面端に触れられないレベルでも、この方法でSide Exitを利用できる。

<!--
* Mario can jump over the goal tape if he's high enough off the top of the screen for his Y position to loop.
-->
* ゴールバーの上を十分高い位置で通り過ぎれば、ゴールせずに通り抜けられる。

<!--
* Mario can jump off of a switch palace switch on the frame he lands on it. You can also extend the time Mario continues to move before freezing by hitting both the switch and a goal tape at the same time.
-->
* スイッチ宮殿のスイッチを踏むFにジャンプすることができる。スイッチを踏むのと同時にゴールバーに触れると、操作できないまま動き、メッセージが遅れて出現する。

<!--
* If Mario activates a switch palace switch but exits the level before the message appears (via dying or side exit), then the switch will count as being hit but the level's event will not be set (meaning you can reenter it).
-->
* スイッチを踏み、メッセージが出る前に（死ぬ・画面横から出るなどで）レベルから出ると、スイッチは押されたが、そのレベルのイベントは終わってないと認識される。つまり再びスイッチ宮殿に入れる。

<!--
* Keyholes will still function during the goal walk. If Yoshi has a key in his mouth during it, it can actually be activated (thus activating the secret exit on the overworld instead of the normal).
-->
* 鍵穴はゴール後の歩いている最中も有効。たとえば、Yが鍵を咥えていたら鍵ゴールが可能で、通常のゴールではなく鍵ゴール扱いになる。

<!--
* Keyholes will still function when exiting or entering a pipe, so carrying a key through the pipe can activate it.
-->
* 鍵穴は土管の出入り中も有効。鍵を持ったまま土管に入ると、鍵ゴールできる。

<!--
* Activating the end of a level in the intro level will reset the room upon fadeout.
-->
* オープニングでレベルを終える（ゴール等）と、フェードアウトしてから再びオープニングが始まる。

<!--
* Dying or hitting a goal point on the title screen will cause the game to reload the title screen level as an actual level, allowing you to play through it. Although doors will take you to other rooms still, "completing" this level with a goal point will simply loop it back. [Fix (for death)](http://www.smwcentral.net/?p=section&a=details&id=4528)
-->
* タイトルで死んだりゴールすると、タイトルのレベルでプレイできるようになる。ドアなどで別のレベルに移動しても、非デモ化する。移動先でクリアしたり死ぬと、再びタイトルのレベルに戻される。[Fix (for death)](http://www.smwcentral.net/?p=section&a=details&id=4528)

<!--
* If Mario exits the title screen level via a side exit (be it in the recording or playable version), he'll spawn near [0,0] on the main overworld.
-->
* タイトルのレベルをSide Exitで抜けると、OWの[0,0]あたりに出現する。

<!--
* Hitting a message box or spawning the display message sprite in the title screen (be it in the recording or playable version) will take Mario to the main overworld near [0,8]. If it's hit while on the recorded title screen, it will also glitch the graphics temporarily.
-->
* タイトルでメッセージボックスかメッセージスプライトでメッセージを表示させると、マリオはOWの[0,8]付近に現れる。タイトルが再読み込みされている最中にメッセージが出ると、表示が一部バグる。

<!--
* Receiving the intro message from a message box rather than a display message sprite will place Mario at an incorrect tile of the main map. Luigi, however, will still spawn in the correct position. This effect will also occur if you take a screen exit from the intro.
-->
* オープニング中、メッセージスプライトではなくメッセージボックスでメッセージを表示させると、マリオはOWで設定していない位置に出現するが、ルイージは設定した位置に出現する。これはSide Exitでレベルを終えても起こる。

<!--
* Dying in the intro or title level will take away one of Mario's lives without giving him a game over; this can cause his life counter to decrease to 0 and loop around to glitched numbers. If Mario's life counter ever hits zero, though, completing the intro level will just return him to the title screen rather than taking him to the overworld.
-->
* オープニングやタイトルでマリオが死ぬと、マリオを操作できるようになる。操作できるようになってから、残機0で死ぬと、ループしてバグった値になる。残機が0以下のときにオープニングレベルを終えても、OWに行かずにタイトル画面になる。

<!--
* Dying in the intro level will always take Mario back to the level's primary entrance, even if he hit a midpoint.
-->
* オープニングで中間を取ってから死んでも、開始位置は必ず初期位置になる。

<!--
* If Mario enters a room with an incorrect FG initial position, he may be killed by the vertical screen borders.
-->
* レベルに設定されている開始位置が正しくないFG位置だと、レベルを開始しても死ぬ。

<!--
* Entering a room with Layer 2 horizontal scrolling set to "none" will cause it to inherit the Layer 2 X position from the previous room. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4263)
-->
* レイヤー2の水平スクロール設定が「なし」に設定されているレベルに入ると、入る前のレベルのレイヤー2のX位置を受け継ぐ。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4263)

<!--
* The long sideways Layer 2 scroll sprite has some odd effects when used in horizontal levels. Placing it at Y=0 will cause it to act like a leftward conveyor. Y=1 to Y=3 will cause Mario to shake when standing on layer 2, and Y=4 will cause both Layer 1 and Mario to constantly shake. Y=5 and below will for the most part either crash or hardlock the game.
-->
* 長いレイヤー2スクロールを発動させるスプライトを横レベルに置くと変な作用がある。Y=0の位置に置く場合は左向きコンベアのようにふるまう。Y=1から3までの場合はマリオがレイヤー2に立っている間揺れるようになる。Y=4の場合はレイヤー1とマリオがずっと揺れる。Y=5以上の場合はだいたいクラッシュかハードロックする。

<!--
* Any of the Layer 2 scroll sprites intended for vertical levels will kill Mario upon spawning if Mario isn't already spawning on the same screen they are.
-->
* 全てのレイヤー2スクロールスプライトは縦ステージで使われると、マリオは出現位置がどこであれ死ぬようになる。

<!--
* Wrong warp: Taking a screen exit 256 times will reload the level from the overworld. The issue with this, however, is that the space of RAM meant for overworld data gets overwritten by level data during level load. This cause the game to try to loading the tile in the level data where the level would be in the overworld data as the translevel number to spawn Mario into. Not only does this potentially allow you to warp to any level in the game (even unused ones), it also can cause some strange effects, such the level getting used as a No-Yoshi entrance in places not meant for one. It should be noted, however, that the No-Yoshi entrance prevents a level from being warped to, as it will load the correct level after being run. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4254) - [Video](https://www.youtube.com/watch?v=v_iv_9QJ6lQ) - [Diagram](http://i.imgur.com/ZcNDrAA.png)
-->
* Wrong warp：コース内でレベルを256回もロードするとコースが改めてOWから読み込まれる。しかし、OWが送り先を決めるために使うRAMがレベルの読み込みで上書きされるため、OWのタイルのデータが入ったはずの位置に実際にレベルのタイルがあり、それが送り先のレベルとして採用される。これで未使用レベルを含めたあらゆるレベルがロードできるだけでなく、送り先がヨッシー禁止の前置きがないはずのコースでもそれとして使用されるなど妙な効果が出ることもある。なお、送り先のレベルにヨッシー禁止の前置きがある場合は、前置きの後に正しいレベルに移動する。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4254) - [Video](https://www.youtube.com/watch?v=v_iv_9QJ6lQ) - [Diagram](http://i.imgur.com/ZcNDrAA.png)

<!--
* When placed next to a screen border, both the screen exit on that screen and the one the door is touching can be accessed depending on Mario's position. Similarly for pipes.
-->
* ページの境目に配置されたマップ移動を利用するとき、マリオの位置でどちらの移動先か決まる。

<!--
* Screen exits are inherited from the previous sublevel, meaning that a door will send you to whatever the last loaded exit on a screen was; it only sends Mario to level 0 if no exit has been loaded yet. This means a room can technically have multiple screen exits on the same screen in vanilla SMW, depending on what level you enter the room from.
-->
* 移動設定は前のレベルのを引き継ぐ。つまり、ドア等は最後に読み込まれた移動先にマリオを届け、移動先が一度も読み込まれてないとマリオをレベル0か100に移動する。この仕様によりバニラハックでも、前のレベルに依存する複雑で多岐にわたるレベル移動にすることが可能。

<!--
* Layer 3 tide interaction with most floating platforms is broken and may cause them to float infinitely upward. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8773)
-->
* レイヤー3の潮流はほとんどの浮かぶ足場との関係が壊れており、足場が無限に上昇し続ける。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8773)

<!--
* If a level has Layer 3 tides active and is less than 3 screens long, then sprites anywhere on the screen can occasionally register themselves as being in water. In 1- or 2-screen rooms, the effect will occur longer and more often the further left the screen is; in 3-screen rooms, it will only occur right of the screen when the screen is all the way at the left edge of the level.
-->
* If a level has Layer 3 tides active and is less than 3 screens long, then sprites anywhere on the screen can occasionally register themselves as being in water. In 1- or 2-screen rooms, the effect will occur longer and more often the further left the screen is; in 3-screen rooms, it will only occur right of the screen when the screen is all the way at the left edge of the level.

<!--
* If a level has Layer 3 tides active and the water is high enough, Mario won't register himself as being in water at the very bottom of the screen.
-->
* レイヤー3の潮流のあるレベルで水面が高い位置にあると、画面下でマリオの水中判定がなくなる。

<!--
* If a level has Layer 3 tides active and the water is low enough, sprites will register themselves as being in water if they go high enough on the top of the screen.
-->
* レイヤー3の潮流のあるレベルで水面が低い位置にあると、高所にいるスプライトが水中判定になる。

<!--
* Floating platforms only check for water touching their leftmost tile.
-->
* 浮かぶ足場は水との接触を一番左のタイルで判定している。

<!--
* If a sprite has a spawn index of 65 or more (i.e. it's the 65th sprite from the left side of the level), then its "killed" status won't be reset when moving between sublevels. Hence, if you kill the 65th sprite in one room, the 65th sprite in any other room of that level will never spawn.
-->
* スプライトの出現インデックスが64以上だと（つまりレベルの一番左から65体目以上のスプライト）、倒しても「倒された」状態を表すフラグがレベル間を移動するときにリセットされない。つまり、対象のスプライトを倒すと、そのコースの他レベルにある同じ番号のスプライトも出現しなくなる。

<!--
* Stopping the title screen animation on the frame Mario touches a coin will let him keep that coin even after the game is actually started.
-->
* マリオがコインを取得するFでタイトル画面のプレーを止めてゲームをスタートすると、そのコインが加算される。

<!--
* The ability to side-screen-exit is carried across sublevels.
-->
* Side Exitはレベルを移動しても有効。

---

<!--
* If Mario enters a room with an incorrect BG initial position, the background may glitch when scrolled too far down or up. Automatically fixed by Lunar Magic 1.70+. [Alt. fix](http://www.smwcentral.net/?p=section&a=details&id=4246)
-->
* 開始位置が正しくないBG位置だと、背景が上下にスクロールしたときバグる。LM1.70以降は自動で修正される。[Alt. fix](http://www.smwcentral.net/?p=section&a=details&id=4246)

<!--
* If Mario enters a room too far to the right, the level will display past the screen borders for a bit before snapping back and glitching some of the Map16 graphics until they are reloaded. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8752)
-->
* マリオのレベル出現位置が右過ぎると、自動に戻されるまで画面がレベル外の領域を表示して、Map16のグラの一部が読み込み直されるまで化けてしまう。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8752)

<!--
* Collecting enough silver coins produced by a silver P-switch will start giving Mario glitched 5-up and coin score sprites. [Fix (for 5-up)](http://www.smwcentral.net/?p=section&a=details&id=4418)
-->
* 大量の銀コインを集めると、5UPとコインスコアスプライトの表示がバグる。[Fix (for 5-up)](http://www.smwcentral.net/?p=section&a=details&id=4418)

<!--
* Collecting enough 1-ups from hitting/bouncing off of enough enemies will eventually cause the point counter to loop back to 100 points. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4254)
-->
* 多くの敵を踏んで大量の1upを集めると、ポイントカウンターが100点に戻る。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4254)

<!--
* A byproduct of the above is right when the consecutive enemies stomped counter ([$7E1697](https://www.smwcentral.net/?p=nmap&m=smwram&u=0#7E1697)) loops, a glitched sound effect occurs ($60, since the game tries to read a RTS instruction as a sound fx pointer), and depending on the emulator it keeps playing glitched sounds indefinitely until another sound replaces it or you exit the level. [Video](https://youtu.be/6j9zBwQgmWU)
-->
* 前述のバグの副作用に、着地せずに踏まれた敵のカウンター（[$7E1697](https://www.smwcentral.net/?p=nmap&m=smwram&u=0#7E1697)）がループするとバグった効果音が鳴る。（RTSコマンドの$60が効果音番号として使われるのが原因。）また、バグった効果音が別の効果音に上書きされるかレベルを出るまで永久に繰り返して再生されるエミュレーターがある。[Video](https://youtu.be/6j9zBwQgmWU)

<!--
* Bouncing off Wigglers enough will start giving Mario glitched score sprites. [Video](https://youtu.be/7nwktrDawdM) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=4441)
-->
* ハナチャンを連続して何匹も踏むと、スコアスプライトの表示がバグる。[Video](https://youtu.be/7nwktrDawdM) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=4441)

<!--
* Generating enough score sprites in a short enough time can cause early ones to get overwritten, preventing the value for it from actually being added.
-->
* スコアスプライトが短時間に大量生成されると、先に生成されたものから上書きされていき、実際のスコア値が加算されない。

<!--
* Despawning a score sprite offscreen before it's processed will cause the value for it to not actually be added.
-->
* スコアスプライトが画面外で消えると、スコアは加算されない。

<!--
* Most score sprites don't set whether they were on Layer 1 or 2, but score sprites spawned from the spinning coin sprites do. As a result, if that score sprite is spawned on Layer 2, almost any score sprites that later take the same slot will also be considered to be on Layer 2 (causing the sprite to spawn offset on that layer).
-->
* Most score sprites don't set whether they were on Layer 1 or 2, but score sprites spawned from the spinning coin sprites do. As a result, if that score sprite is spawned on Layer 2, almost any score sprites that later take the same slot will also be considered to be on Layer 2 (causing the sprite to spawn offset on that layer).

<!--
* Freezing the game (via $9D) on the frame a Koopa shell turns into a normal Koopa will cause its graphics to glitch during Mario's shrinking animation.
-->
* 甲羅がノコノコに変化するFに$9Dでフリーズすると、フリーズが解除されるまでそのノコノコのグラフィックが化ける。

<!--
* Two shell-less Koopas can enter the same Koopa shell if timed correctly, but only the last one to enter before the Koopa emerges will actually have an effect on what spawns.
-->
* タイミングが良ければ裸ノコノコが2匹同時に甲羅に入れるが、出現するノコノコの色に影響を及ぼすのは最後に入った方の裸ノコノコ。

<!--
* Bullet Bills make no sound when spawning directly into the level, even though Banzai Bills do. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8755)
-->
* レベルに直接配置されたキラーに出現音はない。マグナムキラーはある。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8755)

<!--
* Message boxes will not display any letters in transparent levels.
-->
* メッセージブロックはレイヤー2がレイヤー1の裏にあっても見れるレベルでは、文字を表示できない。

<!--
* If multiple flying ? blocks are active ($1564 is set) at the same time, then all of them except the one in the highest slot will briefly turn invisible.
-->
* 複数の飛んでいるブロックが同時に動いている（$1564がセットされている）と、一番スロットが大きい一つ以外、少しの間透明になる。

<!--
* If Mario is holding B and climbing downward or in a Lakitu cloud / P-balloon, touching a wall springboard will cause the bounce sound to be repeatedly played despite Mario never actually bouncing off of it.
-->
* マリオがBおしっぱで網などを掴んで下移動したり雲やPバルーン状態で緑のバネにひっかかると、ジャンプしないがジャンプ音が繰り返される。

<!--
* If there is an offscreen P-switch or key in slot 0, its graphics will "stick" to a Lakitu's cloud.
-->
* もしスロット#0のPスイッチまたは鍵が画面外にあるとき、そのグラフィックはジュゲムの雲に固定される。

<!--
* The Lakitu Cloud's face always appears on top of Mario, even when he's not in the cloud.
-->
* ジュゲムの雲の顔はマリオが乗っていなくても、常に手前に表示される。

<!--
* While the Lakitu Cloud is just slightly off the right side of the screen, its face will loop to the left side of the screen.
-->
* ジュゲムの雲が僅かでも画面右にめりこむと、顔が画面左にループする。

<!--
* Yoshi's head, and carried sprites, will turn invisible when in their turning state while Mario is in a cloud. This includes the improper turning state Yoshi has as a result of the layer-switch glitch.
-->
* マリオが雲に乗っている間に方向転換すると、方向転換中はYの頭や持ち運んでいるスプライトが表示されない。これはレイヤー変更バグで向きが不適切な状態であっても起きる。

<!--
* The net tiles cleared by the climbing net door will improperly update if the sprite is placed across a screen or subscreen border. However, this only affects VRAM and not the actual tiles, so their interaction isn't changed. This can also occur if the screen scrolls far enough before the sprite redraws the gate tiles, though with the same issue.
-->
* 画面境界やサブスクリーン境界に配置された回転金網によって、間違った画面修正が行われる。これはVRAMのみに作用するため、実体は変わらない。これは再描写の時、十分な画面スクロールによっても発生する。

<!--
* Turning from a net gate carries between levels, although you have to be holding a net at the start of the next room for it to have any effect. Unfortunately, it will not move Mario to the back side of the net there.
-->
* 回転金網の回転はレベル間でも保持されるが、レベル移動後に金網を掴む必要がある。移動後のレベルで金網の裏側に行くことはない。

<!--
* If a Wiggler is flashing, then killing it won't make it actually die until it stops flashing. The same glitch occurs if Yoshi tries to eat it the Wiggler while flashing.
-->
* ハナチャンが光っていると、輝き終えるまで殺しても死なない。これと同じことがヨッシーの舌で食べようとしたときに起きる。

<!--
* The hitbox for the extended sprite flower spawned when Wiggler is first bounced on is severely and unusually disjointed from its actual graphic.
-->
* ハナチャンを踏んだときに拡張スプライトである頭部の花の当たり判定は実際の表示とはバラバラ。

<!--
* Mario can still land on a Wiggler even after dying. [Fix](http://www.smwcentral.net/?p=section&a=details&id=6031)
-->
* マリオは死亡中にハナチャンを踏むことができる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=6031)

<!--
* If a Spike Top walks off a ledge, it will get stuck moving in a circle.
-->
* トゲメットが地面の崖に達すると、その場で円状に回り続ける。

<!--
* Spike Tops are able to walk down a sloped ledge, though it will do so strangely. Moving up slopes works fine, though.
-->
* トゲメットは斜めの坂を移動できるが、奇妙な進み方をする。上り坂は正常に登れる。

<!--
* If a Spike Top is surrounded by four blocks, it will start to quickly spin in a circle.
-->
* トゲメットが4つのブロックに囲まれると、高速で回転する。

<!--
* Spike Tops can not be killed with a cape smash while they're on the side or bottom of a block, as they aren't considered as on the ground.
-->
* 壁の側面か底面にいるトゲメットはマント地震で倒されない。

<!--
* After beating the Special World, Buzzy Beetles won't shake when they're about to return to normal.
-->
* スペシャルコースをクリアすると、メットが復活する時に震えなくなる。

<!--
* The bottom half of the vertical jumping dolphins loops vertically every 16 blocks.
-->
* 縦にジャンプするイルカは垂直方向16タイル毎に、下半分がループする。

<!--
* Clappin' Chucks will bounce strangely when on Layer 2 that is moving downward.
-->
* その場で跳ねるブルはレイヤー2が下向きに移動しているとき、奇妙な跳ね方をする。

<!--
* If the Sumo Bro's lightning tries to spawn fire over a screen barrier while Mario is dying, it may create glitched fire graphics on the opposite side of the screen.
-->
* マリオが死んでいる最中、K.K.の雷が画面端をまたいで発火すると、反対側にバグった炎の表示が発生する。

<!--
* Sprites graphics will not display at any scanline with too many sprite tiles written at once.
-->
* スプライトのグラは多量のスプライトタイルが存在すると、異なる走査線上でも描写されなくなる。

<!--
* The three-platform sprite (E0) does not spawn correctly in vertical levels, and will still try to spawn as if it's a horizontal level. [Fix](http://smwc.me/1186807)
-->
* 回る3つの足場スプライト（E0）は縦ステージでは正常に出現しない。[Fix](http://smwc.me/1186807)

<!--
* When sinking in lava, sprites will slide through objects when moving leftwards (they'll be stopped while going right). May be potentially useful when combined with Yoshi.
-->
* スプライトは溶岩に沈んいく最中スライドする。左向きに速度を持っていると壁を貫通する。（右向きだと壁で止まる）。Yと組み合わせられる。

<!--
* Sprites that fall offscreen when killed will still interact with blocks while falling (interestlingly, this includes interaction with lava). This even applies to sprites such as Banzai Bills, Super Koopas, Torpedo Teds, and Bullet Bills, despite them not normally having block interaction. Banzai Bills and Super Koopas are particularly odd in that with lava, they will revert to their normal animations while sinking and additionally receive a sudden increase in speed to the side. [Fix](https://www.smwcentral.net/?p=section&a=details&id=14638)
-->
* 倒されて画面下に落ちていくスプライトはブロックや溶岩と接触判定を持つ。これはマグナムキラー・マントガメ・キラーなどの通常ブロックとの判定を持たないスプライトも当てはまる。マグナムキラーとマントガメは溶岩に対して特殊で、浸かると通常時の表示に戻り、加速しながらスライドして落ちていく。[Fix](https://www.smwcentral.net/?p=section&a=details&id=14638)

<!--
* Sprites that don't have gravity applied to them (e.g. Banzai Bills, super Koopas, etc.) normally won't sink in lava; however, if they're killed and are falling offscreen, they are actually given gravity and will sink in lava. If this happens, the sprite will temporarily revert to its normal animation while continuing to move in its horizontal direction of movement (sometimes even speeding up), though Mario can still not interact with it.
-->
* 重力が働かないスプライト（マグナムキラー・コクッパ等）は通常溶岩に落ちて沈むことはない。それらのスプライトが倒されて画面下に落ちていく最中、重力が働き溶岩に沈む。これが起こると、スプライトは一時的に通常のアニメーションになり、（時々速度を上げ）水平方向に移動する。この状態のスプライトはマリオと当たり判定を持たない。

<!--
* The Rip Van Fish will center vertically on tiles if it falls on them while asleep. This can cause it to "bounce" if it lands on a slope or similar block.
-->
* 眠って落ちていくグースカはY座標を触れたタイルの中央に合わせようとする。坂のタイルに触れるとバウンドすることがある。

<!--
* Reflecting Podoboos will display a glitched graphic while sinking in lava. [Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#07F4C7)
-->
* 反射するバブルは溶岩に沈んでいる最中、表示がバグる。[Fix](http://www.smwcentral.net/?p=nmap&m=smwrom#07F4C7)

<!--
* If you kill Reznor fast enough, a stray Reznor sprite will appear on the screen, sinking in non-existant lava.
-->
* ブイブイを素早く倒すと、存在しない溶岩に沈み、表示が画面上に残り続ける。

<!--
* Making a smoke cloud from a fireball in Reznor's room when $010F is set to 00 will cause part of one of the Reznor platforms to disappear for a frame.
-->
* $010Fが00の時、ブイブイの部屋でファイアから煙雲が出ると、ブイブイの足場の一部が1Fだけ非表示になる。

<!--
* Screen scrolling will cause Reznor's wheel to temporarily dislocate until the screen finishes moving.
-->
* ブイブイの背景の車輪は画面スクロールすると、スクロールし終えるまで一時的に表示がずれる。

<!--
* Scrolling the screen on the frame Reznor spawns a fireball will cause him to duplicate that fireball into all of the remaining extended sprite slots. Not particularly useful, though it might prevent him from spawning another fireball for a bit.
-->
* ブイブイがファイアを生成するFに画面をスクロールさせると、空いている拡張スプライトスロットを全て埋めるようにファイボールを重複させる。特に使えるわけではないが、少しの間だけ別のファイアの生成を防げる。

<!--
* Ludwig will not actually start fighting until the screen passes a certain point, so you can kill him with fireballs before he even attacks by just not letting it scroll that far. Alternatively, you can scroll the screen the opposite way, so you can get right up next to him without actually starting the fight.
-->
* ルドウィッグは画面が特定の位置を通過すると戦い始める。右スクロールを用いれば戦闘を開始させずに、ファイアを当てて倒せる。逆に左スクロールを用いれば、戦闘を開始させずにルドウィッグの隣にまで行ける。

<!--
* Ludwig's fireballs can't hit Mario for a few frames after being fired, allowing you to stand right next to him without risk. [Video](https://twitter.com/Kaizoman666/status/811481990188953600)
-->
* ルドウィッグの炎は発生数Fはダメージ判定がないため、ルドウィッグの隣に立っていれば、ダメージを受けない。[Video](https://twitter.com/Kaizoman666/status/811481990188953600)

<!--
* If you hit Ludwig during the flipping of his jump attack, he'll continue to be diagonal during his hit animation.
-->
* 空中で回転しているルドウィッグを踏むと、斜めの踏まれた表示のまま落下する。

<!--
* Morton, Roy, and Ludwig just force Mario downwards if touched while Mario is moving upwards, rather than directly hurting him. As such, you can survive inside the bosses so long as you jump often enough.
-->
* モートン・ロイ・ルドウィッグは上昇中のマリオに触れると、マリオを下向きに押し出す。マリオはこれらのボスに重なっていても、ジャンプしていればダメージを受けない。

<!--
* After hitting Roy, if you run against his walls as they move inward, Mario will to be pushed by them and will instead end up inside the wall.
-->
* ロイを踏んだ後の壁が迫り来る時、マリオが壁に密着して壁の方向に進もうとしていると、壁にめり込める。

<!--
* Cape diving into Iggy/Lemmy's platform when it's rotated at it's near its maximum degrees leftwards will cause Mario to warp strangely on top of the platform, likely sending Mario either directly on top of Iggy's position and hurting him, or briefly sending him into the lava where he immediately dies.
-->
* イギー・レミーの足場が最も急な角度あたりの時にマント飛行で飛び込むと、マリオは足場の頂点と同じ高さに変に瞬間移動したり、ボスの座標に直接瞬間移動してダメージを受けたり、即死する場所にあるマグマに直接瞬間移動する。

<!--
* The spots at the bottom of Wendy's bow "jump" when she animates, even though there's no logical reason for them to. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4168)
-->
* The spots at the bottom of Wendy's bow "jump" when she animates, even though there's no logical reason for them to. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4168)

<!--
* If you enter Bowser's boss room in a level that used an autoscroll sprite at some point earlier in the level (without spawning any other scroll sprite in the meantime), then touching the edges of the screen in the fight will give Mario a small X speed as if he were still in the autoscroller.
-->
* オートスクロールスプライトがありオートスクロールをしている最中のレベルからクッパのレベルに移動すると、画面端に触れるとマリオがX速度を持つ。

<!--
* Fireballs can cause some of the Bowser battle's blocks to briefly disappear if they're onscreen as Peach descends from Bowser's clown car.
-->
* クッパ戦でクッパを倒して、ピーチが降りてくるときにファイアが表示されていると、地面の表示が欠ける。

<!--
* If you grab a goal sphere in the Bowser fight and Peach spawns before Mario finishes the walk, the game will immediately fade to the overworld with the credits fade effect.
-->
* クッパ戦で、ピーチが現れてからマリオが歩き終わる前に、ゴール玉をとると、クレジットのフェードアウトエフェクトでOWに戻る。

<!--
* Holding up after beating Bowser will result in Mario having a glitched walking animation during the credits ("claps").
-->
* クッパを倒したあと上を押していると、クレジットの最中の歩行アニメーション中にグラがばぐる。

<!--
* Mode 7 boss interaction loops between subscreens, allowing you to hit bosses that use it if you fly high enough.
-->
* モード7のボスとの相互作用はサブスクリーンごとにループするため、十分上に飛べばボスを叩くことができる。

<!--
* Spawning a Koopa Kid that uses Mode 7 in a room where Mode 7 is already active will cause the room to glitch in unusual ways. [Video](https://youtu.be/Dm-Y_TK1vkg)
-->
* モード7が既に稼働している部屋でモード7を使うコクッパが出現すると、部屋がバグる。[Video](https://youtu.be/Dm-Y_TK1vkg)

<!--
* Normally, after completing certain castles, the overworld music doesn't load while Mario walks to the next level. However, dying after the boss is beaten will still cause the music to not play, without moving Mario to the next level.
-->
* 通常、城を攻略した後OWの音楽はマリオが次のレベルへ歩き出すまで読み込まれない。コクッパを倒した後に死ぬと、OWの音楽が流れなくなる。ルイージがマリオと同じマップにいる場合、ルイージに切り替わっても音楽は流れない。

<!--
* Most non-standard sprite types (e.g. smoke/score sprites) will loop their graphics over screen borders. [Fix (smoke)](http://www.smwcentral.net/?p=section&a=details&id=4548)
-->
* ほんとの標準のタイプではないスプライト（煙やスコア）などは画面の境界でループする。[Fix (smoke)](http://www.smwcentral.net/?p=section&a=details&id=4548)

<!--
* Destroying certain extended sprites with a star will cause their graphics to move slightly or have glitched graphics based on their orientation for a frame.
-->
* 拡張スプライトの一部はスターで倒すとグラフィックがずれたり向きによって1Fの間化けたりする。

<!--
* Hitting a directional coin block while Mario has star power will cause the music to be overwritten by the directional coins; however, if the coins end before the star does, the music will continue to play for the directional coin path until Mario's star power ends as well.
-->
* スター中にコントロールコインブロックを叩くと、音楽がコントロールコインのに上書きされる。スターより先にコントロールコインがなくなると、音楽はスターが切れるまでコントロールコインのが流れる。

<!--
* Freezing the game by eating a berry on the same frame that the bonus coin game cloud spawns a coin will cause it to spawn several of its remaining coins at once. Not especially useful, though, since they're counted as extended sprites and therefore won't cause most sprites to despawn, but it is a way of getting the cloud's coins to spawn earlier than normal.
-->
* コインを出す雲がコインを出すFに木の実を食べてフリーズさせると、雲は後に出すコインを一度に全て出し切る。コインは拡張スプライトなのでスプライト制限を引き起こせるわけではないが、雲のコインを通常より早く入手できる。

<!--
* Getting hurt will reset the bonus coin game cloud's collection counter, meaning taking any damage will make getting the 1-up impossible.
-->
* コインを出す雲の取得カウンターはダメージを食らうとリセットされる。したがって途中で1回でもダメージを食らうと、1upはできない。

<!--
* Sometimes the graphics for coins from the coin game cloud loops and you can see them in top of the level. [Video](https://youtu.be/-EH1Fbwbtas)
-->
* コインを出す雲のコインの表示はループすることがあり、レベルの上部で見ることが出来る。[Video](https://youtu.be/-EH1Fbwbtas)

<!--
* Having too many extended sprites onscreen can produce some strange graphics effects, particularly on Mario. A few examples of these are displacing his cape several tiles away or erasing parts of hit animations that don't fit into the standard graphical area.
-->
* 画面内に多くの拡張スプライトがいると、主にマリオのグラフィック表示に変なことが起こりやすくなる。マントのタイルが幾つか欠けたり、通常の表示領域外のダメージアニメーションの一部が消えたりする。

<!--
* Enemies killed so that they fall downward will still interact with very steep slopes on their way down. This glitch can be combined with the Torpedo Ted to get an interesting use out of it, though.
-->
* 倒されて落下中の敵はとても急な坂に作用する。トーピードで行うと面白い。

<!--
* Playing a sound effect which uses the $1DF9 channel (such as the swim, Yoshi gulp, or powerup noise) on the same frame the "time is running out!" sound plays will cause it to get overwritten, with the music never speeding up as a result.
-->
* タイムアップするFに$1DF9チャンネルを使う効果音（泳ぎ・Yの飲み込み・パワーアップ音など）が流れると、値が上書きされる。結果的に音楽の速度が上がらなくなる。

<!--
* Pausing the game on the frame the game's music would normally change will cause it to continue playing the song (e.g. right before touching the goal tape)
-->
* 音楽が変わるFにポーズをすると、前の音楽が続く。例えば、ゴールバーに触れる寸前。

<!--
* Taking damage on the frame Mario enters a pipe will cause the shrinking animation to be skipped.
-->
* マリオが土管に入るFにダメージを受けると、入っていくアニメーションが省略される。

<!--
* Dying on the frame Mario takes a screen exit will cause the next room's music to be replaced by the death theme. Can also be done in the intro level on the frame the message appears.
-->
* 画面が変わるFに死ぬと次のレベルの音楽が死亡時に流れる音楽に置換される。オープニングでメッセージが現れるFでも可能。

<!--
* Dying in a level that has the time set to 0 will cause the game to display the TIME UP! message instead of simply fading to the overworld. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8772)
-->
* TIMEが0に設定されたレベルで死ぬと、TIME UP! と表示されてからOWに戻る。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8772)

<!--
* Dying during the goal walk will glitch the circle effect and not count as completing the level.
-->
* ゴールして歩いている最中に死ぬと、円のエフェクトがバグる。レベルをクリアしたことにはならない。

<!--
* Blocks or sprites that move Mario quickly (e.g. noteblocks) will cause the parts of the goal walk circle to not be redrawn as he moves.
-->
* ゴール後、マリオがブロックまたはスプライト（音符ブロックなど）によって動かされると、円のエフェクトがバグる。

<!--
* Ending a level via goal tape offscreen will cause the circle effect to loop to the wrong screen, occasionally glitching overworld palettes as well. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8783)
-->
* 画面外でゴールバーを切ると、円のエフェクトが上下でループする。この状態でOWに戻ると、OWのパレットがバグることがある。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8783)

<!--
* If Mario finishes a level while climbing, he will continue to climb during the goal walk, even during the thumbs-up pose.
-->
* 金網など掴んでいる状態でゴールすると、掴んだまま右に進んでいく。

<!--
* If Mario is touching the top of a moving platform while holding onto a fence or vine, he will be "pulled" by the platform while still climbing.
-->
* マリオが金網や蔦を掴んで下を押している最中に動く足場スプライトの上部に触れていると、足場スプライトに引っ張られる。

<!--
* In vertical levels, the goal tape will stop Mario as if it were a goal sphere, instead of activating the goal walk.
-->
* 縦ステージでゴールバーを切ると、ゴール玉のように動きが止まる。

<!--
* Hitting a goal tape after defeating a Koopa Kid will cause bonus stars to be added to the counter, but even if you pass 100, there won't be a bonus game.
-->
* コクッパを倒した後にゴールバーを切ると、ボーナススターが追加されていくが、100になってもボーナスゲームにはならない。

<!--
* Keys, throwblocks, and powerups (except 1-ups) will simply disappear when hitting the goal tape, instead of turning into a coin.
-->
* 鍵とパワーアップアイテムはマリオがゴールバーを切ると、コインにならずに消える。

<!--
* Ending a level via keyhole while offscreen may cause the game's palettes to glitch and the keyhole animation to loop.
-->
* 画面外で鍵ゴールすると、鍵穴のエフェクトがループし、パレットがバグる。

<!--
* The flashing color of Yoshi coins will not fade to black on level end.
-->
* ドラゴンコインの輝きはレベルが終わるときの暗転時にも光っている。

<!--
* The bonus game 1ups will keep moving even if the game is frozen with $9D.
-->
* ボーナスゲームの1upキノコは$9Dでフリーズしている間も動き続ける。

<!--
* If a Yoshi coin on Layer 2 is placed across a screen border on an odd-numbered screen, collecting it will cause some tiles in Layer 3's graphics to become corrupted (specifically the digits 0 to 7) depending on the x position within the screen where it is collected.
-->
* レイヤー2の奇数画面の境界にまたがって配置されたYコインを取得すると、YコインのX座標に依存してレイヤー3の幾つかのタイルが数字の0から7に侵食される。

<!--
* In addition to Yoshi coins, other multi-tile objects that change mess up over screen borders as well, including switch palace switches and fence gates. The former isn't particularly useful, however, and the latter only updates VRAM, not the actual tiles.
-->
* Yコインに加え、他の複数タイルのオブジェクトは画面境界上でごちゃごちゃになる。宮殿スイッチは特に有用ではない。金網はVRAM上のタイルだけ誤った更新がなされるが、実際のタイルはそのまま。

<!--
* Scrolling the screen far enough to the right or left before flipping a fence gate will cause some of the tiles for the gate to appear on that edge of the screen. Unfortunately not useful since it is only the VRAM and not the actual tiles being updated.
-->
* 回転金網が回転する前に画面を左右どちらかに大きくスクロールさせると、金網の幾つかのタイルが画面端に表示される。残念にもVRAMのみの更新なので、実際のタイルはそのまま。

<!--
* Yoshi Wings may occasionally steal graphics from other sprites while flying offscreen, causing them to look like they're weirdly flying across the screen. Unfortunately, the interaction doesn't come along with it. [Video](https://www.youtube.com/watch?v=yNdTFyxjP9A&feature=youtu.be&t=5m)
-->
* Yの翼は画面外を飛んでいる最中、他のスプライトの表示を時折パクり、その表示が画面を奇妙にまたいで飛んでいるように見える。残念だが、その表示との接触判定はない。[Video](https://www.youtube.com/watch?v=yNdTFyxjP9A&feature=youtu.be&t=5m)

<!--
* Crossing a screen border in a vertical level can cause pipe palettes to "split" between to colors. This can also happen in horizontal levels with vertically scrolling Layer 2 if it crosses over the vertical screen barier to the next screen.
-->
* 縦ステージで画面の境界を通過すると、土管のパレットを分割させられる。横ステージでもレイヤー2が縦方向にスクロールする場合、起こることがある。

<!--
* The inside of the pipes used in the Lemmy and Wendy battles are non-solid.
-->
* レミーとウェンディのレベルの土管の内部はソリッドではない。

<!--
* Mario will not move with Layer 2 objects, resulting in him sliding across horizontally moving objects. The same occurs when climbing, as well; Mario won't move with the vine/net he's holding onto, which can also allow him to pass into and through solid layer 2 blocks if they're directly above the vine/net.
-->
* マリオはレイヤー2オブジェクトと連動して移動しないので、レイヤー2が水平移動するとき、マリオが滑る。同様のことが網などを掴んでいる時にも起こる。これを利用するとツタなどの1マス上に配置されたソリッドブロックを貫通できる。

<!--
* When the On/Off-switch-controlled Layer 2 sprite hits its lowest level, all sound effects that use $7E1DFC (including spinjumps, coins, and fireballs) will be replaced by the "smash" sound. [Fix](http://www.smwcentral.net/?p=section&a=details&id=11314)
-->
* ON/OFFスイッチで制御されるレイヤー2スプライトがレベルの一番下にくっついてる時、$7E1DFCで鳴る効果音（スピンジャンプ・コイン・ファイア）が全てスマッシュの音に置換される。[Fix](http://www.smwcentral.net/?p=section&a=details&id=11314)

<!--
* When an autoscrolling level passes the screen limit for the level, its graphics (but not interaction) will loop.
-->
* オートスクロールのレベルでマップ端までスクロールすると、実体はないグラフィックがループする。

<!--
* If Mario finishes a level with more than 400 seconds left, the end-of-level score counter won't add correctly. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8894)
-->
* TIME400以上でレベルを終えると、スコアが正しく追加されない。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8894)

<!--
* If the timer goes above 999 (by way of green berries or just directly setting that way), then it will use letters (or other unintended tiles) until it goes below 999 again. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4435)
-->
* （緑木の実やそう設定することで）TIME999以上になると、再び999になるまで数字ではない文字が使われる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4435)

<!--
* If the exit counter goes above 99, additional numbers will be in hexadecimal. In vanilla SMW, this can only be done in the Japanese version; any other version stops counting when the star appears. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4697)
-->
* ゴールカウンターが99を超えると、16進数が使われる。無改造でこれが行えるのは日本版のみ。他の国の場合、99が上限で星が現れる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4697)

<!--
* Sprites other than standard powerup sprites will have glitched graphics when in the item box. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4199) - [More info](https://docs.google.com/spreadsheets/d/1XGzqHuZUoSqhyDk3QcSC0X7mGsA5af7HyQKFYc-busM/edit#gid=0)
-->
* 通常のパワーアップアイテム以外がアイテムボックスに入ると、表示がバグる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4199) - [More info](https://docs.google.com/spreadsheets/d/1XGzqHuZUoSqhyDk3QcSC0X7mGsA5af7HyQKFYc-busM/edit#gid=0)

<!--
* If you pause the game on the overworld while passing a jumping fish, the fish will repeatedly jump in place until you unpause.
-->
* OWでプクプクが跳ねた時にポーズすると、ポーズを解除するまで跳ね続ける。

<!--
* Entering a level while an overworld fish is mid-jump will have the fish wait and resume its fall after you exit the level.
-->
* OWでプクプクが空中に飛び出している最中にレベルに入り、レベルを終えるとプクプクがレベルに入った時の位置から動きを再開する。

<!--
* Obtaining the secret exit in a level set to activate event 77 will cause garbage event data to be loaded on the overworld.
-->
* イベント77をセットしたレベルで別ゴールをすると、OWにイベントデータのゴミがロードされる。

<!--
* If an overworld sprite is placed in the Yoshi's Island or lower Donut Plains area on the main map, then the title screen will have some extra garbage tiles. [Diagram](http://media.smwcentral.net/Diagrams/TitleScreenGarbageImage.png) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=8975)
-->
* OWスプライトをヨッシーアイランドまたはドーナツ平野の下側に配置すると、タイトル画面に余分なタイルが表示されるようになる。[Diagram](http://media.smwcentral.net/Diagrams/TitleScreenGarbageImage.png) - [Fix](http://www.smwcentral.net/?p=section&a=details&id=8975)

<!--
* The S in the ______ START! message uses palette 8 instead of palette A like the other letters. [Fix](http://www.smwcentral.net/?p=section&a=details&id=4168)
-->
* START!のSだけパレット8が使われている。他の文字はパレットA。[Fix](http://www.smwcentral.net/?p=section&a=details&id=4168)

<!--
* Loading a level that has a No-Yoshi entrance (by way of the 256 exit glitch or otherwise) when the entrance has already been run will prevent the cutscene from displaying, but will still function as normal, preventing both Yoshi and warps.
-->
* ヨッシー禁止の前置きがすでに実行された状態で再びレベルをロードすれば（例えばWrong Warpバグで）、前置きのシーン自体は実行されないがその効果は残る。つまり、依然としてヨッシーを取られ、送り先を直される。

<!--
* Loading a No-Yoshi entrance from a pipe (via the 256 exit glitch will cause Mario to not animate correctly. Additionally, bringing an item will cause it to stick to a bush during the walk, and bringing a Yoshi will cause the timing of Mario's movement to get offset due to him being unable to spinjump off, causing him to walk straight through the gate (though you don't keep Yoshi, unfortunately).
-->
* 土管に入って（Wrong Warpバグで）ヨッシー禁止の前置きをロードすれば、マリオのアニメーションがバグる。また、その際持ち運んでいるアイテムはシーン中に藪にくっつき、Yがお供していればスピンジャンプして降りることができないから、マリオの行動のタイミングがずれてしまい、扉を通り過ぎてしまう。（それでもYは取られてしまう。）

<!--
* Collecting a star or dying on the title screen will cause the music to change to the special world's theme. [Fix (for death)](http://www.smwcentral.net/?p=section&a=details&id=4528)
-->
* タイトル画面中、スターをとったり死ぬと、スペシャルワールドの音楽に変わる。[Fix (for death)](http://www.smwcentral.net/?p=section&a=details&id=4528)

<!--
* Pressing a P-switch on the title screen will cause the music to disappear completely until the switch's timer runs out, after which it will be replaced by the main overworld music.
-->
* タイトル画面中、Pスイッチを押すと、Pスイッチのタイマーが切れるまで音楽がなくなる。その後、OWの音楽に変わる。

---
---

<!--
# Locks and Crashes
-->
# ロックとクラッシュ(Locks and Crashes)

<!--
__(Things that break things)__
-->
__ぶっこわ(Things that break things)__  

<!--
_14 recorded glitches_
-->
_14個_  

<!--
* Transforming into caped Mario while offscreen in an autoscrolling level will softlock the game. [Fix](http://www.smwcentral.net/?p=section&a=details&id=5780)
-->
* 強制スクロールステージの画面外でマントに変身すると、ソフトロックされる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=5780)

<!--
* Screen scrolling an autoscroller sprite onto the screen will softlock the game. [Fix](https://www.smwcentral.net/?p=section&a=details&id=15711)
-->
* 強制スクロールスプライトを読み込むようにLRスクロールすると、ソフトロックされる。[Fix](https://www.smwcentral.net/?p=section&a=details&id=15711)

<!--
* Swallowing a berry on the same frame Mario collects a powerup or takes damage will softlock the game while giving Mario an infinite supply of coins. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8770)
-->
* 木の実を食べると同時にパワーアップアイテムをとったりダメージを受けると、ソフトロックされ無限にコインを取得し続ける。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8770)

<!--
* Swallowing a berry while dying will hardlock the game. [Fix](http://www.smwcentral.net/?p=section&a=details&id=8770)
-->
* 死亡中に木の実を食べると、ハードロックされる。[Fix](http://www.smwcentral.net/?p=section&a=details&id=8770)

<!--
* Spawning a Podoboo without sprite buoyancy enabled will hardlock the game.
-->
* バブルがスプライトの浮力設定がないレベルでスポンすると、ハードロックされる。

<!--
* Transforming on the same frame that Mario does his victory pose at the end of a bonus game will hardlock the game.
-->
* ルーレットステージ終了時のピースをするFに変身すると、ハードロックされる。

<!--
* Eating certain sprites via item swap may crash the game. [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)
-->
* アイテムスワップを使って特定のスプライトを食べると、クラッシュする。[Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)

<!--
* Spitting out a null sprite while on a brown revolving platform may cause the game to crash. [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)
-->
* 茶色の回転する足場の上でヌルスプライトを吐くと、クラッシュする。[Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)

<!--
* Collecting powerups with a powerup status greater than the fireflower may cause the game to crash. [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)
-->
* ファイアフラワー以上のパワーアップ状態になるアイテムをとると、クラッシュする。[Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)

<!--
* Some stunned sprites may crash the game when attempting to spawn an invalid sprite. [Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)
-->
* 一部のスタンされたスプライトが無効なスプライトを生成しようとすると、ゲームがクラッシュする。[Data Table](http://smwspeedruns.com/index.php/Unintended_Sprite_Spawning)

<!--
* Certain results from Yoshification may crash the game, for instance by spawning a sprite that writes a value of 0C+ to $160E (the index of the sprite in Yoshi's mouth) which ultimately corrupts RAM when spat out, or by writing a value of 03+ to $1594 (a value specifying the routine currently used for Yoshi's mouth) which will immediately execute garbage code upon setting. Additional crashes can be obtained by transfering values from Yoshi to the sprite in question, such as writing to $151C (which Yoshi uses as the distance of his tongue) to a flying ? block (which uses it to determine the sprite to spawn), and then hitting the block. [Vid](https://youtu.be/4hKg1J9iuUk)[eos](https://www.youtube.com/watch?v=2fLOZrQzDnQ&feature=youtu.be&t=1h8m49s)
-->
* 「ヨッシー化」の結果は特定の場合クラッシュに至る。例えば、Yが口に何を含んでいるかを司る$160Eに$0D以上の値を書き出すスプライトを出現させてYが含んでいるものを吐き出すRAMが化ける。または、Yの口の段階を表す$1594に$03以上の値を書き出すスプライトだとすぐヌルポでコードがずれる。あと、ヨッシー化したスプライトが親（つまり前にそのスロットにいたY）から引き継いだ値によるクラッシュもある。例えば、Yは$151Cを舌の長さとして使うが、飛ぶハテナブロックはその中身として使い、中身として無効な値を引き継いで叩かれるとクラッシュする。[Vid](https://youtu.be/4hKg1J9iuUk)[eos](https://www.youtube.com/watch?v=2fLOZrQzDnQ&feature=youtu.be&t=1h8m49s)

<!--
* Most results from phase pointer manipulation may crash the game.
-->
* 段階ポインター操作の結果は大抵の場合クラッシュに至る。

<!--
* Sending a directional coin sprite off the left side of a level with Layer 3 may crash the game.
-->
* レイヤー3レベルでコントロールコインが画面左端に侵入すると、クラッシュする。

<!--
* Increasing the high bit of the mushroom scale sprite's Y position in a vertical level will crash the game.
-->
* 縦ステージで天秤キノコのY座標の上位ビットが上昇し続けると、クラッシュする。

<!--
* Spawning more than one Big Boo Boss will cause the game to crash or, at the very least, noticeably glitch the screen.
-->
* ボステレサが2匹以上読み込まれると、クラッシュするか画面がバグる。

<!--
* Spawning sprite D2 (stop generator) while the Layer 3 smasher is active will crash the game. [Fix](https://www.smwcentral.net/?p=nmap&m=smwrom&u=0#02D421)
-->
* レイヤー3の大木が稼働中にスプライトD2（stop generator）がスポンすると、クラッシュする。[Fix](https://www.smwcentral.net/?p=nmap&m=smwrom&u=0#02D421)
