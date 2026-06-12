# flask-ping-hello-api

这是一个使用 Python Flask 编写的简单 API 项目，提供两个接口：

- `GET /ping` 返回 `{"message": "pong"}`
- `GET /hello` 返回 `{"message": "Hello World"}`

## 安装依赖

建议先创建并激活虚拟环境：

```bash
python -m venv .venv
source .venv/bin/activate
```

然后安装依赖：

```bash
pip install -r requirements.txt
```

## 运行项目

执行下面命令启动 Flask 服务：

```bash
python app.py
```

默认会启动在本机 `5000` 端口。

## 接口测试

启动服务后，可以使用以下命令验证：

```bash
curl http://127.0.0.1:5000/ping
curl http://127.0.0.1:5000/hello
```

## 运行测试

使用 `pytest` 执行测试：

```bash
pytest
```
