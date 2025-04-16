---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- 自定义 CSS：自定义倒序编号，格式为 [数字] -->
<style>
  ol.custom-counter-reversed {
    list-style: none;                      /* 去除默认编号 */
    padding-left: 0;                       /* 取消内边距 */
    /* CSS 变量 --start 由 HTML 设置，计数器初始值即为 --start 的值 */
    counter-reset: custom-counter calc(var(--start));
  }
  ol.custom-counter-reversed li {
    counter-increment: custom-counter -1;  /* 每一项将计数器递减 1 */
    margin-bottom: 10px;                   /* 每项之间适当间隔 */
    position: relative;
    padding-left: 2em;                     /* 为编号留出空间 */
  }
  ol.custom-counter-reversed li:before {
    content: "[" counter(custom-counter) "] ";  /* 生成 [数字] */
    position: absolute;
    left: 0;
    top: 0;
    width: 2em;
  }
</style>

## Publications

### Journal Papers

<ol class="custom-counter-reversed" style="--start:21;">
  <li>
    <strong>Ge Chen</strong> and Junjie Qin,  
    Neural Risk Limiting Dispatch in Power Networks: Formulation and Generalization Guarantee [<a href="https://arxiv.org/abs/2402.00772">Link</a>],  
    <em>IEEE Transactions on Power Systems</em>, Early Access, 2025.
  </li>
  <li>
    Bin Zhou, <strong>Ge Chen</strong>, Hongcai Zhang, and Yonghua Song,  
    Coordinating Geo-distributed Data Centers for Enhanced Participation in Frequency Regulation Services under Uncertainty,  
    <em>Journal of Modern Power Systems and Clean Energy</em>, Early Access, 2025.
  </li>
  <li>
    Bin Zou, <strong>Ge Chen</strong>, Hongcai Zhang, and Yonghua Song,  
    Improved Divergence-based Distributionally Robust Chance-Constrained Scheduling for Geo-distributed Internet Data Centers,  
    to appear in <em>CSEE Journal of Power and Energy Systems</em>, 2023.
  </li>
  <li>
    Yonghua Song, <strong>Ge Chen</strong>*, and Hongcai Zhang,  
    Constraint learning-based optimal power dispatch for active distribution networks with extremely imbalanced data [<a href="https://ieeexplore.ieee.org/abstract/document/10375977">Link</a>],  
    <em>CSEE Journal of Power and Energy Systems</em>, Early Access, 2023.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, Hongxun Hui, and Yonghua Song,  
    Scheduling HVAC loads to promote renewable generation integration with a learning-based joint chance-constrained approach [<a href="https://ieeexplore.ieee.org/abstract/document/10058886">Link</a>],  
    <em>CSEE Journal of Power and Energy Systems</em>, Early Access, 2022.
  </li>
  <li>
    Qilin Hou, <strong>Ge Chen</strong>, Ningyi Dai, and Hongcai Zhang,  
    Distributionally Robust Chance-Constrained Optimization for Soft Open Points Operation in Active Distribution Networks [<a href="https://ieeexplore.ieee.org/document/9862539">Link</a>],  
    <em>CSEE Journal of Power and Energy Systems</em>, Early Access, 2022.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, and Yonghua Song,  
    Adversarial Constraint Learning for Robust Dispatch of Distributed Energy Resources in Distribution Systems [<a href="https://ieeexplore.ieee.org/document/10766908">Link</a>],  
    <em>IEEE Transactions on Sustainable Energy</em>, vol. 16, no. 2, pp. 1139–1152, April 2025.
  </li>
  <li>
    <strong>Ge Chen</strong>, Junjie Qin, and Hongcai Zhang,  
    Model-Free Self-Supervised Learning for Dispatching Distributed Energy Resources [<a href="https://ieeexplore.ieee.org/document/10700765">Link</a>],  
    <em>IEEE Transactions on Smart Grid</em>, vol. 16, no. 2, pp. 1287–1300, March 2025.
  </li>
  <li>
    Guangxu Fei, Keng-Weng Lao, and <strong>Ge Chen</strong>,  
    Out-of-Distribution Detection of Unknown False Data Injection Attack With Logit-Normalized Bayesian ResNet [<a href="https://ieeexplore.ieee.org/document/9956906">Link</a>],  
    <em>IEEE Transactions on Smart Grid</em>, vol. 15, no. 6, pp. 6005–6017, Nov. 2024.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, Junjie Qin, and Yonghua Song,  
    Replicating Power Flow Constraints Using Only Smart Meter Data for Coordinating Flexible Sources in Distribution Network [<a href="https://ieeexplore.ieee.org/document/10584114">Link</a>],  
    <em>IEEE Transactions on Sustainable Energy</em>, vol. 15, no. 4, pp. 2428–2443, Oct. 2024.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, and Yonghua Song,  
    Efficient constraint learning for data-driven active distribution network operation [<a href="https://ieeexplore.ieee.org/abstract/document/10058008">Link</a>],  
    <em>IEEE Transactions on Power Systems</em>, vol. 39, no. 1, pp. 1472–1484, Jan. 2024.
  </li>
  <li>
    Peipei Yu, Hongcai Zhang, Yonghua Song, Hongxun Hui, and <strong>Ge Chen</strong>,  
    District Cooling System Control for Providing Operating Reserve Based on Safe Deep Reinforcement Learning [<a href="https://ieeexplore.ieee.org/document/10019581">Link</a>],  
    <em>IEEE Transactions on Power Systems</em>, vol. 39, no. 1, pp. 40–52, Jan. 2024.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, Hongxun Hui, and Yonghua Song,  
    Deep-quantile-regression-based surrogate model for joint chance-constrained optimal power flow with renewable generation [<a href="https://ieeexplore.ieee.org/document/9956906">Link</a>],  
    <em>IEEE Transactions on Sustainable Energy</em>, vol. 14, no. 1, pp. 657–672, 2023.
  </li>
  <li>
    Zhihao Zhang, Ji Zhang, Han Yuan, <strong>Ge Chen</strong>, and Ning Mei,  
    Performance improvement of the electric water heater by a waste heat recovery method with the thermoelectric effect [<a href="https://www.sciencedirect.com/science/article/abs/pii/S1359431122018440">Link</a>],  
    <em>Applied Thermal Engineering</em>, 222, 119914, 2023.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, Hongxun Hui, and Yonghua Song,  
    Chance-constrained regulation capacity offering for HVAC systems under non-Gaussian uncertainties with mixture-model-based convexification [<a href="https://ieeexplore.ieee.org/document/9794334">Link</a>],  
    <em>IEEE Transactions on Smart Grid</em>, vol. 13, no. 6, pp. 4379–4391, Nov. 2022.
  </li>
  <li>
    宋永华，张洪财，<strong>陈戈</strong>,  
    智慧城市能源系统迈向碳中和的典型路径研究——以澳门特别行政区为例 [<a href="http://old2022.bulletin.cas.cn/publish_article/2022/11/20221117.htm">Link</a>],  
    <em>中国科学院院刊</em>, vol. 37(11), 1650–1663, Nov. 2022.
  </li>
  <li>
    <strong>Ge Chen</strong>, Biao Yan, Hongcai Zhang, Dongdong Zhang, and Yonghua Song,  
    Time-efficient strategic power dispatch for district cooling systems considering evolution of cooling load uncertainties [<a href="https://ieeexplore.ieee.org/abstract/document/9535415/">Link</a>],  
    <em>CSEE Journal of Power and Energy Systems</em>, vol. 8, no. 5, pp. 1457–1467, Sep. 2022.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, and Yonghua Song,  
    Scheduling thermostatically controlled loads to provide regulation capacity based on a learning-based optimal power flow model [<a href="https://ieeexplore.ieee.org/abstract/document/9502573">Link</a>],  
    <em>IEEE Transactions on Sustainable Energy</em>, vol. 12, no. 4, pp. 2459–2470, Oct. 2021.
  </li>
  <li>
    Biao Yan, <strong>Ge Chen</strong>, Hongcai Zhang, and Man Chung Wong,  
    Strategical district cooling system operation with accurate spatiotemporal consumption modeling [<a href="https://www.sciencedirect.com/science/article/abs/pii/S0378778821004497">Link</a>],  
    <em>Energy and Buildings</em>, 247(11), 111165, Sep. 2021.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, Hongxun Hui, Ningyi Dai, and Yonghua Song,  
    Fast Wasserstein‑distance‑based Distributionally Robust Chance‑constrained Power Dispatch for Multi‑zone HVAC Systems [<a href="https://ieeexplore.ieee.org/document/9417102">Link</a>],  
    <em>IEEE Transactions on Smart Grid</em>, vol. 12, no. 5, pp. 4016–4028, Sep. 2021.
  </li>
</ol>

### Conference Papers

<ol class="custom-counter-reversed" style="--start:5;">
  <li>
    <strong>Ge Chen</strong> and Junjie Qin,  
    On the Choice of Loss Function in Learning‑based Optimal Power Flow [<a href="https://ieeexplore.ieee.org/abstract/document/10688728">Link</a>],  
    <em>2024 IEEE Power &amp; Energy Society General Meeting (PESGM)</em>.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, and Yonghua Song,  
    Chance‑constrained DC optimal power flow with non‑gaussian distributed uncertainties [<a href="https://ieeexplore.ieee.org/abstract/document/9916658">Link</a>],  
    <em>2022 IEEE Power &amp; Energy Society General Meeting (PESGM)</em>, pp. 1–5, 2022.
  </li>
  <li>
    <strong>Ge Chen</strong>, Hongcai Zhang, Hongxun Hui, Ningyi Dai, and Yonghua Song,  
    Topology‑free optimal power dispatch for distribution network considering security constraints and flexible building thermal inertia [<a href="https://ieeexplore.ieee.org/abstract/document/9638204">Link</a>],  
    <em>2021 IEEE Power &amp; Energy Society General Meeting (PESGM)</em>, pp. 1–5, 2021.
  </li>
  <li>
    <strong>Ge Chen</strong>, Biao Yan, Hongcai Zhang, and Yonghua Song,  
    Optimal power dispatch for district cooling system considering cooling water transport delay [<a href="https://ieeexplore.ieee.org/document/8743401">Link</a>],  
    <em>2020 12th IEEE PES Asia‑Pacific Power and Energy Engineering Conference</em>, pp. 1–5, Sep. 2020.
  </li>
</ol>
