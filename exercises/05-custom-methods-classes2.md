1. Write a Song class with attributes for name, artist, and duration. 
    <details><summary>Ruby solution</summary>

    ```ruby
    class Song
      def initialize(name, artist, duration)
        @name = name
        @artist = artist
        @duration = duration
      end
    end

    song = Song.new("Gloria", "Patti Smith", "5:56")
    pp song
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Song {
      constructor(name, artist, duration) {
        this.name = name;
        this.artist = artist;
        this.duration = duration;
      }
    }

    var song = new Song("Gloria", "Patti Smith", "5:56");
    console.log(song);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Song:
      def __init__(self, name, artist, duration):
        self.name = name
        self.artist = artist
        self.duration = duration

    song = Song("Gloria", "Patti Smith", "5:56")
    print(song)
    ```
    </details>

2. Write a Rectangle class with attributes for width and height. 
    <details><summary>Ruby solution</summary>

    ```ruby
    class Rectangle
      def initialize(height, width)
        @height = height
        @width = width
      end
    end

    rectangle = Rectangle.new(10, 20)
    pp rectangle
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Rectangle {
      constructor(height, width) {
        this.height = height;
        this.width = width;
      }
    }

    var rectangle = new Rectangle(10, 20);
    console.log(rectangle);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Rectangle:
      def __init__(self, height, width):
        self.height = height
        self.width = width

    rectangle = Rectangle(10, 20)
    print(rectangle)
    ```
    </details>

3. Write a Person class with attributes for name and age.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Person
      def initialize(name, age)
        @name = name
        @age = age
      end
    end

    person = Person.new("Omar", 36)
    pp person
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Person {
      constructor(name, age) {
        this.name = name;
        this.age = age;
      }
    }

    var person = new Person("Omar", 36);
    console.log(person);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Person:
      def __init__(self, name, age):
        self.name = name
        self.age = age

    person = Person("Omar", 36)
    print(person)
    ```
    </details>

4. Write a Location class with attributes for latitude and longitude.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Location
      def initialize(latitude, longitude)
        @latitude = latitude
        @longitude = longitude
      end
    end

    location = Location.new(41.881832, -87.623177)
    pp location
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Location {
      constructor(latitude, longitude) {
        this.latitude = latitude;
        this.longitude = longitude;
      }
    }

    var location = new Location(41.881832, -87.623177);
    console.log(location);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Location:
      def __init__(self, latitude, longitude):
        self.latitude = latitude
        self.longitude = longitude

    location = Location(41.881832, -87.623177)
    print(location)
    ```
    </details>

5. Write an Account class with attributes for name and balance.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Account
      def initialize(name, balance)
        @name = name
        @balance = balance
      end
    end

    account = Account.new("Checking", 7000)
    pp account
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Account {
      constructor(name, balance) {
        this.name = name;
        this.balance = balance;
      }
    }

    var account = new Account("Checking", 7000);
    console.log(account);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Account:
      def __init__(self, name, balance):
        self.name = name
        self.balance = balance

    account = Account("Checking", 7000)
    print(account)
    ```
    </details>

6. Write a Movie class with attributes for title, director, and year.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Movie
      def initialize(title, director, year)
        @title = title
        @director = director
        @year = year
      end
    end

    movie = Movie.new("Kiss Kiss Bang Bang", "Shane Black", 2005)
    pp movie
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Movie {
      constructor(title, director, year) {
        this.title = title;
        this.director = director;
        this.year = year;
      }
    }

    var movie = new Movie("Kiss Kiss Bang Bang", "Shane Black", 2005);
    console.log(movie);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Movie:
      def __init__(self, title, director, year):
        self.title = title
        self.director = director
        self.year = year

    movie = Movie("Kiss Kiss Bang Bang", "Shane Black", 2005)
    print(movie)
    ```
    </details>

7. Write a Car class with attributes for make, model, year, and color. 
    <details><summary>Ruby solution</summary>

    ```ruby
    class Car
      def initialize(make, model, year, color)
        @make = make
        @model = model
        @year = year
        @color = color
      end
    end

    car = Car.new("Chevy", "Impala", 1958, "black")
    pp car
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Car {
      constructor(make, model, year, color) {
        this.make = make;
        this.model = model;
        this.year = year;
        this.color = color;
      }
    }

    var car = new Car("Chevy", "Impala", 1958, "black");
    console.log(car);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Car:
      def __init__(self, make, model, year, color):
        self.make = make
        self.model = model
        self.year = year
        self.color = color

    car = Car("Chevy", "Impala", 1958, "black")
    print(car)
    ```
    </details>

8. Write a Point class with attributes for x, y, and z coordinates.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Point
      def initialize(x, y, z)
        @x = x
        @y = y
        @z = z
      end
    end

    point = Point.new(12, -5, 7)
    pp point
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Point {
      constructor(x, y, z) {
        this.x = x;
        this.y = y;
        this.z = z;
      }
    }

    var point = new Point(12, -5, 7);
    console.log(point);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Point:
      def __init__(self, x, y, z):
        self.x = x
        self.y = y
        self.z = z

    point = Point(12, -5, 7)
    print(point)
    ```
    </details>

9. Write a Book class with attributes for title, author, and year.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Book
      def initialize(title, author, year)
        @title = title
        @author = author
        @year = year
      end
    end

    book = Book.new("Little Brother", "Cory Doctorow", 2008)
    pp book
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Book {
      constructor(title, author, year) {
        this.title = title;
        this.author = author;
        this.year = year;
      }
    }

    var book = new Book("Little Brother", "Cory Doctorow", 2008);
    console.log(book);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Book:
      def __init__(self, title, author, year):
        self.title = title
        self.author = author
        self.year = year

    book = Book("Little Brother", "Cory Doctorow", 2008)
    print(book)
    ```
    </details>

10. Write a Plant class with attributes for name, size, and price.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Plant
      def initialize(name, size, price)
        @name = name
        @size = size
        @price = price
      end
    end

    plant = Plant.new("Japanese Peace Lily", "large", 40)
    pp plant
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Plant {
      constructor(name, size, price) {
        this.name = name;
        this.size = size;
        this.price = price;
      }
    }

    var plant = new Plant("Japanese Peace Lily", "large", 40);
    console.log(plant);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Plant:
      def __init__(self, name, size, price):
        self.name = name
        self.size = size
        self.price = price

    plant = Plant("Japanese Peace Lily", "large", 40)
    print(plant)
    ```
    </details>
