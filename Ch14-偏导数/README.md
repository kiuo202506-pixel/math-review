# Ch14 · 偏导数

> PPT 覆盖：14.1-14.7 全部
> **不考：14.8 Lagrange 乘数法**

---

## 核心公式速查

| 概念 | 公式 |
|------|------|
| 切平面 | \(z - z_0 = f_x(x_0,y_0)(x-x_0) + f_y(x_0,y_0)(y-y_0)\) |
| 线性逼近 | \(L(x,y) = f(x_0,y_0) + f_x\cdot(x-x_0) + f_y\cdot(y-y_0)\) |
| 全微分 | \(dz = f_x dx + f_y dy\) |
| 链式法则 Case 1 | \(dz/dt = (\partial f/\partial x)(dx/dt) + (\partial f/\partial y)(dy/dt)\) |
| 方向导数 | \(D_u f = \nabla f \cdot u\)（u 为单位向量） |
| 最大方向导数 | \(\|\nabla f\|\)，方向为 \(\nabla f/\|\nabla f\|\) |
| 梯度 | \(\nabla f = \langle f_x, f_y, f_z \rangle\) |
| 二阶判别法 | \(D = f_{xx}f_{yy} - (f_{xy})^2\) |
| D>0, f_xx>0 → 极小 | D>0, f_xx<0 → 极大 | D<0 → 鞍点 |

---

## 实战推荐

| 优先级 | 资源 | 质量 | 覆盖 |
|--------|------|:--:|------|
| 1 | UCSD Review2 + 解答 | 🟢 | 14.2-14.6 全部核心题型+完整解答 |
| 2 | LibreTexts 14.7E | 🟢 | 14.7 极值整套练习，100% 不含 Lagrange |
| 3 | MIT 偏导 | 🟢 | 14.3 偏导+克莱罗定理 |
| 4 | GradeSaver 14.7 | 🟢 | 14.7 逐题免费解答 |

---

## 全部资源明细

### 14.1-14.6（一揽子）

| # | 来源 | 链接 | 质量 | 说明 |
|---|------|------|:--:|------|
| 1 | UCSD Review2 | [review2.pdf](http://www.math.ucsd.edu/~meyoo/review2.pdf) | 🟢 | 极限双路径法、偏导、切平面、链式法则、方向导数/梯度。含完整解答。覆盖 14.2-14.6 全部核心题型。 |
| 2 | UCSD 解答 | [review2sol.pdf](http://www.math.ucsd.edu/~meyoo/review2sol.pdf) | 🟢 | 配套完整解答 |
| 3 | MIT 偏导 | [Partial Derivatives.pdf](https://math.mit.edu/~fgotti/docs/Courses/Math%2053/Partial%20Derivatives/2.%20Partial%20Derivatives/Partial%20Derivatives.pdf) | 🟢 | 14.3 偏导+克莱罗定理+微分条件 |
| 4 | UMN Duluth HW3 | [m3298s16hw3.pdf](http://www.d.umn.edu/~mhampton/m3298s16/m3298s16hw3.pdf) | 🔴 | 14.1-14.4 习题号列表 |
| 5 | USC HW14 | [HW14.pdf](https://people.math.sc.edu/kustin/teaching/241/HW14.pdf) | 🔴 | 14.1-14.7 全章习题号列表 |
| 6 | NTHU HW | [TCET_12e_Ch14.pdf](http://www.math.nthu.edu.tw/~wangwc/teaching/ee15/hw_ee15/TCET_12e_Ch14.pdf) | 🟡 | 14.2-14.7 综合练习，含提示 |
| 7 | Philadelphia 练习 | [cal3-Exercises-v1.pdf](https://www.philadelphia.edu.jo/academics/fawad/uploads/cal3-Exercises-v1.pdf) | 🟡 | 全章练习合集，含提示 |

### 14.7 · 极值与二阶判别法（100% 不含 Lagrange）

| # | 来源 | 链接 | 质量 | 说明 |
|---|------|------|:--:|------|
| 8 | LibreTexts 14.7E | [14.7E.pdf](https://math.libretexts.org/@api/deki/pages/154213/pdf/14.7E%3A%2BExercises%2Bfor%2BSection%2B14.7.pdf) | 🟢 | 无条件极值+闭区域最值全面练习 |
| 9 | CSUN HW | [m250_hw14_7.pdf](https://www.csun.edu/~panferov/math250_su13/m250_hw14_7.pdf) | 🟡 | 14.7 标准作业题 |
| 10 | Charleston 14.7 | [stew1407prob.pdf](https://people.charleston.edu/~kunklet/MATH221/stew1407prob.pdf) | 🟡 | 精选极值题，含部分解答 |
| 11 | GradeSaver 14.7 | [搜索页](https://www.gradesaver.com/textbooks/math/calculus/calculus-8th-edition/) | 🟢 | 逐题免费解答 |
| 12 | Berkeley WS19 | [Worksheet19Ans.pdf](https://math.berkeley.edu/~xlni/Teaching/FA22%20Math%2053/Worksheet19Ans.pdf) | 🟢 | 含完整解答 |
| 13 | NTU 14.7 | [14_7.pdf](https://www.math.ntu.edu.tw/~mathcal/download/exercise/14_7.pdf) | 🔴 | 习题列表 |

---

## 弃用

| 资源 | 原因 |
|------|------|
| GradeSaver Ch14 Review (p.1023) | 含 14.8 Lagrange 乘数题 |
| Colorado Extra Problems | 含 Lagrange 乘数法（已提前过滤，14.6 梯度部分安全） |
