## Immutable

Immutable is a library that provides immutable data structures. Immutable data structures are data structures that cannot be changed once they are created. This makes them much safer to use than mutable data structures, as there is no chance of accidentally changing data that you don't want to change.

Immutable is a very powerful library, and it can be used to create very efficient and performant code. However, it can also be a bit difficult to learn, as it takes some time to get used to the immutable paradigm.

In this tutorial, we will learn how to use Immutable to create immutable data structures. We will also learn how to use Immutable to perform common data manipulation operations, such as filtering, sorting, and mapping.

## Getting Started

To get started with Immutable, you will need to install the library. You can do this by running the following command in your terminal:

```
npm install immutable
```

Once the library is installed, you can start using it in your code.

## Creating Immutable Data Structures

The most basic immutable data structure is the `Map`. A `Map` is a collection of key-value pairs. To create a `Map`, you can use the `Map()` constructor. For example:

```
const map = new Map();
```

You can then add key-value pairs to the `Map` by using the `set()` method. For example:

```
map.set('key1', 'value1');
map.set('key2', 'value2');
```

You can also get the value of a key from the `Map` by using the `get()` method. For example:

```
const value1 = map.get('key1');
```

## Filtering Immutable Data Structures

You can filter an immutable data structure by using the `filter()` method. The `filter()` method takes a function as its argument. The function should return a boolean value. If the function returns `true`, then the item will be included in the filtered data structure. If the function returns `false`, then the item will be excluded from the filtered data structure.

For example, the following code filters a `Map` of students by their score:

```
const students = new Map();
students.set('John', 90);
students.set('Jane', 80);