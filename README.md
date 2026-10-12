<div align="center">

<!--
  ⚠️ 校徽图片：出于版权与规范考虑，本仓库未内置南昌大学校徽文件。
  若课程允许，请自行将官方校徽保存为 assets/ncu-logo.png，
  然后删掉下面这一行首尾的注释符号，即可显示校徽。
-->
<!-- <img src="assets/ncu-logo.png" width="110" alt="Nanchang University Logo"> -->

# 南昌大学 · 课程个人作品集

**NANCHANG UNIVERSITY**

课程实验全过程记录仓库

</div>

---

## 一、个人档案

| 项目 | 内容 |
| :--- | :--- |
| 学号 | `[学号]` |
| 姓名 | 刘育栋 |
| 专业 | `[专业]` |
| 学院 | 南昌大学 |
| 学期 | 2026 — 2027 学年 第一学期 |
| 仓库用途 | 全学期 16 次实验的代码、报告与总结归档 |

> **待填写**：请把上表中的 `[学号]`、`[专业]` 替换为你的真实信息。

---

## 二、仓库目录结构

```text
ncu-course-portfolio/
├── README.md                 # 仓库总览（本文件）
├── .gitignore                # Git 忽略规则，避免上传垃圾文件
├── assets/                   # 图片、示意图等静态素材（可选）
├── week05_pendulum_sim/      # 第 05 周独立模块：双摆混沌仿真
├── week06_shooting_sim/      # 第 06 周独立模块：我不是炮神（弹道射击仿真）
└── labs/                     # 实验区：全学期 16 周
    ├── week01/
    │   └── .gitkeep          # 占位文件，保证空目录也能被 Git 记录
    ├── week02/
    ├── week03/
    ├── week04/
    ├── week05/
    ├── week06/
    ├── week07/
    ├── week08/
    ├── week09/
    ├── week10/
    ├── week11/
    ├── week12/
    ├── week13/
    ├── week14/
    ├── week15/
    └── week16/
```

---

## 三、全学期 16 周实验目录树

| 周次 | 目录 | 实验主题 | 状态 |
| :---: | :--- | :--- | :---: |
| 第 01 周 | [`labs/week01`](./labs/week01) | 环境搭建与开发工具链配置 | ⬜ 未开始 |
| 第 02 周 | [`labs/week02`](./labs/week02) | 待补充 | ⬜ 未开始 |
| 第 03 周 | [`labs/week03`](./labs/week03) | 待补充 | ⬜ 未开始 |
| 第 04 周 | [`labs/week04`](./labs/week04) | 待补充 | ⬜ 未开始 |
| 第 05 周 | [`week05_pendulum_sim`](./week05_pendulum_sim) | 双摆混沌仿真（物理建模 + RK4 数值积分 + Canvas 可视化） | 🟨 进行中 |
| 第 06 周 | [`week06_shooting_sim`](./week06_shooting_sim) | **我不是炮神** · 抛物线弹道射击（含空气阻力 + RK4 + 蒙特卡洛散布验证） | 🟨 进行中 |
| 第 07 周 | [`labs/week07`](./labs/week07) | 待补充 | ⬜ 未开始 |
| 第 08 周 | [`labs/week08`](./labs/week08) | 待补充 | ⬜ 未开始 |
| 第 09 周 | [`labs/week09`](./labs/week09) | 待补充 | ⬜ 未开始 |
| 第 10 周 | [`labs/week10`](./labs/week10) | 待补充 | ⬜ 未开始 |
| 第 11 周 | [`labs/week11`](./labs/week11) | 待补充 | ⬜ 未开始 |
| 第 12 周 | [`labs/week12`](./labs/week12) | 待补充 | ⬜ 未开始 |
| 第 13 周 | [`labs/week13`](./labs/week13) | 待补充 | ⬜ 未开始 |
| 第 14 周 | [`labs/week14`](./labs/week14) | 待补充 | ⬜ 未开始 |
| 第 15 周 | [`labs/week15`](./labs/week15) | 待补充 | ⬜ 未开始 |
| 第 16 周 | [`labs/week16`](./labs/week16) | 综合实验与期末总结 | ⬜ 未开始 |

**状态图例**：⬜ 未开始 ｜ 🟨 进行中 ｜ ✅ 已完成

> **目录约定说明**：第 05 周起，实验模块改为在仓库**根目录**下建立独立目录
> （如 `week05_pendulum_sim/`、`week06_shooting_sim/`），以符合课程对"独立无菌子模块"的要求。
> `labs/weekNN/` 骨架结构保留，用于其余周次的归档；`labs/week05/`、`labs/week06/`
> 为早期生成的占位目录，不再作为这两周的入口。

---

## 四、每周实验归档约定

每个 `labs/weekNN/` 目录内建议按以下结构组织内容：

```text
labs/week01/
├── README.md          # 实验报告：目的、步骤、现象、结论
├── src/               # 源码（.c / .py / .ino 等）
└── figures/           # 截图、波形图、连线图
```

---

## 五、日常提交命令（零基础备忘）

```bash
git status                      # 查看哪些文件被改动了
git add .                       # 把改动放入“待提交”区
git commit -m "feat: 完成第01周实验"   # 生成一次提交记录
git push                        # 推送到 GitHub 远程仓库
```

提交信息推荐前缀：`feat:` 新增内容 ｜ `fix:` 修正错误 ｜ `docs:` 文档更新

---

<div align="center">

**南昌大学 · Nanchang University**

本仓库仅用于课程学习与实验记录

</div>
