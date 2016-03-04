# atom-configuration

## 导出目前安装的 package

apm ls -installed -package -json > mypackages.json

## 根据json 来安装 package

apm install --packages-file mypackages.json