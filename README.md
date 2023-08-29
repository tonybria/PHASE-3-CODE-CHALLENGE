## PHASE-3-CODE-CHALLENGE: Object Relations - Restaurants
This README provides an overview of the PHASE-3-CODE-CHALLENGE related to Object Relations, focusing on the interactions between three models: Restaurant, Customer, and Review. The challenge involves implementing various methods to manage these relationships and functionalities.

## Models
Restaurant
Customer
Review

## Relationships
 1. A Restaurant has many Reviews
2. A Customer has many Reviews
3. A Review belongs to a Customer and a Restaurant
4. Restaurant - Customer relationship is many-to-many

## Topics Covered
Classes and Instances

Class and Instance Methods

Variable Scope

Object Relationships

Lists and List Methods

## Deliverables

## Initializers, Readers, and Writers

Customer
__init__(self, given_name, family_name)
given_name(self) - Returns customer's given name.
family_name(self) - Returns customer's family name.
full_name(self) - Returns full name (given name + family name).
all(cls) - Returns all customer instances.
Restaurant
__init__(self, name)
name(self) - Returns restaurant's name.
Review
__init__(self, customer, restaurant, rating)
rating(self) - Returns the review's rating.
all(cls) - Returns all reviews.
Object Relationship Methods
## Review
customer(self) - Returns the customer object for the review.
restaurant(self) - Returns the restaurant object for the review.

## Restaurant
reviews(self) - Returns a list of reviews for the restaurant.
customers(self) - Returns a unique list of customers who reviewed the restaurant.

## Customer
restaurants(self) - Returns a unique list of restaurants reviewed by the customer.
add_review(cls, restaurant, rating) - Creates a new review associated with the customer and restaurant.

## AGGREGATE AND ASSOCIATION METHODS 
## Customer
num_reviews(self) - Returns the total number of reviews by the customer.
find_by_name(cls, name) - Returns the first customer with a matching full name.
find_all_by_given_name(cls, name) - Returns a list of customers with a given name.
## Restaurant
average_star_rating(self) - Returns the average star rating based on reviews.
## Python Version
Python version used: 3.10






