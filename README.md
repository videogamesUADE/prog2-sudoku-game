# prog2-sudoku-game

Reference game: http://www.247sudoku.com/

Create a new project called "sudoku-game"

Create the clases: 

Player
- name:string
+ Player( vName:string )
+ string:Name

Token
- key : int
- value : int
- state : bool
- position : int[,]
+ Token( vKey:int, vValue:int, vState:bool, vPosX:int, v:PosY:int)
+ int:Key
+ int:Value
+ bool:State
+ int[,]:Position

Board
- currentBoard : Token[,]
- listTokens : List<int>
- name : string
+ Board( vName:string )
+ void LoadBoard( sizeBoard:int )
+ void BuildBoard( sizeBoard:int )
+ int[,] CurrentBoard
+ List<Token> ListTokens
+ string Name
