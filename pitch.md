# Why do I keep getting "Thread 1: Fatal error: Unexpectedly found nil while unwrapping an Optional value" ?! Aren't Swift supposed to be easy?



You set out to learn how to program iOS apps, you downloaded Xcode and followed several online tutorials to learn iOS development and it seems to go well with the tutorials. But once you start coding on your own, you start noticing some weird looking symbols like :

1. **nameLabel: UILabel!**
2. **as! PersonTableViewCell** 
3. **name: String?**



It doesn't seem like a big deal until your app crashes and you are greeted with the scary "**Fatal error: Unexpectedly found nil while unwrapping an Optional value**" : 

![classicError](pitch_img/classicError.png)



You asked online and some people suggested using **if let** and **guard let** to prevent the crash, but what does these mean?! Some suggested to never use the "**!**" symbol in code but Xcode complains when you don't do so : 

![mustBeUnwrapped](pitch_img/mustBeUnwrapped.png)



You Googled online, found some articles which provide fixes, but you still don't understand why those fixes work , and you're back to square one the next time you are greeted with the same "Fatal error: Unexpectedly found nil" error again. Worse, some of those article are outdated and the Swift syntax is different and you end up with more errors.



And after a while, you just give up and use the "Fix" button provided by Xcode to make the error go away : 

![autoFix](pitch_img/autoFix.png)



Wouldn't it be good if those funky symbols ("?", "!") doesn't exist? Instead of spending hours fighting with errors, you could focus on the fun part - building features for your app! Unfortunately, optionals are there in Swift, and with good reason, there's no way to avoid it, but we can understand it, be friend with it and use it to our advantage when building features!



## What if you could focus on the fun part - building features ?

What if you are able to navigate through the symbols (**?** , **!** , **as!** ) easily? You could save hours trying to wrap your head around the errors and focus on your code. Imagine being able to indulge in building features you like and see the result appear in your phone, wouldn't that be great? 



You could finish the app idea that you have been wanting to work on, **submit it to the App Store**, and have a better resume for applying iOS developer positions.



## Understand how and why Optionals works and use it to your advantage





