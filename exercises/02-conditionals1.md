1. Use a variable to store a number, then write a condition that prints 0 if the number is equal to 10, and prints -1 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 10
    if number == 10
      puts 0
    else
      puts -1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 10;
    if (number === 10) {
      console.log(0);
    } else {
      console.log(-1);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 10
    if number == 10:
        print(0)
    else:
        print(-1)
    ```
    </details>

2. Use a variable to store a number, then write a condition that prints -1 if the number is less than 10, prints 1 if the number is greater than 10, and prints 0 if the number is equal to 10.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 3
    if number < 10
      puts -1
    elsif number > 10
      puts 1
    else
      puts 0
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 3;
    if (number < 10) {
      console.log(-1);
    } else if (number > 10) {
      console.log(1);
    } else {
      console.log(0);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 3
    if number < 10:
        print(-1)
    elif number > 10:
        print(1)
    else:
        print(0)
    ```
    </details>

3. Use variables to store two numbers, then write a condition that prints 1 if the numbers are both less than 10, and prints 0 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    number1 = 4
    number2 = 9
    if number1 < 10 && number2 < 10
      puts 1
    else
      puts 0
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number1 = 4;
    var number2 = 9;
    if (number1 < 10 && number2 < 10) {
      console.log(1);
    } else {
      console.log(0);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number1 = 4
    number2 = 9
    if number1 < 10 and number2 < 10:
        print(1)
    else:
        print(0)
    ```
    </details>

4. Use a variable to store a number, then write a condition that prints 1 if the number is over 9000, and prints -1 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    power_level = 9321
    if power_level > 9000
      puts 1
    else
      puts -1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var powerLevel = 9321;
    if (powerLevel > 9000) {
      console.log(1);
    } else {
      console.log(-1);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    power_level = 9321
    if power_level > 9000:
        print(1)
    else:
        print(-1)
    ```
    </details>

5. Use a variable to store a number, then write a condition that prints 9 if the number is less than 10, prints 19 if the number is less than 20, prints 29 if the number is less than 30, and prints -1 otherwise (only one print statement should occur).
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 24
    if number < 10
      puts 9
    elsif number < 20
      puts 19
    elsif number < 30
      puts 29
    else
      puts -1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 24;
    if (number < 10) {
      console.log(9);
    } else if (number < 20) {
      console.log(19);
    } else if (number < 30) {
      console.log(29);
    } else {
      console.log(-1);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 24
    if number < 10:
        print(9)
    elif number < 20:
        print(19)
    elif number < 30:
        print(29)
    else:
        print(-1)
    ```
    </details>

6. Use variables to store two numbers, then write a condition that prints 100 if either number is greater than 10, and prints -100 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    number1 = 20
    number2 = 4
    if number1 > 10 || number2 > 10
      puts 100
    else
      puts -100
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number1 = 20;
    var number2 = 4;
    if (number1 > 10 || number2 > 10) {
      console.log(100);
    } else {
      console.log(-100);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number1 = 20
    number2 = 4
    if number1 > 10 or number2 > 10:
        print(100)
    else:
        print(-100)
    ```
    </details>

7. Use a variable to store a number, then write a condition that prints 1776 if the number is less than 0, and prints 1979 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = -345
    if number < 0
      puts 1776
    else
      puts 1979
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = -345;
    if (number < 0) {
      console.log(1776);
    } else {
      console.log(1979);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = -345
    if number < 0:
        print(1776)
    else:
        print(1979)
    ```
    </details>

8. Use a variable to store a number, then write a condition that prints 100 if the number equals 100, prints 99 if the number is equal to 99, and prints 0 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 3
    if number == 100
      puts 100
    elsif number == 99
      puts 99
    else
      puts 0
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 3;
    if (number === 100) {
      console.log(100);
    } else if (number === 99) {
      console.log(99);
    } else {
      console.log(0);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 3
    if number == 100:
        print(100)
    elif number == 99:
        print(99)
    else:
        print(0)
    ```
    </details>

9. Use variables to store two numbers, then write a condition that prints 1 if the first number is less than zero and the second number is greater than 0, and prints 0 otherwise.
    <details><summary>Ruby solution</summary>

    ```ruby
    number1 = -4
    number2 = -9
    if number1 < 0 && number2 > 0
      puts 1
    else
      puts 0
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number1 = -4;
    var number2 = -9;
    if (number1 < 0 && number2 > 0) {
      console.log(1);
    } else {
      console.log(0);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number1 = -4
    number2 = -9
    if number1 < 0 and number2 > 0:
        print(1)
    else:
        print(0)
    ```
    </details>

10. Use a variable to store a number, then write a condition that prints 5 if the number is greater than 80, prints 4 if the number is greater than 60, prints 3 if the number is greater than 40, prints 2 if the number is greater than 20, and prints 1 otherwise (only one print statement should occur).
    <details><summary>Ruby solution</summary>

    ```ruby
    grade = 72
    if grade > 80
      puts 5
    elsif grade > 60
      puts 4
    elsif grade > 40
      puts 3
    elsif grade > 20
      puts 2
    else
      puts 1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var grade = 72;
    if (grade > 80) {
      console.log(5);
    } else if (grade > 60) {
      console.log(4);
    } else if (grade > 40) {
      console.log(3);
    } else if (grade > 20) {
      console.log(2);
    } else {
      console.log(1);
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    grade = 72
    if grade > 80:
        print(5)
    elif grade > 60:
        print(4)
    elif grade > 40:
        print(3)
    elif grade > 20:
        print(2)
    else:
        print(1)
    ```
    </details>