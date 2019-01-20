# PettyJudgements
An experiment with Xcode source editor extensions that makes stupid 'petty judgements' about your source code. For example, using the 'Judge'
editor command will transform the following code:

```swift 
let 😜 = "hello world"

if 😜.count > 5 {
    if 😜.contains("hello") {
        if 😜 == "hello world" {
            
            print("i think you wrote hello")
            let x = 😜 as! [Character]
        }
    }
}
```

```swift
let 😜 /* you monster */  = "hello world"

if 😜 /* an emoji? AN EMOJI? */ .count > 5 {
    if 😜 /* you monster */ .contains("hello") {
        if 😜 /* an emoji? AN EMOJI? */  == "hello world" {
            
            print("i think you wrote hello")
            let x = 😜 /* an emoji? AN EMOJI? */  as! /* force unwrap, really? */  [Character]
        }
    }
}
```

Note: Obviously this is not meant at all seriously and should only be used as what it is - a complete joke. Having said that, PRs and improvements are always welcome!
