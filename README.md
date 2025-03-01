# Electron-App-Template

一个 electron + vue3 + naive-ui 的框架模板

![image-20240318095609210](https://pic-bed-1307818467.cos.ap-guangzhou.myqcloud.com/img/image-20240318095609210.png)

![image-20240318095624035](https://pic-bed-1307818467.cos.ap-guangzhou.myqcloud.com/img/image-20240318095624035.png)


## 安装依赖包前先配下镜像不然404
```bash
npm config edit

# 添加下面几行到配置文件
ELECTRON_BUILDER_BINARIES_MIRROR=https://npmmirror.com/mirrors/electron-builder-binaries/
ELECTRON_MIRROR=https://cdn.npmmirror.com/binaries/electron/
registry=https://registry.npmmirror.com
```

## 常用命令

```bash
# 安装依赖（install dependencies）
npm install 

# 运行 （run in developer mode）
npm run dev

# fix
# 若出现报错 "Electron failed to install correctly, please delete node_modules/electron and try installing again"
# When "Electron failed to install correctly, please delete node_modules/electron and try installing again" error occurs 
electron-fix start
```
