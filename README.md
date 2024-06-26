# EXAMS-V: A Multi-Discipline Multilingual Multimodal Exam Benchmark for Evaluating Vision Language Models

<p align="center" style="display: flex; flex-direction: row; justify-content: center; align-items: center">
📄 <a href="https://arxiv.org/abs/2403.10378" target="_blank" style="margin-right: 15px; margin-left: 10px">Paper</a> • 
🤗 <a href="https://huggingface.co/datasets/Rocktim/EXAMS-V" target="_blank" style="margin-left: 10px">Dataset</a> 
</p>


## Introduction
We introduce EXAMS-V, a new challenging multi-discipline multimodal multilingual exam benchmark for evaluating vision language models. It consists of  20,932 multiple-choice questions across 20 school disciplines covering natural science, social science, and other miscellaneous studies, e.g.,~religion, fine arts, business, etc. EXAMS-V includes a variety of multimodal features such as text, images, tables, figures, diagrams, maps, scientific symbols, and equations. The questions come in 11 languages from 7 language families. Unlike existing benchmarks, EXAMS-V is uniquely curated by gathering school exam questions from various countries, with a variety of education systems. This distinctive approach calls for intricate reasoning across diverse languages and relies on region-specific knowledge. Solving the problems in the dataset requires advanced perception and joint reasoning over the text and the visual content of the image. 
Our evaluation results demonstrate that this is a challenging dataset, which is difficult even for advanced vision--text models such as GPT-4V and Gemini; this underscores the inherent complexity of the dataset and its significance as a future benchmark.

![image](./images/language_samples-1.png)

## Dataset Statistics

The following table shows the statistics of EXAMS-V dataset. The languages are ordered from high-resource to low-resource languages. Here, \# visual Q. refers to questions with multimodal context and \# text Q. refers to text only questions.

| *Language* |*Family* | *Grade* | *\# Subjects* | *\# Questions* | *\# visual Q.* | *\# text Q.* |
|-------------------|-----------------|------------------------------------|------------------------------------------|-------------------------------------------|-------------------------------------------|-----------------------------------------|
| English           |  Germanic        | 11, 12                             | 4                                        | 724                                       | 181                                       | 543                                     |
| Chinese           | Sino-Tibetan    | 8-12                               | 6                                        | 2,635                                     | 1,991                                     | 644                                     |
| French            | Romance         | 12                                 | 3                                        | 439                                       | 50                                        | 389                                     |
| German            | Germanic        | 12                                 | 5                                        | 819                                       | 144                                       | 675                                     |
| Italian           | Romance         | 12                                 | 11                                       | 1,645                                     | 292                                       | 1,353                                   |
| Arabic            |  Semitic         | 4-12                               | 6                                        | 823                                       | 117                                       | 706                                     |
| Polish            | Slavic          | 12                                 | 1                                        | 2,511                                     | 422                                       | 2,089                                   |
| Hungarian         | Finno-Ugric     | 12                                 | 6                                        | 3,801                                     | 495                                       | 3,306                                   |
| Bulgarian         |Slavic          | 4, 12                              | 4                                        | 2,132                                     | 435                                       | 1,697                                   |
| Croatian          | Slavic          | 12                                 | 13                                       | 3,969                                     | 700                                       | 3,269                                   |
| Serbian           | Slavic          | 12                                 | 11                                       | 1,434                                     | 259                                       | 1,175                                   |

<!-- ![fig](./images/figure_data_dist-1.png) -->
The following is a pie-diagram showing the distribution of subject and languages in the dataset.
<div style="text-align: center;">
<img src="./images/figure_data_dist-1.png" alt="Image Description" width="500"/>
</div>

## Citation
If you find this useful in your research, please consider citing it:
```
@misc{das2024examsv,
      title={EXAMS-V: A Multi-Discipline Multilingual Multimodal Exam Benchmark for Evaluating Vision Language Models}, 
      author={Rocktim Jyoti Das and Simeon Emilov Hristov and Haonan Li and Dimitar Iliyanov Dimitrov and Ivan Koychev and Preslav Nakov},
      year={2024},
      eprint={2403.10378},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
