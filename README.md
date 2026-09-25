# ⚠️ 这个仓库已经迁移

> **新的地址：[`bedkillerspacex-boop/bsk-hypixel-api`](https://github.com/bedkillerspacex-boop/bsk-hypixel-api)**
>
> 请把书签、clone 地址、文档里的链接都换成新地址。这个仓库不再更新。

---

## 为什么改名

原来叫 `bsk-denick-api`，但它其实装了**两个**服务，仓库名只体现了第一个，
而且容易让人以为这里只有 denick 反查 —— 尤其**反代**那部分（镜像 Hypixel
官方接口）根本不会被人从"denick"这个名字联想到。改名之后名字和内容对得上。

## 现在去哪儿

| 服务 | Base | 文档 |
|---|---|---|
| **denick 查询**（本站自有接口） | `https://api.firebounce.today` | [新仓库 README](https://github.com/bedkillerspacex-boop/bsk-hypixel-api#readme) |
| **Hypixel 官方 API 反代** | `https://hyp-api.firebounce.today` | [反代那一节](https://github.com/bedkillerspacex-boop/bsk-hypixel-api#hypixel-官方接口反代) |

**反代是 Hypixel 官方接口的镜像** —— 要写调用代码请以官方为准：

- Hypixel 官方 API 入口：https://api.hypixel.net/
- Hypixel 官方 API 文档 / 仓库：https://github.com/HypixelDev/PublicAPI
- Hypixel 官方开发者后台：https://developer.hypixel.net/

你唯一要改的是 **base url**：把 `api.hypixel.net` 换成
`hyp-api.firebounce.today`，路径 / 参数 / 返回的 JSON 一模一样。

## 旧地址还能用吗

**GitHub 的旧 URL 会自动跳转到新仓库**，`git clone` 老地址也能用。
但这个仓库本身就是个占位说明 —— 别再从它拿代码了。
