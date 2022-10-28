# pruebaark
Toy example in arkworks

Based on: https://github.com/Pratyush/algebra-intro

Found an error in : `let mut rng = ark_std::rand::thread_rng();`

Replaced with :

 `use rand::{thread_rng};`
 
 `//let mut rng = ark_std::rand::thread_rng();`
 
 `let mut rng = thread_rng();`
 
 
 
    

