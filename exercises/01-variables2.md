1. Write a program that uses variables to store a first and last name, then prints the full name in one line using string concatenation (the + operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    first_name = "Grace"
    last_name = "Hopper"
    p first_name + " " + last_name
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var firstName = "Grace";
    var lastName = "Hopper";
    console.log(firstName + " " + lastName);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    first_name = "Grace"
    last_name = "Hopper"
    print(first_name + " " + last_name)
    ```
    </details>

2. Write a program that uses variables to store a first and last name, then prints the full name in one line using string interpolation (the #{} operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    first_name = "Beyonce"
    last_name = "Knowles"
    p "#{first_name} #{last_name}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var firstName = "Beyonce";
    var lastName = "Knowles";
    console.log(`${firstName} ${lastName}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    first_name = "Beyonce"
    last_name = "Knowles"
    print(f"{first_name} {last_name}")
    ```
    </details>

3. Write a program that asks the user to input a word. If the word is "marco", print "polo".
    <details><summary>Ruby solution</summary>

    ```ruby
    puts "Enter a word: "
    word = gets.chomp
    if word == "marco"
      puts "polo"
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var word = window.prompt("Enter a word:");
    if (word === "marco") {
      console.log("polo");
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    word = input("Enter a word: ")
    if word == "marco":
        print("polo")
    ```
    </details>

4. Write a program that uses variables to store three different colors, then prints out a sentence using the colors with string concatenation (the + operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    color1 = "red"
    color2 = "green"
    color3 = "blue"
    puts "My favorite colors are " + color1 + ", " + color2 + ", and " + color3 + "."
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var color1 = "red";
    var color2 = "green";
    var color3 = "blue";
    console.log("My favorite colors are " + color1 + ", " + color2 + ", and " + color3 + ".");
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    color1 = "red"
    color2 = "green"
    color3 = "blue"
    print("My favorite colors are " + color1 + ", " + color2 + ", and " + color3 + ".")
    ```
    </details>

5. Write a program that uses variables to store three different colors, then prints out a sentence using the colors with string interpolation (the #{} operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    color1 = "red"
    color2 = "green"
    color3 = "blue"
    puts "My favorite colors are #{color1}, #{color2}, and #{color3}."
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var color1 = "red";
    var color2 = "green";
    var color3 = "blue";
    console.log(`My favorite colors are ${color1}, ${color2}, and ${color3}.`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    color1 = "red"
    color2 = "green"
    color3 = "blue"
    print(f"My favorite colors are {color1}, {color2}, and {color3}.")
    ```
    </details>

6. Write a program that asks the user to enter a name. If the name is not "Santa", print "You're not Santa."
    <details><summary>Ruby solution</summary>

    ```ruby
    puts "What is your name?"
    name = gets.chomp
    if name != "Santa"
      puts "You're not Santa."
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var name = window.prompt("What is your name?");
    if (name !== "Santa") {
      console.log("You're not Santa.");
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    name = input("What is your name?")
    if name != "Santa":
        print("You're not Santa.")
    ```
    </details>

7. Write a program that uses variables to store a book's title and author, then prints out a sentence using that information with string concatenation (the + operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    book_title = "Practical Object-Oriented Design in Ruby"
    book_author = "Sandi Metz"
    puts "The author of " + book_title + " is " + book_author + "."
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var bookTitle = "Practical Object-Oriented Design in Ruby";
    var bookAuthor = "Sandi Metz";
    console.log("The author of " + bookTitle + " is " + bookAuthor + ".");
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    book_title = "Practical Object-Oriented Design in Ruby"
    book_author = "Sandi Metz"
    print("The author of " + book_title + " is " + book_author + ".")
    ```
    </details>

8. Write a program that uses variables to store a book's title and author, then prints out a sentence using that information with string interpolation (the #{} operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    book_title = "Practical Object-Oriented Design in Ruby"
    book_author = "Sandi Metz"
    puts "The author of #{book_title} is #{book_author}."
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var bookTitle = "Practical Object-Oriented Design in Ruby";
    var bookAuthor = "Sandi Metz";
    console.log(`The author of ${bookTitle} is ${bookAuthor}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    book_title = "Practical Object-Oriented Design in Ruby"
    book_author = "Sandi Metz"
    print(f"The author of {book_title} is {book_author}.")
    ```
    </details>

9. Write a program that asks the user to enter a password. If the password is "Joshua", the program responds "Shall we play a game?". For any other password, the program responds "Access denied"
    <details><summary>Ruby solution</summary>

    ```ruby
    puts "Enter the password: "
    password = gets.chomp
    if password == "Joshua"
      puts "Shall we play a game?"
    else
      puts "Access denied"
    end
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var password = window.prompt("Enter the password: ");
    if (password === "Joshua") {
      console.log("Shall we play a game?");
    } else {
      console.log("Access denied");
    }
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    password = input("Enter the password: ")
    if password == "Joshua":
        print("Shall we play a game?")
    else:
        print("Access denied")
    ```
    </details>

10. Write a program that uses variables to store the names of three cities, then prints out a sentence using that information with string concatenation (the + operator).
    <details><summary>Ruby solution</summary>

    ```ruby
    city1 = "Chicago"
    city2 = "New York"
    city3 = "San Francisco"
    puts city1 + ", " + city2 + ", and " + city3 + " are three major cities in the United States."
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var city1 = "Chicago";
    var city2 = "New York";
    var city3 = "San Francisco";
    console.log(city1 + ", " + city2 + ", and " + city3 + " are three major cities in the United States.");
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    city1 = "Chicago"
    city2 = "New York"
    city3 = "San Francisco"
    print(city1 + ", " + city2 + ", and " + city3 + " are three major cities in the United States.")
    ```
    </details>
