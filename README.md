# JSON Resume 简历项目

本项目基于 [JSON Resume](https://jsonresume.org) 标准构建，包含简历数据源与渲染后的静态网页，可通过 Gitee Pages 进行在线展示和维护。

## 项目内容

- `resume.json`：使用 JSON Resume 标准描述的结构化简历数据。
- `index.html`：使用指定主题渲染后的静态 HTML 简历页面。
- `style.css`（可选）：简历页面的自定义样式。
- `README.md`：项目说明文件。
- `CNAME`（可选）：用于绑定自定义域名。

## 在线访问

静态简历主页已部署至 Gitee Pages，可通过以下地址访问：

[https://resume.fanqinglin.com/](https://resume.fanqinglin.com/)

## 快速构建

如需重新生成 HTML 页面，可使用 resume-cli 工具：

```bash
npm install -g resume-cli
resume export index.html --theme flat
````

可根据需求替换为其他主题。

## 许可证

* 简历模板代码（HTML/CSS）遵循 MIT License。
* 简历内容（resume.json）版权归原作者所有，未经授权禁止转载或商用。

