# Welcome to My Repository

## Skills
- Java
- Python
- Github

## Achievements
- Have made several homepages from scratch 
- Certifications in Python and Java
  
## Contact
📱+372 5519583

📩 lilian1valge@gmail.com

📜 [LinkedIn](https://www.linkedin.com/in/lilian-valge-203a35164/)

## Some Examples of the Codes I've Been Working on
### AND OR
```java
public class Main {
  public static void main(String[] args) {
    
  String studentName = "Anna";
  int yearOfSchool = 12;
  double studentAge = 18.5;
  double grade = 6.8;
  boolean olympicsWinner = true;
  
    
  // conditions for accepting to the university
  // student age must be 18 or older 
  // AND grade must be more than or equal to 8 
  // OR must have won olympics
    

    boolean isAgeEligible = studentAge >= 18; // get T or F values already here
    boolean isGradeEligible = grade >= 8;
    boolean isOlympicsWinner = olympicsWinner;

    if (isAgeEligible && (isGradeEligible  || isOlympicsWinner)){ // T && (F || T)
      System.out.println("Congratulations! You are accepted to the university");
     } else {
      System.out.println("Try again next year!");
    }
```
### IF, ELSE, ELSE IF

```java
public class Main {
  public static void main(String[] args) {    
  
    // winter, spring, summer, autumn
    // warm jacket, t-shirt, swimming suite, rain coat
    String season = "autumn";

    if (season == "winter") {
      System.out.println("Wear a warm jacket!");
    }
    else if (season == "spring") {
      System.out.println("Wear a T-shirt!");
    }
    else if (season == "summer") {
      System.out.println("Wear a swimming suite!");
    }
    else if (season == "autumn") {
      System.out.println("Wear a rain coat!");
    }
    else {
      System.out.println("I do not recongnize this season!");
    }
```
### NOT
```java

public class Main {
  public static void main(String[] args) {

    boolean waitressRude = false; // Assuming waitress is not rude

    // NOT
    // conditions for going to the restaurant
    // waitress must not be rude

    boolean isWaitressRude = waitressRude;

    if (!isWaitressRude) { // Checking if the waitress is not rude
      System.out.println("Yes, I am coming to the restaurant");
    } else {
      System.out.println("No, I will skip this time");
    }
```
