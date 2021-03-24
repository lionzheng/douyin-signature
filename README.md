# 网页版抖音复活版

## 说明
稍微修改了一下代码，并找到了代码中检测node与浏览器差异的部分，现已可以直接使用node运行，欢迎star

## usage
```
npm install jsdom@16.5.1 canvas@2.7.0

node douyin.js
```

## Docker
```
docker run -d -p 7878:7878 --name douyin --rm  makkapakka/douyin-web:latest

# then
curl http://127.0.0.1:7878
```

## 版权说明
仅供交流学习使用，严禁商业用途
