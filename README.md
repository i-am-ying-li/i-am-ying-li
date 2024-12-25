## Hi there 👋

Ying Li identifies acronyms in a succinct description of an algorithm for solving 2-SAT 2-CNF[^1]:

https://github.com/user-attachments/assets/57c2c8ff-7982-420e-b170-0d8b01b2e248

Ying Li's favorite things:

https://github.com/user-attachments/assets/2f762559-39cd-4a1a-82cd-d25cf6dd99c7

[^1]: The image Ying Li analyzes in the video is an original presentation of the algorithm using acronyms 2SAT, 2CNF, SCC (as were used in e.g. graduate course slides we encountered as well, but we own the rights to the algorithm description in this video, so use that here instead). To compare and check, we also provide below the original algorithm description (reused with explicit permission from Elsevier for posting on a public website):
"Two-satisfiability algorithm: Process the strong components S of G(F) [the implication graph for the logical formula] in reverse topological order as
follows: General Step. If S is marked, do nothing. Otherwise if S = S[-complement] then stop: C is unsatisfiable. Otherwise
mark S true and S[-complement] false.  This algorithm stops prematurely only if some
vertex is in the same strong component as its complement. By using the duality property and induction, it is easy to prove every component marked true has only true components as successors and every component marked false has only false components as predecessors. Thus, if the algorithm does not stop prematurely, it marks the components so that complementary components have complementary values and no path leads from a true component to a false component. If we assign to each vertex the truth value of the component containing it, we get a truth
assignment satisfying 2(i) and 2(ii)." Reprinted from Information Processing Letters, Volume 8, Issue 3, Bengt Aspvall, Michael F. Plass, Robert Endre Tarjan, "A linear-time algorithm for testing the truth of certain quantified boolean formulas", Page 122 bottom of left column and upper half of right column, Copyright 1978-1979, with permission from
Elsevier (purchased license for posting on a website) ( https://www.sciencedirect.com/science/article/abs/pii/0020019079900024 ).
