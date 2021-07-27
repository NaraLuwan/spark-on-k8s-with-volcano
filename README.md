## spark-on-k8s-with-volcano
kubernetes上使用spark operator方式部署任务，并集成volcano框架

## 测试步骤
1. 安装volcano
```shell script
kubectl apply -f ./volcano-install/volcano-development.yaml
```
2. 参考[GoogleCloudPlatform/spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator)安装spark-on-k8s-operator
3. 分别启动spark-pi-volcano-without-operator和spark-pi-volcano，修改deploy参数测试，观察执行过程
