## Raveeha Choudhery 251731363
## Task1
fun main() {
    var time: String = ""
    val weekday = "Thursday";
    if (weekday == "Monday") {
        println("On $weekday the opening hours are 9AM to 12pm (9:00 - 12:00)")
    }
    else if (weekday == "Tuesday"){
        println("On $weekday the opening hours are 8AM to 6PM (8:00 - 18:00)")
    }
    else if (weekday == "Wednesday"){
        println("On $weekday the opening hours are 8AM to 6PM (8:00 - 18:00)")
    }
    else if (weekday == "Thursday"){
        println("On $weekday the opening hours are 8AM to 6PM (8:00 - 18:00)")
    }
    else if (weekday == "Friday"){
        println("On $weekday the opening hours are 8AM to 9PM (8:00 - 21:00)")
    }
    else if (weekday == "Saturday"){
        println("On $weekday the opening hours are 9AM to 4PM (9:00 - 16:00)")
    }
    else if (weekday == "Sunday"){
        println("On $weekday the opening hours are 8AM to 4PM (8:00 - 16:00)")
    }
    else{
        println("Invalid Input")
    }   
}
## Task2
fun main() {
    for(i in 0..5){
        for(j in 0..i){
            print("*")
        }
        println()
    }
}

## Task3
fun getPoints(basePoints: Int, boost: Int): Int{
    return basePoints * boost
}
fun main() {
    var score = 0;
    println(score)
    score += getPoints(10, 1)
    println(score)
    score += getPoints(20, 2)
     println(score)
    score+= getPoints(-10, 1)
    println(score)
    score += getPoints(5,3)
    println(score)
    score += getPoints(-15, 2)
}


