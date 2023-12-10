# Embodied AI x LLM Papers

This is a paper list on integrating large language models with embodied AI. Large language models have shown sparks of artificial general intelligence, but they are not grounded in the physical world, lacking general embodied intelligence like humans. The integration of LLM with embodied AI is undertaken to address this challenge.

### Keywords Convention
<p><img align="center" height="20" src="https://img.shields.io/badge/GATO-52b5f7?style=flat-square"> The abbreviation of the work. </p>
<p><img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square"> / <img align="center" height="20" src="https://img.shields.io/badge/planner-yellow?style=flat-square"> The role LLM played in the work. If the large language model serves as an embodied agent without depending on extra modules, we use a green background. In other cases, such as when the large language model acts as a text planner, a tool user or a supervisor, we use a yellow background. </p> 
<p><img align="center" height="20" src="https://img.shields.io/badge/game-20b2aa?style=flat-square"> The mainly explored tasks of the work. </p>


## Papers

* **A Generalist Agent.** TMLR 2022.

  *Scott Reed, Konrad Zolna, Emilio Parisotto, Sergio Gomez Colmenarejo, Alexander Novikov, Gabriel Barth-Maron, Mai Gimenez, Yury Sulsky, Jackie Kay, Jost Tobias Springenberg, Tom Eccles, Jake Bruce, Ali Razavi, Ashley Edwards, Nicolas Heess, Yutian Chen, Raia Hadsell, Oriol Vinyals, Mahyar Bordbar, Nando de Freitas* [[pdf](https://arxiv.org/abs/2205.06175)], 2022.5
  <img align="center" height="20" src="https://img.shields.io/badge/GATO-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/game, robot, robot--arm-20b2aa?style=flat-square">

* **PaLM-E: An Embodied Multimodal Language Model.** ICML 2023.

  *Danny Driess, Fei Xia, Mehdi S. M. Sajjadi, Corey Lynch, Aakanksha Chowdhery, Brian Ichter, Ayzaan Wahid, Jonathan Tompson, Quan Vuong, Tianhe Yu, Wenlong Huang, Yevgen Chebotar, Pierre Sermanet, Daniel Duckworth, Sergey Levine, Vincent Vanhoucke, Karol Hausman, Marc Toussaint, Klaus Greff, Andy Zeng, Igor Mordatch, Pete Florence* [[pdf](https://arxiv.org/abs/2303.03378)], [[page](https://palm-e.github.io/)], 2023.3
  <img align="center" height="20" src="https://img.shields.io/badge/PaLM--E-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/planner-yellow?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot, robot--arm-20b2aa?style=flat-square">

* **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control.** Preprint.

    *Anthony Brohan, Noah Brown, Justice Carbajal, Yevgen Chebotar, Xi Chen, Krzysztof Choromanski, Tianli Ding, Danny Driess, Avinava Dubey, Chelsea Finn, Pete Florence, Chuyuan Fu, Montse Gonzalez Arenas, Keerthana Gopalakrishnan, Kehang Han, Karol Hausman, Alexander Herzog, Jasmine Hsu, Brian Ichter, Alex Irpan, Nikhil Joshi, Ryan Julian, Dmitry Kalashnikov, Yuheng Kuang, Isabel Leal, Lisa Lee, Tsang-Wei Edward Lee, Sergey Levine, Yao Lu, Henryk Michalewski, Igor Mordatch, Karl Pertsch, Kanishka Rao, Krista Reymann, Michael Ryoo, Grecia Salazar, Pannag Sanketi, Pierre Sermanet, Jaspiar Singh, Anikait Singh, Radu Soricut, Huong Tran, Vincent Vanhoucke, Quan Vuong, Ayzaan Wahid, Stefan Welker, Paul Wohlhart, Jialin Wu, Fei Xia, Ted Xiao, Peng Xu, Sichun Xu, Tianhe Yu, Brianna Zitkovich* [[pdf](https://arxiv.org/abs/2307.15818)], [[page](https://robotics-transformer2.github.io/)], 2023.7
  <img align="center" height="20" src="https://img.shields.io/badge/RT--2-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot, robot--arm-20b2aa?style=flat-square">

* **Physically Grounded Vision-Language Models for Robotic Manipulation.** Preprint.

  *Jensen Gao, Bidipta Sarkar, Fei Xia, Ted Xiao, Jiajun Wu, Brian Ichter, Anirudha Majumdar, Dorsa Sadigh* [[pdf](https://arxiv.org/pdf/2309.02561.pdf)], [[page](https://iliad.stanford.edu/pg-vlm/)], 2023.9
  <img align="center" height="20" src="https://img.shields.io/badge/robot--arm-20b2aa?style=flat-square">

* **Large Language Models as Generalizable Policies for Embodied Tasks.** Preprint.

  *Andrew Szot, Max Schwarzer, Harsh Agrawal, Bogdan Mazoure, Walter Talbott, Katherine Metcalf, Natalie Mackraz, Devon Hjelm, Alexander Toshev* [[pdf](https://arxiv.org/abs/2310.17722)], [[page](https://llm-rl.github.io/)], 2023.10
  <img align="center" height="20" src="https://img.shields.io/badge/LLaRP-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot-20b2aa?style=flat-square">

* **Octopus: Embodied Vision-Language Programmer from Environmental Feedback.** Preprint.

  *Jingkang Yang, Yuhao Dong, Shuai Liu, Bo Li, Ziyue Wang, Chencheng Jiang, Haoran Tan, Jiamu Kang, Yuanhan Zhang, Kaiyang Zhou, Ziwei Liu* [[pdf](https://arxiv.org/abs/2310.08588)], [[page](https://choiszt.github.io/Octopus/)], 2023.10
  <img align="center" height="20" src="https://img.shields.io/badge/Octopus-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/game, robot-20b2aa?style=flat-square">

* **Vision-Language Foundation Models as Effective Robot Imitators.** Preprint.

  *Xinghang Li, Minghuan Liu, Hanbo Zhang, Cunjun Yu, Jie Xu, Hongtao Wu, Chilam Cheang, Ya Jing, Weinan Zhang, Huaping Liu, Hang Li, Tao Kong* [[pdf](https://arxiv.org/pdf/2311.01378.pdf)], [[page](https://roboflamingo.github.io/)], 2023.11
  <img align="center" height="20" src="https://img.shields.io/badge/RoboFlamingo-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot--arm-20b2aa?style=flat-square">

* **An Embodied Generalist Agent in 3D World.** Preprint.

  *Jiangyong Huang, Silong Yong, Xiaojian Ma, Xiongkun Linghu, Puhao Li, Yan Wang, Qing Li, Song-Chun Zhu, Baoxiong Jia, Siyuan Huang* [[pdf](https://arxiv.org/abs/2311.12871)], [[page](https://embodied-generalist.github.io/)], 2023.11
  <img align="center" height="20" src="https://img.shields.io/badge/LEO-52b5f7?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/embodiment-green?style=flat-square">
  <img align="center" height="20" src="https://img.shields.io/badge/robot, robot--arm-20b2aa?style=flat-square">

