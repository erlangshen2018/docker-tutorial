# 使用官方 Python 镜像作为基础镜像
FROM python:3.11-slim

# 设置工作目录
WORKDIR /app

# 拷贝本地文件到容器中
COPY hello.py .

# 设置启动命令
CMD ["python", "hello.py"]
