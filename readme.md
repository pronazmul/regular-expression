<p align="center"><a href="http://pronazmul.com" target="_blank"><img src="https://i.ibb.co/BZcrznf/featured.png" width="300"></a></p>

## Expression To check Name
>Conditions:
* Only Uppercase, LowerCase & Spaces Are allowed
* Length Should be between 5 to 20

```sh
Expression = /^([a-zA-Z ]){5,20}$/

Check:
if(!Expression.test(data)){
      alert("invalid Data")
   }
```
