1. Write a while loop to print the numbers 1 through 10.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 1
    while number <= 10
      puts number
      number = number + 1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 1;
    while (number <= 10) {
      console.log(number);
      number = number + 1;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 1
    while number <= 10:
        print(number)
        number = number + 1
    ```
    </details>
2. Write a while loop that prints the word "hello" 5 times.
    <details><summary>Ruby solution</summary>

    ```ruby
    count = 0
    while count < 5
      puts "hello"
      count = count + 1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var count = 0;
    while (count < 5) {
      console.log("hello");
      count = count + 1;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    count = 0
    while count < 5:
        print("hello")
        count = count + 1
    ```
    </details>

3. Write a while loop that asks the user to enter a word and will run forever until the user enters the word "stop".
    <details><summary>Ruby solution</summary>

    ```ruby
    while true
      puts "Enter a word: "
      input = gets.chomp
      if input == "stop"
        break
      end
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    while (true) {
      var input = window.prompt("Enter a word: ");
      if (input === "stop") {
        break;
      }
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    while True:
        word = input("Enter a word: ")
        if word == "stop":
            break
    ```
    </details>

4. Write a while loop that prints the numbers 0 through 100, increasing by 5 each time.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 0
    while number <= 100
      puts number
      number = number + 5
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 0;
    while (number <= 100) {
      console.log(number);
      number = number + 5;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 0
    while number <= 100:
        print(number)
        number = number + 5
    ```
    </details>

5. Write a while loop that prints the number 9000 ten times.
    <details><summary>Ruby solution</summary>

    ```ruby
    count = 0
    while count < 10
      puts 9000
      count = count + 1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var count = 0;
    while (count < 10) {
      console.log(9000);
      count = count + 1;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    count = 0
    while count < 10:
        print(9000)
        count = count + 1
    ```
    </details>

6. Write a while loop that asks the user to enter a number and will run forever until the user enters a number greater than 10.
    <details><summary>Ruby solution</summary>

    ```ruby
    while true
      puts "Enter a number: "
      input = gets.chomp
      if input.to_i > 10
        break
      end
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    while (true) {
      var input = window.prompt("Enter a number: ");
      if (parseInt(input) > 10) {
        break;
      }
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    while True:
        number = input("Enter a number: ")
        if int(number) > 10:
            break
    ```
    </details>

7. Write a while loop that prints the numbers 50 to 70.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 50
    while number <= 70
      puts number
      number = number + 1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 50;
    while (number <= 70) {
      console.log(number);
      number = number + 1;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 50
    while number <= 70:
          print(number)
          number = number + 1
    ```
    </details>

8. Write a while loop that prints the phrase "Around the world" 144 times.
    <details><summary>Ruby solution</summary>

    ```ruby
    count = 0
    while count < 144
      puts "Around the world"
      count = count + 1
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var count = 0;
    while (count < 144) {
      console.log("Around the world");
      count = count + 1;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    count = 0
    while count < 144:
        print("Around the world")
        count = count + 1
    ```
    </details>

9. Write a while loop that asks the user to enter a word and will run forever until the user enters a word with more than 5 letters.
    <details><summary>Ruby solution</summary>

    ```ruby
    while true
      puts "Enter a word: "
      input = gets.chomp
      if input.length > 5
        break
      end
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    while (true) {
      var input = window.prompt("Enter a word: ");
      if (input.length > 5) {
        break;
      }
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    while True:
        word = input("Enter a word: ")
        if len(word) > 5:
            break
    ```
    </details>

10. Write a while loop that prints the even numbers from 2 to 40.
    <details><summary>Ruby solution</summary>

    ```ruby
    number = 2
    while number <= 40
      puts number
      number = number + 2
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var number = 2;
    while (number <= 40) {
      console.log(number);
      number = number + 2;
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    number = 2
    while number <= 40:
        print(number)
        number = number + 2
    ```
    </details>