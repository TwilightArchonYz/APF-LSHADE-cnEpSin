在本研究中，我们发现人工势场（APF）方法的路径搜索机制与优化问题求解过程之间存在显著相似性。APF方法通过创建势场并利用其梯度引导机器人向目标移动，同时避开障碍物。这一概念可以有效应用于优化算法中。梯度引导个体朝潜在的最优解前进，而已识别的局部劣解则被视为障碍物，算法通过障碍规避策略绕过低质量区域。基于这一观察，我们提出了一种基于APF的框架来增强差分进化（DE）算法，为解决优化问题引入了一种新的设计范式。在此框架下开发的DE变体在2023年中国智能优化竞赛的单目标赛道中获得二等级，并在国际知名的CEC2023竞赛的单目标优化赛道中获得第三名，展现了其卓越性能。

本文的主要贡献如下：

(1) 本研究首次指出了APF方法的路径搜索机制与进化算法优化过程之间的相似性，揭示了一种全新的概念关联。

(2) 首次将APF方法应用于进化算法，通过开发一种将APF的梯度引导特性与进化算法的探索与开发机制相结合的混合策略，实现了算法性能的提升。

(3) 提出了一个基于APF的通用框架，用于增强进化算法，并通过全面的实验评估验证了其在不同算法变体中的适应性和可扩展性。

(4) 将基于APF的框架应用于四种先进的差分进化（DE）算法变体，显著提高了算法在多个基准问题上的性能表现。

In this study, we identified a striking similarity between the path-searching mechanism of the Artificial Potential Field (APF) method and the process of solving optimization problems. The APF method creates a potential field and leverages its gradient to guide robots toward a target while avoiding obstacles. This concept can be effectively applied to optimization algorithms. Gradients guide individuals toward potential optimal solutions, while identified local inferior solutions are treated as obstacles, allowing the algorithm to bypass low-quality regions using obstacle avoidance strategies. Building on this observation, we proposed an APF-based framework to enhance DE algorithms, introducing a new design paradigm for tackling optimization problems. DE variants developed under this framework showcased their effectiveness by achieving second prize in the single-objective track of the 2023 Chinese Intelligent Optimization Competition and third place in the single-objective optimization track of the internationally renowned CEC2023 competition.

The primary contributions of this paper are as follows:

(1) This study identifies a similarity between the path-searching mechanism of the APF method and the optimization process of evolutionary algorithms, highlighting a novel conceptual link.

(2) For the first time, the APF method is applied to enhance evolutionary algorithms by developing a hybrid strategy that integrates the gradient-guided characteristics of APF with the exploration and exploitation mechanisms of evolutionary algorithms.

(3) A general APF-based framework is proposed for enhancing evolutionary algorithms, and its adaptability and scalability across various algorithm variants are validated through comprehensive experimental evaluations.

(4) The APF-based framework is applied to four advanced Differential Evolution (DE) variants, demonstrating its effectiveness in significantly improving algorithm performance across multiple benchmark problems.
