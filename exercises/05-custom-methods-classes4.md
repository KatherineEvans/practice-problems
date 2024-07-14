1. Write a ShoppingCart class that stores an array of items with methods to add an item, remove an item, and display all the items.  
    <details><summary>Ruby solution</summary>

    ```ruby
    class ShoppingCart
      def initialize
        @items = []
      end

      def add_item(item)
        @items.push(item)
      end

      def remove_item(item)
        @items.delete(item)
      end

      def display_items
        puts "Items in the shopping cart:"
        @items.each { |item| puts "- #{item}" }
      end
    end

    cart = ShoppingCart.new
    cart.add_item("Apple")
    cart.add_item("Banana")
    cart.add_item("Orange")
    cart.display_items
    cart.remove_item("Banana")
    cart.display_items
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class ShoppingCart {
      constructor() {
        this.items = [];
      }

      addItem(item) {
        this.items.push(item);
      }

      removeItem(item) {
        const index = this.items.indexOf(item);
        if (index > -1) {
          this.items.splice(index, 1);
        }
      }

      displayItems() {
        console.log("Items in the shopping cart:");
        this.items.forEach((item) => {
          console.log("- " + item);
        });
      }
    }

    const cart = new ShoppingCart();
    cart.addItem("Apple");
    cart.addItem("Banana");
    cart.addItem("Orange");
    cart.displayItems();
    cart.removeItem("Banana");
    cart.displayItems();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class ShoppingCart:
        def __init__(self):
            self.items = []

        def add_item(self, item):
            self.items.append(item)

        def remove_item(self, item):
            if item in self.items:
                self.items.remove(item)

        def display_items(self):
            print("Items in the shopping cart:")
            for item in self.items:
                print("- " + item)

    cart = ShoppingCart()
    cart.add_item("Apple")
    cart.add_item("Banana")
    cart.add_item("Orange")
    cart.display_items()
    cart.remove_item("Banana")
    cart.display_items()
    ```
    </details>

2. Write a Product class that stores the name, price, and metadata, where metadata is a hash that stores additional information about the product. 
    <details><summary>Ruby solution</summary>

    ```ruby
    class Product
      attr_reader :name, :price, :metadata
      attr_writer :name, :price, :metadata

      def initialize(name, price, metadata)
        @name = name
        @price = price
        @metadata = metadata
      end
    end

    product = Product.new("Smartphone", 499.99, { brand: "Apple", color: "Silver" })
    puts "Product Details:"
    puts "Name: #{product.name}"
    puts "Price: $#{product.price}"
    puts "Metadata: #{product.metadata}"
    puts "Brand: #{product.metadata[:brand]}"
    puts "Color: #{product.metadata[:color]}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Product {
      constructor(name, price, metadata) {
        this.name = name;
        this.price = price;
        this.metadata = metadata;
      }
    }

    const product = new Product("Smartphone", 499.99, { brand: "Apple", color: "Silver" });
    console.log("Product Details:");
    console.log(`Name: ${product.name}`);
    console.log(`Price: $${product.price}`);
    console.log(`Metadata: ${product.metadata}`);
    console.log(`Brand: ${product.metadata.brand}`);
    console.log(`Color: ${product.metadata.color}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Product:
        def __init__(self, name, price, metadata):
            self.name = name
            self.price = price
            self.metadata = metadata

    product = Product("Smartphone", 499.99, { "brand": "Apple", "color": "Silver" })
    print("Product Details:")
    print(f"Name: {product.name}")
    print(f"Price: ${product.price}")
    print(f"Metadata: {product.metadata}")
    print(f"Brand: {product.metadata['brand']}")
    print(f"Color: {product.metadata['color']}")
    ```
    </details>

3. Write a Playlist class that stores a name and an array of songs with methods to add a song, remove a song, shuffle the songs into a random order, and display all the songs.  
    <details><summary>Ruby solution</summary>

    ```ruby
    class Playlist
      def initialize(name)
        @name = name
        @songs = []
      end

      def add_song(song)
        @songs << song
      end

      def remove_song(song)
        @songs.delete(song)
      end

      def shuffle
        @songs.shuffle!
      end

      def display_playlist
        puts "Playlist: #{@name}"
        puts "Songs in the playlist:"
        @songs.each { |song| puts "- #{song}" }
      end
    end

    playlist = Playlist.new("My Playlist")
    playlist.add_song("Song 1")
    playlist.add_song("Song 2")
    playlist.add_song("Song 3")
    playlist.display_playlist
    playlist.remove_song("Song 2")
    playlist.display_playlist
    playlist.shuffle
    playlist.display_playlist
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Playlist {
      constructor(name) {
        this.name = name;
        this.songs = [];
      }

      addSong(song) {
        this.songs.push(song);
      }

      removeSong(song) {
        const index = this.songs.indexOf(song);
        if (index > -1) {
          this.songs.splice(index, 1);
        }
      }

      shuffle() {
        for (let i = this.songs.length - 1; i > 0; i--) {
          const j = Math.floor(Math.random() * (i + 1));
          [this.songs[i], this.songs[j]] = [this.songs[j], this.songs[i]];
        }
      }

      displayPlaylist() {
        console.log(`Playlist: ${this.name}`);
        console.log("Songs in the playlist:");
        this.songs.forEach((song) => {
          console.log("- " + song);
        });
      }
    }

    const playlist = new Playlist("My Playlist");
    playlist.addSong("Song 1");
    playlist.addSong("Song 2");
    playlist.addSong("Song 3");
    playlist.displayPlaylist();
    playlist.removeSong("Song 2");
    playlist.displayPlaylist();
    playlist.shuffle();
    playlist.displayPlaylist();
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    import random

    class Playlist:
        def __init__(self, name):
            self.name = name
            self.songs = []

        def add_song(self, song):
            self.songs.append(song)

        def remove_song(self, song):
            if song in self.songs:
                self.songs.remove(song)

        def shuffle(self):
            random.shuffle(self.songs)

        def display_playlist(self):
            print(f"Playlist: {self.name}")
            print("Songs in the playlist:")
            for song in self.songs:
                print("- " + song)

    playlist = Playlist("My Playlist")
    playlist.add_song("Song 1")
    playlist.add_song("Song 2")
    playlist.add_song("Song 3")
    playlist.display_playlist()
    playlist.remove_song("Song 2")
    playlist.display_playlist()
    playlist.shuffle()
    playlist.display_playlist()
    ```
    </details>

4. Write a Contact class that stores the name, age, and contact_info, where contact_info is a hash that stores any additional information about the contact. 
    <details><summary>Ruby solution</summary>

    ```ruby
    class Person
      attr_reader :name, :age, :contact_info

      def initialize(name, age, contact_info)
        @name = name
        @age = age
        @contact_info = contact_info
      end
    end

    person = Person.new("John Doe", 30, { phone: "123-456-7890", email: "john@example.com" })
    puts "Person Details:"
    puts "Name: #{person.name}"
    puts "Age: #{person.age}"
    puts "Contact Info: #{person.contact_info}"
    puts "Phone: #{person.contact_info[:phone]}"
    puts "Email: #{person.contact_info[:email]}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    class Person {
      constructor(name, age, contactInfo) {
        this.name = name;
        this.age = age;
        this.contactInfo = contactInfo;
      }
    }

    const person = new Person("John Doe", 30, { phone: "123-456-7890", email: "john@example.com" });

    console.log("Person Details:");
    console.log(`Name: ${person.name}`);
    console.log(`Age: ${person.age}`);
    console.log(`Contact Info: ${person.contactInfo}`);
    console.log(`Phone: ${person.contactInfo.phone}`);
    console.log(`Email: ${person.contactInfo.email}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    class Person:
        def __init__(self, name, age, contact_info):
            self.name = name
            self.age = age
            self.contact_info = contact_info

    person = Person("John Doe", 30, { "phone": "123-456-7890", "email": "john@example.com" })

    print("Person Details:")
    print(f"Name: {person.name}")
    print(f"Age: {person.age}")
    print(f"Contact Info: {person.contact_info}")
    print(f"Phone: {person.contact_info['phone']}")
    print(f"Email: {person.contact_info['email']}")
    ```
    </details>
