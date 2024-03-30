# Chess_Game_Data_Analysis
The main idea for doing this project is to capture the sequences of moves that leads to a successful check-mate.

The Devlopment of this project has many stages, which I would like to summarize as following : 
1. The idea for this project is inspired from another project management project that I did couple of years ago as part
   of project management symposium organzied by the Collins Aerospace.
2. We had developed a NLP model which could accept the project status and classify the overall project status into three categories : Red(At Risk) , Amber(On the verge) and Green(Okay).
3. Although , having a dataset of project statuses is not readily available, for simplicity purposes we can assume the chess moves sequences as project statuses. Each sequence of moves or statuses
   will lead to a check mate or not ( in project management terms Red or Green)
5. Exploratory Analysis was performed to understand different moves leading to a successful check-mates (either by white or black).
6. RL agent is developed (inspired from the RL package created to replicate the BCG success sequence in the BCG's Growth Share Matrix) and was trained on the dataset of sequence of moves.
7. I will publish a short paper describing this methodology (hopefully and shortly)

![](https://github.com/ShoyebKhan09/Chess_Game_Data_Analysis/blob/main/chess_game_RL_01.gif)
