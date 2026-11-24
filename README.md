# D4-Triality-3Cycle-Particle-Model
( $D_4$ トライアリティの3巡回と正24胞体による標準モデル3世代粒子の離散構造)

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

---

## 0. Axiomatic Core / 公理的コア

> **English:**
> Instead of attributing particle generations to arbitrary continuous mass parameters, we model the three generations of matter as a closed   $C_3$   cyclic rotation of $D_4$ triality projected onto Hurwitz integer principal ideals ($S^3$ / 24-cell) under orthogonal projection:
> $$P_1 + P_2 = 1, \quad P_1 P_2 = 0$$

> **日本語:**
> 素粒子の世代構造を連続的な質量パラメータの恣意的な調整に委ねるのでなく、直交射影（ $P_1 + P_2 = 1,\; P_1 P_2 = 0$ ）のもとで $D_4$ トライアリティの $C_3$ 巡回対称性がフルヴィッツ整数の単項イデアル（ $S^3$ 上の正24胞体）へ射影される離散代数構造として定式化する。

---

## 1. Overview / 概要

This repository presents a discrete geometric and algebraic model for the three-generation structure of the Standard Model. Rather than treating the three fermion generations as redundant copies in continuous spacetime, this framework derives them directly from the **three-fold outer automorphism ($C_3$ cycle) of the $D_4$ Dynkin diagram** and its realization inside the **24-cell (Hurwitz unit quaternions)**.

本リポジトリは、素粒子標準模型における「3世代構造」の離散的・幾何学的な起源を示す概念モデルです。3つのフェルミオン世代を連続時空上の単なる重複コピーとして扱うのではなく、** $D_4$  ディンキン図形が持つ唯一の3回外部自己同型（ $C_3$ 巡回対称性）**と、その4次元球面 $S^3$ 上の**正24胞体（フルヴィッツ単元）**への射影から必然的に導かれる離散サイクルとして記述します。

---

## 2. Algebraic Engine: $D_4$ Triality & $C_3$ Cycling / 代数エンジン： $D_4$  トライアリティと3巡回

Among all simple Lie algebras and Coxeter groups, $D_4$ ( $\mathfrak{so}(8)$ ) is unique in possessing a symmetric three-pronged Dynkin diagram, yielding an outer automorphism group isomorphic to $S_3$ containing the cyclic rotation $C_3$:

すべての単純リー代数およびコクセター群の中で、 $D_4$ のみが中心ノードから3本の腕が完全に対称に伸びるディンキン図形を持ち、その外部自己同型群 $S_3$ の部分群として**3巡回群 $C_3$** を内包します。

| Triality Sector / 巡回セクター | $D_4$ Representation / $D_4$ 表現 (8D) | Discrete Quaternion Coset / 四元数剰余類 (24-cell) | Physical Correspondence / 物理的対応（3世代・ゲージ） |
| :--- | :--- | :--- | :--- |
| **Cycle 1 ($e^0$)** | **Vector ($8_v$)** | $Q_8 = \{\pm 1, \pm i, \pm j, \pm k\}$<br>(8 pure integer units) | **1st Generation / Gauge Basis**<br>第1世代フェルミオンおよび基準フレーム |
| **Cycle 2 ($e^{2\pi i/3}$)** | **Spinor ($8_s$)** | $\frac{1}{2}(\pm 1 \pm i \pm j \pm k)$ (Even minus)<br>(8 half-integer units) | **2nd Generation**<br>第2世代（ $C_3$ 位相回転による射影断面） |
| **Cycle 3 ($e^{4\pi i/3}$)** | **Conjugate Spinor ($8_c$)** | $\frac{1}{2}(\pm 1 \pm i \pm j \pm k)$ (Odd minus)<br>(8 half-integer units) | **3rd Generation**<br>第3世代（第2のスピノル共役断面） |

* **Closed Cyclic Recovery (閉じた巡回回収):** Under the $C_3$ generator $\omega = \frac{1}{2}(-1 + i + j + k)$ (where $\omega^3 = 1$), multiplication rotates the three 8-element cosets of the 24-cell ($2T$, binary tetrahedral group) into one another without leaving the finite manifold $S^3$.
* **閉じた巡回回収:** 位数3の生成元 $\omega = \frac{1}{2}(-1 + i + j + k)$ （ $\omega^3 = 1$ ）の作用により、正24胞体（二項正四面体群 $2T$ ）を構成する3つの8元剰余類が $S^3$ の有限多様体から逸脱することなく互いに巡回（置換）します。

---

## 3. Orthogonal Projection & Flavor Mixing / 直交射影と世代混合のメカニズム

When the $C_3$ triality cycle is observed through discrete orthogonal projections ($P_1 + P_2 = 1,\; P_1 P_2 = 0$) aligned with a chosen principal ideal axis:

特定の単項イデアルの軸（基準フレーム）に沿って、直交射影分解（ $P_1 + P_2 = 1,\; P_1 P_2 = 0$ ）を通じてこの3巡回を観測するとき、以下の離散構造が現れます。

1. **Mass Hierarchy as Projection Depth (射影深度としての質量階層):**
   * The three cosets ($8_v, 8_s, 8_c$) intersect the chosen projection axis at discrete algebraic angles (related to $\cos(2\pi/3)$ and Hurwitz norm residues), producing three distinct discrete eigenvalues without requiring continuous fine-tuning.
   * 3つの剰余類（ $8_v, 8_s, 8_c$ ）は選択された射影軸に対して離散的な代数的角度（フルヴィッツノルムの剰余構造）で交差するため、連続的な微調整なしに3段階の離散的な固有値（質量階層）が生じます。

2. **Flavor Mixing as Discrete Basis Rotation (基底回転としてのフレーバー混合):**
   * Because $C_3$ triality rotates vector and spinor bases into each other while $G_2 = \mathrm{Aut}(\mathbb{O})$ fixes the octonionic identity, the mismatch between interaction eigenstates ($P_1$) and propagation eigenstates ($P_2$) manifests naturally as discrete mixing angles (analogous to CKM / PMNS matrices).
   * $C_3$ トライアリティがベクトル基底とスピノル基底を互いに回転させる一方で八元数の単位元（ $G_2$ 対称性）が固定されるため、相互作用の固有状態（ $P_1$ ）と伝播の固有状態（ $P_2$ ）のズレが離散的な混合角（CKM行列・PMNS行列に相当する回転）として自然に現れます。

3. **Why Exactly Three Generations (なぜ「3世代」で閉じるのか):**
   * Because $D_4$ is the unique Dynkin diagram admitting a 3-fold symmetry ($C_3$), and $S_3 / \mathbb{Z}_2 \cong C_3$ closes strictly at order 3, a 4th generation is algebraically excluded by structural apoptosis ($P_2 \to 0$).
   * $D_4$ が3回対称性（ $C_3$ ）を許容する唯一のディンキン図形であり、巡回が位数3で完全に閉じるため、第4世代の存在は代数構造の丸め込み（アポトーシス）によって自然に排除されます。

---

## 4. Engineering & Information-Theoretic Implications / 工学・情報理論への示唆

* **3-Phase Fault-Tolerant Modulation & Coding (3相トライアリティ誤り訂正・変調):** Mapping three independent data streams onto the $8_v, 8_s, 8_c$ cosets of the 24-cell ($F_4$), allowing cyclic $C_3$ rotation to equalize channel fading and recover packet asymmetry within a single Hurwitz principal ideal.
* **Redundancy-Bounded State Machines (冗長性を3状態に制限する離散ステートマシン):** Designing self-checking digital logic where state verification cycles strictly across three orthogonal/triality bases ($C_3$), preventing runaway state explosion.

---

## 5. License / ライセンス

This work is dedicated to the public domain under **CC0 1.0 Universal (CC0 1.0) Public Domain Dedication**.  
No rights reserved. You can copy, modify, distribute, and apply these ideas and structures for any purpose, even commercially, without asking permission.
