---
title: "Paper Title Number 3"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2015-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Yuxing Wang, Shuang Wu, Haobo Fu, Qiang Fu, Tiantian Zhang, Yongzhe Chang, Xueqian Wang'
---

Co-design of morphology and control of a Voxel-based Soft Robot (VSR) is challenging due to the notorious bi-level optimization. In this paper, we present a Curriculum-based Co-design (CuCo) method for learning to design and control VSRs through an easy-to-difficult process. Specifically, we expand the design space from a small size to the target size gradually through a predefined curriculum. At each learning stage of the curriculum, we use reinforcement learning to simultaneously train the design policy and the control policy, which is enabled by incorporating the design process into the environment and using differentiable policy representations. The converged morphology and the learned policies from last stage are inherited and then serve as the starting point for the next stage. In empirical studies, we show that CuCo is more efficient in creating larger robots with better performance by reusing the practical design and control patterns learned within each stage, in comparison to prior approaches that learn from scratch in the space of target size.

<iframe height=498 width=510 src="/images/cuco_video.mp4">


[Download paper here](https://openreview.net/pdf?id=r9fX833CsuN)

bibtex<br />
```bash
@inproceedings{wang2023curriculum,
  title={Curriculum-based Co-design of Morphology and Control of Voxel-based Soft Robots},
  author={Wang, Yuxing and Wu, Shuang and Fu, Haobo and Fu, Qiang and Zhang, Tiantian and Chang, Yongzhe and Wang, Xueqian},
  booktitle={The Eleventh International Conference on Learning Representations},
  year={2023}
}
```