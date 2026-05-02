# Financial Math & Quant Finance Pre-Master's Preparation Guide

This repository is my structured preparation plan for a future master's program in financial mathematics, computational finance, or risk management.

It is designed for an AI engineer preparing to move deeper into financial risk, quantitative systems, and regulated AI. The goal is not to become a full quant expert before the master's program. The goal is to build the right foundation so graduate-level coursework feels challenging but manageable.

## Core Goal

My long-term goal is to become an AI engineer specialized in financial risk, quantitative systems, and regulated AI.

This preparation guide is built around that direction:

> Build strong AI engineering skills first, then add financial mathematics, risk management, derivatives, and quantitative finance as the domain specialization.

This repo is not a generic quant roadmap, trading roadmap, or stock-prediction project collection. It is a focused pre-master's study guide for building the foundations needed before entering a program such as UW CFRM, Johns Hopkins EP Financial Mathematics, UChicago Financial Mathematics, or a similar financial mathematics/risk management program.

## Target Master's Programs

This guide is meant to prepare for programs such as:

* University of Washington MS in Computational Finance and Risk Management
* Johns Hopkins Engineering for Professionals MS in Financial Mathematics
* University of Chicago MS in Financial Mathematics
* Similar programs in financial mathematics, computational finance, quantitative finance, or risk management

## Career Direction

The career path this repo supports is:

> AI Engineer → Financial Risk / Quant Systems / Regulated AI Specialist

The target is not pure quant research from scratch. The better path is to combine production AI engineering with financial domain expertise.

Relevant future roles may include:

* AI Engineer in Financial Services
* Financial Machine Learning Engineer
* Quantitative AI Engineer
* Risk Analytics Engineer
* Model Risk / AI Governance Engineer
* AI Engineer for Clearing, Margin, or Derivatives Systems
* Quantitative Developer focused on risk systems
* Applied AI Engineer for financial data and decision systems

## Study Philosophy

This guide follows a simple principle:

> Learn the math, then implement it in Python, then apply it to finance and risk.

The most effective preparation path is:

1. Quant programming and math refresh
2. Probability and statistics
3. Financial markets foundation
4. Portfolio risk and risk management
5. Derivatives and options
6. Monte Carlo, time series, and backtesting
7. Financial machine learning
8. Regulated AI and model risk

This order is intentional. Probability, statistics, linear algebra, and Python come before advanced finance because they are the tools used throughout financial mathematics and risk modeling.

## What This Repo Is Optimized For

This repo is optimized for:

* Preparing for graduate-level financial math coursework
* Building confidence before starting a master's program
* Connecting math concepts to Python implementation
* Learning financial markets and risk from the ground up
* Building small but meaningful quant finance projects
* Preserving and strengthening an AI engineering advantage
* Developing a long-term specialization in financial AI and model risk

This repo is not optimized for:

* Day trading
* Get-rich-quick trading systems
* Pure quant researcher preparation from zero
* High-frequency trading infrastructure
* Elite quant interview puzzle grinding
* Random stock prediction projects
* Learning every possible topic in finance at once

## Phase 1: Quant Programming and Math Refresh

### Goal

Rebuild core math foundations while using Python to make the concepts concrete.

### Topics

* Python fundamentals
* NumPy
* pandas
* matplotlib
* Jupyter notebooks
* Algebra review
* Functions
* Exponents and logarithms
* Single-variable calculus review
* Multivariable calculus basics
* Partial derivatives
* Gradients
* Linear algebra basics
* Vectors
* Matrices
* Matrix multiplication
* Dot products
* Systems of equations
* Eigenvalues and eigenvectors
* Optimization basics

### Why This Matters

Financial mathematics depends heavily on calculus, linear algebra, and optimization. These topics appear in portfolio theory, derivatives pricing, risk modeling, numerical methods, and machine learning.

Since this guide is for an AI engineer, the best way to learn these topics is to code them. Every important concept should eventually become a notebook, function, simulation, or visualization.

### Mini-Projects

* Returns calculator
* Matrix operations notebook
* Covariance and correlation calculator
* Gradient descent notebook
* Basic optimization notebook

### Success Criteria

Before moving on, I should be able to:

* Read basic mathematical notation without panic
* Use NumPy and pandas comfortably
* Work with vectors and matrices
* Explain what a derivative and gradient represent
* Understand why optimization matters in finance and machine learning
* Implement simple calculations in Python instead of only reading formulas

## Phase 2: Probability and Statistics

### Goal

Become comfortable with uncertainty, randomness, and statistical reasoning.

### Topics

* Sample spaces
* Events
* Probability rules
* Conditional probability
* Bayes' theorem
* Random variables
* Expected value
* Variance
* Standard deviation
* Covariance
* Correlation
* Common distributions

  * Bernoulli
  * Binomial
  * Poisson
  * Normal
  * Lognormal
  * Exponential
* Law of large numbers
* Central limit theorem
* Sampling
* Confidence intervals
* Hypothesis testing
* p-values
* Regression
* Maximum likelihood estimation

### Why This Matters

Probability and statistics are the foundation of quantitative finance. Risk, pricing, forecasting, backtesting, model validation, and machine learning all depend on understanding uncertainty.

This is one of the most important phases in the entire roadmap.

### Mini-Projects

* Coin flip and dice simulation
* Distribution simulator
* Confidence interval notebook
* Regression notebook
* Monte Carlo probability notebook

### Success Criteria

Before moving on, I should be able to:

* Calculate expected value and variance
* Explain covariance and correlation
* Use Bayes' theorem in simple examples
* Interpret confidence intervals
* Understand hypothesis testing
* Run and interpret a basic regression
* Simulate probability problems in Python

## Phase 3: Financial Markets Foundation

### Goal

Learn the language and structure of financial markets before going deeper into financial mathematics.

### Topics

* Stocks
* Bonds
* ETFs
* Mutual funds
* Interest rates
* Yield curves
* Inflation
* Volatility
* Liquidity
* Leverage
* Short selling
* Exchanges
* Market makers
* Clearing houses
* Margin
* Settlement
* Collateral
* Counterparty risk
* Market risk
* Credit risk
* Liquidity risk
* Operational risk

### Why This Matters

Graduate financial math courses move quickly. The formulas are easier to understand when I already know what the instruments and institutions are.

For my long-term career goal, I should pay special attention to clearing, margin, collateral, derivatives, counterparty risk, and model risk.

### Mini-Projects

* Market data notebook using yfinance or OpenBB
* Stock and bond comparison notes
* Yield curve explainer
* Clearing and margin explainer
* Risk types summary note

### Success Criteria

Before moving on, I should be able to:

* Explain stocks, bonds, ETFs, and derivatives at a high level
* Explain what interest rates and yield curves represent
* Explain what clearing houses do
* Explain why margin and collateral matter
* Understand the difference between market risk, credit risk, liquidity risk, and operational risk

## Phase 4: Portfolio Risk and Risk Management

### Goal

Build the first major quantitative finance foundation by learning how risk is measured, modeled, and communicated.

### Topics

* Simple returns
* Log returns
* Annualized return
* Volatility
* Annualized volatility
* Covariance matrix
* Correlation matrix
* Diversification
* Portfolio weights
* Portfolio expected return
* Portfolio volatility
* Sharpe ratio
* Beta
* Alpha
* Maximum drawdown
* Value at Risk
* Expected shortfall
* Stress testing
* Scenario analysis
* Backtesting risk models

### Why This Matters

Portfolio risk is the best first major quant topic because it combines math, statistics, Python, financial data, and practical risk thinking.

This phase should produce the first serious project in the repo.

### Main Project: Portfolio Risk Dashboard

The dashboard should include:

* Ticker input
* Historical price data
* Daily returns
* Log returns
* Portfolio weights
* Annualized return
* Annualized volatility
* Sharpe ratio
* Maximum drawdown
* Correlation matrix
* Historical VaR
* Expected shortfall
* Monte Carlo simulation
* Basic stress scenarios
* Clear visualizations

### Success Criteria

Before moving on, I should be able to:

* Calculate and interpret portfolio return
* Calculate and interpret volatility
* Explain diversification
* Use a covariance matrix
* Calculate historical VaR and expected shortfall
* Explain why stress testing matters
* Build a working portfolio risk dashboard in Python

## Phase 5: Derivatives and Options

### Goal

Prepare for one of the most important and challenging areas of financial mathematics programs.

### Topics

* Forwards
* Futures
* Swaps
* Options
* Calls and puts
* Payoff diagrams
* Intrinsic value
* Time value
* Put-call parity
* Implied volatility
* Delta
* Gamma
* Theta
* Vega
* Rho
* Binomial option pricing
* Black-Scholes intuition
* Black-Scholes formula
* Monte Carlo option pricing

### Why This Matters

Derivatives are central to financial mathematics, computational finance, and risk management. I do not need to master all derivatives before starting a master's program, but I should know the core language and intuition.

This phase is especially relevant for financial risk, clearing, margin, and derivatives systems.

### Main Project: Options Pricing and Greeks Calculator

The calculator should include:

* Call and put pricing
* Payoff diagrams
* Put-call parity checks
* Black-Scholes pricing
* Delta
* Gamma
* Theta
* Vega
* Rho
* Sensitivity analysis
* Simple Monte Carlo pricing
* Visualizations for price and Greek changes

### Success Criteria

Before moving on, I should be able to:

* Explain what calls and puts are
* Draw basic payoff diagrams
* Explain what the Greeks measure
* Understand the intuition behind Black-Scholes
* Implement basic option pricing in Python
* Explain why derivatives matter for risk management

## Phase 6: Monte Carlo, Time Series, and Backtesting

### Goal

Learn how to simulate uncertainty, work with financial time series, and test financial models realistically.

### Topics

* Monte Carlo simulation
* Random walks
* Geometric Brownian motion intuition
* Financial time series
* Stationarity
* Autocorrelation
* Moving averages
* Volatility clustering
* Rolling windows
* Walk-forward validation
* Look-ahead bias
* Survivorship bias
* Transaction costs
* Backtesting metrics
* Benchmark comparison

### Why This Matters

Financial data is noisy, unstable, and easy to misuse. This phase helps avoid bad modeling habits and unrealistic stock prediction projects.

Backtesting is not just about making a strategy look good. It is about testing assumptions honestly.

### Main Project: Basic Backtesting Engine

The backtesting engine should include:

* Price data loading
* Strategy rules
* Buy/sell signals
* Rolling-window evaluation
* Transaction costs
* Benchmark comparison
* Sharpe ratio
* Maximum drawdown
* Win rate
* Turnover
* Equity curve visualization

### Additional Project: Monte Carlo VaR Simulator

The simulator should include:

* Portfolio inputs
* Return assumptions
* Simulated price paths
* Portfolio value distribution
* VaR calculation
* Expected shortfall calculation
* Scenario analysis

### Success Criteria

Before moving on, I should be able to:

* Explain what Monte Carlo simulation does
* Simulate basic portfolio outcomes
* Identify look-ahead bias
* Explain why financial time series are difficult
* Build a basic backtest with realistic assumptions
* Compare a strategy against a benchmark

## Phase 7: Financial Machine Learning

### Goal

Connect AI engineering skills to financial risk in a realistic and disciplined way.

### Topics

* Train/test splits
* Time series validation
* Walk-forward validation
* Feature engineering
* Linear regression
* Logistic regression
* Random forests
* Gradient boosting
* Classification metrics
* Regression metrics
* Calibration
* Overfitting
* Model interpretability
* Drift detection
* Regime change
* Risk prediction
* Anomaly detection

### Why This Matters

Machine learning in finance is difficult because signals are weak, markets change, and backtests can lie. The goal is not to predict tomorrow's stock price. The goal is to use ML carefully for risk-related problems.

This phase should use AI skills while respecting the limitations of financial data.

### Main Project: Financial ML Risk Model

Better targets than stock price prediction:

* Predict high-volatility periods
* Classify drawdown risk
* Detect unusual market movement
* Estimate risk regime changes
* Flag portfolio risk increases

The model should include:

* Clean feature engineering
* Time-aware validation
* Baseline model comparison
* Performance metrics
* Interpretability
* Drift discussion
* Limitations section

### Success Criteria

Before moving on, I should be able to:

* Explain why normal ML validation can fail in finance
* Build a time-aware ML pipeline
* Avoid basic data leakage
* Evaluate a financial ML model honestly
* Explain model limitations clearly
* Connect ML outputs to risk decisions

## Phase 8: Regulated AI and Model Risk

### Goal

Use my AI engineering background to build a specialization that most finance/math students do not have.

### Topics

* Model validation
* Model governance
* Model monitoring
* Explainability
* Audit trails
* Human-in-the-loop review
* Data quality
* Stress testing
* Challenger models
* Limitations and assumptions
* LLM evaluation
* RAG evaluation
* Hallucination detection
* Tool-call logging
* Guardrails
* Failure analysis
* Confidence scoring
* Documentation

### Why This Matters

Financial institutions need AI systems that are reliable, explainable, monitored, and auditable. This is where AI engineering and financial risk come together.

This phase is what makes the overall path personally optimized. It connects graduate financial math preparation with real production AI work.

### Main Project: AI Model Risk Evaluation Tool

The tool should track:

* Test questions
* Expected answers
* Model answers
* Source quality
* Hallucination rate
* Tool-call correctness
* Calculation accuracy
* Human override rate
* Confidence scores
* Failure categories
* Audit logs
* Evaluation reports

### Success Criteria

Before finishing this phase, I should be able to:

* Explain why model governance matters in finance
* Design an evaluation process for an AI system
* Track AI failures in a structured way
* Build audit logs for model outputs
* Explain how human review fits into high-risk AI workflows
* Connect financial risk concepts to responsible AI deployment

## Optimized 12-Month Timeline

| Month | Focus                           | Deliverable                         |
| ----: | ------------------------------- | ----------------------------------- |
|     1 | Python and math refresh         | Quant Python notebooks              |
|     2 | Linear algebra and optimization | Matrix and optimization notebooks   |
|     3 | Probability                     | Probability simulation notebooks    |
|     4 | Statistics and regression       | Statistics and regression notebooks |
|     5 | Finance and market basics       | Finance market notes                |
|     6 | Portfolio risk                  | Portfolio Risk Dashboard            |
|     7 | Derivatives basics              | Options and derivatives notes       |
|     8 | Black-Scholes and Greeks        | Options Pricing Calculator          |
|     9 | Monte Carlo and VaR             | Monte Carlo VaR Simulator           |
|    10 | Time series and backtesting     | Basic Backtesting Engine            |
|    11 | Financial ML                    | Financial ML Risk Model             |
|    12 | Regulated AI and model risk     | AI Model Risk Evaluation Tool       |

## Weekly Study Plan

A realistic weekly schedule while working full time:

| Day       | Focus                             |          Time |
| --------- | --------------------------------- | ------------: |
| Monday    | Math, probability, or statistics  | 45-60 minutes |
| Tuesday   | Python implementation             | 45-60 minutes |
| Wednesday | Finance or derivatives reading    | 45-60 minutes |
| Thursday  | Project work                      | 60-90 minutes |
| Saturday  | Deep work session                 |     2-3 hours |
| Sunday    | Review, notes, and GitHub cleanup |     1-2 hours |

Target weekly commitment:

> 6 to 9 hours per week

This is meant to be sustainable while working full time.

## Repository Structure

```text
financial-math-prep/
│
├── README.md
│
├── notes/
│   ├── math-foundations/
│   ├── probability-statistics/
│   ├── finance-basics/
│   ├── portfolio-risk/
│   ├── derivatives/
│   ├── monte-carlo-time-series/
│   ├── financial-ml/
│   └── regulated-ai-model-risk/
│
├── notebooks/
│   ├── math-foundations/
│   ├── probability-statistics/
│   ├── portfolio-risk/
│   ├── derivatives/
│   ├── monte-carlo/
│   ├── time-series-backtesting/
│   └── financial-ml/
│
├── projects/
│   ├── portfolio-risk-dashboard/
│   ├── options-pricing-calculator/
│   ├── monte-carlo-var-simulator/
│   ├── backtesting-engine/
│   ├── financial-ml-risk-model/
│   └── ai-model-risk-evaluator/
│
├── resources/
│   ├── books.md
│   ├── courses.md
│   ├── papers.md
│   ├── tools.md
│   └── program-prerequisites.md
│
└── progress/
    ├── weekly-log.md
    ├── monthly-review.md
    └── concept-checklist.md
```

## Recommended Resources

### Math and Statistics

* Khan Academy for quick review
* 3Blue1Brown for intuition
* StatQuest for statistics and machine learning intuition
* MIT OpenCourseWare for deeper linear algebra, probability, and calculus

### Finance and Quant Finance

* Open Yale Financial Markets for market intuition
* John Hull's Options, Futures, and Other Derivatives for derivatives
* CFA Level I-style material for finance vocabulary
* Program course pages from UW CFRM, JHU EP Financial Mathematics, and UChicago Financial Mathematics as topic guides

### Python and Data

* Python for Data Analysis by Wes McKinney
* pandas documentation
* NumPy documentation
* SciPy documentation
* scikit-learn documentation
* yfinance
* OpenBB

### AI and Model Risk

* Agentic AI design pattern resources
* RAG evaluation resources
* LLM evaluation resources
* Model monitoring resources
* AI governance and responsible AI materials

## Progress Tracking

Each week, I will track:

* Topics studied
* Problems completed
* Notes written
* Code written
* Concepts I struggled with
* Questions to revisit
* Next week's focus

Each month, I will review:

* What I learned
* What needs more practice
* What projects moved forward
* What should be simplified
* What should be delayed
* Whether the roadmap still supports my master's preparation

## Definition of Success

Before starting a master's program, I want to be able to:

* Read mathematical notation with more confidence
* Solve basic probability and statistics problems
* Use Python for quantitative analysis
* Explain core financial market concepts
* Calculate portfolio risk metrics
* Understand basic derivatives terminology
* Implement simple option pricing models
* Run basic Monte Carlo simulations
* Understand common backtesting mistakes
* Build small finance-related projects
* Connect AI engineering skills to financial risk and model governance

The goal is not perfection.

The goal is preparation, consistency, and confidence.

## Final North Star

This repository exists to support one focused direction:

> Become an AI engineer with strong financial mathematics, risk management, and quantitative systems knowledge.

The master's program will provide structure and depth. This guide is the preparation layer that makes that transition smoother.
