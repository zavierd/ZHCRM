# 智能CRM系统架构图表

本目录包含智能CRM系统的所有架构图表，使用Mermaid语法编写，支持在多种平台上渲染显示。

## 📁 文件列表

| 文件名 | 描述 | 图表类型 |
|--------|------|----------|
| `system-architecture.mmd` | 整体系统架构图 | 流程图 |
| `bpmn-workflow.mmd` | BPMN业务流程图（含泳道） | 流程图 |
| `rbac-matrix.mmd` | RBAC权限矩阵 | 图表+表格 |
| `rag-architecture.mmd` | RAG智能层架构 | 流程图 |
| `third-party-integration.mmd` | 第三方集成架构 | 流程图 |
| `implementation-roadmap.mmd` | 分阶段实施路线图 | Gantt图 |
| `technology-stack.mmd` | 技术栈选型 | 思维导图 |
| `database-design.mmd` | 数据库设计ER图 | 实体关系图 |

## 🔧 使用方法

### 在线渲染平台

1. **Mermaid Live Editor** (推荐)
   - 访问：https://mermaid.live/
   - 复制`.mmd`文件内容到编辑器
   - 实时预览和导出

2. **GitHub/GitLab**
   - 直接在仓库中查看，支持自动渲染
   - 在Markdown文件中引用：`![图表](./diagrams/文件名.mmd)`

3. **VS Code**
   - 安装插件：Mermaid Preview
   - 右键选择"Open Preview"

### 本地工具

1. **Mermaid CLI**
   ```bash
   npm install -g @mermaid-js/mermaid-cli
   mmdc -i system-architecture.mmd -o system-architecture.png
   ```

2. **Draw.io**
   - 支持导入Mermaid代码
   - 可进一步编辑和美化

### 导出格式

支持导出为以下格式：
- PNG（高清图片）
- SVG（矢量图）
- PDF（文档格式）
- HTML（交互式）

## 📋 图表说明

### 1. 整体系统架构 (`system-architecture.mmd`)
展示完整的微服务架构，包含用户层、服务层、数据层、外部集成和基础设施。

### 2. BPMN业务流程图 (`bpmn-workflow.mmd`)
含泳道的售前售后流程，明确9个角色的职责和流程交接点。

### 3. RBAC权限矩阵 (`rbac-matrix.mmd`)
基于角色的访问控制体系，展示角色继承关系和权限矩阵。

### 4. RAG智能层架构 (`rag-architecture.mmd`)
检索增强生成的完整技术栈，从知识源到智能体的端到端流程。

### 5. 第三方集成架构 (`third-party-integration.mmd`)
企业微信、钉钉等外部系统的双向集成方案。

### 6. 分阶段实施路线图 (`implementation-roadmap.mmd`)
5个阶段的项目实施计划，从MVP到全功能平台。

### 7. 技术栈选型 (`technology-stack.mmd`)
完整的技术选型思维导图，涵盖前端、后端、AI、基础设施。

### 8. 数据库设计 (`database-design.mmd`)
核心实体关系模型，展示数据表结构和关联关系。

## 🎨 自定义样式

所有图表都包含了自定义样式定义，支持：
- 颜色主题
- 节点样式
- 连接线样式
- 字体和布局

## 📝 编辑指南

1. **保持一致性**：使用统一的命名规范和样式
2. **模块化设计**：每个图表专注于特定的架构层面
3. **版本控制**：重要修改请更新版本注释
4. **文档同步**：修改图表后同步更新主文档

## 🔄 更新流程

1. 修改对应的`.mmd`文件
2. 在Mermaid Live Editor中验证语法
3. 更新主文档中的图表说明
4. 提交变更并更新版本

## 📞 技术支持

如需帮助或有问题，请参考：
- [Mermaid官方文档](https://mermaid-js.github.io/mermaid/)
- [Mermaid语法指南](https://mermaid-js.github.io/mermaid/#/flowchart)
- [GitHub Issues](https://github.com/mermaid-js/mermaid/issues)
