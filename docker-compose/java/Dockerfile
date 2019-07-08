# Base images 基础镜像
FROM java:openjdk-8u111-jre-alpine

#MAINTAINER 维护者信息
MAINTAINER lichong

#拷贝本地文件到镜像内部
COPY app.jar /

#EXPOSE 映射端口
EXPOSE 8080

#CMD 运行以下命令
CMD ["java","-jar","app.jar"]