# Day 57

Joined the Serverless MN meetup with guest speaker and AWS Data Hero, [Alex Debrie](https://twitter.com/alexbdebrie), talking about Single-Table Design in DynamoDB and five strategies to one-to-many relationships.

Tips:
- know your access patterns in advance
- get comfortable with denormalization

### How to do one-to-many relationships:

There are five strategies:
1. denormalization + complex attribute
good when: no access pattern on related items directly; limited number of related items (400kb limit)
2. denormalization with duplication
good when: duplicated data is immutable; duplicated data doesn't change often or is not replicated much
3. composite primary key + query
4. secondary index + query
5. composite sort key
good when: multiple (>2) evels of hierarchy; when searching a level in hierarchy, you want all sub-items

# Resources

- [Alex Debrie](https://twitter.com/alexbdebrie)
- [Understanding Single-Table Design in DynamoDB @ Serverless MN](https://www.meetup.com/Serverless-MN/events/273463018/)
- [Serverless MN](https://twitter.com/ServerlessMN)

# Social proof

[The tweet]()
