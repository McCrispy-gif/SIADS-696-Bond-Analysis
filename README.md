# SIADS-696-Bond-Analysis
Milestone project analyzing bonds using supervised and unsupervised machine learning methods.

**Authors:**
Transaint Gau, Christian Goelz, Carter Pasternak
tgau@umich.edu, chgoelz@umich.edu, pasterna@umich.edu

**Abstract**

Artificial Intelligence is increasingly used in financial markets, yet the performance of enterprise systems remains largely unexplored. This research evaluates the performance of BondDroid, an AI-based corporate bond pricing system. For this, we use an engineered target, BondDroids estimated price as a midpoint by the true TRACE price to get the absolute error. Using a mixture of both unsupervised learning (K-Means, Gaussian Mixture Models, and HDBSCAN) along with supervised learning (Ridge, Lasso, Random Forest, XGBoost, and LightGBM), we identify distinct pricing regimes and model pricing errors present in BondDroid. Our results identify four pricing regimes, with varying levels of error, where features like liquidity, quote staleness, maturity, or coupon influence the pricing accuracy differently. These findings indicate that BondDroid reliability depends on market conditions and bond characteristics, helping to provide insight when bond pricing may be most or least reliable.
