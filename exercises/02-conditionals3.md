1. Write a program that stores a customer's age and a movie's time in two separate variables.
   Then calculate the price of a movie ticket based on the following conditions:
   - If the age is 12 years old or younger, the ticket price is $5.
   - If the age is between 13 and 59 years old and the movie is before 6 PM, the ticket price is $7. After 6 PM, the ticket price is $10.
   - If the customer is 60 years old or older, the ticket price is $7.
    <details><summary>Ruby solution</summary>

    ```ruby
    age = 50
    time = 12
    if age <= 12
      ticket_price = 5
    elsif age >= 13 && age <= 59
      if time < 18
        ticket_price = 7
      else
        ticket_price = 10
      end
    elsif age >= 60
      ticket_price = 7
    end

    puts "Ticket price: $#{ticket_price}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var age = 50;
    var time = 12;
    var ticketPrice;

    if (age <= 12) {
      ticketPrice = 5;
    } else if (age >= 13 && age <= 59) {
      if (time < 18) {
        ticketPrice = 7;
      } else {
        ticketPrice = 10;
      }
    } else if (age >= 60) {
      ticketPrice = 7;
    }

    console.log(`Ticket price: $${ticketPrice}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    age = 50
    time = 12
    ticket_price = None

    if age <= 12:
        ticket_price = 5
    elif age >= 13 and age <= 59:
        if time < 18:
            ticket_price = 7
        else:
            ticket_price = 10
    elif age >= 60:
        ticket_price = 7

    print("Ticket price: $" + str(ticket_price))
    ```
    </details>

2. Write a program to store the type of book (regular, reference, or special collection) and the number of days its overdue. 
   Then calculate the fine amount based on the following conditions:
   - If the book is a regular book and overdue by up to 7 days, the fine is $1 per day.
   - If the book is a regular book and overdue by more than 7 days, the fine is $2 per day. 
   - If the book is a reference book, there is no fine, regardless of the number of days overdue.
   - If the book is a special collection book, the fine is $5 per day, regardless of the number of days overdue.

    <details><summary>Ruby solution</summary>

    ```ruby
    days_overdue = 10
    book_type = "regular"

    fine_amount = 0
    if book_type == "regular"
      if days_overdue <= 7
        fine_amount = days_overdue * 1
      else
        fine_amount = days_overdue * 2
      end
    elsif book_type == "reference"
      fine_amount = 0
    elsif book_type == "special collection"
      fine_amount = days_overdue * 5
    end

    puts "Fine amount: $#{fine_amount}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var days_overdue = 10;
    var book_type = "regular";

    var fineAmount = 0;
    if (book_type === "regular") {
      if (days_overdue <= 7) {
        fineAmount = days_overdue * 1;
      } else {
        fineAmount = days_overdue * 2;
      }
    } else if (book_type === "reference") {
      fineAmount = 0;
    } else if (book_type === "special collection") {
      fineAmount = days_overdue * 5;
    }

    console.log(`Fine amount: $${fineAmount}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    days_overdue = 10
    book_type = "regular"

    fine_amount = 0
    if book_type == "regular":
        if days_overdue <= 7:
            fine_amount = days_overdue * 1
        else:
            fine_amount = days_overdue * 2
    elif book_type == "reference":
        fine_amount = 0
    elif book_type == "special collection":
        fine_amount = days_overdue * 5

    print("Fine amount: $" + str(fine_amount))
    ```
    </details>

3. Write a program that stores a person's order value and membership level (regular or premium). Then calculate a discount amount based on the following conditions:
   - If the total order value is less than $50, there is no discount.
   - If the total order value is between $50 and $100, the discount is 5% for regular customers and 10% for premium customers.
   - If the total order value is greater than $100, the discount is 10% for regular customers and 15% for premium customers.

    <details><summary>Ruby solution</summary>

    ```ruby
    order_value = 200
    membership_level = "regular"

    discount_amount = 0
    if order_value < 50
      discount_amount = 0
    elsif order_value >= 50 && order_value <= 100
      if membership_level == "regular"
        discount_amount = order_value * 0.05
      elsif membership_level == "premium"
        discount_amount = order_value * 0.10
      end
    elsif order_value > 100
      if membership_level == "regular"
        discount_amount = order_value * 0.10
      elsif membership_level == "premium"
        discount_amount = order_value * 0.15
      end
    end

    puts "Discount amount: $#{discount_amount}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var orderValue = 200;
    var membershipLevel = "regular";

    var discountAmount = 0;
    if (orderValue < 50) {
      discountAmount = 0;
    } else if (orderValue >= 50 && orderValue <= 100) {
      if (membershipLevel === "regular") {
        discountAmount = orderValue * 0.05;
      } else if (membershipLevel === "premium") {
        discountAmount = orderValue * 0.10;
      }
    } else if (orderValue > 100) {
      if (membershipLevel === "regular") {
        discountAmount = orderValue * 0.10;
      } else if (membershipLevel === "premium") {
        discountAmount = orderValue * 0.15;
      }
    }

    console.log(`Discount amount: $${discountAmount}`);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    order_value = 200
    membership_level = "regular"

    discount_amount = 0
    if order_value < 50:
        discount_amount = 0
    elif order_value >= 50 and order_value <= 100:
        if membership_level == "regular":
            discount_amount = order_value * 0.05
        elif membership_level == "premium":
            discount_amount = order_value * 0.10
    elif order_value > 100:
        if membership_level == "regular":
            discount_amount = order_value * 0.10
        elif membership_level == "premium":
            discount_amount = order_value * 0.15

    print("Discount amount: $" + str(discount_amount))
    ```
    </details>

4. Write a Ruby program that stores the weight of a package and the destination (domestic or international). Then calculate the shipping fee based on the following conditions:

    - If the destination is domestic:
      - If the weight is less than or equal to 1 kg, the shipping fee is $5.
      - If the weight is greater than 1 kg, the shipping fee is $10.
    - If the destination is an international shipment:
      - If the weight is less than or equal to 1 kg, the shipping fee is $15.
      - If the weight is greater than 1 kg, the shipping fee is $25.
    <details><summary>Ruby solution</summary>

    ```ruby
    destination = "domestic"
    weight = 4

    shipping_fee = 0
    if destination == "domestic"
      if weight <= 1
        shipping_fee = 5
      else
        shipping_fee = 10
      end
    elsif destination == "international"
      if weight <= 1
        shipping_fee = 15
      else
        shipping_fee = 25
      end
    end

    puts "Shipping fee: $#{shipping_fee}"
    ```
    </details>

    <details><summary>JavaScript solution</summary>

    ```js
    var destination = "domestic";
    var weight = 4;

    var shippingFee = 0;
    if (destination === "domestic") {
      if (weight <= 1) {
        shippingFee = 5;
      } else {
        shippingFee = 10;
      }
    } else if (destination === "international") {
      if (weight <= 1) {
        shippingFee = 15;
      } else {
        shippingFee = 25;
      }
    }

    console.log("Shipping fee: $" + shippingFee);
    ```
    </details>
    
    <details><summary>Python solution</summary>

    ```python
    destination = "domestic"
    weight = 4

    shipping_fee = 0
    if destination == "domestic":
        if weight <= 1:
            shipping_fee = 5
        else:
            shipping_fee = 10
    elif destination == "international":
        if weight <= 1:
            shipping_fee = 15
        else:
            shipping_fee = 25

    print("Shipping fee: $" + str(shipping_fee))
    ```
    </details>
