Object Oriented programming - Rust   

public Member   
    new() -  new Game setup    
    play_game() - initialise Game in main file    

private methods    
    play_turn()    
        * get_player_move()   
            Parameter - None    
            return - interger (u32)   
            validate(string)    
                Parameter - str     
                return - Result<u32, String>    
                is_valid_move() - just a requirement validating what player marked.    
                    Param - u32    
                    return - bool   
        * get_bot_move()    
            Parameter - None   
            return - integer (u32)   
    bool: game_is_won() - check if game is won   
        * parameter - None    
        * return - bool   
    reset() - reset game    
        * parameter - None    
        * return - None    
    get_next_turn() -> next player to play   
        * parameter - None   
        * return - Turn   

Made with help from :-    
  
https://www.ibm.com/developerworks/library/os-using-rust/index.html   
