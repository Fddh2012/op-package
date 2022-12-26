# Argon-package
Fddh2012's Argon-package

建议使用Lean源进行编译。这个Branch的argon不适合官方版本。
包含了 如下应用
- Argon 主题
- Argon 主题配置应用

## 使用方法

添加 src-git Argon https://github.com/Fddh2012/Argon-package 到 OpenWRT 源码根目录feeds.conf.default文件

然后执行

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```
