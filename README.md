# 安装
1. 安装node.js
   windows: https://nodejs.org/en/download/
   macos: brew install node
2. 安装yarn
   npm install --global yarn
3. 安装本工程
   ```
    git clone https://github.com/aod321/jspsych_builder_demo.git
    cd jspsych_builder_demo
    yarn install
   ```
4. 本地测试
   ```
    yarn start
   ```
   然后访问http://localhost:3000即可
5. 打包成标准静态html(纯前端, 不带数据保存逻辑, 适合用于自己在代码中编写了数据保存的情况)
   ```
    yarn build
   ```
6. 打包成JATOS
   ```
    yarn run jatos
   ```
   packaged/目录下会生成jatos.zip, 上传到JATOS即可
