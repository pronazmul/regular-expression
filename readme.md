<p align="center"><a href="http://pronazmul.com" target="_blank"><img src="https://i.ibb.co/BZcrznf/featured.png" width="600"></a></p>

## Expression To check Name
>Conditions:
* Only Uppercase, LowerCase & Spaces Are allowed
* Length Should be between 5 to 20

```sh
Expression = /^([a-zA-Z ]){5,20}$/

Check:
if(!Expression.test(name)){
      alert("invalid Name")
   }
```

## Expression To check Email
>Conditions:
* Required Special Char: @ . 
* Required tex@text.text

```sh
Expression = /\S+@\S+\.\S+/

Check:
if(!Expression.test(email)){
      alert("invalid email")
   }
```
