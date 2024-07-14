1. Start with an array of numbers and compute the sum of all the numbers.
   <br>For example, [5, 10, 8, 3] becomes 26.
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [5, 10, 8, 3]
    sum = 0
    index = 0
    while index < numbers.length
      sum = sum + numbers[index]
      index = index + 1
    end
    p sum

    # Alternative solution with the array .each method
    numbers = [5, 10, 8, 3]
    sum = 0
    numbers.each do |number|
      sum = sum + number
    end
    p sum

    # Alternative solution with the array .reduce method
    numbers = [5, 10, 8, 3]
    sum = numbers.reduce(0) { |sum, number| sum + number }
    p sum
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [5, 10, 8, 3];
    var sum = 0;
    var index = 0;
    while (index < numbers.length) {
      sum = sum + numbers[index];
      index = index + 1;
    }
    console.log(sum);

    // Alternative solution with the array .forEach method
    var numbers = [5, 10, 8, 3];
    var sum = 0;
    numbers.forEach(function (number) {
      sum = sum + number;
    });
    console.log(sum);

    // Alternative solution with the array .reduce method
    var numbers = [5, 10, 8, 3];
    var sum = numbers.reduce(function (sum, number) {
      return sum + number;
    }, 0);
    console.log(sum);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

2. Start with an array of strings and combine them all into a single string.
   <br>For example, ["volleyball", "basketball", "badminton"] becomes "volleyballbasketballbadminton".
    <details><summary>Ruby solution</summary>

    ```ruby
    sports = ["volleyball", "basketball", "badminton"]
    word = ""
    index = 0
    while index < sports.length
      sport = sports[index]
      word = word + sport
      index = index + 1
    end
    p word

    # Alternative solution with the array .each method
    sports = ["volleyball", "basketball", "badminton"]
    word = ""
    sports.each do |sport|
      word = word + sport
    end
    p word

    # Alternative solution with the array .reduce method
    sports = ["volleyball", "basketball", "badminton"]
    word = sports.reduce("") { |word, sport| word + sport }
    p word
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var sports = ["volleyball", "basketball", "badminton"];
    var word = "";
    var index = 0;
    while (index < sports.length) {
      var sport = sports[index];
      word = word + sport;
      index = index + 1;
    }
    console.log(word);

    // Alternative solution with the array .forEach method
    var sports = ["volleyball", "basketball", "badminton"];
    var word = "";
    sports.forEach(function (sport) {
      word = word + sport;
    });
    console.log(word);

    // Alternative solution with the array .reduce method
    var sports = ["volleyball", "basketball", "badminton"];
    var word = sports.reduce(function (word, sport) {
      return word + sport;
    }, "");
    console.log(word);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

3. Start with an array of hashes and compute the sum of the prices (from the :price key).
   <br>For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes 105.
    <details><summary>Ruby solution</summary>

    ```ruby
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    total_price = 0
    index = 0
    while index < items.length
      total_price += items[index][:price]
      index += 1
    end
    p total_price

    # Alternative solution with the array .each method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    total_price = 0
    items.each do |item|
      total_price += item[:price]
    end
    p total_price

    # Alternative solution with the array .reduce method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    total_price = items.reduce(0) { |total, item| total + item[:price] }
    p total_price
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var totalPrice = 0;
    var index = 0;
    while (index < items.length) {
      totalPrice += items[index].price;
      index += 1;
    }
    console.log(totalPrice);

    // Alternative solution with the array .forEach method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var totalPrice = 0;
    items.forEach(function (item) {
      totalPrice += item.price;
    });
    console.log(totalPrice);

    // Alternative solution with the array .reduce method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var totalPrice = items.reduce(function (total, item) {
      return total + item.price;
    }, 0);
    console.log(totalPrice);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

4. Start with an array of numbers and compute the the minumum number.
   <br>For example, [5, 10, 8, 3, 9] becomes 3.
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [5, 10, 8, 3]
    minimum = numbers[0]
    index = 0
    while index < numbers.length
      number = numbers[index]
      if number < minimum
        minimum = number
      end
      index = index + 1
    end
    p minimum

    # Alternative solution with the array .each method
    numbers = [5, 10, 8, 3]
    minimum = numbers[0]
    numbers.each do |number|
      if number < minimum
        minimum = number
      end
    end
    p minimum

    # Alternative solution with the array .reduce method
    numbers = [5, 10, 8, 3]
    minimum = numbers.reduce(numbers[0]) do |min, number|
      if number < min
        number
      else
        min
      end
    end
    p minimum
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [5, 10, 8, 3];
    var minimum = numbers[0];
    var index = 0;
    while (index < numbers.length) {
      var number = numbers[index];
      if (number < minimum) {
        minimum = number;
      }
      index++;
    }
    console.log(minimum);

    // Alternative solution with the array .forEach method
    var numbers = [5, 10, 8, 3];
    var minimum = numbers[0];
    numbers.forEach(function (number) {
      if (number < minimum) {
        minimum = number;
      }
    });
    console.log(minimum);

    // Alternative solution with the array .reduce method
    var numbers = [5, 10, 8, 3];
    var minimum = numbers.reduce(function (min, number) {
      if (number < min) {
        return number;
      } else {
        return min;
      }
    }, numbers[0]);
    console.log(minimum);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

5. Start with an array of strings and compute the total length of all the strings.
   <br>For example, ["volleyball", "basketball", "badminton"] becomes 29.
    <details><summary>Ruby solution</summary>

    ```ruby
    words = ["volleyball", "basketball", "badminton"]
    total_length = 0
    index = 0
    while index < words.length
      total_length += words[index].length
      index += 1
    end
    p total_length

    # Alternative solution with the array .each method
    words = ["volleyball", "basketball", "badminton"]
    total_length = 0
    words.each do |word|
      total_length += word.length
    end
    p total_length

    # Alternative solution with the array .reduce method
    words = ["volleyball", "basketball", "badminton"]
    total_length = words.reduce(0) { |sum, word| sum + word.length }
    p total_length
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var words = ["volleyball", "basketball", "badminton"];
    var totalLength = 0;
    var index = 0;
    while (index < words.length) {
      totalLength += words[index].length;
      index += 1;
    }
    console.log(totalLength);

    // Alternative solution with the array .forEach method
    var words = ["volleyball", "basketball", "badminton"];
    var totalLength = 0;
    words.forEach(function (word) {
      totalLength += word.length;
    });
    console.log(totalLength);

    // Alternative solution with the array .reduce method
    var words = ["volleyball", "basketball", "badminton"];
    var totalLength = words.reduce(function (sum, word) {
      return sum + word.length;
    }, 0);
    console.log(totalLength);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

6. Start with an array of hashes and find the hash with the lowest price (from the :price key).
   <br>For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes {name: "pencil", price: 1}.
    <details><summary>Ruby solution</summary>

    ```ruby
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    cheapest_item = items[0]
    index = 0
    while index < items.length
      item = items[index]
      if item[:price] < cheapest_item[:price]
        cheapest_item = item
      end
      index = index + 1
    end
    p cheapest_item

    # Alternative solution with the array .each method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    cheapest_item = items[0]
    items.each do |item|
      if item[:price] < cheapest_item[:price]
        cheapest_item = item
      end
    end
    p cheapest_item

    # Alternative solution with the array .reduce method
    items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    cheapest_item = items.reduce(items[0]) do |cheapest_item, item|
      if item[:price] < cheapest_item[:price]
        item
      else
        cheapest_item
      end
    end
    p cheapest_item
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var cheapestItem = items[0];
    var index = 0;
    while (index < items.length) {
      var item = items[index];
      if (item.price < cheapestItem.price) {
        cheapestItem = item;
      }
      index = index + 1;
    }
    console.log(cheapestItem);

    // Alternative solution with the array .forEach method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var cheapestItem = items[0];
    items.forEach(function (item) {
      if (item.price < cheapestItem.price) {
        cheapestItem = item;
      }
    });
    console.log(cheapestItem);

    // Alternative solution with the array .reduce method
    var items = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var cheapestItem = items.reduce(function (cheapestItem, item) {
      if (item.price < cheapestItem.price) {
        return item;
      } else {
        return cheapestItem;
      }
    }, items[0]);
    console.log(cheapestItem);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

7. Start with an array of numbers and compute product of all the numbers.
   <br>For example, [5, 10, 8, 3] becomes 1200.
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [5, 10, 8, 3]
    product = 1
    index = 0
    while index < numbers.length
      product = product * numbers[index]
      index = index + 1
    end
    p product

    # Alternative solution with the array .each method
    numbers = [5, 10, 8, 3]
    product = 1
    numbers.each do |number|
      product = product * number
    end
    p product

    # Alternative solution with the array .reduce method
    numbers = [5, 10, 8, 3]
    product = numbers.reduce(1) { |product, number| product * number }
    p product
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [5, 10, 8, 3];
    var product = 1;
    var index = 0;
    while (index < numbers.length) {
      product = product * numbers[index];
      index = index + 1;
    }
    console.log(product);

    // Alternative solution with the array .forEach method
    var numbers = [5, 10, 8, 3];
    var product = 1;
    numbers.forEach(function (number) {
      product = product * number;
    });
    console.log(product);

    // Alternative solution with the array .reduce method
    var numbers = [5, 10, 8, 3];
    var product = numbers.reduce(function (product, number) {
      return product * number;
    }, 1);
    console.log(product);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

8. Start with an array of strings and combine them all into a single string, separated by dashes.
   <br>For example, ["volleyball", "basketball", "badminton"] becomes "-volleyball-basketball-badminton-".
    <details><summary>Ruby solution</summary>

    ```ruby
    strings = ["volleyball", "basketball", "badminton"]
    single_string = "-"
    index = 0
    while index < strings.length
      string = strings[index]
      single_string += "#{string}-"
      index += 1
    end
    p single_string

    # Alternative solution with the array .each method
    strings = ["volleyball", "basketball", "badminton"]
    single_string = "-"
    strings.each do |string|
      single_string += "#{string}-"
    end
    p single_string

    # Alternative solution with the array .reduce method
    strings = ["volleyball", "basketball", "badminton"]
    single_string = strings.reduce("-") { |total, string| total + "#{string}-" }
    p single_string
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var strings = ["volleyball", "basketball", "badminton"];
    var singleString = "-";
    var index = 0;
    while (index < strings.length) {
      var string = strings[index];
      singleString += string + "-";
      index += 1;
    }
    console.log(singleString);

    // Alternative solution with the array .forEach method
    var strings = ["volleyball", "basketball", "badminton"];
    var singleString = "-";
    strings.forEach(function (string) {
      singleString += string + "-";
    });
    console.log(singleString);

    // Alternative solution with the array .reduce method
    var strings = ["volleyball", "basketball", "badminton"];
    var singleString = strings.reduce(function (total, string) {
      return total + string + "-";
    }, "-");
    console.log(singleString);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

9. Start with an array of hashes and find the hash with the shortest name (from the :name key).
   <br>For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes {name: "book", price: 4}.
    <details><summary>Ruby solution</summary>

    ```ruby
    products = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    shortest_name_product = products[0]
    index = 0
    while index < products.length
      if products[index][:name].length < shortest_name_product[:name].length
        shortest_name_product = products[index]
      end
      index = index + 1
    end
    p shortest_name_product

    # Alternative solution with the array .each method
    products = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    shortest_name_product = products[0]
    products.each do |product|
      if product[:name].length < shortest_name_product[:name].length
        shortest_name_product = product
      end
    end
    p shortest_name_product

    # Alternative solution with the array .reduce method
    products = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }]
    shortest_name_product = products.reduce(products[0]) do |shortest, product|
      if product[:name].length < shortest[:name].length
        product
      else
        shortest
      end
    end
    p shortest_name_product
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var products = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var shortestNameProduct = products[0];
    var index = 0;
    while (index < products.length) {
      if (products[index].name.length < shortestNameProduct.name.length) {
        shortestNameProduct = products[index];
      }
      index++;
    }
    console.log(shortestNameProduct);

    // Alternative solution with the array .forEach method
    var products = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var shortestNameProduct = products[0];
    products.forEach(function (product) {
      if (product.name.length < shortestNameProduct.name.length) {
        shortestNameProduct = product;
      }
    });
    console.log(shortestNameProduct);

    // Alternative solution with the array .reduce method
    var products = [{ name: "chair", price: 100 }, { name: "pencil", price: 1 }, { name: "book", price: 4 }];
    var shortestNameProduct = products.reduce(function (shortest, product) {
      if (product.name.length < shortest.name.length) {
        return product;
      } else {
        return shortest;
      }
    }, products[0]);
    console.log(shortestNameProduct);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

10. Start with an array of numbers and compute the maximum number.
    <br>For example, [5, 10, 8, 3] becomes 10.
    <details><summary>Ruby solution</summary>

    ```ruby
    numbers = [5, 10, 8, 3]
    maximum = numbers[0]
    index = 0
    while index < numbers.length
      number = numbers[index]
      if number > maximum
        maximum = number
      end
      index += 1
    end
    p maximum

    # Alternative solution with the array .each method
    numbers = [5, 10, 8, 3]
    maximum = numbers[0]
    numbers.each do |number|
      if number > maximum
        maximum = number
      end
    end
    p maximum

    # Alternative solution with the array .reduce method
    numbers = [5, 10, 8, 3]
    maximum = numbers.reduce(numbers[0]) do |max, number|
      if number > max
        number
      else
        max
      end
    end
    p maximum
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var numbers = [5, 10, 8, 3];
    var maximum = numbers[0];
    var index = 0;
    while (index < numbers.length) {
      var number = numbers[index];
      if (number > maximum) {
        maximum = number;
      }
      index += 1;
    }
    console.log(maximum);

    // Alternative solution with the array .forEach method
    var numbers = [5, 10, 8, 3];
    var maximum = numbers[0];
    numbers.forEach(function (number) {
      if (number > maximum) {
        maximum = number;
      }
    });
    console.log(maximum);

    // Alternative solution with the array .reduce method
    var numbers = [5, 10, 8, 3];
    var maximum = numbers.reduce(function (max, number) {
      if (number > max) {
        return number;
      } else {
        return max;
      }
    }, numbers[0]);
    console.log(maximum);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>