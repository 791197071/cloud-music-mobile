## cloud-music-mobile

This is a music player

![cloud-music-mobile](https://raw.githubusercontent.com/Yangfan2016/PicBed/master/Blog/cloud-music-mobile.gif)

### Intro

- [x] 推荐歌单  
- [x] 歌单详情  
- [x] 搜索歌曲  
- [x] 播放器  
- [x] 播放列表  
- [x] 随机播放、列表播放、单曲循环

### Technology stack

`Vue`    
`Vue-router`       
`Vuex`   
`axios`    
`Muse-UI`    
`vue-awesome-swiper`    

### API service

由[网易云音乐 Node.js API service](https://github.com/Binaryify/NeteaseCloudMusicApi)提供  
version: 3.0

### Install

```bash

# 安装项目依赖
$ yarn

# 获取子项目
$ git submodule init
$ git submodule update

# 安装子项目的依赖
$ cd NeteaseCloudMusicApi
$ yarn
$ cd ../

```

### Run

```bash

# 启动 api 服务
$ yarn sever
# 启动前台服务
$ yarn start

```

### Build

```bash
# 打包
$ yarn build

```


### Contributing
- Fork this Repo first
- Clone your Repo
- Install dependencies by `$ npm install`
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Publish your local branch, Open a pull request
- Enjoy hacking <3

---
built upon love by [docor](https://github.com/turingou/docor.git) v0.3.0
