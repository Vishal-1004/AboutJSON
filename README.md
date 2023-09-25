# JSON (JavaScript Object Notation)

`Lightweight data interchange format`

It is a text-based format that is easy for humans to read and write and easy for machines to parse and generate.
JSON is often used for data exchange between a server and a web application, as well as for configuration files, logging, and various other purposes in software development.

JSON is structured as a collection of **_key-value pairs_**, where each key is a **_string enclosed in double quotes_** and **_followed by a colon_**
and the corresponding value can be:

- string
- number
- boolean
- null
- object
- array

## Example

```
{
  "name": "John Doe",
  "age": 30,
  "isStudent": false,
  "hobbies": ["reading", "swimming", "coding"]
}
```

## Note

You can store this JSON in any variable as follows:
myJson = {
"name": "John Doe",
"age": 30,
"isStudent": false,
"hobbies": ["reading", "swimming", "coding"]
}

Now in order to access the values of this we need to do the following:

```
parsed = JSON.parse(myJson);
```

Once done with parsing then we can do the following to access each element of this json:

```
console.log(parsed["name"])
// John Doe

console.log(parsed["age"])
// 30

console.log(parsed["hobbies"][1])
// swimming
```

**_ For more uunderstanding check out the first.json and firstImg.json files _**
