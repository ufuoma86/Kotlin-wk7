# Kotlin-wk7
Reverse array function
import java.util.Arrays

fun main(args: Array) {
    val numberArray: IntArray = intArrayOf(1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
    var reversedArray = numberArray.reversedArray()

    println(Arrays.toString(reversedArray))
}
