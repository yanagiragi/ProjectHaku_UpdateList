# GlobalGameController:
    
* HakuScene Cleanup Func (重要度：高)

* LunchScene Cleanup Func  (重要度：高)

* Bgm  (重要度：高)

* 遊戲第0場景  (重要度：高)

* loading...效果 (重要度：低) 

<br />

# Minecraft 場景：

* 苦力怕：死掉 -> 倒地 (重要度：高)


* 音量調整(Mix) (重要度：高)
    
* 教學 (重要度：高)
    
* 加入陀螺? (重要度：中)

* MKGlow Shader Error (重要度：低)
    ```
    Shader error in 'MK/MKGlow/Normal/ParallaxDiffuse': Program 'frag_surf', error X4506: ps_4_0_level_9_3 input limit (8) exceeded, shader uses 9 inputs. (on d3d11_9x)
    Shader error in 'MK/MKGlow/Illumin/Parallax': Program 'frag_surf', error X4506: ps_4_0_level_9_3 input limit (8) exceeded, shader uses 9 inputs. (on d3d11_9x)
    Shader error in 'MK/MKGlow/Normal/DiffuseBumpedRim': Program 'frag_surf', error X4506: ps_4_0_level_9_3 input limit (8) exceeded, shader uses 9 inputs. (on d3d11_9x)
    ```

* 別的劍也可以攻擊 or 回歸 (重要度：低)

* 場景打光 上火焰 (重要度：低)


* 強化 "測試" 的意義 (重要度：低)
    
    ```
    也許可以設計 苦力怕綁架了Haku公主 增加Minecraft場景與辦公室場景的關聯性
    或者是加入 "達成條件" (例如要打贏幾隻苦力怕) 強化 "測試" 的意義
    ```
       
* Minecraft: 碰撞好像沒有用? (重要度：低)

        (幅度很小)

<br />

# 辦公室場景：

## 原則： OL 鞋子拿掉 < 直接用Uniform < Uniform 改過動畫 < Uniform + 改OL裝 + 改過動畫

* 面對樹 光影閃爍問題 (重要度：高)
    
        // 重新bake光罩似乎就可以了，但是realtime directional light 超怪

* 上半身隨機腳本 (重要度：高)

* Haku 桌子東西要多一點? (重要度：高)

* keyboard -> thinking? (重要度：高)

        兩者的動畫都還沒有導入


* 讓其他的東西也可以送 (重要度：高)
    
        送完要去的區域也決定好
       
* MorphController (重要度：高)

        拿東西評價的表情


* Camera 比例 (重要度：高)
    
        // 其實現在的就還不錯


* 場景大小Issue (重要度：高)
    
        畫可以調小一點(女生以外)
        樹要矮一點
        點唱機?
       
* 教學最後一面的hover特效 (重要度：中)

* 點唱機播放 (重要度：中)

* 加上 PostProcess (重要度：低)

<br />

# Lunch 場景：

* 重構method

* 餵完再吃一口才轉換成下個場景

* 流程改成:吃->吃>覺得好吃->吃->噎到->吃->餵->吃

* 表情

* 接收資訊來調整good end和bad end

* 蟹和餅還沒到正確位置上

* 風的效果 (重要度：低)

        聲音
        Cloth

* 午餐場景陽台矮一點

* 修改材質

        deiriguchi
        tesuri
        daiza
        okujou
<br />

# 結局場景：

* 修改Glass Shader  (重要度：高)

