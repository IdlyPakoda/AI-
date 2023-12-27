# AI-

UNIT 1

1.  What is considered 'intelligence' in artificial intelligence? 
   - Intelligence in AI is the ability to learn, understand, and apply knowledge to adapt to new situations and solve problems.

2.  Name some foundational disciplines of AI. 
   - Foundational disciplines include computer science, cognitive science, psychology, mathematics, linguistics, and philosophy.

3.  What was a significant milestone in the history of AI? 
   - A significant milestone was when the term "Artificial Intelligence" was coined at the Dartmouth Conference in 1956.

4.  How is an AI agent structured? 
   - An AI agent is structured to include components for perception, reasoning, and acting within its environment.

5.  What does formulating a problem in AI involve? 
   - It involves defining the initial state, goal state, and the actions that lead from one to the other.

6.  What types of problems can AI solve? 
   - AI can solve deterministic, stochastic, discrete, continuous, and adversarial problems, among others.

7.  What are states in AI? 
   - States are the various configurations or conditions that can exist in the environment of an AI problem.

8.  What are operators in AI? 
   - Operators are actions that transition the problem from one state to another.

9.  What is a state space? 
   - State space is the set of all possible states of the problem domain.

10.  What are search strategies in AI? 
    - These are algorithms that dictate the order in which nodes in a state space are expanded to find a solution path.

11.  What is an informed search strategy? 
    - It's a search that uses problem-specific knowledge to find solutions more efficiently than an uninformed search.

12.  How does Best First Search work? 
    - It selects the most promising node to expand next based on a given heuristic.

13.  What distinguishes the A* algorithm? 
    - A* uses heuristics to estimate the cost to reach the goal from the current node and chooses the path that appears to be the best.

14.  What are heuristic functions? 
    - These are functions that estimate the cost from the current state to the goal state.

15.  What is Iterative Deepening A* (IDA*)? 
    - IDA* is an algorithm that combines depth-first search's space-efficiency with A*'s optimality and completeness.

16.  Define a perfect decision game in AI. 
    - It's a game with complete information where the result of every possible move is known.

17.  What is an imperfect decision game? 
    - It's a game where some information is hidden, leading to elements of uncertainty.

18.  How are evaluation functions used in AI game playing? 
    - They are used to assign a numerical value to game positions to assess their desirability for winning.

19.  What is the purpose of alpha-beta pruning? 
    - To reduce the number of nodes evaluated in the minimax algorithm for game playing.

20.  Why do we need to formulate problems in AI? 
    - To clearly define the objectives and constraints of the problem for an AI to solve it effectively.

21.  Can you give an example of a heuristic in A*? 
    - The straight-line distance between the current state and the goal state in a geographical pathfinding problem.

22.  Why is the A* algorithm considered optimal? 
    - Because it always finds the least-cost path to the goal if the heuristic function is admissible.

23.  What does it mean for a heuristic to be admissible? 
    - It never overestimates the cost to reach the goal.

24.  Why is Iterative Deepening A* useful? 
    - Because it finds the best depth limit without using excessive memory.

25.  What is the difference between depth-first and breadth-first search? 
    - Depth-first explores as far as possible along a branch before backtracking, while breadth-first explores all neighbors of a node before going to the next level.

26.  How does the minimax algorithm work? 
    - It simulates all possible moves in a game to find the move that maximizes a player’s minimum gain.

27.  What is an adversarial search problem? 
    - It's a problem where an agent competes against an opponent, such as in a game.

28.  What is the significance of the branching factor in search algorithms? 
    - It's the average number of successors per state; a lower branching factor improves the efficiency of the search.

29.  What is a search tree? 
    - It's a tree representation of the state space created by the search process.

30.  What does 'expanding a node' mean in search algorithms? 


    - It means generating successors of that node and adding them to the search tree.

31.  What is a search path? 
    - It's a sequence of states from the initial state to the goal state.

32.  What is a node in the context of AI search? 
    - A node corresponds to a state in the state space of the problem.

33.  Why is game theory important in AI? 
    - It provides the mathematical framework for analyzing strategies in adversarial environments.

34.  What is a zero-sum game in AI? 
    - It's a game where one player's gain is exactly balanced by the losses of the other player(s).

35.  How does backtracking work in search algorithms? 
    - It involves undoing the last step in the search process when a dead end is reached and trying a different path.


UNIT 2

1.   What is a knowledge-based agent?  
   - A knowledge-based agent is an AI system that applies reasoning to a body of knowledge to make informed decisions.

2.   What is propositional logic?  
   - Propositional logic is a branch of logic that deals with propositions that can be true or false.

3.   What is inference in AI?  
   - Inference in AI is the process of deriving new propositions from known propositions using logical rules.

4.   What is predicate logic?  
   - Predicate logic, or first-order logic, extends propositional logic by including quantifiers and variables, allowing for more complex expressions about some domain.

5.   What is resolution in AI?  
   - Resolution is a rule of inference leading to a new clause implied by two clauses containing complementary literals.

6.   What are frames in AI?  
   - Frames are data structures for representing a stereotype situation, like a room or building, with default assumptions.

7.   What are semantic nets in AI?  
   - Semantic nets are graphical notations for representing knowledge in patterns of interconnected nodes and arcs.

8.   How does a simple planning agent work?  
   - A simple planning agent generates actions that reduce the difference between the current state and the goal state.

9.   How is problem-solving different from planning in AI?  
   - Problem-solving typically involves finding a sequence of actions to achieve a goal, while planning involves organizing actions by taking into account the desired future outcome and constraints.

10.   What are the basic representations of plans in AI?  
    - Plans can be represented as a sequence of actions, a tree of actions, or a graph of actions.

11.   What is partial-order planning?  
    - Partial-order planning is a type of planning that does not fix the order of actions unless required, allowing for more flexibility.

12.   What is hierarchical planning?  
    - Hierarchical planning involves creating plans by decomposing tasks into sub-tasks, creating a hierarchy of actions.

13.   Why is first-order logic preferred over propositional logic in AI?  
    - Because first-order logic can represent more complex statements with quantifiers and variables, which are needed for detailed knowledge representation.

14.   What is a unification algorithm in AI?  
    - Unification is a process that determines the substitutions needed to make different logical expressions identical.

15.   How do frames facilitate knowledge representation?  
    - Frames allow AI to store knowledge in structured forms that resemble real-world objects and concepts, making it easier to handle complex information.

16.   Can you give an example of a semantic net?  
    - A semantic net could represent family relationships, with nodes representing people and arcs representing relationships like "parent of" or "married to".

17.   What role does the closed-world assumption play in knowledge representation?  
    - The closed-world assumption posits that what is not known to be true is assumed to be false.

18.   What is the purpose of an inference engine in a knowledge-based system?  
    - An inference engine applies logical rules to the knowledge base to infer new knowledge or make decisions.

19.   What is backward chaining in AI?  
    - Backward chaining is an inference method that works from the goal backward to the initial data.

20.   What is forward chaining in AI?  
    - Forward chaining is an inference method that starts from the known data and applies inference rules to extract more data until a goal is reached.

21.   How does truth maintenance work in AI systems?  
    - Truth maintenance systems keep track of the dependencies in known facts and ensure consistency when facts are added or retracted.

22.   What is a planning graph?  
    - A planning graph is a data structure that represents a planning problem and is used to identify a solution efficiently.

23.   What are the limitations of propositional logic in representing knowledge?  
    - Propositional logic cannot represent relationships between objects or the properties of objects, which are essential in many AI applications.

24.   What is meant by the term 'ontology' in AI?  
    - Ontology in AI refers to the explicit specification of a conceptualization, often used to share common understanding of the structure of information.

25.   How do planners deal with uncertainty in the environment?  
    - Planners can use probabilistic reasoning and decision-theoretic approaches to handle uncertainty.

26.   What is a frame problem in AI?  
    - The frame problem is the challenge of specifying what does not change in response to an action, as opposed to what does change.

27.   What is a plan library in hierarchical planning?  
    - A plan library is a repository of predefined plan structures and strategies that can be reused for solving different but similar problems.

28.   What is meant by non-monotonic reasoning in AI?  
    - Non-monot

onic reasoning is reasoning where the introduction of new information can invalidate previous conclusions.

29.   How does a planner use heuristics?  
    - Planners use heuristics to guide the search for plans by estimating the cost or likelihood of reaching the goal from a given state.

30.   What is a deductive database?  
    - A deductive database combines a relational database with a rule-based inference engine to derive new information.

31.   What is an action schema in planning?  
    - An action schema is a description of an action in terms of its preconditions and effects.

32.   How do AI systems use default reasoning?  
    - Default reasoning allows AI systems to make assumptions in the absence of complete information.

33.   What is a consistency algorithm?  
    - A consistency algorithm checks whether a set of knowledge, rules, or statements can all be true at the same time.

34.   What is qualitative reasoning in AI?  
    - Qualitative reasoning is the ability to reason with qualitative descriptions rather than precise quantitative measures.

35.   What is a reactive planner?  
    - A reactive planner responds to changes in the environment in real-time and adjusts the plan accordingly, rather than following a pre-set sequence of actions.

UNIT 3

1.    What is an Expert System?   
   - An Expert System is a computer program that mimics the decision-making ability of a human expert. It uses knowledge and inference procedures to solve problems that are difficult enough to require significant human expertise for their solutions.

2.    What are the applications of Expert Systems?   
   - Applications include medical diagnosis, financial analysis, fraud detection, manufacturing process control, flight scheduling, and customer service, among others.

3.    What are the phases in building Expert Systems?   
   - The phases typically include problem selection, knowledge acquisition, knowledge representation, system building, testing, and maintenance.

4.    Describe the architecture of an Expert System.   
   - The architecture usually comprises a knowledge base, an inference engine, a user interface, and sometimes an explanation and knowledge acquisition module.

5.    What is the role of the knowledge base in an Expert System?   
   - The knowledge base stores domain-specific and case-specific facts, rules, and heuristics that are used to make inferences.

6.    How does the inference engine function in an Expert System?   
   - The inference engine applies logical rules to the knowledge base to deduce new information and solve problems.

7.    What is knowledge acquisition in the context of Expert Systems?   
   - Knowledge acquisition is the process of extracting, structuring, and organizing knowledge from domain experts or source materials to build the knowledge base.

8.    Can you explain the role of the user interface in Expert Systems?   
   - The user interface allows users to interact with the expert system, inputting data and receiving advice or recommendations.

9.    What is the importance of testing in Expert System development?   
   - Testing ensures that the system provides accurate, reliable, and consistent answers and behaves as expected.

10.    How are expert systems maintained?   
    - Maintenance involves updating the knowledge base, refining the inference mechanisms, and ensuring the system adapts to changes in its operational environment.

11.    What is the purpose of the explanation module in an Expert System?   
    - The explanation module helps users understand how the expert system arrived at a particular conclusion or advice, thereby increasing its transparency and trustworthiness.

12.    How do Expert Systems handle uncertain or incomplete information?   
    - They use techniques like fuzzy logic, Bayesian networks, and confidence factors to make reasoned judgments in the face of uncertainty.

13.    What distinguishes Expert Systems from conventional computer programs?   
    - Expert Systems are designed to solve complex problems by reasoning through bodies of knowledge, unlike conventional programs that follow predefined algorithms and procedures.

14.    What are the limitations of Expert Systems?   
    - Limitations include their inability to learn from experience, high cost of development, maintenance challenges, and difficulty in capturing tacit expert knowledge.

15.    How is a rule-based system implemented in an Expert System?   
    - In a rule-based system, knowledge is represented using if-then rules that guide the inference engine to make logical deductions.

16.    What is forward chaining in rule-based Expert Systems?   
    - Forward chaining starts with the available data and uses inference rules to extract more data until a conclusion is reached.

17.    What is backward chaining in rule-based Expert Systems?   
    - Backward chaining begins with a list of goals and works backwards to determine what data is required to achieve these goals.

18.    How do Expert Systems differ from Artificial Intelligence in general?   
    - While all expert systems are a form of AI, not all AI systems are expert systems. AI includes a broader range of technologies like machine learning, natural language processing, and robotics.

19.    Can Expert Systems adapt to new situations or changes in the environment?   
    - Traditional expert systems are not adaptive; they do not learn from new experiences unless their knowledge base is updated by human experts.

20.    What is a hybrid Expert System?   
    - A hybrid Expert System combines various AI techniques, like rule-based reasoning with machine learning, to enhance its problem-solving capability.


