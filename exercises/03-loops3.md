1. Start with an array of numbers and create a new array with only the numbers less than 20.
   <br>For example, [2, 32, 80, 18, 12, 3] becomes [2, 18, 12, 3].
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [2, 32, 80, 18, 12, 3]
    small_numbers = []
    index = 0
    while index < numbers.length
      number = numbers[index]
      if number < 20
        small_numbers << number
      end
      index = index + 1
    end
    p small_numbers

    # Alternative solution with the array .each method
    numbers = [2, 32, 80, 18, 12, 3]
    small_numbers = []
    numbers.each do |number|
      if number < 20
        small_numbers << number
      end
    end
    p small_numbers

    # Alternative solution with the array .select method
    numbers = [2, 32, 80, 18, 12, 3]
    small_numbers = numbers.select { |number| number < 20 }
    p small_numbers
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [2, 32, 80, 18, 12, 3];
    var smallNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      var number = numbers[index];
      if (number < 20) {
        smallNumbers.push(number);
      }
      index = index + 1;
    }
    console.log(smallNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [2, 32, 80, 18, 12, 3];
    var smallNumbers = [];
    numbers.forEach(function (number) {
      if (number < 20) {
        smallNumbers.push(number);
      }
    });
    console.log(smallNumbers);

    // Alternative solution with the array .filter method
    var numbers = [2, 32, 80, 18, 12, 3];
    var smallNumbers = numbers.filter(function (number) {
      return number < 20;
    });
    console.log(smallNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

2. Start with an array of strings and create a new array with only the strings that start with the letter "w".
   <br>For example, ["winner", "winner", "chicken", "dinner"] becomes ["winner", "winner"].
    <details><summary>Ruby solution</summary>

    ```ruby
    strings = ["winner", "winner", "chicken", "dinner"]
    w_strings = []
    index = 0
    while index < strings.length
      if strings[index][0] == "w"
        w_strings << strings[index]
      end
      index += 1
    end
    p w_strings

    # Alternative solution with the array .each method
    strings = ["winner", "winner", "chicken", "dinner"]
    w_strings = []
    strings.each do |string|
      if string[0] == "w"
        w_strings << string
      end
    end
    p w_strings

    # Alternative solution with the array .select method
    strings = ["winner", "winner", "chicken", "dinner"]
    w_strings = strings.select { |string| string[0] == "w" }
    p w_strings
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var strings = ["winner", "winner", "chicken", "dinner"];
    var wStrings = [];
    var index = 0;
    while (index < strings.length) {
      if (strings[index][0] === "w") {
        wStrings.push(strings[index]);
      }
      index += 1;
    }
    console.log(wStrings);

    // Alternative solution with the array .forEach method
    var strings = ["winner", "winner", "chicken", "dinner"];
    var wStrings = [];
    strings.forEach(function (string) {
      if (string[0] === "w") {
        wStrings.push(string);
      }
    });
    console.log(wStrings);

    // Alternative solution with the array .filter method
    var strings = ["winner", "winner", "chicken", "dinner"];
    var wStrings = strings.filter(function (string) {
      return string[0] === "w";
    });
    console.log(wStrings);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

3. Start with an array of hashes and create a new array with only the hashes with prices greater than 5 (from the :price key).
   <br>For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes [{name: "chair", price: 100}].
    <details><summary>Ruby solution</summary>

    ```ruby
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    expensive_items = []
    index = 0
    while index < items.length
      item = items[index]
      if item[:price] > 5
        expensive_items << item
      end
      index = index + 1
    end
    p expensive_items

    # Alternative solution with the array .each method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    expensive_items = []
    items.each do |item|
      if item[:price] > 5
        expensive_items << item
      end
    end
    p expensive_items

    # Alternative solution with the array .select method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    expensive_items = items.select { |item| item[:price] > 5 }
    p expensive_items
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var expensiveItems = [];
    var index = 0;
    while (index < items.length) {
      var item = items[index];
      if (item.price > 5) {
        expensiveItems.push(item);
      }
      index++;
    }
    console.log(expensiveItems);

    // Alternative solution with the array .forEach method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var expensiveItems = [];
    items.forEach(function (item) {
      if (item.price > 5) {
        expensiveItems.push(item);
      }
    });
    console.log(expensiveItems);

    // Alternative solution with the array .filter method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var expensiveItems = items.filter(function (item) {
      return item.price > 5;
    });
    console.log(expensiveItems);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

4. Start with an array of numbers and create a new array with only the even numbers.
   <br>For example, [2, 4, 5, 1, 8, 9, 7] becomes [2, 4, 8].
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [2, 4, 5, 1, 8, 9, 7]
    even_numbers = []
    index = 0
    while index < numbers.length
      if numbers[index] % 2 == 0
        even_numbers << numbers[index]
      end
      index = index + 1
    end
    p even_numbers

    # Alternative solution with the array .each method
    numbers = [2, 4, 5, 1, 8, 9, 7]
    even_numbers = []
    numbers.each do |number|
      if number % 2 == 0
        even_numbers << number
      end
    end
    p even_numbers

    # Alternative solution with the array .select method
    numbers = [2, 4, 5, 1, 8, 9, 7]
    even_numbers = numbers.select { |number| number % 2 == 0 }
    p even_numbers
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [2, 4, 5, 1, 8, 9, 7];
    var evenNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      if (numbers[index] % 2 === 0) {
        evenNumbers.push(numbers[index]);
      }
      index = index + 1;
    }
    console.log(evenNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [2, 4, 5, 1, 8, 9, 7];
    var evenNumbers = [];
    numbers.forEach(function (number) {
      if (number % 2 === 0) {
        evenNumbers.push(number);
      }
    });
    console.log(evenNumbers);

    // Alternative solution with the array .filter method
    var numbers = [2, 4, 5, 1, 8, 9, 7];
    var evenNumbers = numbers.filter(function (number) {
      return number % 2 === 0;
    });
    console.log(evenNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

5. Start with an array of strings and create a new array with only the strings shorter than 4 letters.
   <br>For example, ["a", "man", "a", "plan", "a", "canal", "panama"] becomes ["a", "man", "a", "a"].
    <details><summary>Ruby solution</summary>

    ```ruby
    words = ["a", "man", "a", "plan", "a", "canal", "panama"]
    short_words = []
    index = 0
    while index < words.length
      word = words[index]
      if word.length < 4
        short_words << word
      end
      index = index + 1
    end
    p short_words

    # Alternative solution with the array .each method
    words = ["a", "man", "a", "plan", "a", "canal", "panama"]
    short_words = []
    words.each do |word|
      if word.length < 4
        short_words << word
      end
    end
    p short_words

    # Alternative solution with the array .select method
    words = ["a", "man", "a", "plan", "a", "canal", "panama"]
    short_words = words.select { |word| word.length < 4 }
    p short_words
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var words = ["a", "man", "a", "plan", "a", "canal", "panama"];
    var shortWords = [];
    var index = 0;
    while (index < words.length) {
      var word = words[index];
      if (word.length < 4) {
        shortWords.push(word);
      }
      index = index + 1;
    }
    console.log(shortWords);

    // Alternative solution with the array .forEach method
    var words = ["a", "man", "a", "plan", "a", "canal", "panama"];
    var shortWords = [];
    words.forEach(function (word) {
      if (word.length < 4) {
        shortWords.push(word);
      }
    });
    console.log(shortWords);

    // Alternative solution with the array .filter method
    var words = ["a", "man", "a", "plan", "a", "canal", "panama"];
    var shortWords = words.filter(function (word) {
      return word.length < 4;
    });
    console.log(shortWords);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

6. Start with an array of hashes and create a new array with only the hashes with names shorter than 6 letters (from the :name key).
   <br>For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes [{name: "chair", price: 100}, {name: "book", price: 4}].
    <details><summary>Ruby solution</summary>

    ```ruby
    things = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    short_name_things = []
    index = 0
    while index < things.length
      if things[index][:name].length < 6
        short_name_things << things[index]
      end
      index = index + 1
    end
    p short_name_things

    # Alternative solution with the array .each method
    things = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    short_name_things = []
    things.each do |thing|
      if thing[:name].length < 6
        short_name_things << thing
      end
    end
    p short_name_things

    # Alternative solution with the array .select method
    things = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    short_name_things = things.select { |thing| thing[:name].length < 6 }
    p short_name_things
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var things = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var shortNameThings = [];
    var index = 0;
    while (index < things.length) {
      if (things[index].name.length < 6) {
        shortNameThings.push(things[index]);
      }
      index = index + 1;
    }
    console.log(shortNameThings);

    // Alternative solution with the array .forEach method
    var things = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var shortNameThings = [];
    things.forEach(function (thing) {
      if (thing.name.length < 6) {
        shortNameThings.push(thing);
      }
    });
    console.log(shortNameThings);

    // Alternative solution with the array .filter method
    var things = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var shortNameThings = things.filter(function (thing) {
      return thing.name.length < 6;
    });
    console.log(shortNameThings);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

7. Start with an array of numbers and create a new array with only the numbers less than 10.
   <br>For example, [8, 23, 0, 44, 1980, 3] becomes [8, 0, 3].
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [8, 23, 0, 44, 1980, 3]
    large_numbers = []
    index = 0
    while index < numbers.length
      number = numbers[index]
      if number >= 23
        large_numbers << number
      end
      index += 1
    end
    p large_numbers

    # Alternative solution with the array .each method
    numbers = [8, 23, 0, 44, 1980, 3]
    large_numbers = []
    numbers.each do |number|
      if number >= 23
        large_numbers << number
      end
    end
    p large_numbers

    # Alternative solution with the array .select method
    numbers = [8, 23, 0, 44, 1980, 3]
    large_numbers = numbers.select { |number| number >= 23 }
    p large_numbers
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [8, 23, 0, 44, 1980, 3];
    var largeNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      var number = numbers[index];
      if (number >= 23) {
        largeNumbers.push(number);
      }
      index += 1;
    }
    console.log(largeNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [8, 23, 0, 44, 1980, 3];
    var largeNumbers = [];
    numbers.forEach(function (number) {
      if (number >= 23) {
        largeNumbers.push(number);
      }
    });
    console.log(largeNumbers);

    // Alternative solution with the array .filter method
    var numbers = [8, 23, 0, 44, 1980, 3];
    var largeNumbers = numbers.filter(function (number) {
      return number >= 23;
    });
    console.log(largeNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

8. Start with an array of strings and create a new array with only the strings that don't start with the letter "b".
   <br>For example, ["big", "little", "good", "bad"] becomes ["little", "good"].
    <details><summary>Ruby solution</summary>

    ```ruby
    words = ["big", "little", "good", "bad"]
    non_b_words = []
    index = 0
    while index < words.length
      if words[index][0] != "b"
        non_b_words << words[index]
      end
      index = index + 1
    end
    p non_b_words

    # Alternative solution with the array .each method
    words = ["big", "little", "good", "bad"]
    non_b_words = []
    words.each do |word|
      if word[0] != "b"
        non_b_words << word
      end
    end
    p non_b_words

    # Alternative solution with the array .select method
    words = ["big", "little", "good", "bad"]
    non_b_words = words.select { |word| word[0] != "b" }
    p non_b_words
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var words = ["big", "little", "good", "bad"];
    var nonBWords = [];
    var index = 0;
    while (index < words.length) {
      if (words[index][0] !== "b") {
        nonBWords.push(words[index]);
      }
      index = index + 1;
    }
    console.log(nonBWords);

    // Alternative solution with the array .forEach method
    var words = ["big", "little", "good", "bad"];
    var nonBWords = [];
    words.forEach(function (word) {
      if (word[0] !== "b") {
        nonBWords.push(word);
      }
    });
    console.log(nonBWords);

    // Alternative solution with the array .filter method
    var words = ["big", "little", "good", "bad"];
    var nonBWords = words.filter(function (word) {
      return word[0] !== "b";
    });
    console.log(nonBWords);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

9. Start with an array of hashes and create a new array with only the hashes with prices less than 10 (from the :price key).
   <br>For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes [{name: "pencil", price: 1}, {name: "book", price: 4}].
    <details><summary>Ruby solution</summary>

    ```ruby
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    inexpensive_items = []
    index = 0
    while index < items.length
      item = items[index]
      if item[:price] < 10
        inexpensive_items << item
      end
      index += 1
    end
    p inexpensive_items

    # Alternative solution with the array .each method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    inexpensive_items = []
    items.each do |item|
      if item[:price] < 10
        inexpensive_items << item
      end
    end
    p inexpensive_items

    # Alternative solution with the array .select method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    inexpensive_items = items.select { |item| item[:price] < 10 }
    p inexpensive_items
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var inexpensiveItems = [];
    var index = 0;
    while (index < items.length) {
      var item = items[index];
      if (item.price < 10) {
        inexpensiveItems.push(item);
      }
      index += 1;
    }
    console.log(inexpensiveItems);

    // Alternative solution with the array .forEach method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var inexpensiveItems = [];
    items.forEach(function (item) {
      if (item.price < 10) {
        inexpensiveItems.push(item);
      }
    });
    console.log(inexpensiveItems);

    // Alternative solution with the array .filter method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var inexpensiveItems = items.filter(function (item) {
      return item.price < 10;
    });
    console.log(inexpensiveItems);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

10. Start with an array of numbers and create a new array with only the odd numbers.
    <br>For example, [2, 4, 5, 1, 8, 9, 7] becomes [5, 1, 9, 7].
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [2, 4, 5, 1, 8, 9, 7]
    odd_numbers = []
    index = 0
    while index < numbers.length
      if numbers[index] % 2 == 1
        odd_numbers << numbers[index]
      end
      index = index + 1
    end
    p odd_numbers

    # Alternative solution with the array .each method
    numbers = [2, 4, 5, 1, 8, 9, 7]
    odd_numbers = []
    numbers.each do |number|
      if number % 2 == 1
        odd_numbers << number
      end
    end
    p odd_numbers

    # Alternative solution with the array .select method
    numbers = [2, 4, 5, 1, 8, 9, 7]
    odd_numbers = numbers.select { |number| number % 2 == 1 }
    p odd_numbers
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [2, 4, 5, 1, 8, 9, 7];
    var oddNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      if (numbers[index] % 2 === 1) {
        oddNumbers.push(numbers[index]);
      }
      index++;
    }
    console.log(oddNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [2, 4, 5, 1, 8, 9, 7];
    var oddNumbers = [];
    numbers.forEach(function (number) {
      if (number % 2 === 1) {
        oddNumbers.push(number);
      }
    });
    console.log(oddNumbers);

    // Alternative solution with the array .filter method
    var numbers = [2, 4, 5, 1, 8, 9, 7];
    var oddNumbers = numbers.filter(function (number) {
      return number % 2 === 1;
    });
    console.log(oddNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>
