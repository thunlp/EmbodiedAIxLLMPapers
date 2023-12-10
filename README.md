# Embodied AI x LLM Papers

This is a paper list on integrating large language models with embodied AI. Large language models have shown sparks of artificial general intelligence, but they are not grounded in the physical world, lacking human-like embodied intelligence. The integration of LLM with embodied AI is undertaken to address this challenge. Note that works without training the LLM for embodiment capabilities may not be included in this repository, such as using ChatGPT for planning, tool-using or supervision.

### Keywords Convention
<p><img align="center" height="20" src="https://img.shields.io/badge/GATO-52b5f7?style=flat-square"> The abbreviation of the work. </p>
<p><img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square"> The role LLM plays in the work. </p> 
<p><img align="center" height="20" src="https://img.shields.io/badge/game-20b2aa?style=flat-square"> The mainly explored tasks of the work. </p>

## Papers

* **A Generalist Agent.** TMLR 2022.

  *Scott Reed, Konrad Zolna, Emilio Parisotto, Sergio Gomez Colmenarejo, Alexander Novikov, Gabriel Barth-Maron, Mai Gimenez, Yury Sulsky, Jackie Kay, Jost Tobias Springenberg, Tom Eccles, Jake Bruce, Ali Razavi, Ashley Edwards, Nicolas Heess, Yutian Chen, Raia Hadsell, Oriol Vinyals, Mahyar Bordbar, Nando de Freitas* [[pdf](https://arxiv.org/abs/2205.06175)], 2022.5
  <img align="center" height="20" src="https://img.shields.io/badge/GATO-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/game, robot, robot--arm-20b2aa?style=flat-square">
  
* **PaLM-E: An Embodied Multimodal Language Model.** ICML 2023.

  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence* [[pdf](https://arxiv.org/abs/2303.03378)], [[page](https://palm-e.github.io/)], 2023.3
  <img align="center" height="20" src="https://img.shields.io/badge/PaLM--E-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/planner-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot, robot--arm-20b2aa?style=flat-square">

* **EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought.** Preprint.

  *Yao Mu, Qinglong Zhang, Mengkang Hu, Wenhai Wang, Mingyu Ding, Jun Jin, Bin Wang, Jifeng Dai, Yu Qiao, Ping Luo* [[pdf](https://arxiv.org/abs/2305.15021)], 2023.5
  <img align="center" height="20" src="https://img.shields.io/badge/EmbodiedGPT-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot, robot--arm-20b2aa?style=flat-square">
  
* **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control.** Preprint.

    *Anthony Brohan, Noah Brown, Justice Carbajal, Yevgen Chebotar, Xi Chen, Krzysztof Choromanski, Tianli Ding, Danny Driess, Avinava Dubey, Chelsea Finn, Pete Florence, Chuyuan Fu, Montse Gonzalez Arenas, Keerthana Gopalakrishnan, Kehang Han, Karol Hausman, Alexander Herzog, Jasmine Hsu, Brian Ichter, Alex Irpan, Nikhil Joshi, Ryan Julian, Dmitry Kalashnikov, Yuheng Kuang, Isabel Leal, Lisa Lee, Tsang-Wei Edward Lee, Sergey Levine, Yao Lu, Henryk Michalewski, Igor Mordatch, Karl Pertsch, Kanishka Rao, Krista Reymann, Michael Ryoo, Grecia Salazar, Pannag Sanketi, Pierre Sermanet, Jaspiar Singh, Anikait Singh, Radu Soricut, Huong Tran, Vincent Vanhoucke, Quan Vuong, Ayzaan Wahid, Stefan Welker, Paul Wohlhart, Jialin Wu, Fei Xia, Ted Xiao, Peng Xu, Sichun Xu, Tianhe Yu, Brianna Zitkovich* [[pdf](https://arxiv.org/abs/2307.15818)], [[page](https://general-pattern-machines.github.io/)], 2023.7
  <img align="center" height="20" src="https://img.shields.io/badge/RT--2-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot--arm-20b2aa?style=flat-square">

* **Large Language Models as General Pattern Machines.** CoRL 2023.

    *Suvir Mirchandani, Fei Xia, Pete Florence, Brian Ichter, Danny Driess, Montserrat Gonzalez Arenas, Kanishka Rao, Dorsa Sadigh, Andy Zeng* [[pdf](https://arxiv.org/abs/2307.04721)], [[page](https://robotics-transformer2.github.io/)], 2023.7
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot--arm-20b2aa?style=flat-square">

* **Large Language Models as Generalizable Policies for Embodied Tasks.** Preprint.

  *Andrew Szot, Max Schwarzer, Harsh Agrawal, Bogdan Mazoure, Walter Talbott, Katherine Metcalf, Natalie Mackraz, Devon Hjelm, Alexander Toshev* [[pdf](https://arxiv.org/abs/2310.17722)], [[page](https://llm-rl.github.io/)], 2023.10
  <img align="center" height="20" src="https://img.shields.io/badge/LLaRP-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot-20b2aa?style=flat-square">

* **Octopus: Embodied Vision-Language Programmer from Environmental Feedback.** Preprint.

  *Jingkang Yang, Yuhao Dong, Shuai Liu, Bo Li, Ziyue Wang, Chencheng Jiang, Haoran Tan, Jiamu Kang, Yuanhan Zhang, Kaiyang Zhou, Ziwei Liu* [[pdf](https://arxiv.org/abs/2310.08588)], [[page](https://choiszt.github.io/Octopus/)], 2023.10
  <img align="center" height="20" src="https://img.shields.io/badge/Octopus-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/game, robot-20b2aa?style=flat-square">

* **Vision-Language Foundation Models as Effective Robot Imitators.** Preprint.

  *Xinghang Li, Minghuan Liu, Hanbo Zhang, Cunjun Yu, Jie Xu, Hongtao Wu, Chilam Cheang, Ya Jing, Weinan Zhang, Huaping Liu, Hang Li, Tao Kong* [[pdf](https://arxiv.org/pdf/2311.01378.pdf)], [[page](https://roboflamingo.github.io/)], 2023.11
  <img align="center" height="20" src="https://img.shields.io/badge/RoboFlamingo-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot--arm-20b2aa?style=flat-square">

* **An Embodied Generalist Agent in 3D World.** Preprint.

  *Jiangyong Huang, Silong Yong, Xiaojian Ma, Xiongkun Linghu, Puhao Li, Yan Wang, Qing Li, Song-Chun Zhu, Baoxiong Jia, Siyuan Huang* [[pdf](https://arxiv.org/abs/2311.12871)], [[page](https://embodied-generalist.github.io/)], 2023.11
  <img align="center" height="20" src="https://img.shields.io/badge/LEO-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/controller-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot, robot--arm-20b2aa?style=flat-square">
