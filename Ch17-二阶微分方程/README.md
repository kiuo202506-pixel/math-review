# Ch17 · 二阶微分方程

> PPT 覆盖：**仅 17.1**（常系数齐次二阶线性方程）
> **不考：17.2 非齐次、17.3 振动/电路应用、17.4 幂级数解法**

---

## 核心方法：特征方程

对 `ay'' + by' + cy = 0`：

| 判别式 | 根 | 通解 |
|--------|-----|------|
| b²-4ac > 0 | 相异实根 r₁, r₂ | \(y = c_1 e^{r_1 x} + c_2 e^{r_2 x}\) |
| b²-4ac = 0 | 重根 r | \(y = c_1 e^{rx} + c_2 x e^{rx}\) |
| b²-4ac < 0 | 共轭复根 α±iβ | \(y = e^{\alpha x}(c_1\cos\beta x + c_2\sin\beta x)\) |

---

## 全部资源明细

### 课本 17.1 Exercises（35 题，全部安全）

| # | 来源 | 链接 | 质量 | 说明 |
|---|------|------|:--:|------|
| 1 | GradeSaver #18 | [链接](https://www.gradesaver.com/textbooks/math/calculus/calculus-early-transcendentals-8th-edition/chapter-17-section-17-1-second-order-linear-equations-17-1-exercise-page-1160/18) | 🟢 | y''-2y'-3y=0, y(0)=2, y'(0)=2 → y=e^(3x)+e^(-x) |
| 2 | GradeSaver #33 | [链接](https://www.gradesaver.com/textbooks/math/calculus/calculus-8th-edition/chapter-17-second-order-differential-equations-17-1-second-order-linear-equations-17-1-exercises-page-1200/33) | 🟢 | 特征值问题 y''+λy=0 |
| 3 | Bartleby #5 | [链接](https://www.bartleby.com/solution-answer/chapter-171-problem-5e-calculus-mindtap-course-list-8th-edition/9781337076722/) | 💲🟢 | y'' - 2y = 0 |
| 4 | Bartleby #18 | [链接](https://www.bartleby.com/solution-answer/chapter-171-problem-18e-calculus-early-transcendentals-8th-edition/9781305270367/) | 💲🟢 | 初值问题 |
| 5 | Bartleby #29 | [链接](https://www.bartleby.com/solution-answer/chapter-171-problem-29e-calculus-early-transcendentals-8th-edition/9781305782198/) | 💲🟢 | 边值问题 |
| 6 | Numerade 17.1 | [链接](https://www.numerade.com/notes/directory/school/4819/courses/279259/files/3101863) | 💲🟢 | 教学笔记+例题 |

### 完整习题列表

```
Group 1 — 通解 (#1-10)
#1  y''+2y'-3y=0     r=-3,1               相异实根
#2  y''-6y'+9y=0     r=3(重根)            重根
#3  y''+4y'+13y=0    r=-2±3i              共轭复根
#4  4y''+4y'+y=0     r=-1/2(重根)         重根
#5  y''-2y=0         r=±√2               相异实根
#6  y''+9y=0         r=±3i               共轭复根(纯虚数)
#7  y''-4y'+5y=0     r=2±i               共轭复根
#8  y''+y'-6y=0      r=-3,2               相异实根
#9  9y''+6y'+y=0     r=-1/3(重根)         重根
#10 2y''-y'=0        r=0,1/2              相异实根(含0)

Group 2 — 初值问题 (#11-20)
#11 y''+6y'+13y=0, y(0)=2, y'(0)=0
#13 y''-8y'+16y=0, y(0)=4, y'(0)=3
#15 y''+4y=0, y(0)=1, y'(0)=1
#18 y''-2y'-3y=0, y(0)=2, y'(0)=2         → y=e^(3x)+e^(-x)
#19 y''+4y'+5y=0, y(0)=1, y'(0)=0

Group 3 — 边值问题 (#21-28)
#21 y''+4y=0, y(0)=0, y(π)=0
#25 y''+9y=0, y(0)=1, y(π/2)=0

Group 4 — 特征值问题 (#29-34)
#33 y''+λy=0, y(0)=0, y(π/2)=0           求 λ

Group 5 — 理论题 (#35)
#35 a,b,c>0时 ay''+by'+cy=0 的解当 x→∞ 时 y→0
```

---

## 弃用

| 资源 | 原因 |
|------|------|
| GradeSaver Ch17 Review (p.1221) | 含 17.2 非齐次、17.3 振动应用 |
| LibreTexts 17.R Review | 含 17.2 非齐次方程 |
| UCSC 非齐次 ODE 练习 | 整本都是 17.2 待定系数法/参数变易法 |
