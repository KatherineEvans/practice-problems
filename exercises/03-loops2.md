1. Start with an array of numbers and create a new array with each number times 3.
   <br>For example, [1, 2, 3] becomes [3, 6, 9].
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [1, 2, 3]
    new_numbers = []
    index = 0
    while index < numbers.length
      new_numbers << numbers[index] * 3
      index = index + 1
    end
    p new_numbers

    # Alternative solution with the array .each method
    numbers = [1, 2, 3]
    new_numbers = []
    numbers.each do |number|
      new_numbers << number * 3
    end
    p new_numbers

    # Alternative solution with the array .map method
    numbers = [1, 2, 3]
    new_numbers = numbers.map { |number| number * 3 }
    p new_numbers
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [1, 2, 3];
    var newNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      var number = numbers[index];
      newNumbers.push(number * 3);
      index = index + 1;
    }
    console.log(newNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [1, 2, 3];
    var newNumbers = [];
    numbers.forEach(function (number) {
      newNumbers.push(number * 3);
    });
    console.log(newNumbers);

    // Alternative solution with the array .map method
    var numbers = [1, 2, 3];
    var newNumbers = numbers.map(function (number) {
      return number * 3;
    });
    console.log(newNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

2. Start with an array of strings and create a new array with each string upcased.
   <br>For example, ["hello", "goodbye"] becomes ["HELLO", "GOODBYE"].
    <details><summary>Ruby solution</summary>

    ```ruby
    strings = ["hello", "goodbye"]
    new_strings = []
    index = 0
    while index < strings.length
      string = strings[index]
      new_strings << string.upcase
      index = index + 1
    end
    p new_strings

    # Alternative solution with the array .each method
    strings = ["hello", "goodbye"]
    new_strings = []
    strings.each do |string|
      new_strings << string.upcase
    end
    p new_strings

    # Alternative solution with the array .map method
    strings = ["hello", "goodbye"]
    new_strings = strings.map { |string| string.upcase }
    p new_strings
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var strings = ["hello", "goodbye"];
    var newStrings = [];
    index = 0;
    while (index < strings.length) {
      newStrings.push(strings[index].toUpperCase());
      index += 1;
    }
    console.log(newStrings);

    // Alternative solution with the array .forEach method
    var strings = ["hello", "goodbye"];
    var newStrings = [];
    strings.forEach(function (string) {
      newStrings.push(string.toUpperCase());
    });
    console.log(newStrings);

    // Alternative solution with the array .map method
    var strings = ["hello", "goodbye"];
    var newStrings = strings.map(function (string) {
      return string.toUpperCase();
    });
    console.log(newStrings);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

3. Start with an array of hashes and create a new array of string values from each hash's :name key.
   <br>For example, [{name: "Alice", age: 27}, {name: "Blane", age: 16}] becomes ["Alice", "Blane"].
    <details><summary>Ruby solution</summary>

    ```ruby
    hashes = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    strings = []
    index = 0
    while index < hashes.length
      strings << hashes[index][:name]
      index += 1
    end
    p strings

    # Alternative solution with the array .each method
    hashes = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    strings = []
    hashes.each do |hash|
      strings << hash[:name]
    end
    p strings

    # Alternative solution with the array .map method
    hashes = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    strings = hashes.map { |hash| hash[:name] }
    p strings
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }];
    var names = [];
    var index = 0;
    while (index < people.length) {
      var name = people[index].name;
      names.push(name);
      index++;
    }
    console.log(names);

    // Alternative solution with the array .forEach method
    var people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }];
    var names = [];
    people.forEach(function (person) {
      names.push(person.name);
    });
    console.log(names);

    // Alternative solution with the array .map method
    var people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }];
    var names = people.map(function (person) {
      return person.name;
    });
    console.log(names);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

4. Start with an array of numbers and create a new array with each number plus 7.
   <br>For example, [1, 2, 3] becomes [8, 9, 10].
    <details><summary>Ruby solution</summary>

    ```ruby
    items = [1, 2, 3]
    bigger_items = []
    index = 0
    while index < items.length
      item = items[index]
      bigger_items << item + 7
      index = index + 1
    end
    p bigger_items

    # Alternative solution with the array .each method
    items = [1, 2, 3]
    bigger_items = []
    items.each do |item|
      bigger_items << item + 7
    end
    p bigger_items

    # Alternative solution with the array .map method
    items = [1, 2, 3]
    bigger_items = items.map { |item| item + 7 }
    p bigger_items
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [1, 2, 3];
    var newNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      newNumbers.push(numbers[index] + 7);
      index = index + 1;
    }
    console.log(newNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [1, 2, 3];
    var newNumbers = [];
    numbers.forEach(function (number) {
      newNumbers.push(number + 7);
    });
    console.log(newNumbers);

    // Alternative solution with the array .map method
    var numbers = [1, 2, 3];
    var newNumbers = numbers.map(function (number) {
      return number + 7;
    });
    console.log(newNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

5. Start with an array of strings and create a new array with each string's length.
   <br>For example, ["hello", "goodbye"] becomes [5, 7].
    <details><summary>Ruby solution</summary>

    ```ruby
    words = ["hello", "goodbye"]
    lengths = []
    index = 0
    while index < words.length
      lengths << words[index].length
      index += 1
    end
    p lengths

    # Alternative solution with the array .each method
    words = ["hello", "goodbye"]
    lengths = []
    words.each do |word|
      lengths << word.length
    end
    p lengths

    # Alternative solution with the array .map method
    words = ["hello", "goodbye"]
    lengths = words.map { |word| word.length }
    p lengths
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var words = ["hello", "goodbye"];
    var lengths = [];
    var index = 0;
    while (index < words.length) {
      var word = words[index];
      lengths.push(word.length);
      index++;
    }
    console.log(lengths);

    // Alternative solution with the array .forEach method
    var words = ["hello", "goodbye"];
    var lengths = [];
    words.forEach(function (word) {
      lengths.push(word.length);
    });
    console.log(lengths);

    // Alternative solution with the array .map method
    var words = ["hello", "goodbye"];
    var lengths = words.map(function (word) {
      return word.length;
    });
    console.log(lengths);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

6. Start with an array of hashes and create a new array of number values from each hash's :age key.
   <br>For example, [{name: "Alice", age: 27}, {name: "Blane", age: 16}] becomes [27, 16].
    <details><summary>Ruby solution</summary>

    ```ruby
    people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    ages = []
    index = 0
    while index < people.length
      person = people[index]
      ages << person[:age]
      index = index + 1
    end
    p ages

    # Alternative solution with the array .each method
    people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    ages = []
    people.each do |person|
      ages << person[:age]
    end
    p ages

    # Alternative solution with the array .map method
    people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    ages = people.map { |person| person[:age] }
    p ages
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var people = [{ name: "Alice", age: 27 },  { name: "Blane", age: 16 }];
    var ages = [];
    var index = 0;
    while (index < people.length) {
      ages.push(people[index]["age"]);
      index = index + 1;
    }
    console.log(ages);

    // Alternative solution with the array .forEach method
    var people = [{ name: "Alice", age: 27 },  { name: "Blane", age: 16 }];
    var ages = [];
    people.forEach(function (person) {
      ages.push(person.age);
    });
    console.log(ages);

    // Alternative solution with the array .map method
    var people = [{ name: "Alice", age: 27 },  { name: "Blane", age: 16 }];
    var ages = people.map(function (person) {
      return person.age;
    });
    console.log(ages);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

7. Start with an array of numbers and create a new array with each number divided by 2.
   <br>For example, [1, 2, 3] becomes [0.5, 1.0, 1.5].
    <details><summary>Ruby solution</summary>

    ```ruby
    prices = [1, 2, 3]
    sale_prices = []
    index = 0
    while index < prices.length
      sale_prices << prices[index] / 2.0
      index = index + 1
    end
    p sale_prices

    # Alternative solution with the array .each method
    prices = [1, 2, 3]
    sale_prices = []
    prices.each do |price|
      sale_prices << price / 2.0
    end
    p sale_prices

    # Alternative solution with the array .map method
    prices = [1, 2, 3]
    sale_prices = prices.map { |price| price / 2.0 }
    p sale_prices
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [1, 2, 3];
    var newNumbers = [];
    var index = 0;
    while (index < numbers.length) {
      var number = numbers[index];
      var newNumber = number / 2;
      newNumbers.push(newNumber);
      index += 1;
    }
    console.log(newNumbers);

    // Alternative solution with the array .forEach method
    var numbers = [1, 2, 3];
    var newNumbers = [];
    numbers.forEach(function (number) {
      newNumbers.push(number / 2);
    });
    console.log(newNumbers);

    // Alternative solution with the array .map method
    var numbers = [1, 2, 3];
    var newNumbers = numbers.map(function (number) {
      return number / 2;
    });
    console.log(newNumbers);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

8. Start with an array of strings and create a new array with each string's first letter only.
   <br>For example, ["hello", "goodbye"] becomes ["h", "g"].
    <details><summary>Ruby solution</summary>

    ```ruby
    words = ["hello", "goodbye"]
    first_letters = []
    index = 0
    while index < words.length
      word = words[index]
      first_letters << word[0]
      index = index + 1
    end
    p first_letters

    # Alternative solution with the array .each method
    words = ["hello", "goodbye"]
    first_letters = []
    words.each do |word|
      first_letters << word[0]
    end
    p first_letters

    # Alternative solution with the array .map method
    words = ["hello", "goodbye"]
    first_letters = words.map { |word|  word[0] }
    p first_letters
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var strings = ["hello", "goodbye"];
    var letters = [];
    var index = 0;
    while (index < strings.length) {
      letters.push(strings[index][0]);
      index++;
    }
    console.log(letters);

    // Alternative solution with the array .forEach method
    var strings = ["hello", "goodbye"];
    var letters = [];
    strings.forEach(function (string) {
      letters.push(string[0]);
    });
    console.log(letters);

    // Alternative solution with the array .map method
    var strings = ["hello", "goodbye"];
    var letters = strings.map(function (string) {
      return string[0];
    });
    console.log(letters);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

9. Start with an array of hashes and create a new array of number values from each hash's :age key times 2.
   <br>For example, [{name: "Alice", age: 27}, {name: "Blane", age: 16}] becomes [54, 32].
    <details><summary>Ruby solution</summary>

    ```ruby
    participants = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    doubled_ages = []
    index = 0
    while index < participants.length
      doubled_ages << participants[index][:age] * 2
      index += 1
    end
    p doubled_ages

    # Alternative solution with the array .each method
    participants = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    doubled_ages = []
    participants.each do |participant|
      doubled_ages << participant[:age] * 2
    end
    p doubled_ages

    # Alternative solution with the array .map method
    participants = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }]
    doubled_ages = participants.map { |participant| participant[:age] * 2 }
    p doubled_ages
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }];
    var doubleAges = [];
    var index = 0;
    while (index < people.length) {
      var age = people[index].age;
      doubleAges.push(age * 2);
      index = index + 1;
    }
    console.log(doubleAges);

    // Alternative solution with the array .forEach method
    var people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }];
    var doubleAges = [];
    people.forEach(function (person) {
      doubleAges.push(person["age"] * 2);
    });
    console.log(doubleAges);

    // Alternative solution with the array .map method
    var people = [{ name: "Alice", age: 27 }, { name: "Blane", age: 16 }];
    var doubleAges = people.map(function (person) {
      return person["age"] * 2;
    });
    console.log(doubleAges);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

10. Start with an array of numbers and create a new array with each number converted into a string.
    <br>For example, [1, 2, 3] becomes ["1", "2", "3"].
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [1, 2, 3]
    numbers_as_strings = []
    index = 0
    while index < numbers.length
      number = numbers[index]
      numbers_as_strings << number.to_s
      index = index + 1
    end
    p numbers_as_strings

    # Alternative solution with the array .each method
    numbers = [1, 2, 3]
    numbers_as_strings = []
    numbers.each do |number|
      numbers_as_strings << number.to_s
    end
    p numbers_as_strings

    # Alternative solution with the array .map method
    numbers = [1, 2, 3]
    numbers_as_strings = numbers.map { |number| number.to_s }
    p numbers_as_strings
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [1, 2, 3];
    var strings = [];
    var index = 0;
    while (index < numbers.length) {
      strings.push(numbers[index].toString());
      index += 1;
    }
    console.log(strings);

    // Alternative solution with the array .forEach method
    var numbers = [1, 2, 3];
    var strings = [];
    numbers.forEach(function (number) {
      strings.push(number.toString());
    });
    console.log(strings);

    // Alternative solution with the array .map method
    var numbers = [1, 2, 3];
    var strings = numbers.map(function (number) {
      return number.toString();
    });
    console.log(strings);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>