1. Write a method that takes in a number and returns the number times two. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def get_double(number)
      return number * 2
    end

    pp get_double(8)
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function getDouble(number) {
      return number * 2;
    }

    console.log(getDouble(8));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def get_double(number):
        return number * 2

    print(get_double(8))
    ```
    </details>

2. Write a method that takes in a string and returns the string with all capital letters. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def make_upcase(string)
      return string.upcase
    end

    pp make_upcase("hello")
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function makeUpcase(string) {
      return string.toUpperCase();
    }

    console.log(makeUpcase("hello"));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def make_upcase(string):
        return string.upcase

    print(make_upcase("hello"))
    ```
    </details>

3. Write a method that takes in two numbers and returns the first number subtracted by the second. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def get_difference(number1, number2)
      return number1 - number2
    end

    pp get_difference(4, 2)
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function getDifference(number1, number2) {
      return number1 - number2;
    }

    console.log(getDifference(4, 2));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def get_difference(number1, number2):
        return number1 - number2

    print(get_difference(4, 2))
    ```
    </details>

4. Write a method that takes in a number and returns the number times itself. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def square(number)
      return number * number
    end

    pp square(4)
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function square(number) {
      return number * number;
    }

    console.log(square(4));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def square(number):
        return number * number

    print(square(4))
    ```
    </details>

5. Write a method that takes in a string and returns the first letter of the string. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def get_first_letter(string)
      return string[0]
    end

    pp get_first_letter("something")
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function getFirstLetter(string) {
      return string[0];
    }

    console.log(getFirstLetter("something"));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def get_first_letter(string):
        return string[0]

    print(get_first_letter("something"))
    ```
    </details>

6. Write a method that takes in three strings and returns a string that combines all three strings with spaces in between. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def string_combiner(string1, string2, string3)
      return "#{string1} #{string2} #{string3}"
    end

    pp string_combiner("the", "cat", "jumped")
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function stringCombiner(string1, string2, string3) {
      return string1 + " " + string2 + " " + string3;
    }

    console.log(stringCombiner("the", "cat", "jumped"));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def string_combiner(string1, string2, string3):
        return f"{string1} {string2} {string3}"

    print(string_combiner("the", "cat", "jumped"))
    ```
    </details>

7. Write a method that takes in a number and returns the number as a string. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def convert_to_string(number)
      return number.to_s
    end

    pp convert_to_string(4)
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function convertToString(number) {
      return number.toString();
    }

    console.log(convertToString(4));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def convert_to_string(number):
        return str(number)

    print(convert_to_string(4))
    ```
    </details>

8. Write a method that takes in a string and returns the string repeated 5 times. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def repeat_string(string)
      return string * 5
    end

    pp repeat_string("bob")
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function repeatString(string) {
      return string + string + string + string + string;
    }

    console.log(repeatString("bob"));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def repeat_string(string):
        return string * 5

    print(repeat_string("bob"))
    ```
    </details>

9. Write a method that takes in 3 numbers and returns the average (the sum divided by 3.0). Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def average(number1, number2, number3)
      return (number1 + number2 + number3) / 3.0
    end

    pp average(95, 100, 70)
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function average(number1, number2, number3) {
      return (number1 + number2 + number3) / 3;
    }

    console.log(average(95, 100, 70));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def average(number1, number2, number3):
      return (number1 + number2 + number3) / 3.0

    print(average(95, 100, 70))
    ```
    </details>

10. Write a method that takes in a number and returns the number times 10 plus 30. Then run the method and print the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    def convert_number(number)
      return number * 10 + 30
    end

    pp convert_number(2)
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    function convertNumber(number) {
      return number * 10 + 30;
    }

    console.log(convertNumber(2));
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    def convert_number(number):
        return number * 10 + 30

    print(convert_number(2))
    ```
    </details>
