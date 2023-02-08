<p align="center">
  <img width="220px" src="https://i.ibb.co/rGK4hCV/i-va-6.png" />
</p>
<p align="center"><b>✨ hometown-npm-proxy 💥</b></p>
<p align="center">HoMeTown's npm proxy setting guidelines.</p>

### 淘宝镜像

#### 设置淘宝镜像

```arduino
// new
npm config set registry https://registry.npmmirror.com
```
```arduino
// old
npm config set registry http://registry.npm.taobao.org
```

### 官网镜像

#### 设置官网镜像

```arduino
npm config set registry https://registry.npmjs.org
```

### 检查镜像

```arduino
npm get registry 
```

### 装包使用

```bash
npm install --save-dev @hometownjs/npm-proxy
```

## Author

[HoMeTown](https://juejin.cn/user/4116184668057390) 🙊
