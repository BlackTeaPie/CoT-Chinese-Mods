# Course-of-Temptation-Chinese-Mods

本页面用于收录游戏Course of Temptation中文区玩家制作的模组信息、以及与制作模组相关的内容。有意向编写、改进模组与模组相关工具的开发者欢迎加入交流群：984850682
汉化版 Discord 交流服务器：

[![](https://dcbadge.vercel.app/api/server/PfFKvBxH68)](https://discord.gg/PfFKvBxH68)

## 注意事项

1. 本页面所收录的模组都是已经可以正常游玩的，如果你的模组连最基本的游玩功能都尚未达到，请不要提交收录申请。如果你的模组不再维护，请明确标出“本模组停止维护”。
2. 请在填写模组信息的时候注意用词正式，不要使用无法理解的缩写、黑话等，以免引起不必要的误会。
3. 本页面对模组进行如下分类，请在填写时注意不要填错分类，以免引起不必要的误会：
- “公开模组”：意为完全公开源代码、与游戏本身一样遵守 CC-BY-NC-SA-4.0 协议的模组。
- “私有模组”：意为该模组可能：在获取上有一定限制 / 游玩需要遵守一定规则 / 源代码不完全公开。
- “可以使用模组加载器(ModLoader)加载”：意为该模组遵守 JML 的加载格式，可以直接通过 JML 加载。
- “可以作为模组加载器(ModLoader)的载体”：意为该模组以旧方法编写，以编译后的 HTML 形式发布，本身可以作为游戏本体加载其它的模组。
- “与模组加载器(ModLoader)无关”：意为该模组通过其他方式编写加载，仅能单独游玩。
4. 发布在Discord的模组请先点击上方邀请链接加入服务器，才能定向到指定页面。

## 模组列表
### 可以使用模组加载器加载
| 模组名称 | 模组简介 | 模组作者 | 发布页或文件链接 | 最后更新时间 |
|:----:|:----:|:----:|:----:|:----:|
| 中文本地化翻译 | 将游戏语言翻译为中文 | CoT汉化组 | [汉化发布页](https://github.com/BlackTeaPie/Course-of-Temptation-Chinese-Localization) | ---- |
| 存档导出MOD | 在存档界面加入文本框方便导出存档码 | HCPTangHY | [仓库内下载](https://github.com/BlackTeaPie/CoT-Chinese-Mods/raw/main/mods/CoTSaveExportMod-0.0.1.mod.zip) | 2024-09-05 |
| NoLGBTMod | 移除NPCLGBT内容 | --- | [仓库内下载](https://github.com/BlackTeaPie/CoT-Chinese-Mods/raw/main/mods/NoLGBTMod-0.0.1.mod.zip) | 2024-09-06 |
| 中文名MOD | 替换I18N的英文名翻译为中文姓名 | HCPTangHY | [仓库内下载](https://github.com/BlackTeaPie/CoT-Chinese-Mods/raw/main/mods/ChineseNameMod-0.1.0(%E5%85%A8%E6%96%B0%E4%BA%BA%E5%90%8D%E8%B0%A8%E6%85%8E%E6%9B%B4%E6%96%B0).mod.zip) | 2024-09-19 |
| WhoIsHere | 在页面下面加入原本需要在人物界面查看的附近的人 | HCPTangHY | [仓库内下载](https://github.com/BlackTeaPie/CoT-Chinese-Mods/raw/main/mods/WhoIsHere0.0.2.mod.zip) | 2024-09-16 |
| 日文名MOD | 替换I18N的英文名翻译为日文姓名 | 未来 | [仓库内下载](https://github.com/BlackTeaPie/CoT-Chinese-Mods/raw/main/mods/JPNameMod-0.1.0.mod.zip) | 2024-09-18 |
| 便捷修改NPC倾向 | 在编辑NPC倾向界面将中英倾向列出 | 林夜无霜 | [Discord](https://discord.com/channels/1276544544749391902/1286609803291922443) | 2024-09-24 | 
| 身材管理小助手 | 在食物贮藏处增加了当前饮食、锻炼情况对体型影响情况的说明 | 林夜无霜 | [Discord](https://discord.com/channels/1276544544749391902/1288088552961478740) | 2024-09-24 |

## 模组收录提交
请通过[issue](https://github.com/BlackTeaPie/CoT-Chinese-Mods/issues)的方式提交模组，至少包含模组分类、模组名称、简介、作者、发布页或文件等信息
- **请务必确保自己的模组可以正常运行，如果你的模组连最基本的游玩功能都尚未达到，请不要提交收录申请**


## 模组制作指北

CoT的模组与DoL等使用ModLoader作为模组加载器的游戏相似，需要将模组打包为`.mod.zip`的格式并填有完整的`boot.json`
相关内容链接
- JavaScript：本游戏为HTML游戏，从游戏引擎到实际内容均有JS的参与。[菜鸟教程](https://www.runoob.com/js/js-tutorial.html) [MDN教程](https://developer.mozilla.org/zh-CN/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
  > 如果JS基础不好的话，建议先学JS。
- SugarCube2官方文档：本游戏由Twine-Sugarcube编写运行，模组也需要按照Sugarcube的语法进行编写 [Sugarcube官方文档](https://www.motoslave.net/sugarcube/2/docs/)
- ModLoader仓库：内有完整详细的模组填写、打包教程 [Lyoko-Jeremie/sugarcube-2-ModLoader](https://github.com/Lyoko-Jeremie/sugarcube-2-ModLoader)
- DOL Mod制作助手：适用于DOL的模组制作助手，大部分内容均可用于cot模组的制作和打包 [DOL-Mod-Created-Helper](https://github.com/NumberSir/DOL-Mod-Created-Helper)
