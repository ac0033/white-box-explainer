# White-Box Explainer

一个用于讲解代码、数据科学和机器学习项目的 Agent Skill。讲解从项目要解决的问题出发，结合真实源码、数据与复算过程，帮助读者理解结果如何得到，以及结论适用的边界。

## 使用

```bash
git clone https://github.com/ac0033/white-box-explainer.git
```

让 Agent 读取 [SKILL.md](SKILL.md)，再指定要讲解的项目、Notebook 或代码文件。例如：

> 按 white-box-explainer 讲解这个项目，先读入口和数据，用实际材料解释每个阶段，并展示关键数字的复算过程。

这是提示与参考材料集合，没有常驻服务或 Web 界面。若要运行复算模板，请先检查模板的数据字段与依赖是否适合当前项目。

## 文件导航

- [SKILL.md](SKILL.md)：核心原则、讲解顺序与检查要求。
- [复算模板](references/recompute_templates.py)：关键数字的计算示例。
- [建模阶段讲解示例](references/worked_example_s4.md)。
- [后续分析阶段讲解示例](references/worked_example_s5s6.md)。
- [交付速查卡](references/cheatsheet_onepager.md)。

本技能也通过子模块收录在 [ac0033/skills](https://github.com/ac0033/skills)。更多写作、汇报技能可从该集合进入。
