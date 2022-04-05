# 常規能力

常規能力是一隻小精靈在對戰中的各種參數。每個精靈有15個能力值，包括HP、ATK、SPE、ADF、CRE、CRI、DAM、ARM、HIT、AGI、INT、STA、STR、POT和EAV。

| 簡稱     | 英文名稱                | 中文名稱 |
| ------ | ------------------- | ---- |
| ATK    | Attack Power        | 戰鬥力  |
| HP     | Hit Points          | 生命值  |
| POT    | Potential           | 潛力值  |
| STA    | Stamina             | 耐力   |
| _+sta_ | Stamina Growth      | 耐力成長 |
| STR    | Strength            | 力量   |
| _+str_ | Strength Growth     | 力量成長 |
| AGI    | Agility             | 敏捷   |
| _+agi_ | Agility Growth      | 敏捷成長 |
| INT    | Intelligence        | 智力   |
| _+int_ | Intelligence Growth | 智力成長 |
| DAM    | Damage              | 傷害   |
| ADF    | Magic Defense       | 魔抗   |
| ARM    | Armor               | 護甲   |
| CRE    | Critical Resistance | 抗暴   |
| CRI    | Critical            | 暴擊   |
| EVA    | Vasion              | 閃避   |
| HIT    | Hit                 | 命中   |
| SPE    | Speed               | 速度   |

HP = STA\*10

_ATK = DAM\*1 + ADF\*1 + ARM\*1 +HP\*0.1 + SPE\*1 + HIT\*2 + EVA\*2.4 +CRI\*2 + CRE\*2_

#### 關於 STA 、 STR 、 AGI 、 INT  成長公式:&#x20;

$$
f(x) =n (x -1)* 1.17^{ i*4}+N
$$

x=精灵等级

i=进化次数

N=( STA / STR / AGI / INT )

n=( _+sta / +str / +agi / +int_ )
