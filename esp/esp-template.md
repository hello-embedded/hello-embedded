# esp-template使用
https://github.com/esp-rs/esp-template

## 安装
1. 按照[esp-template->README.md](https://github.com/esp-rs/esp-template#esp-template)安装模板

## 测试/运行

### wokwi-server
1. 下载 [wokwi-server](https://github.com/MabezDev/wokwi-server)
2. 运行脚本`./scripts/run-wokwi.sh`
   1. 使用自定义 wokwi 项目 id
      1. 编辑`./scripts/run-wokwi.sh`中 `export WOKWI_PROJECT_ID=""`
      ```
      # https://wokwi.com/projects/338213365241348691
      export WOKWI_PROJECT_ID="338213365241348691"
      ```
### web-flash
1. 下载 [web-flash](https://github.com/bjoernQ/esp-web-flash-server)
2. 运行脚本`./scripts/flash.sh`
