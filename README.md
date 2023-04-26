一个 todoList 系统，需要先打开后端文件夹，在打开前端文件夹运行，包含身份验证，注册登陆后才可以看到某些 ui，后端用的 nodejs，登录后后端返回一个 token，前端保存在 localStorage 里，每次请求都带上这个 token，后端验证 token 后返回数据。token 有效期 1 小时，过期后需要重新登录。
