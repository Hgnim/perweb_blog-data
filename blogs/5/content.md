# 求生之路2单人游玩对抗模式

*求生之路2中在单人模式下游玩可扮演被感染者的模式的方法*


1. 在steam创意工坊中订阅该模组：https://steamcommunity.com/sharedfiles/filedetails/?id=121070254
2. 如果想在对抗模式中启用模组：
   1. 编辑`[游戏本体根目录](Left 4 Dead 2)\left4dead2\cfg\addonconfig.cfg`
   2. `Left 4 Dead 2\left4dead2\cfg\addonconfig.cfg`文件大致内容：
      ```cfg
      # 请不要直接将下列内容全部直接复制到文件内，避免出现可能的格式不统一的问题
      "RestrictAddons"
      {
        "default" "0" # 战役和普通模式
        "versus" "1" # 对抗模式
        "scavenge" "1" # 清道夫模式
        "mutation15" "1" # 生还者对抗模式
      }
      ```
   3. 将需要启用模组的模式的值改为`0`即可，禁用模组的模式的值则为`1`
3. 最后，享受游戏吧:)