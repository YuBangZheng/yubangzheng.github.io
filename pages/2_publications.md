---
layout: page
title: Publications
comments: true
permalink: /publications/

---

* content
{:toc}




<style>
.biblist { }

/* The item */
.biblist li { }

/* You can define custom styles for plstyle field here. */


/*************************************
   The box that contain BibTeX code
 *************************************/
div.noshow { display: none; }
div.BibTeX {
  margin-right: 1%;
  margin-left: 3.5%;
  margin-top: 1.2em;
  margin-bottom: 1.3em;
  border: 1px solid silver;
  padding: 0.3em 0.5em;
  background: #eeeeee;
}
div.BibTeX pre { font-size: 85%; overflow: auto;  width: 100%; }
</style>

<script>
function toggleBibtex(articleid) {
  var bib = document.getElementById('bib_'+articleid);
  if (bib) {
    if(bib.className.indexOf('BibTeX') != -1) {
    bib.className.indexOf('noshow') == -1?bib.className = 'BibTeX noshow':bib.className = 'BibTeX';
    }
  } else {
    return;
  }
}
</script>

* **Yu-Bang Zheng**, Ting-Zhu Huang, Xi-Le Zhao, Qibin Zhao, Tai-Xiang Jiang, "Fully-Connected Tensor Network Decomposition and Its Application to Higher-Order Tensor Completion", in _Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2021)_, vol. 35, no. 12, pp. 11071-11078, 2021. <a href="javascript:toggleBibtex('zhengFCTN2021')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/AAAI2021_FCTN_Decomposition_ybz.pdf) [[Material]](https://yubangzheng.github.io/papers/Supplementary_Material_FCTN_decomposition.pdf) [[Slide]](https://yubangzheng.github.io/papers/Slide_FCTN_decomposition.pdf) [[Poster]](https://yubangzheng.github.io/papers/Poster_FCTN_decomposition.pdf) [[Code]](https://yubangzheng.github.io/codes/code_FCTN_Decomposition.zip)

<div id="bib_zhengFCTN2021" class="BibTeX noshow">
<pre>
@inproceedings{zhengFCTN2021,
  title={Fully-Connected Tensor Network Decomposition and Its Application to Higher-Order Tensor Completion}, 
  author={Zheng, Yu-Bang and Huang, Ting-Zhu and Zhao, Xi-Le and Zhao, Qibin and Jiang, Tai-Xiang}, 
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={35},
  number={12},
  pages={11071-11078},
  year={2021},  
}
</pre>
</div>


* **Yu-Bang Zheng**, Ting-Zhu Huang, Xi-Le Zhao, Yong Chen, Wei He, "Double-Factor-Regularized Low-Rank Tensor Factorization for Mixed Noise Removal in Hyperspectral Image", _IEEE Transactions on Geoscience and Remote Sensing_, vol. 58, no. 12, pp. 8450-8464, 2020. <a href="javascript:toggleBibtex('TGRS_LRTFDFR')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/TGRS-LRTFDFR.pdf) [[Code]](https://yubangzheng.github.io/codes/code_LRTFDFR.zip)

<div id="bib_TGRS_LRTFDFR" class="BibTeX noshow">
<pre>
@article{TGRS_LRTFDFR,
  author = {Yu-Bang Zheng and Ting-Zhu Huang and Xi-Le Zhao and Yong Chen and Wei He}, 
  journal = {IEEE Transactions on Geoscience and Remote Sensing},  
  title = {Double-Factor-Regularized Low-Rank Tensor Factorization for Mixed Noise Removal in Hyperspectral Image},
  year={2020},
  volume={58},
  number={12},
  pages={8450-8464},
  month={Dec.},
}
</pre>
</div>


* **Yu-Bang Zheng**, Ting-Zhu Huang, Xi-Le Zhao, Tai-Xiang Jiang, Teng-Yu Ji, Tian-Hui Ma, "Tensor N-tubal Rank and Its Convex Relaxation for Low-Rank Tensor Recovery", _Information Sciences_, vol. 532, pp. 170-189, 2020. <a href="javascript:toggleBibtex('IS_Ntubal')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/IS-N-tubal-rank.pdf) [[PDF2]](https://yubangzheng.github.io/papers/IS-N-tubal-rank2.pdf) [[Code]](https://yubangzheng.github.io/codes/code_WSTNN.zip)

<div id="bib_IS_Ntubal" class="BibTeX noshow">
<pre>
@article{IS_Ntubal,
  author = {Yu-Bang Zheng and Ting-Zhu Huang and Xi-Le Zhao and Tai-Xiang Jiang and Teng-Yu Ji and Tian-Hui Ma},
  journal = {Information Sciences},
  title = {Tensor {N}-tubal rank and its convex relaxation for low-rank tensor recovery},
  volume = {532},
  pages = {170-189},
  year = {2020},
  month={Sep.},
}
</pre>
</div>


* **Yu-Bang Zheng**, Ting-Zhu Huang, Xi-Le Zhao, Tai-Xiang Jiang, Tian-Hui Ma, Teng-Yu Ji, "Mixed Noise Removal in Hyperspectral Image via Low-Fibered-Rank Regularization", _IEEE Transactions on Geoscience and Remote Sensing_, vol. 58, no. 1, pp. 734-749, 2020. <a href="javascript:toggleBibtex('TGRS_fibered')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/TGRS-low-fibered-rank.pdf) [[Code]](https://yubangzheng.github.io/codes/code_TGRS_low-fibered-rank.zip) (<span style="color:red">ESI Highly Cited Paper</span>)

<div id="bib_TGRS_fibered" class="BibTeX noshow">
<pre>
@article{TGRS_fibered,
  author ={Yu-Bang Zheng and Ting-Zhu Huang and Xi-Le Zhao and Tai-Xiang Jiang and Tian-Hui Ma and Teng-Yu Ji},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  title={Mixed Noise Removal in Hyperspectral Image via Low-Fibered-Rank Regularization},
  year={2020},
  volume={58},
  number={1},
  pages={734-749},
  month={Jan.},
}
</pre>
</div>


* **Yu-Bang Zheng**, Ting-Zhu Huang, Teng-Yu Ji, Xi-Le Zhao, Tai-Xiang Jiang, Tian-Hui Ma, "Low-Rank Tensor Completion via Smooth Matrix Factorization", _Applied Mathematical Modelling_, vol. 70, pp. 677-695, 2019. <a href="javascript:toggleBibtex('AMM_SMFLRTC')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/AMM_SMFLRTC_zheng.pdf) [[Code]](https://yubangzheng.github.io/codes/code_SMF-LRTC.zip)

<div id="bib_AMM_SMFLRTC" class="BibTeX noshow">
<pre>
@article{AMM_SMFLRTC,
  title = {Low-Rank Tensor Completion via Smooth Matrix Factorization},
  journal = {Applied Mathematical Modelling},
  volume = {70},
  pages = {677-695},
  year = {2019},
  author = {Yu-Bang Zheng and Ting-Zhu Huang and Teng-Yu Ji and Xi-Le Zhao and Tai-Xiang Jiang and Tian-Hui Ma},
  month={Jun.},
}
</pre>
</div>


* **Yu-Bang Zheng**, Ting-Zhu Huang, Xi-Le Zhao, Tai-Xiang Jiang, Jie Huang, "Hyperspectral Image Denoising via Convex Low-Fibered-Rank Regularization", in _IEEE International Geoscience and Remote Sensing Symposium (IGARSS)_, 2019, pp. 222-225. (**Oral**) <a href="javascript:toggleBibtex('IGARSS2019_fibered')" class="textlink">[BibTeX]</a> [[PDF]](https://yubangzheng.github.io/papers/IGARSS2019-low-fibered-rank.pdf) [[Slide]](https://yubangzheng.github.io/papers/Oral_IGARSS2019_ybz.pdf) [[Code]](https://yubangzheng.github.io/codes/code_TGRS_low-fibered-rank.zip)

<div id="bib_IGARSS2019_fibered" class="BibTeX noshow">
<pre>
@inproceedings{IGARSS2019_fibered,
  author={Zheng, Yu-Bang and Huang, Ting-Zhu and Zhao, Xi-Le and Jiang, Tai-Xiang and Huang, Jie},
  booktitle={IEEE International Geoscience and Remote Sensing Symposium}, 
  title={Hyperspectral Image Denoising Via Convex Low-Fibered-Rank Regularization}, 
  year={2019},
  volume={},
  number={},
  pages={222-225},
  }
</pre>
</div>


* Yun-Yang Liu, Xi-Le Zhao, **Yu-Bang Zheng**, Tian-Hui Ma, Hongyan Zhang, "Hyperspectral Image Restoration by Tensor Fibered Rank Constrained Optimization and Plug-and-Play Regularization", _IEEE Transactions on Geoscience and Remote Sensing_, **accepted**, doi: 10.1109/TGRS.2020.3045169, 2021. [[PDF]](https://yubangzheng.github.io/papers/TGRS-yyl.pdf) [[Code]](https://github.com/zhaoxile/TGRS_FRCTR_PnP)

* Yu-Chun Miao, Xi-Le Zhao, Xiao Fu, Jian-Li Wang, **Yu-Bang Zheng**, "Hyperspectral Denoising Using Unsupervised Disentangled Spatio-Spectral Deep Priors", _IEEE Transactions on Geoscience and Remote Sensing_, **accepted**, 2021. [[PDF]](https://arxiv.org/pdf/2102.12310.pdf)

* Xiao-Tong Li, Xi-Le Zhao, Tai-Xiang Jiang, **Yu-Bang Zheng**, Teng-Yu Ji, Ting-Zhu Huang, "Low-Rank Tensor Completion via Combined Non-local Self-Similarity and Low-Rank Regularization", _Neurocomputing_, vol. 367, pp. 1-12, 2019. [[PDF]](https://yubangzheng.github.io/papers/Neurocomputing-NLSLR-xtl.pdf)

* Jian-Li Wang, Ting-Zhu Huang, Xi-Le Zhao, Jie Huang, Tian-Hui Ma, **Yu-Bang Zheng**, "Reweighted Block Sparsity Regularization for Remote Sensing Images Destriping", _IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing_, vol. 12, no. 12, pp. 4951-4963, 2019. [[PDF]](https://yubangzheng.github.io/papers/JSTARS-jlwang.pdf) [[Code]](https://yubangzheng.github.io/codes/code_RBSUTV.zip)

* Xin Li, Ting-Zhu Huang, Xi-Le Zhao, Teng-Yu Ji, **Yu-Bang Zheng**, Liang-Jian Deng, "Adaptive Total Variation and Second-Order Total Variation-Based Model for Low-Rank Tensor Completion", _Numerical Algorithms_, vol. 86, pp. 1-24, 2021.

* Lin Guo, Xi-Le Zhao, Xian-Ming Gu, Yong-Liang Zhao, **Yu-Bang Zheng**, Ting-Zhu Huang, "Three-Dimensional Fractional Total Variation Regularized Tensor Optimized Model for Image Deblurring", _Applied Mathematics and Computation_, vol. 404, pp. 126224, 2021.

* Jie Lin, Ting-Zhu Huang, Xi-Le Zhao, Tian-Hui Ma, Tai-Xiang Jiang, **Yu-Bang Zheng**, "A Novel Non-Convex Low-Rank Tensor Approximation Model for Hyperspectral Image Restoration", _Applied Mathematics and Computation_, vol. 408, pp. 126342, 2021.

* Tian Lu, Xi-Le Zhao, **Yu-Bang Zheng**, Meng Ding, Xiao-Tong Li, "Tensor Completion via Global Low-Tubal-Rankness and Nonlocal Self-Similarity", in _IEEE Global Conference on Signal and Information Processing (GlobalSIP)_, 2019, pp. 1-5. (**Oral**) [[PDF]](https://yubangzheng.github.io/papers/TianLu.pdf)

