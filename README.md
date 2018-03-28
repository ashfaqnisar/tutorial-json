# tutorial-json

## About

tutorial-json is a tutorial about how to write and read JSON files, in order to write your own databases and access other databases.

This tutorial was written by [Aarón Montoya-Moraga](http://montoyamoraga.io/). If you want to check out more tutorials, visit [http://montoyamoraga.io/education](http://montoyamoraga.io/education).

It is also available in [Spanish](link). It is written in [Markdown](https://en.wikipedia.org/wiki/Markdown) and hosted in [GitHub](https://github.com/).

## Introduction

JSON is a syntax for storing data.

It can be easily parsed by JavaScript, and it is heavily used in databases for this same reason.

The syntax of a JSON object can be summarized as follows:

* Data is organized in key/value pairs.
* Keys are Strings, written inside double quotes ""
* Values can be a String, a number, a JSON Object, an array, a boolean, null.
* Data is separated by commas.
* Curly braces {} store objects
* Square brackets [] store arrays
* The file extension is .json

## Writing your own JSON file

This is the simplest JSON file you can write.

It has one key/value between curly braces {}.

```json
{
  "key": "value"
}
```

Let's add more key/value pairs, making sure to add commas, and not using one after the last pair.

```json
{
  "key": "value",
  "otherKey": "otherValue",
  "lastKey": "lastValue"
}
```
Let's add other types of values

```json
{
  "key": "value",
  "otherKey": "otherValue",
  "aNumber": 38.0,
  "aBoolean": false,
  "null": null,
  "lastKey": "lastValue"
}
```

## Typical mistakes

* Using keys that are not strings.
* Using single quotes instead of double quotes.
* Unmatched curly braces or square brackets.
* Missing a comma after each key/value pair.
* Using a comma after the last key/value pair.

## JSON and JavaScript

```javascript
//this returns a JavaScript object
JSON.parse()
```

## Projects that work with JSON files.

## Auxiliary files

This repository contains examples in:

* Processing
* p5.js

## References

* [JSON syntax](https://www.w3schools.com/js/js_json_syntax.asp)
* [JSON validator](https://jsonlint.com/)

## Thanks

* Jen Kagan, for inspiring me with her beautiful work [https://whatisit.tech/](https://whatisit.tech/).
