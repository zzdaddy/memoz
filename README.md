<img height="56px" src="https://www.usememos.com/full-logo-landscape.png" alt="Memos" />

基于Memos V0.22.3 魔改
<a href="https://www.usememos.com/docs">Memos官方文档</a> •

后续不考虑升版本，除非官方有了特别好用的功能，升版本时会手动合并

进度：0%

## 计划功能

> [!TIP]
> ⚠️ 已有功能不再罗列，去官网查看即可
> 
> 先优化前端部分，后续再尝试扩展Go


- [ ] 分享Memos时，生成图片，并附上地址的二维码
- [ ] 标签分级、标签管理页面

## Docker运行

> -v 部分记得修改成自己想要设置的挂载目录


```bash
docker run -d --name memoz -p 5230:5230 -v ~/memos/:/var/opt/memos gnakdogg/memoz:latest
```
