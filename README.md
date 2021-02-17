# cnki-bibtex
知网不提供BibTex， 所以写了个脚本将NodeExpress中的信息转化为 BibTex，在知网paper详细信息页右上角。

（一般是从搜索结果）进入某文献详情页，右上角会出现一个 Bibtex 的小图标和文字，点击即可将bibtex复制到剪切板（注意：不显示提示信息）。

所得bibtex 为知网提供的NodeExpress转化而来，citation key 使用时请自行编辑 （例如通过 [betterBibtex 插件](https://github.com/retorquere/zotero-better-bibtex/releases)）。

Firefox    中先安装 [Greasemonkey]扩展后，再安装脚本；

Chrome  中先安装 [tampermonkey]后，再安装脚本；

Safari      中先安装 [Ninjiakit]后，再安装脚本

Edge       中先安装 [tampermonkey]后，再安装脚本

IE 不支持。

ref: [Hao同学的](https://greasyfork.org/zh-CN/scripts/393305-%E7%9F%A5%E7%BD%91-%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE-bibtex)版本不能被Zotero识别且无法pull-reques，因此另开repo。
