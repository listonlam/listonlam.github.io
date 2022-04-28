打包的任何镜像内进程都要使用前台运行。

### 指令

|指令|说明|
| :-------: | :-----------------------------------------------------|
|FROM|构建新镜像的镜像来源|
|LABEL|标签|
|RUN|构建镜像时运行的Shell命令|
|COPY<br />|拷贝文件或目录到镜像中|
|ADD|解压压缩包并拷贝|
|ENV|设置环境变量|
|USER|为RUN、CMD、ENTRYPOINT执行指定用户|
|EXPOSE|声明容器运行时的服务|
|WORKDIR|为RUN、CMD、ENTRYPOINT、COPY和ADD设置工作目录|
|CMD|运行容器时默认执行的命令，如有多个指令，最后一个生效|

### 构建

```shell
docker build -t [label]:[tag] .
```
