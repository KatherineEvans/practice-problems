1. Write a Song class with attributes and reader/writer methods for name, artist, and duration. 
   Then write a method that prints the name, artist, and duration in a single sentence.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Song
      attr_reader :name, :artist, :duration
      attr_writer :name, :artist, :duration

      def initialize(name, artist, duration)
        @name = name
        @artist = artist
        @duration = duration
      end

      def print_info
        puts "The song #{name} by #{artist} has a duration of #{duration}."
      end
    end

    song = Song.new("Gloria", "Patti Smith", "5:56")
    pp song
    song.print_info
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
      
      printInfo() {
        console.log(`The song ${this.name} by ${this.artist} has a duration of ${this.duration}.`);
      }
    }

    var song = new Song("Gloria", "Patti Smith", "5:56");
    console.log(song);
    song.printInfo();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Song:
      def __init__(self, name, artist, duration):
        self.name = name
        self.artist = artist
        self.duration = duration

      def print_info(self):
        print(f"The song {self.name} by {self.artist} has a duration of {self.duration}.")

    song = Song("Gloria", "Patti Smith", "5:56")
    print(song)
    song.print_info()
    ```
    </details>

2. Write a Rectangle class with attributes and reader/writer methods for width and height.
   Then write a method that returns the area of the rectangle. 
    <details><summary>Ruby solution</summary>

    ```ruby
    class Rectangle
      attr_reader :height, :width
      attr_writer :height, :width

      def initialize(height, width)
        @height = height
        @width = width
      end

      def area
        width * height
      end
    end

    rectangle = Rectangle.new(10, 20)
    pp rectangle
    puts "The rectangle has a width of #{rectangle.width}, a height of #{rectangle.height}, and an area of #{rectangle.area}."
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Rectangle {
      constructor(height, width) {
        this.height = height;
        this.width = width;
      }

      area() {
        return this.height * this.width;
      }
    }

    var rectangle = new Rectangle(10, 20);
    console.log(rectangle);
    console.log(rectangle.area());
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Rectangle:
      def __init__(self, height, width):
        self.height = height
        self.width = width
        
      def area(self):
        return self.height * self.width

    rectangle = Rectangle(10, 20)
    print(rectangle)
    print(rectangle.area())
    ```
    </details>

3. Write a Person class with attributes and reader/writer methods for name and age.
   Then write a method that returns the person's name in all capital letters.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Person
      attr_reader :name, :age
      attr_writer :name, :age

      def initialize(name, age)
        @name = name
        @age = age
      end

      def formatted_name
        name.upcase
      end
    end

    person = Person.new("Omar", 36)
    pp person
    puts person.formatted_name
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Person {
      constructor(name, age) {
        this.name = name;
        this.age = age;
      }

      formattedName() {
        return this.name.toUpperCase();
      }
    }

    var person = new Person("Omar", 36);
    console.log(person);
    console.log(person.formattedName());
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Person:
      def __init__(self, name, age):
        self.name = name
        self.age = age
        
      def formatted_name(self):
        return self.name.upper()

    person = Person("Omar", 36)
    print(person)
    print(person.formatted_name())
    ```
    </details>

4. Write a Coordinate class with attributes and reader/writer methods for latitude and longitude.
   Then write a method that prints out the latitude and longitude in a single sentence.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Coordinate
      attr_reader :latitude, :longitude
      attr_writer :latitude, :longitude

      def initialize(latitude, longitude)
        @latitude = latitude
        @longitude = longitude
      end

      def print_info
        puts "The coordinate has a latitude of #{latitude} and a longitude of #{longitude}."
      end
    end

    coordinate = Coordinate.new(41.881832, -87.623177)
    pp coordinate
    coordinate.print_info
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Coordinate {
      constructor(latitude, longitude) {
        this.latitude = latitude;
        this.longitude = longitude;
      }

      printInfo() {
        console.log(`The coordinate has a latitude of ${this.latitude} and a longitude of ${this.longitude}.`);
      }
    }

    var coordinate = new Coordinate(41.881832, -87.623177);
    console.log(coordinate);
    coordinate.printInfo();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Coordinate:
      def __init__(self, latitude, longitude):
        self.latitude = latitude
        self.longitude = longitude
        
      def print_info(self):
        print(f"The coordinate has a latitude of {self.latitude} and a longitude of {self.longitude}.")

    coordinate = Coordinate(41.881832, -87.623177)
    print(coordinate)
    coordinate.print_info()
    ```
    </details>

5. Write an Account class with attributes and reader/writer methods for name and balance.
   Then write a method that prints a warning if the balance is below $100.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Account
      attr_reader :name, :balance
      attr_writer :name, :balance

      def initialize(name, balance)
        @name = name
        @balance = balance
      end

      def warning
        if balance < 100
          puts "Warning: Your account balance is less than $100."
        end
      end
    end

    account = Account.new("Checking", 7000)
    pp account
    account.warning
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Account {
      constructor(name, balance) {
        this.name = name;
        this.balance = balance;
      }

      warning() {
        if (this.balance < 100) {
          console.log("Warning: Your account balance is less than $100.");
        }
      }
    }

    var account = new Account("Checking", 7000);
    console.log(account);
    account.warning();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Account:
      def __init__(self, name, balance):
        self.name = name
        self.balance = balance
        
      def warning(self):
        if self.balance < 100:
          print("Warning: Your account balance is less than $100.")

    account = Account("Checking", 70)
    print(account)
    account.warning()
    ```
    </details>

6. Write a Movie class with attributes and reader/writer methods for title, director, and year.
   Then write a method that prints out the attributes in a single sentence.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Movie
      attr_reader :title, :director, :year
      attr_writer :title, :director, :year

      def initialize(title, director, year)
        @title = title
        @director = director
        @year = year
      end

      def info
        puts "The movie #{title} was directed by #{director} and released in #{year}."
      end
    end

    movie = Movie.new("Kiss Kiss Bang Bang", "Shane Black", 2005)
    pp movie
    movie.info
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

      printInfo() {
        console.log(`The movie ${this.title} was directed by ${this.director} and released in ${this.year}.`);
      }
    }

    var movie = new Movie("Kiss Kiss Bang Bang", "Shane Black", 2005);
    console.log(movie);
    movie.printInfo();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Movie:
      def __init__(self, title, director, year):
        self.title = title
        self.director = director
        self.year = year
        
      def print_info(self):
        print(f"The movie {self.title} was directed by {self.director} and released in {self.year}.")

    movie = Movie("Kiss Kiss Bang Bang", "Shane Black", 2005)
    print(movie)
    movie.print_info()
    ```
    </details>

7. Write a Car class with attributes and reader/writer methods for make, model, year, and color. 
   Then write a method that returns the make and model as a single sentence in all lowercase letters.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Car
      attr_reader :make, :model, :year, :color
      attr_writer :make, :model, :year, :color

      def initialize(make, model, year, color)
        @make = make
        @model = model
        @year = year
        @color = color
      end

      def formatted_make_and_model
        "#{make} #{model}".downcase
      end
    end

    car = Car.new("Chevy", "Impala", 1958, "black")
    pp car
    puts car.formatted_make_and_model
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

      formattedMakeAndModel() {
        return `${this.make} ${this.model}`.toLowerCase();
      }
    }

    var car = new Car("Chevy", "Impala", 1958, "black");
    console.log(car);
    console.log(car.formattedMakeAndModel());
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
        
      def formatted_make_and_model(self):
        return f"{self.make} {self.model}".lower()

    car = Car("Chevy", "Impala", 1958, "black")
    print(car)
    print(car.formatted_make_and_model())
    ```
    </details>

8. Write a Point class with attributes and reader/writer methods for x, y, and z coordinates.
   Then write a method that returns true if all 3 numbers are positive, otherwise it returns false.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Point
      attr_reader :x, :y, :z
      attr_writer :x, :y, :z

      def initialize(x, y, z)
        @x = x
        @y = y
        @z = z
      end

      def check_positive
        x >=0 && y >= 0 && z >= 0
      end
    end

    point = Point.new(12, -5, 7)
    pp point
    puts point.check_positive
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

      checkPositive() {
        return this.x >= 0 && this.y >= 0 && this.z >= 0;
      }
    }

    var point = new Point(12, -5, 7);
    console.log(point);
    console.log(point.checkPositive());
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Point:
      def __init__(self, x, y, z):
        self.x = x
        self.y = y
        self.z = z
        
      def check_positive(self):
        return self.x >= 0 and self.y >= 0 and self.z >= 0

    point = Point(12, -5, 7)
    print(point)
    print(point.check_positive())
    ```
    </details>

9. Write a Book class with attributes and reader/writer methods for title, author, and year.
   Then write a method that returns "Classic" if the book is older than 2000, otherwise it returns "Modern".
    <details><summary>Ruby solution</summary>

    ```ruby
    class Book
      attr_reader :title, :author, :year
      attr_writer :title, :author, :year

      def initialize(title, author, year)
        @title = title
        @author = author
        @year = year
      end

      def category
        if year < 2000
          "Classic"
        else
          "Modern"
        end
      end
    end

    book = Book.new("Little Brother", "Cory Doctorow", 2008)
    pp book
    puts book.category
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

      category() {
        if (this.year < 2000) {
          return "Classic";
        } else {
          return "Modern";
        }
      }
    }

    var book = new Book("Little Brother", "Cory Doctorow", 2008);
    console.log(book);
    console.log(book.category());
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Book:
      def __init__(self, title, author, year):
        self.title = title
        self.author = author
        self.year = year
        
      def category(self):
        if self.year < 2000:
          return "Classic"
        else:
          return "Modern"

    book = Book("Little Brother", "Cory Doctorow", 2008)
    print(book)
    print(book.category())
    ```
    </details>

10. Write a Plant class with attributes and reader/writer methods for name, size, and price.
    Then write a method that prints out the attributes in a single sentence.
    <details><summary>Ruby solution</summary>

    ```ruby
    class Plant
      attr_reader :name, :size, :price
      attr_writer :name, :size, :price

      def initialize(name, size, price)
        @name = name
        @size = size
        @price = price
      end

      def print_info
        puts "Name: #{name}, Size: #{size}, Price: $#{price}"
      end
    end

    plant = Plant.new("Japanese Peace Lily", "large", 40)
    pp plant
    plant.print_info
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

      printInfo() {
        console.log(`Name: ${this.name}, Size: ${this.size}, Price: $${this.price}`);
      }
    }

    var plant = new Plant("Japanese Peace Lily", "large", 40);
    console.log(plant);
    plant.printInfo();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Plant:
      def __init__(self, name, size, price):
        self.name = name
        self.size = size
        self.price = price
        
      def print_info(self):
        print(f"Name: {self.name}, Size: {self.size}, Price: ${self.price}")

    plant = Plant("Japanese Peace Lily", "large", 40)
    print(plant)
    plant.print_info()
    ```
    </details>
