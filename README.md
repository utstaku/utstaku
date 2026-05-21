# Hi, I'm Takuro ABE 👋

## 日本語

東京大学大学院で、プラズマ物理シミュレーションと機械学習を組み合わせた研究に取り組んでいます。特に、Vlasov–Poisson 系における Landau damping や two-stream instability を対象として、流体モデル・潜在変数モデル・データ駆動型 PDE 発見を組み合わせた、解釈可能な低次元モデルの構築を目指しています。

## 研究関心

- プラズマ物理シミュレーション
- Vlasov–Poisson 方程式
- Landau damping / Two-stream instability
- Physics-informed machine learning
- Auto-Encoder / 潜在変数ダイナミクス
- SINDy / シンボリック回帰 / PDE 発見
- 流体 closure モデリング
- Neural operators / Fourier Neural Operator
- データ同化・状態空間モデル

現在の研究では、分布関数を直接扱う高次元な Vlasov シミュレーションを、流体モーメントや潜在変数を用いて低次元化し、その時間発展を解釈可能な方程式として表現することを目指しています。Auto-Encoder による速度空間方向の圧縮、Hammett–Perkins closure の残差学習、SINDy や PySR による方程式同定などを組み合わせ、物理的解釈性と予測性能の両立を探っています。

## 開発経験

研究では主に Python を用いて、数値シミュレーション、機械学習モデルの実装、データ解析、可視化を行っています。

- Vlasov–Poisson シミュレーションデータの生成・解析
- Auto-Encoder を用いた分布関数の低次元表現学習
- PyTorch によるニューラルネットワークモデルの実装
- PySINDy / PySR を用いたデータ駆動型方程式発見
- Fourier Neural Operator などのニューラルオペレータの検討
- Docker / VS Code Remote SSH / Linux 環境での研究開発
- Git / GitHub を用いたコード管理

また、インターンシップでは太陽光発電量予測に関する機械学習モデルの開発にも取り組みました。気象データや発電量データを用いた特徴量設計、時系列予測モデルの検討、予測誤差の分析などを行い、実データに対する機械学習モデルの構築・評価を経験しました。

## スキル

### Programming

- Python
- NumPy / SciPy
- PyTorch
- pandas
- matplotlib
- Git / GitHub
- Docker
- Linux

### Machine Learning

- Auto-Encoder
- Neural Operator
- Time-series forecasting
- Sparse regression
- Symbolic regression
- Physics-informed modeling

### Physics / Simulation

- Plasma physics
- Vlasov–Poisson simulation
- Fluid modeling
- Numerical PDEs
- Data-driven closure modeling

## 現在の関心

現在は、プラズマの運動論的効果を保持しつつ、流体方程式や潜在変数方程式として表現できるモデルの構築に関心があります。特に、単なるブラックボックス予測ではなく、得られたモデルがどの物理量に依存しているのか、どのような非局所性・履歴効果を近似しているのかを解釈できる形で表すことを重視しています。

---

## English

I am a graduate student at The University of Tokyo, working on research that combines plasma physics simulations with machine learning. In particular, I focus on constructing interpretable reduced-order models for the Vlasov–Poisson system, targeting phenomena such as Landau damping and two-stream instability. My research combines fluid models, latent-variable models, and data-driven PDE discovery.

## Research Interests

- Plasma physics simulation
- Vlasov–Poisson equation
- Landau damping / Two-stream instability
- Physics-informed machine learning
- Auto-Encoder / latent dynamics
- SINDy / symbolic regression / PDE discovery
- Fluid closure modeling
- Neural operators / Fourier Neural Operator
- Data assimilation and state-space modeling

In my current research, I aim to reduce high-dimensional Vlasov simulation data, which directly represents the distribution function, into lower-dimensional descriptions using fluid moments and latent variables. I then seek to describe their time evolution as interpretable equations. To this end, I explore methods such as velocity-space compression using Auto-Encoders, residual learning of Hammett–Perkins closure, and equation discovery using SINDy and PySR, with the goal of balancing physical interpretability and predictive performance.

## Development Experience

In my research, I mainly use Python for numerical simulations, machine learning implementation, data analysis, and visualization.

- Generation and analysis of Vlasov–Poisson simulation data
- Learning low-dimensional representations of distribution functions using Auto-Encoders
- Implementation of neural network models with PyTorch
- Data-driven equation discovery using PySINDy and PySR
- Exploration of neural operators such as Fourier Neural Operator
- Research and development in Docker / VS Code Remote SSH / Linux environments
- Code management using Git and GitHub

I also have internship experience in developing machine learning models for photovoltaic power forecasting. In this work, I worked on feature engineering using meteorological and power generation data, explored time-series forecasting models, analyzed prediction errors, and evaluated machine learning models on real-world data.

## Skills

### Programming

- Python
- NumPy / SciPy
- PyTorch
- pandas
- matplotlib
- Git / GitHub
- Docker
- Linux

### Machine Learning

- Auto-Encoder
- Neural Operator
- Time-series forecasting
- Sparse regression
- Symbolic regression
- Physics-informed modeling

### Physics / Simulation

- Plasma physics
- Vlasov–Poisson simulation
- Fluid modeling
- Numerical PDEs
- Data-driven closure modeling

## Current Focus

My current focus is on constructing models that retain kinetic effects in plasmas while representing them in the form of fluid equations or latent-variable equations. Rather than relying only on black-box prediction, I aim to build models that reveal which physical variables they depend on and how they approximate nonlocal or memory effects in an interpretable way.
