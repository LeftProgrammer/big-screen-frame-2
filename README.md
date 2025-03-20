# jinghe-lanhai-monorepo 大屏可视化框架

## jinghe-laihai 包发布

...
打包：pnpm run build:lib

npm 包推送： 
npm login --registry=http://192.168.10.110:8081/repository/npm-hosted-jinghe/
npm publish @jinghe/jinghe-sanjioarou-bigscreen --registry=http://192.168.10.110:8081/repository/npm-hosted-jinghe/

删除包： npm unpublish @jinghe/jinghe-sanjioarou-bigscreen@1.0.0 --registry=http://192.168.10.110:8081/repository/npm-hosted-jinghe/ --force

npm 包使用： pnpm install @jinghe/jinghe-sanjioarou-bigscreen --filter jinghe-sanjiaoroad-bigscreen-template --registry=http://192.168.10.110:8081/repository/npm-hosted-jinghe
...