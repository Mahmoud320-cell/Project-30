# Project-30
Functions inside of other Functions

fun main (){

    sayHiAndBye()
 }

fun sayHiAndBye(){

    println("Hi")
    
    fun sayBye(){
    
        println("Bye")
        
        fun name(){
        
            println("Mahmoud")
            }
            
            name()
        }
        
        sayBye()
    }
