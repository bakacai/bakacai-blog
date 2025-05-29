# 菜菜の博客仓库 🍵

### 哟👋\~大家好，我是笨蛋菜，也可以叫我“菜菜”。

## 📝 这是什么？

这是我用 [Hexo](https://hexo.io/zh-cn/) 搭建的个人博客仓库，内容涵盖技术、生活、随笔以及一些偶尔抽风（？）的文学创作。

你可以直接访问 👉 [https://bakacai.life](https://bakacai.life) 来阅读我发布的博客内容。

当然，如果你愿意，也可以自行克隆本仓库并本地构建阅读，~~甚至可以直接在 [`source/_posts`](https://github.com/bakacai/blog/tree/init/source/_posts) 中查看原始 Markdown 文件（应该没人用这么原始的阅读方式吧x）~~

## 🚧 如何构建？

> ⚠️ 建议直接访问部署好的博客阅读内容，除非你有特别的本地构建需求。

1. 安装 Hexo 所需环境（可参考 [Hexo 官方文档](https://hexo.io/zh-cn/docs/index.html)）：

   * `git`
   * `nodejs`
   * `hexo-cli`

2. 克隆本仓库（包含子模块）：

   ```bash
   git clone --recurse-submodules https://github.com/bakacai/blog.git
   ```

   > 如果忘记添加 `--recurse-submodules` 参数，也可以执行以下命令来初始化子模块：
   >
   > ```bash
   > git submodule update --init --recursive
   > ```

3. 安装依赖（使用 [pnpm](https://pnpm.io/)）：

   ```bash
   pnpm install
   ```

4. 本地预览 / 构建：

   * 本地预览：

     ```bash
     hexo server
     ```
   * 构建静态文件：

     ```bash
     hexo generate
     ```

   构建完成后，生成的文件会位于 `public/` 目录中。

## 📜 协议说明

![GitHub](https://img.shields.io/github/license/bakacai/blog)

 <img alt="CC BY-NC-ND 4.0" width="96" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-nd.png"/>

本仓库内位于 `source/_posts` 目录下的内容（除特别声明外）采用 [CC BY-NC-ND 4.0 DEED](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh-hans) 协议发布，意为：

* ✅ 允许转载（需注明出处）
* ❌ 不得用于商业用途
* ❌ 不得修改或衍生

仓库中除 `source/_posts` 目录外的其他所有文件（如主题、配置、构建脚本等），均采用 [Apache 2.0 许可证](https://opensource.org/licenses/Apache-2.0) 授权，欢迎自由修改、再发布。

> 若你希望将本项目用于其他用途（如自建博客），可删除 `source/_posts` 目录或保留但注明来源，并遵守 CC 协议要求，剩余部分则仅受 Apache 2.0 约束。

---

欢迎 star ⭐、fork 🍴、评论 💬！
