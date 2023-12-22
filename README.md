# Submition

Note: my dataset, league_rank_predictions.csv is sorted by 'club_id'

# 1. Data analysis - preprocessing
- Data analysis:
  
This is all about understanding features, what they represent. These are worthy of attention:
**league_id**: this is not just random generated id, but actually very important feature, it turns out that the bigger this league_id is the better that league_is - clubs in this league are better, we can see that by many corelations like:

<img src="Screeens/global.PNG" alt="Alt Text" width="312" height="256"> <img src="Screeens/payment.PNG" alt="Alt Text" width="312" height="256">

**club_id** again not just random generated number, but actually this id is generated in order, the bigger this id is that club created later

<img src="Screeens/club.PNG" alt="Alt Text" width="256" height="376">

- Preprocessing

I made two different preprocessing functions, one using both categorical features, one without them



## Essentials
- implementing **alpha-beta-pruning** algorithm on game tree, for the purpose of finding best move for ai player on every move
- implementing search on game tree in the purpose of funding **valid moves** for every move in the game

## Main Game features
1. Two player game - classic
2. Ai vs player

<img src="Screens_6_11_23/Start.PNG" alt="Alt Text" width="256" height="256"> <img src="Screens_6_11_23/Game.PNG" alt="Alt Text" width="256" height="256">

## Main APP features
1. Undoing a move on rigth click, reseting game
2. Menu - player can choose between normal game or player vs ai, and color agains ai
3. Showing controling squares in game

<img src="Screens_6_11_23/ControlSquares.PNG" alt="Alt Text" width="256" height="256"><img src="Screens_6_11_23/Menu.PNG" alt="Alt Text" width="256" height="256"> 


## Other features
1. Meni icons - when player clicks outside of game board, menu icons show up
2. Check mate animation
3. Changing board stile and menu background picture

 <img src="Screens_6_11_23/Mate.PNG" alt="Alt Text" width="256" height="256"><img src="Screens_6_11_23/matew.PNG" alt="Alt Text" width="256" height="256"> 

## **Thank you for exploring my project!** 
If you'd like to learn more about my background and qualifications, please visit my [LinkedIn profile](https://www.linkedin.com/in/your-profile)
