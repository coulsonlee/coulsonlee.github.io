---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
  body {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
  }
  .container {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
  }

  .about-section {
    margin-bottom: 40px;
  }
  .about-section h1 {
    font-size: 2.2rem;
    margin-bottom: 10px;
    color: #222;
  }
  .about-section p {
    font-size: 1rem;
    margin: 8px 0;
  }
  .about-section a {
    color: #0066cc;
    text-decoration: none;
  }
  .about-section a:hover {
    text-decoration: underline;
  }

  .news-section {
    margin-bottom: 50px;
  }
  .news-title {
    display: flex;
    align-items: center;
    font-size: 1.5rem;
    margin-bottom: 12px;
    color: #222;
  }
  .news-title::before {
    content: "📰";
    margin-right: 8px;
    font-size: 1.8rem;
  }
  .news-list {
    background: linear-gradient(135deg, #fafafa 0%, #f0f0f0 100%);
    border: 1px solid #ddd;
    border-radius: 6px;
    padding: 12px 16px;
    max-height: 300px;
    overflow-y: auto;
  }
  .news-item {
    font-size: 0.95rem;
    color: #555;
    margin: 6px 0;
    position: relative;
    padding-left: 20px;
  }
  .news-item::before {
    content: "●";
    position: absolute;
    left: 0;
    top: 2px;
    font-size: 0.6rem;
    color: #0066cc;
  }

  .pub-section h2 {
    font-size: 1.5rem;
    margin-bottom: 12px;
    color: #222;
  }

  /* 这部分是新增的：限制高度并启用滚动 */
  .pub-list-container {
    max-height: 600px;        /* 根据实际需要，自行调整 */
    overflow-y: auto;
    padding-right: 6px;       /* 给滚动条留空隙 */
    border: 1px solid #ddd;
    border-radius: 6px;
    background-color: #fafafa;
  }
  .pub-list-container::-webkit-scrollbar {
    width: 6px;
  }
  .pub-list-container::-webkit-scrollbar-thumb {
    background-color: rgba(0, 0, 0, 0.2);
    border-radius: 3px;
  }
  .pub-list-container::-webkit-scrollbar-track {
    background-color: transparent;
  }

  .publication-card {
    border: 1px solid #ddd;
    border-radius: 6px;
    padding: 15px 18px;
    margin: 12px;
    transition: box-shadow 0.25s ease;
    position: relative;
    background-color: #fff;
  }
  .publication-card:hover {
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    border-color: #ccc;
  }
  .publication-card h3 {
    font-size: 1.1rem;
    margin: 4px 0 6px 0;
    color: #111;
  }
  .publication-card .authors {
    font-size: 0.95rem;
    color: #4fb2d9;
    margin-bottom: 6px;
    font-style: italic;
  }
  .publication-card .meta {
    font-size: 0.9rem;
    color: #333;   /* 改为更深色 */
  }
  .publication-card .meta a {
    color: #0066cc;
    text-decoration: none;
  }
  .publication-card .meta a:hover {
    text-decoration: underline;
  }
  .pub-badge {
    display: inline-block;
    background-color: #ffecec;
    color: #a94442;
    padding: 2px 6px;
    border-radius: 3px;
    font-size: 0.85rem;
    vertical-align: middle;
    margin-right: 6px;
  }
  .pdf-link {
    position: absolute;
    bottom: 12px;
    right: 12px;
    width: 20px;
    height: 20px;
  }
  .pdf-link img {
    width: 100%;
    height: 100%;
    display: block;
  }
</style>

<div class="container">

  <!-- About Me -->
  <div class="about-section">
    <p>
      <strong>Gen Li</strong> is a third-year Ph.D. student at Clemson University, 
      supervised by Prof. 
      <a href="https://xiaolongma2016.com/" target="_blank" rel="noopener noreferrer">Xiaolong Ma</a> 
      and co-advised by Prof. 
      <a href="https://cecas.clemson.edu/~linkeg/index.html" target="_blank" rel="noopener noreferrer">Linke Guo</a>. 
      His primary research interests span efficient Machine Learning, 
      algorithm-hardware co-design for mobile devices, 
      and fairness & robustness in broad AI applications.
    </p>
  </div>

  <!-- News -->
  <div class="news-section">
    <div class="news-title">Latest News</div>
    <div class="news-list">
      <div class="news-item">09/2024 — Paper accepted at <strong>NeurIPS 2024</strong>.</div>
      <div class="news-item">09/2024 — Paper accepted at <strong>S&P 2025</strong>.</div>
      <div class="news-item">07/2024 — Paper accepted at <strong>ECCV 2024</strong>.</div>
      <div class="news-item">05/2024 — Two papers accepted at <strong>ICML 2024</strong>.</div>
      <div class="news-item">01/2024 — Paper accepted at <strong>ICLR 2024</strong>.</div>
      <div class="news-item">09/2023 — Paper accepted at <strong>NeurIPS 2023</strong>.</div>
      <div class="news-item">02/2023 — “Spotlight” paper at ICLR SNN Workshop.</div>
      <div class="news-item">02/2023 — “Highlight” paper (top 2.5%) at <strong>CVPR 2023</strong>.</div>
    </div>
  </div>

  <!-- Selected Publications -->
Selected Publications
======
<div style="font-family: Arial, sans-serif;">
  <style>
    .publication-card {
      padding: 15px;
      margin-bottom: 10px;
      border: 2px solid #dfdfdf;  /* Very light gray border */
      border-radius: 5px;
      transition: box-shadow 0.3s ease, border 0.3s ease;
    }
    .publication-card:hover {
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-color: #d0d0d0;  /* Slightly darker gray color on hover */
    }
    .pdf-logo {
      position: absolute;
      bottom: 10px; /* Adjust as needed */
      right: 10px; /* Adjust as needed */
      width: 24px; /* Set the size of the PDF icon */
      height: 24px;
    }
    .pdf-logo img {
      width: 100%; /* Ensure the image fills the anchor */
      height: 100%;
      display: block;
    }
  </style>

  <!-- First Paper -->
  
  <div class="publication-card">
    <h3 style="margin: 5px 0;">Adversarial Robust ViT-based Automatic Modulation Recognition in Practical Deep Learning-based Wireless Systems</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Gen Li, Chun-Chih Lin, Xiaonan Zhang, Xiaolong Ma, Linke Guo</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">S&P '25</span> &middot; Acceptance rate: 14.3% &middot; <a href="https://www.computer.org/csdl/proceedings-article/sp/2025/223600a030/21B7Qkjltcs" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
 </div>

  <div class="publication-card">
    <h3 style="margin: 5px 0;">A Single-Step, Sharpness-Aware Minimization is All You Need to Achieve Efficient and Accurate Sparse Training</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Jie Ji, Gen Li, Jingjing Fu, Fatemeh Afghah, Linke Guo, Xiaoyong Yuan, Xiaolong Ma</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">NeurIPS '24</span> &middot; Acceptance rate: 25.8% &middot; <a href="https://openreview.net/forum?id=MJgMMqMDu4" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>
  
  
  <div class="publication-card">
    <h3 style="margin: 5px 0;">Data Overfitting for On-Device Super-Resolution with Dynamic Algorithm and Compiler Co-Design</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Gen Li, Zhihao Shu, Jie Ji, Minghai Qin, Fatemeh Afghah, Wei Niu, Xiaolong Ma</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">ECCV '24</span> &middot; Acceptance rate: 27.9% &middot; <a href="https://arxiv.org/abs/2407.02813" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>
  
  <div class="publication-card">
    <h3 style="margin: 5px 0;">Advancing Dynamic Sparse Training by Exploring Optimization Opportunities</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Jie Ji*, Gen Li*, Lu Yin, Minghai Qin, Geng Yuan, Linke Guo, Shiwei Liu, Xiaolong Ma</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">ICML '24</span> &middot; Acceptance rate: 27.5% &middot; <a href="https://openreview.net/forum?id=szRHR9XGrY" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>

  
  <div class="publication-card">
    <h3 style="margin: 5px 0;">Outlier weighed layerwise sparsity (owl): A missing secret sauce for pruning llms to high sparsity</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Lu Yin, You Wu, Zhenyu Zhang, Cheng-Yu Hsieh, Yaqing Wang, Yiling Jia, Gen Li, Ajay Jaiswal, Mykola Pechenizkiy, Yi Liang, Michael Bendersky, Zhangyang Wang, Shiwei Liu</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">ICML '24</span> &middot; Acceptance rate: 27.5% &middot; <a href="https://arxiv.org/abs/2310.05175" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>

  <div class="publication-card">
    <h3 style="margin: 5px 0;">NeurRev: Train Better Sparse Neural Network Practically via Neuron Revitalization</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Gen Li, Lu Yin, Jie Ji, Wei Niu, Minghai Qin, Bin Ren, Linke Guo, Shiwei Liu, Xiaolong Ma</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">ICLR '24</span>
    &middot; Acceptance rate: 31% &middot; <a href="https://openreview.net/forum?id=60lNoatp7u" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>
  
  <div class="publication-card">
    <h3 style="margin: 5px 0;">Dynamic Sparsity Is Channel-Level Sparsity Learner</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Lu Yin, Gen Li, Meng Fang, Li Shen, Tianjin Huang, Zhangyang Wang, Vlado Menkovski, Xiaolong Ma, Mykola Pechenizkiy, Shiwei Liu</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">NeurIPS '23</span> &middot; Acceptance rate: 26.1% &middot; <a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/d6d0e41e0b1ed38c76d13c9e417a8f1f-Paper-Conference.pdf" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>

  <div class="publication-card">
    <h3 style="margin: 5px 0;">Towards High-Quality and Efficient Video Super-Resolution via Spatial-Temporal Data Overfitting</h3>
    <p style="margin: 5px 0; color: #4fb2d9;"><i>Gen Li, Jie Ji, Minghai Qin, Wei Niu, Bin Ren, Fatemeh Afghah, Linke Guo, Xiaolong Ma</i></p>
    <p style="margin: 5px 0;"><span style="background-color: #f2dede; padding: 2px 5px; border-radius: 3px;">CVPR '23</span> &middot; Highlight paper: top 2.5%  &middot; <a href="https://ieeexplore.ieee.org/abstract/document/10203894" 
          target="_blank" 
          rel="noopener noreferrer" 
          style="text-decoration: none; color: #007BFF;">Paper Link</a>
    </p>  
  </div>

</div>
