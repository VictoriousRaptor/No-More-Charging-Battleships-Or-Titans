## 初衷

最近我回坑的时候，发现了一个bug，其表现为总有一条战列舰带头冲锋，如果舰队里有泰坦，那么泰坦就带头冲锋。

[Before pic](https://imgur.com/VPYKKKs)

这个bug，它最早在**2016年10月**发布的1.3版本里面出现. 没错，**五年多了**，尽管舰船ai的代码被大改过，瑞典蠢驴还没有修好它。

[After pic](https://imgur.com/XdvVNq4)

这个bug和舰船的“炮击行为”ai有关。实际上修复它用的代码只有一行。修复后的结果，所有的船都乖乖呆在远处。

## 新的舰船AI

为了发挥X槽和T槽武器的射程优势，我写了一个新的舰船AI，称作“狙击AI”。狙击作战电脑可以装在战列舰、泰坦和主宰上，效果是让它们停在其武器的最大射程上。

## 兼容性

本mod覆盖了原版的炮击ai.

不兼容成就。

## 其他

### 我的其他mod

[Locate It!](https://steamcommunity.com/sharedfiles/filedetails/?id=2245491122)
[Societal Advancement (fixed)](https://steamcommunity.com/sharedfiles/filedetails/?id=2247594997)
[Demilitarize (fixed)](https://steamcommunity.com/sharedfiles/filedetails/?id=2254396324)

### GitHub

[GitHub Repo](https://github.com/VictoriousRaptor/No-More-Charging-Battleships-Or-Titans)