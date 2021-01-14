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

## Expression To check Password
>Conditions:
* Required Number, Uppercase, Lowercase & Special char
* Length Must be 6 to 15 

```sh
Expression = /^(?=.*[0-9])(?=(?:[^A-Z]*[A-Z]){1})(?=.*[!@#$%^&*])[a-zA-Z0-9!@#$%^&*]{6,15}$/

Check:
if(!Expression.test(password)){
      alert("invalid password")
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
## Expression To Validate Image Extention
>Conditions:
* Required only number
* Length Must be 2 to 12

```sh
Expression = /\.(jpg|jpeg|png|gif)$/

Check:
if(!Expression.test(Image_Extension)){
      alert("invalid Image")
   }
```

## Expression To check Number & Set Number Range
>Conditions:
* Firstly Separate Image Extension.
* Chek Image Extention jpg, jpeg, png, gif.

```sh
Expression = /\.(jpg|jpeg|png|gif)$/

Check:
if(!Expression.test(Image_Extension)){
      alert("invalid Image")
   }
```
