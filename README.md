# Lecture notes for Artificial Intelligence (人工智能讲义)

Python 3.5 and Visual Studio 2010

### 主要内容
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter1-CN.html">Chapter Python程序设计基础</a>, <a href="Chapter1-CN.pdf">(Download PDF, 197 Pages)</a>
   - Python的基本元素，<a href="Lesson1-CN.pdf">(Download PPT, 10 Pages)</a>；
   - Python的数值数据；
   - 图形，<a href="Lesson2-CN.pdf">(Download PPT, 17 Pages)</a>，<a href="SourceCode3.zip">Download Source Code</a>；
   - 字符串、列表与文件，<a href="SourceCode2.zip">Download Source Code</a>；
   - 函数与对象；
   - 选择结构与循环结构；
   - 类，Download Source Code：<a href="Maze1.zip">Maze</a>，<a href="Puzzle8-1.zip">Puzzle8</a>，<a href="TicTacToe1.zip">TicTacToe</a>；
   - 其它结构化数据类型；
   - 函数式编程初步；

- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter2-CN.html">Chapter Python算法基础</a>, <a href="Chapter2-CN.pdf">(Download PDF, 181 Pages)</a>
   - 基本的ADT及其实现；
   - 递归；
   - 排序；
   - 算法设计策略；
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter3-CN.html">Chapter 基本的搜索技术</a>, <a href="Chapter3-CN.pdf">(Download PDF, 33 Pages)</a>, <a href="Search1-CN.pdf">(Download PPT, 34 Pages)</a>
   - 宽度优先搜索(Breadth-First Search, BFS)，<a href="maze_bfs.png">Result</a>；
   - 深度优先搜索(Depth-First Search, DFS)，<a href="maze_dfs.png">Result</a>；
   - Download Source Code：<a href="Maze_DBFS.zip">Maze(Python)</a>、<a href="DFSMaze.zip">Maze(Visual Studio 2010)</a>
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter4-CN.html">Chapter 启发式搜索技术</a>, <a href="Chapter4-CN.pdf">(Download PDF, 16 Pages)</a>, <a href="Search2-CN.pdf">(Download PPT, 39 Pages)</a>
   - 最佳优先搜索算法(Best-First Search, BFS)；
   - 贪心最佳优先搜索(Greedy Best-First Search, GBFS)；
   - A* 搜索(A* Search)，Download Source Code：<a href="Puzzle8-AStar.zip">Puzzle8(Python)</a>、<a href="AStarMaze.zip">Maze(Visual Studio 2010)</a>，<a href="Puzzle8AStarResult.mp4">Result(Video)</a>；
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter5-CN.html">Chapter 博弈树搜索技术</a>，<a href="Chapter5-CN.pdf">(Download PDF, 21 Pages)</a>, <a href="Search3-CN.pdf">(Download PPT, 56 Pages)</a>
   - Minimax算法；
   - alpha-beta算法；
   - Monte Carlo树搜索(Monte Carlo Tree Search, MCTS)；
   - Download Source Code：<a href="TicTacToe-GameTree.zip">TicTacToe(Minimax, alpha-beta, MCTS for Python)</a>、<a href="TTTAlphaBeta.zip">TicTacToe(Minimax, alpha-beta for Visual Studio 2010)</a>、<a href="TTTMonteCarlo.zip">TicTacToe(MCTS for Visual Studio 2010)</a>，<a href="Minimax-AlphaBetaResult.mp4">Results for Minimax and alpha-beta(Video)</a>，<a href="MCTSResult.mp4">Result for MCTS(Video)</a>
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter-CSP.html">Chapter 约束满足问题</a>，<a href="Chapter-CSP.pdf">(Download PDF, 27 Pages)</a>
   - CSP形式化；
   - 求解CSP的通用方法；
   - Download Source Code：<a href="QueensCode.zip">Queens(Python)</a>，<a href="SudokuCode.zip">Sudoku(Python)</a>，<a href="QueensDemo.mp4">Queens Result(Video)</a>，<a href="SudokuDemo.mp4">Sudoku Result(Video)</a>
   - Student's Source Code：<a href="Queens-FC3.zip">Forward Checking Algorithm(FC-3) for Queens(Python), by 郑逢宝(计算机11801, 1804240131)</a>
   - Student's Source Code：<a href="Queens-MAC3.zip">Maintaining Arc Consistency Algorithm(MAC-3) for Queens(Python), by 周迪(2020级电子信息研究生，研2014班, 2015363060)</a>

- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter7-CN.html">Chapter 遗传算法基础</a>，<a href="Chapter7-CN.pdf">(Download PDF, 16 Pages)</a>, <a href="Genetic-Algorithm-CN.pdf">(Download PPT, 37 Pages)</a>
   - 基本算法；
   - 理论基础，<a href="SourceCodeGA.zip">Download Source Code</a>；
   - Download Source Code：<a href="TicTacToeGA.zip">TicTacToe(Python)</a>，<a href="TTTGAResult.mp4">Result(Video)</a>
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter-Logic.html">Chapter 命题逻辑与一阶逻辑基础</a>，<a href="Chapter-Logic.pdf">(Download PDF, 53 Pages)</a>
   - 命题逻辑；
      - 基本的逻辑运算符；
      - 摩根定律；
      - 恒真、恒假、逻辑等价及命题的相容性；
      - 基本的逻辑等价式；
      - 论证、有效论证与谬误推理；
      - 命题逻辑与 SAT 问题；
      - 归结证明；
   - 一阶逻辑；
      - 命题逻辑的局限性；
      - 语法与语义；
   - Download Source Code：<a href="LogicQueensSrc.zip">Queens(Python)</a>，<a href="LogicQueensDemo.mp4">Queens Result(Video)</a>
   - Student's Source Code：<a href="Queens-DPLL.zip">DPLL SAT Solver for Queens(Python), by 郑逢宝(计算机11801, 1804240131)</a>
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter-Planning.html">Chapter 规划基础</a>，<a href="Chapter-Planning.pdf">(Download PDF, 30 Pages)</a>
   - 规划的标准化语言；
      - STRIPS；
      - ADL；
      - PDDL；
   - 规划算法；
      - 算法分类；
      - 基于状态空间搜索的规划；
   - Download Source Code：<a href="GripperPlanning.zip">Gripper(Python)</a>，<a href="Puzzle8Planning.zip">Puzzle8(Python)</a>

- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter6-CN.html">Chapter 强化学习基础</a>，<a href="Chapter6-CN.pdf">(Download PDF, 37 Pages)</a>, <a href="RL-CN.pdf">(Download PPT, 68 Pages)</a>
   - 环境-智能体交互模型(EA Model)；
   - 任务环境；
   - Markov性质(Markov Property)；
   - Markov决策过程(Markov Decision Process, MDP)；
   - MDP的基本方法；
   - Semi-Markov决策过程；
   - Download Source Code：<a href="TicTacToeRL.zip">TicTacToe(Python)</a>、<a href="TTTRL.zip">TicTacToe(Visual Studio 2010)</a>，<a href="TTTRLResult.mp4">Result(Video)</a>
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/Chapter8-CN.html">Chapter 人工神经网络基础</a>，<a href="Chapter8-CN.pdf">(Download PDF, 32 Pages)</a>, <a href="Neural-Networks-CN.pdf">(Download PPT, 97 Pages)</a>
   - 前馈神经网络；
      - 神经元；
      - 基于梯度下降的反传算法；
      - 神经元饱和问题；
      - 过拟合问题；
   
- <a href="https://duxiaoqin.github.io/Lecture-notes-for-Artificial-Intelligence/GAMEAI-CN.html">游戏与人工智能</a>, <a href="GAMEAI-CN.pdf">(Download PPT, 94 Pages)</a>
   - 游戏；
   - 人工智能；
   - 游戏与人工智能；
      - Game for AI;
      - AI for Game;

- 贡献者列表：
   - Chapter 约束满足问题，Student's Source Code：<a href="Queens-FC3.zip">Forward Checking Algorithm(FC-3) for Queens(Python), by 郑逢宝(计算机11801, 1804240131)</a>
   - Chapter 约束满足问题，Student's Source Code：<a href="Queens-MAC3.zip">Maintaining Arc Consistency Algorithm(MAC-3) for Queens(Python), by 周迪(2020级电子信息研究生，研2014班, 2015363060)</a>   
   - Chapter 命题逻辑与一阶逻辑基础，Student's Source Code：<a href="Queens-DPLL.zip">DPLL SAT Solver for Queens(Python), by 郑逢宝(计算机11801, 1804240131)</a>
