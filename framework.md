
#### 渲染效果
1. **`root((核心主题))`**：表示中心节点。
2. 缩进的层级表示脑图的层次结构：
   - `子主题1` 和 `子主题2` 是一级节点。
   - `子主题1.1` 和 `子主题2.1` 是二级节点。

---

### 进阶示例

#### 添加颜色和样式
通过 Mermaid 的标签增强脑图的视觉效果：
```markdown
```mermaid
mindmap
  root((核心主题)):::main
    子主题1:::sub1
      子主题1.1
      子主题1.2
    子主题2:::sub2
      子主题2.1
      子主题2.2
      子主题2.3

%% 定义样式
  classDef main fill:#f9f,stroke:#333,stroke-width:4px;
  classDef sub1 fill:#1f77b4,stroke:#fff,stroke-width:2px;
  classDef sub2 fill:#ff7f0e,stroke:#fff,stroke-width:2px;
