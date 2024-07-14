1. Make a hash to store a person's first name, last name, and email address. Then print each attribute on separate lines.
    <details><summary>Ruby solution</summary>

    ```ruby
    person = { "first_name" => "Ada", "last_name" => "Lovelace", "email" => "ada.lovelace@email.com" }
    pp person["first_name"]
    pp person["last_name"]
    pp person["email"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var person = { firstName: "Ada", lastName: "Lovelace", email: "ada.lovelace@email.com" };
    console.log(person.firstName);
    console.log(person["lastName"]);
    console.log(person.email);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

2. Make an array of hashes to store the first name and last name for 3 different people. Then print out the first person's info.
    <details><summary>Ruby solution</summary>

    ```ruby
    people = [
      { "first_name" => "Grace", "last_name" => "Hopper" },
      { "first_name" => "Mace", "last_name" => "Windu" },
      { "first_name" => "Robert", "last_name" => "Chase" }
    ]
    pp people[0]["first_name"]
    pp people[0]["last_name"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var people = [
      { firstName: "Grace", lastName: "Hopper" },
      { firstName: "Mace", lastName: "Windu" },
      { firstName: "Robert", lastName: "Chase" },
    ];
    console.log(people[0]["firstName"]);
    console.log(people[0]["lastName"]);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

3. Make a hash to store prices for 3 different menu items. Then add a new menu item and price and print the hash to see the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    menu = { "sandwich" => 4, "soda" => 2, "juice" => 3 }
    menu["salad"] = 5
    pp menu
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var menu = { sandwich: 4, soda: 2, juice: 3 };
    menu["salad"] = 5;
    console.log(menu);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

4. Make a hash to store a book's title, author, number of pages, and language. Then print each attribute on separate lines.
    <details><summary>Ruby solution</summary>

    ```ruby
    book = { "title" => "The Art of Game Design", "author" => "Jesse Schell", "pages" => 520, "language" => "English" }
    pp book["title"]
    pp book["author"]
    pp book["pages"]
    pp book["language"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var book = { title: "The Art of Game Design", author: "Jesse Schell", pages: 520, language: "English" };
    console.log(book["title"]);
    console.log(book.author);
    console.log(book.pages);
    console.log(book["language"]);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

5. Make an array of hashes to store the title and author for 3 different books. Then print out the third book's author.
    <details><summary>Ruby solution</summary>

    ```ruby
    books = [
      { "title" => "Reality is Broken", "author" => "Jane McGonigal" },
      { "title" => "Code", "author" => "Charles Petzlod" },
      { "title" => "The Humane Interface", "author" => "Jef Raskin" }
    ]
    pp books[2]["author"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var books = [
      { title: "Reality is Broken", author: "Jane McGonigal" },
      { title: "Code", author: "Charles Petzlod" },
      { title: "The Humane Interface", author: "Jef Raskin" },
    ];
    console.log(books[2].author);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

6. Make a hash to store 3 different states and their captitals. Then add a new state and capital and print the hash to see the
    <details><summary>Ruby solution</summary>

    ```ruby
    capitals = { "California" => "Sacremento", "Illinois" => "Springfield", "New York" => "Albany" }
    capitals["Tennessee"] = "Nashville"
    pp capitals
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var capitals = { California: "Sacremento", Illinois: "Springfield", "New York": "Albany" };
    capitals["Tennessee"] = "Nashville";
    console.log(capitals);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details> result.

7. Make a hash to store a laptop's brand, model, and year. Then print each attribute on separate lines.
    <details><summary>Ruby solution</summary>

    ```ruby
    laptop = { "brand" => "Apple", "model" => "MacBook Air", "year" => 2014 }
    pp laptop["brand"]
    pp laptop["model"]
    pp laptop["year"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var laptop = { brand: "Apple", model: "MacBook Air", year: 2014 };
    console.log(laptop["brand"]);
    console.log(laptop.model);
    console.log(laptop.year);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

8. Make an array of hashes to store the brand and model for 3 different laptops. Then print out the second laptop's model.
    <details><summary>Ruby solution</summary>

    ```ruby
    laptops = [
      { "brand" => "Microsoft", "model" => "Surface" },
      { "brand" => "Apple", "model" => "MacBook Pro" },
      { "brand" => "Dell", "model" => "XPS 13" }
    ]
    pp laptops[1]["model"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var laptops = [
      { brand: "Microsoft", model: "Surface" },
      { brand: "Apple", model: "MacBook Pro" },
      { brand: "Dell", model: "XPS 13" },
    ];
    console.log(laptops[1]["model"]);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

9. Make a hash to store definitions for 2 different words. Then add a new word and definition and print the hash to see the result.
    <details><summary>Ruby solution</summary>

    ```ruby
    dictionary = { "bad" => "of poor quality or a low standard", "mad" => "very angry" }
    dictionary["glad"] = "delighted"
    pp dictionary
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var dictionary = { bad: "of poor quality or a low standard", mad: "very angry" };
    dictionary.glad = "delighted";
    console.log(dictionary);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>

10. Make a hash to store a shirt's brand, color, and size. Then print each attribute on separate lines.
    <details><summary>Ruby solution</summary>

    ```ruby
    shirt = { "brand" => "Hanes", "color" => "white", "size" => "large" }
    pp shirt["brand"]
    pp shirt["color"]
    pp shirt["size"]
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var shirt = { brand: "Hanes", color: "white", size: "large" };
    console.log(shirt.brand);
    console.log(shirt["color"]);
    console.log(shirt.size);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    ```
    </details>
