# 常用 Markdown 语法
## 1 代码高亮

### `print 'Hello code' `

```python
print("Hello, world!")
```

## 2 制作待办事项

### Task List

- [ ] a bigger project
    - [x] first subtask
    - [x] follow up subtask
    - [ ] final subtask
- [ ] a separate task

[Task List Syntax](https：//help.github.com/articles/writing-on-github/#task-lists)

## 3 高效绘制流程图、序列图、甘特图、表格、公式

### 3.1 流程图 Flowchart
```mermaid
graph TD
    A[Chrismas] --> |Get Money| B(Go Shopping)
    B --> C{Let me think}
    C --> |One| D[laptop]
    C --> |Two| E[iPhone]
    C --> |Three| F[Car]
```

### 3.2 序列图 Sequence diagram
```mermaid
sequenceDiagram
    loop every day
        Alice->>John:  Hello John, how are you?
        John-->>Alice: Great!
    end
```

### 3.3 甘特图 Gantt diagram
```mermaid
gantt
    dateFormat YYYY-MM-DD
    title Adding GANTT diagram functionality to mermaid

    section A Section
    Completed task: done, des1, 2014-01-06, 2014-01-08
    Active task: active, des2, 2014-01-09, 3d
    Future task: des3, after des2, 5d
    Future task2: des4, after des3, 5d
```

### 3.4 表格 Tables and alignment

| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first columu | Content in the second columu |

| Left-Aligned | Center Aligned  | Right Aligned |
| ------------ | --------------- | ------------- |
| col 3 is     | some wordy text | $1600         |
| col 2 is     | centered        | $12           |

### 3.5 公式 LaTeX Mathmatical Formula

Math inline: $\dfrac{\tfrac{1}{2}[1-(\tfrac{1}{2})^n]}{1-\tfrac{1}{2}} = s_n$

Math block:
$$
\oint_C x^3\,dx + 4y^2\,dy
$$

$$
2 = \left(\frac{\left(3-x\right)\times2}{3-x}\right)
$$

$$
\sum_{m=1}^\infty\sum_{n=1}^\infty\frac{m^2\,n}{3^m\left(m\,3^n+n\,3^m\right)}
$$

$$
\phi_n(\kappa) = \frac{1}{\kappa\pi^2}\int_0^\infty\frac{\sin(\kappa R)}{\kappa R}R^2
$$

