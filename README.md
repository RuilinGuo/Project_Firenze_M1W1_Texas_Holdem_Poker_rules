# 德州扑克规则详解
### by Ruiling Guo
---

## 基本介绍
德州扑克是目前世界上最流行的扑克游戏，后略

## 基本规则及相关名词解释

### 基本规则
>简单概括一下，这是一个比较牌的大小的游戏，每一局游戏中，哪位玩家的牌大，谁就赢得这一局游戏。

因此我们需要首先理解如何比较牌的大小

- 牌的大小
    - 在德州扑克中，每位玩家会获得两张扑克（对自己可见），同时场面上会有5张扑克，将自己的扑克与场中的扑克进行配对，将自己最大的组合与其他人的组合进行对比，谁的组合大谁就获胜
- 组合大小

组合名称 | 组合(X表示任意牌)
---|---
皇家同花顺 | 10 J Q K A (花色相同)
同花顺 | 5 6 7 8 9（花色相同）
四条 | X Q Q Q Q
葫芦 | J J J Q Q
同花 | 3 5 7 9 J (花色相同)
顺子 | 5 6 7 8 9
三条 | 10 10 10 X X
两对 | 5 5 6 6 X
一对 | 5 5 X X X
高牌 | A X X X X

#### 例子-1.牌的大小比较：
    小明手牌：♥️5 ♠6
    小红授牌：♣️3 ♦️J
    场中：♥️7 ♥ 8 ♥ ️9 ♥️J ♠️J
    我们来尝试组合一下，发现小明有一个顺子，小红有一个三条
    顺子大于三条，因此小明获胜
我们通过查表可以简单的得知谁大谁小，如果同样都是顺子，那么就比较数字大小即可。例如678910的顺子肯定大于45678的顺子，JJJ肯定大于999。

牌面的大小顺序是 A K Q J 10 9 8 7 6 5 4 3 2 1（与花色无关）

因此可以简单记忆,现比较组合，再比较数字

如果出现牌一样大，则平局（平局详见补充规则-1.平局）

### 德州扑克的规则
如果只是比个大小，德州扑克就没啥意思了，接下来会进一步的讲述德州扑克的独有规则，当然扑克比大小的规则也不能忘了，所以的规则都基于比大小这一核心规则衍生出来的。

#### 身份
在德州扑克中，每位玩家都有着自己的身份
- 庄家
    - 在开始游戏前，首先需要确定庄家由哪位玩家担任，其他身份根据庄家的位置进行确定。庄家通常也会担任每一局的发牌员。当一局游戏结束之后，庄家按顺时针方向轮换给下一位
- 小盲注/大盲注
    - 在确定了庄家之后，庄家的顺时针方向的下一位为小盲注，然后是大盲注
- 玩家
    - 没有身份的剩下人员都是玩家

#### 盲注
在身份中我们提到了两个特殊的身份，称之为大小盲注。所谓盲注，可以简单的理解为入场费。
>试想没有入场费的话，每个想获胜的玩家都会一直等待，直到自己拿到一手好牌才会入场进行游戏，这样不利于游戏的推进，因此需要这样的机制去确保游戏的正常进行

一般来将，在游戏开始之前，会事先确定盲注的数额（通常数额会根据人数进行变动。例如游戏后期玩家人数越少，盲注的数额会越大），小盲注通常会是大盲注的一半。

### 如何进行游戏

在上文中阐述了胜利条件与身份，接下来将阐述玩家行动，如何去进行游戏

#### 游戏流程

一场成功的德州扑克会由许多局游戏构成，每一局游戏会由4个回合（轮）构成。

>一局游戏 => 四轮

#### 入场
每位玩家确定自己所持的筹码数额，分配好每个人的位置（座位），
确定大小盲注的数额

#### 第0回合（轮）
确定庄家身份，大小盲注身份，投注额度限制
>投注额度限制在游戏流程-1.加/跟注规则进行讲解

#### 第1回合（轮）
每位参与者获得两张手牌（对自己可见），从小盲注开始，小盲注投入事先定好的小盲注数额的筹码，大盲注投入两倍小盲注数额的筹码。然后从大盲注的下一位玩家开始本轮游戏

此时玩家需要根据自己的手牌确定自己的行动，首先明确每位玩家有哪些行动

1.**跟注（CALL**），投入筹码，将本轮自己投注的筹码总数（本轮投注额）提高至当前轮次中最高的投注额相等
>假设你是大盲注过后的第一位玩家，你的手牌很不错，你想参这场游戏，那么你选择跟注，假设大盲注是100个筹码，那么你就需要投入100个筹码，
在投入之后，你本轮的投注额为100个筹码

2.**加注（BET）**，投入筹码，并且是投入比本轮最高投注额还要高的数额。此时将会抬高本轮最高投注额
>加注的数额可能存在一定限制，会事先确定好加注规则，见 补充规则-2.加注数额限制

3.**弃牌（FOLD）**，你觉得风险太大，放弃本局游戏，不投入筹码。
>一旦弃牌，则本局游戏与你无关，你只管看戏

4.**过牌（CHECK）**，不投注，什么事情都不做，让后面的玩家行动。
**第一局不能过牌**，在之后的轮次中可以过牌。为什么第一局不能过见后文

每位玩家在轮到自己时需要在上述四种行动中选择一种来执行，在进一步进行讲解之前，需要先解释几个概念
- 本轮最高投注额：指的是，当前轮次中，玩家投注的最高数额
  >小王当前投注100，小红当前投注200，小刚当前投注300，则本轮最高投注额为300
- 玩家本轮投注额：指某位玩家当前投注的数额
- 底池：指所有玩家总共投注的数额

首先需要明确一点，只有当**所有玩家**的本轮投注额都与本轮最高投注额相等，且没有玩家再进行加注时，才能进入下一轮游戏。
- 通过两个例子进行说明，
    - 没有加注时的玩家行动顺序（四位玩家：庄家，大/小盲注，玩家1）
        - 小盲注投10
        - 大盲注投20
        - 玩家1手牌不错决定入场，选择叫牌跟注，投入20
        - 庄家手牌不错决定入场，选择叫牌跟注，投入20
        - 小盲注手牌不错决定入场，选择叫牌跟注，投入10（已经投入了小盲注10，因此只需要再投入10就够了）
        - 大盲注不加注
        - 第一轮结束
    - 有加注的情况（同样四位玩家）
        - 小盲注投10
        - 大盲注投20
        - 玩家1手牌非常好决定入场，选择叫牌加注，投入40
        - 庄家手牌不错决定入场，选择叫牌跟注，投入40
        - 小盲注手牌不错决定入场，选择叫牌跟注，投入30（已经投入了小盲注10，因此只需要再投入30就够了）
        - 大盲注跟住，投入20
        - 第一轮结束

一旦有人加注，就需要对所有人进行确认，是否要跟注，如果不跟注则**只能选择弃牌**。**（因为已经有大小盲注抬高了本轮最高投注额，所以第一轮无法过牌，只能跟住加注弃牌）**
>可能会存在某位玩家所持有的筹码数量不足以更注的情况，假设这位玩家想进行游戏，则只能选择投入所有筹码（ALL—IN），这里需要参照补充规则-x.ALL-IN特殊处理

**请注意，加注的确认，一直需要进行到加注者的前一个人为止**
>例如正常顺序为A->B->C->D,轮到C的时候，C加注了，则对D->A->B进行确认是否跟注

>也可以简单记住，**当每个人的投注额等于当前轮最大加注额之后才能进行下一轮**

当所有玩家确认完毕，进入下一轮游戏玩家的本轮投注金额都一致后，进入**第2轮**

#### 第2/3/4回合（轮）

第二回合开始，会翻出三张公共牌，对所有玩家可见。此时第2轮下注开始

从第2轮开始，玩家可以选择**过牌（Check）**。过牌表示什么事情都不做，让其他玩家进行行动，如果所有玩家都选择过牌，则直接进入下一轮，底池维持不变。

其他行动与第一轮一致，都可以进行。

第三轮和第四轮会分别翻出一张公共牌。

第四轮开始时会有5张公共牌，此时在玩家行动后，会进行结算

#### 结算
进行结算，还在游戏内的玩家（弃牌的玩家请继续看戏）展示自己的手牌，按照大小比较，谁最大，谁获得底池中的所有筹码，然后开始下一局游戏。
>如果大小一致，则平局，平分奖池

结算会出现一种特殊情况，在123轮的时候，如果场上只剩下一位玩家（其他人都弃牌），则本局游戏这位玩家直接获胜获得场上所有筹码



## 补充规则
1.平局：当最终结算时，牌大小一致，则平局，平分奖池

2.加注数额限制：通常有 限注，底池，无限制。
- 限注：只能增加与大盲注相同数额
- 底池：只能最多增加与底池数额相等的数额
- 无限制：无限制
- 加注数额的限制在游戏开始前进行确认，请以具体规则为准，这里提到的三种仅作为参考

3.ALL-IN：ALL—IN，指投入自己所有的筹码，在之后的加注环节直接过牌（这不是废话，筹码都进去了还加啥啊）