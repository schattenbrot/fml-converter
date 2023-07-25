# fml-converter
Takes json/yaml and converts it into a hard to maintanable folder structure

```json
{
  "user": {
    "name": "Uwuff",
     "age": 6
  },
  "produktId": 1
}
```

Gets converted to:

```
Main
  > user
    > name.txt (Uwuff)
    > age.txt (6)
  > productId
```
