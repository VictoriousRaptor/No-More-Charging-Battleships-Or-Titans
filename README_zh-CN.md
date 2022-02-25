## 初衷

最近我回坑的时候，发现了一个bug，其表现为总有一条战列舰带头冲锋，如果舰队里有泰坦，那么泰坦就带头冲锋。

[Before pic](https://steamuserimages-a.akamaihd.net/ugc/1833529903248924121/2B890CA9EBE4A40AC5C19F96693795DA512A6F80/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

这个bug，它最早在**2016年10月**发布的1.3版本里面出现. 没错，**五年多了**，尽管舰船ai的代码被大改过，瑞典蠢驴还没有修好它。

这个bug和舰船的“炮击行为”ai有关。实际上修复它用的代码只有一行。修复后之后，所有的船都乖乖呆在远处。

[After pic](https://steamuserimages-a.akamaihd.net/ugc/1833529903248928964/CD7AF7F3C2E2A7C50C5D8D74CF1731AE8F029FA8/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

## 新的舰船AI

为了发挥X槽和T槽武器的射程优势，我写了一个新的舰船AI，称作“狙击AI”。狙击作战电脑可以装在战列舰、泰坦和主宰上，效果是让它们停在其武器的最大射程上。

## 兼容性

本mod覆盖了原版的01_standard_ship_behaviors.txt.

不兼容成就。

## 其他

### 我的其他mod

[Locate It!](https://steamcommunity.com/sharedfiles/filedetails/?id=2245491122)
[Societal Advancement (fixed)](https://steamcommunity.com/sharedfiles/filedetails/?id=2247594997)
[Demilitarize (fixed)](https://steamcommunity.com/sharedfiles/filedetails/?id=2254396324)

### GitHub

[GitHub Repo](https://github.com/VictoriousRaptor/No-More-Charging-Battleships-Or-Titans)

### 鸣谢

Stellaris吧的
- @xhxc1111
- @ab981223789
- @QQQ_111_888