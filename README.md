#efte-initEfte 项目构建工具## 创建 unit-m 项目```bashefte unit-m-name```注: 项目创建期间, 要求指定 git url## 其他命令build unit-m-name```bashcd unit-m-nameefte build```install 依赖包```bash# 神似 npm install, 就是 cortex installefte install zepto --save```update 依赖包```bash# update 当前项目的所有依赖包efte update# update 指定的依赖包efte update [name...]```watch 文件变化```bashefte watch```link 创建其他项目的软连接```bash# apollo 是 efte 站点上创建的 App 名称efte link apollo```## TODO1. 自动 ln [ `OK` ]2. cortex.json 配置修改 [ `OK` ]3. ln 其他 unit 到主页所在项目 [ `OK` ]4. add demo to template [ `OK` ]5. add next step info for user6. 帮助文档 [ `OK` ]7. 兼容 windows/Linux8. efte update [ `OK` ]