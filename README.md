# Mount-Blade-II
骑砍MOD


## Features
* 增加AI钱和经验 P0
  ````
  游戏最大的问题，就是没有挑战性。
  原版的经济，太脆弱了，哪怕有一座大城，ai家族也养不起足够的兵，若是只有小堡，那就更不用说了。
  希望能加强原版的经济，同时增加ai带兵数量，给与ai练兵经验，这样，挑战性才足够。
  ````
* 强盗增强 P0
  ````
  可以给几个强盗势力加几个NPC，这些NPC可以找一些新的强盗高级兵，出一些强盗定居点（强盗文化的可以占领的山寨什么的），强盗们实力强大了之后可以攻城成为一方势力
  ````
  - 新的盗贼兵种树
  - 盗贼的行为，攻城
* 等级影响血量 P0
  ````
  修改血量上限，等级越高血量越多
  领主私兵
  ````
  - 目前是等级 * 2
* 增加单挑系统 P0
  ````
  阵前单挑功能，单挑赢的一方，可以加士气，和让对方低阶士兵逃跑一部分。
  ````
* 城池分配者必有国王 P0
  ````
  许个愿想要一个郡县制mod郡县制作为王国政策的一个选项。可能实现难度有点大。就是城镇，城堡，乡村的土地，税收全部归国王家族所有。旧领主家族依然可以四处征兵，各领主的费用由国王家族负责，征兵规模由家族等级作上下限。国王  
  家族每日需要按各领主家族等级拨付一定数量的钱。国王可以任命任何领主做任何城镇和城堡的总督，可以自由抽调或赠与领主军队，并且可以命令领主或军团进攻或防守某个地点。
  ````
* 基于关系的互动
  ````
  外交大修和灭国mod一打体验蹭的就上来了感觉这两个功能已经很完备了，我的话想再加一些NPC对话，比如根据亲缘关系会有不同的对话，
  我养了18年的女儿一朝嫁出去后对我像陌生人一样和岳父岳母的特殊对话，和老婆聊天能多点关于家里的事什么的，好感度高低也会影响对话内容
  被与你关系比较好的贵族击败后对方有概率直接放你走而不俘虏你，玩家可以放ai为什么ai不能放玩家？可以用关系值和领主性格来设置放走你的概率
  我觉得关系好的话战场上被他抓到应该直接放出来又或者说遇到也不会攻击的这种
  联姻系统
  原版只是加关系太蠢了
  我的想法是老婆结了婚同老婆的关系要发挥作用，老婆本身会因为娘家状况出“任务”：比如说娘家里没钱了希望你能送一定量的钱（要的钱有一定上下限，但是你肯定支付得起）家里有人战败被俘了希望你能帮忙出赎金，
  同意会加老婆关系不同意会减
  ````
  - 添加基于亲缘关系的NPC对话系统，包括家庭成员和贵族，好感度高低会影响对话内容和放走概率。
  - 可以通过关系值和领主性格设置NPC放走玩家的概率，达到更真实的游戏体验。
  - 添加联姻系统，让夫妻关系在游戏中得到更好的利用，例如夫妻关系会影响任务和奖励，比如娘家需要钱或出赎金等。
* 运兵运粮
  ````
  加一个往某个地方驻军，比如地图左边的国家想打阿塞来只能从一个小桥上过去，可以直接派兵驻守那座桥把人全堵住，免得最外边的城总被烧村，可以给驻军加一些buff，吃的就靠最近的城养着，或者加一个采购粮草的商队专门买粮草送来
  ````
* 可以发布一些悬赏任务
  ````
  指派AI领主某个任务，比如让AI部队跟随自己部队，或者让AI攻略某个地点或者去防守某个地点，或者让AI去攻击某个敌对领主部队，AI根据兵力对比权衡是否接受
  ````
* 有用的同伴和工坊的相关的提示
  ````
  买工坊前可以询问npc工坊的预计收益（我真不明白，1代就有的机制怎么到2代没了，烤肉社真是****）
  ````
* 增加巡视和巡视相关的一些互动，奖励治安值?
  ````
  骑砍1中城镇总督可以带领军队在城镇周围进行巡逻，有点怀念
  ````

* 结盟行为，士气的影响
  ````
  AI全面优化：
  1，行为层_士兵：AI分为多个等级，士兵的等级决定了AI等级，高等级的AI更加聪明多变，会互相配合且难以预测行动。
  2，行为层_英雄：与士兵基本相同，但英雄的AI等级比同级的士兵高好几个档次，而且其AI等级额外受到武器掌握技能的等级的加成，因此战斗力比大多数士兵更强。
  3，战术层_战场战斗：
  主要要点有2个，1是领主的性格与属性和装备强度决定了其好战程度、猥琐苟命倾向和战术与阵型选择，从而避免领主就是一个低能吉祥物的情况。
  2是士兵的行为受到士气与领主的统御等级影响，统御低且士气低则士兵有越高的概率在【接战（靠近敌方士兵一定距离）】后违背领主（包括玩家）的命令，自行选择执行其他行为，如：擅离职守独自冲锋、旁观看戏、抛弃队友后撤苟命、直接开始逃亡、恢复勇气继续冲锋、突然变得遵守命令、再次不遵守命令、绕后偷袭敌人、疯狂巨盾极地概率还击从而试图苟命……等，总之AI的可能性是无穷的，然而骑砍的开发程度太低。
  4，战略层_领主性格、决策与行为：领主的性格决定了烧村、掠夺、攻城、守城、野战、逃跑、援助友军、强势进攻、勇气值、寻找己方领主一起战斗……等决策，而不是清一色的烧村爱好者+猥琐苟命流。
  同盟相关：敌人的敌人就是朋友，为什么不能结成军事同盟，花钱也行啊，嫁女儿也行，质子也行，这游戏甚至不显示敌人与哪些国家开战（突然想到n界面可能会写，反正王国页面没有），我好去螳螂捕蝉黄雀在后抓别人打残的啊
  ````
* 运兵，远程管理城镇
  ````
  运兵，老家的兵要亲自去提出来运到前线城镇，太麻烦了。用mod指派一个npc去老家调出兵马运到前线城镇。
  tab战斗结算页面，显示每个分队的战损，比如1队步兵，活30，死20，伤50，杀60。这样有个统计的总数，更直观看。
  ````
* 增加锻造驽和马甲
  ````
  大佬，能把锻造这部分扩展一下吗，至少支持服装，弓弩等原版无法打造的物品，如果可能，能支持一下mod物品不？
  ````
* 配置多套装备
  ````
  多加几个装备界面，像城里那种，野战城战不用老是换装备…
  ````
* 玩家可以发布悬赏任务
  ````
  让玩家也可以悬赏任务吧，随家族等级改变，比如想要马或者征兵啥的，ai可以凭啥俺不可以
  ````
* 比武大会
  ````
  每过一年会在随机国家的都城（不重复举办卡拉迪亚竞技大会，领主就是除玩家外全卡拉迪亚胜场数前几个，举行三场赢两场即可，为期35天，奖励是该国顶级传奇品质装备一套（6级甲头满级鞋手六级武器）可自选。打过全部之后可以在铁匠铺diy一把全属性加十二的武器，可改名。之后会固定在吕卡隆或帕拉汶举办终极竞技大会可以选择任意国家传奇一套或者再diy上述的武器。（弓可以直接拿全属性+12的）
  ````
* 建议权,使用影响建议军团行为。
  ````
  请看我个人的建议。
  『完善和加强军团系统』
  该想法取材于骑砍1，但是有部分更改
  ；以下是决策系统
  1.国家设立元帅，可以和“元帅”政策相关联。向元帅可以提出军事行动建议。
  2.作为领主，可以向元帅提出“进攻某地”和“防御某地”的建议，可以用付出影响力作为加权。
  3.作为国王，可以向元帅更多提出“战略方向”
  建议。如“进攻某地所在的方向”，可以分为“进攻”,“防御“，“全力进攻”，“全力防御”。
  [解释该系统]
  ○进攻某地：如“我建议进攻”“(选择地点，王国接壤的敌国定居点)”
  ○防御某地：如“我建议防御”“(选择地点，王国接壤的敌国定居点)”
  ；可以付出影响力进行加权。
  ；如果该地点情况有变，在一定时间内搜索该地点周边符合条件的地区，否则恢复自主决策。
  ○全力进攻某地(国王指令)：集结所有军团对某定居点方向发动攻击，多支军团一主一辅，夺下城市后继续收拾该方向防御薄弱的定居点。无则烧村或者转入防御。
  ○全力进攻某地(国王指令)：军团进行主动或者被动的防御对某定居点和周边地区。巡逻，或驻扎城市，取决于敌人的规模和强度。
  ；在军团改变状态时，应向统治者送信：
  ；“我们正在向**定居点全力进攻！”
  ：“敌人没有薄弱环节了，我们准备防御敌人的反扑！”
  ````

* 黑帮玩法
  ````
  黑帮玩法，玩家不仅自己当老大，还可以派任务给npc，比如游戏里是玩家在黑帮老大那里接的任务，现在玩家作为黑帮老大遇到麻烦了可以将此作为任务让npc去帮忙解决。
  还有就是帮派收保护费啊，抢地盘，招兵买马，打通官府关系之类的，等等……
  ````
* 设置巡守地
  ````
  战区系统，以领地或者家族来设置，任命战区总督，这样一个战区内那些家族就比较稳定的跟敌对势力来回拉锯，会更好玩吧。
  ````

