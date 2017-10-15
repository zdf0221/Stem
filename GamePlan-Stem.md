# 梗(Stem)游戏策划

1. **游戏概要**

  - 游戏名称： 梗(Stem)
  - 游戏类型： RPG + CCG

2. **游戏背景&世界观**<br>
  待补完

3. **游戏实现&平台**<br>
  PC<br>
  Unity / Cocox 2d (Depend on fund)

4. **游戏系统 & 游戏规则 & 游戏特色**
  1. 资源系统<br>
  游戏中的资源分为两大类：决斗内资源(in-duel resource)与决斗外资源(out-duel resource)。其中决斗内资源仅包括卡牌资源，包括手牌资源，牌库资源等。决斗外资源分为两类，一类为卡牌制作材料(Materials)，一类为卡包获取资源(Gold or Diamond)。
  2. RPG系统<br>
  游戏中玩家所扮演的角色类似于[MTG中的旅法师](https://magic.wizards.com/en/story/planeswalkers),他们是一次牌局的主人公，在游戏过程中扮演着指挥者的角色，并利用自己的牌库(Deck)与其他玩家进行对决(Duel)；除此之外，玩家需要通过完成地图(Map)上的主线与支线任务(Mission)，通关挑战(Challenge)、参加竞技场(Arena)等方式来获取游戏中的资源，从而进行卡牌的合成，分解；牌组的构筑等。
  3. CCG系统<br>
  其中CCG系统借鉴于[巫师之昆特牌](https://www.playgwent.cn/index)，
  [无尽之战TCG](http://store.steampowered.com/app/257730/Infinity_Wars_Animated_Trading_Card_Game/)， [PokemonTCG](https://www.pokemon.com/us/pokemon-tcg/play-online/)。<br>
    1. <a name="battlefield"></a>战场(Battlefield)<br>
  战场是两名玩家进行决斗的场地，也是游戏中的主界面，其大致分为如下几个部分：<br>
        * 战斗区域(Battle Zone)，该区域负责承载所有进入战斗的永久物(Permanents)，该区域的生物(Creatures)可以发动自己的主动 / 被动异能(Ability)
        * 整备区域(Rested Zone), 该区域承载所有进入整备阶段的永久物， 该区域的生物不能发动异能
        * 手牌区
        * 牌库
        * 坟场
        * 放逐区

5. **游戏用户定位**  
  * 学生群体
  * 社会人群体

6. **术语解释**(*Alphabatical Ordered*)  
  Battlefield : 战场，详见4.3.1节[游戏系统-CCG系统-战场](#battlefield)

  CCG : Collection Card Game， 收集类卡牌游戏，与TCG不同的是，CCG没有玩家间的卡牌交易系统，卡牌的收集仅依赖于玩家与游戏系统之间的互动。  

  Deck : 牌库，这里特指在决斗中处于玩家牌库区域内卡牌的统称。该区域的初始卡牌数量为30-45张，为决斗过程中玩家的固定手牌获取地点。

  Duel : 决斗，指游戏中玩家之间的对战，一般是以1 VS 1的形式进行。  

  *todo...*
