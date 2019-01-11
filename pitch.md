# Aren't Swift supposed to be easy? Why do I keep getting "Thread 1: Fatal error: Unexpectedly found nil while unwrapping an Optional value" ?!



You set out to learn how to program iOS apps, you downloaded Xcode and followed several online tutorials to learn iOS development and it seems to go well with the tutorials. But once you start coding on your own, you start noticing some weird looking symbols like :

1. **nameLabel: UILabel!**
2. **as! PersonTableViewCell** 
3. **name: String?**



It doesn't seem like a big deal until your app crashes and you are greeted with the scary "**Fatal error: Unexpectedly found nil while unwrapping an Optional value**" : 

![classicError](pitch_img/classicError.png)



You asked online and some people suggested using **if let** and **guard let** to prevent the crash, but what does these mean?! Some suggested to never use the "**!**" symbol in code but Xcode complains when you don't do so : 

![mustBeUnwrapped](pitch_img/mustBeUnwrapped.png)



You Googled online, found some articles which provide fixes, but you still don't understand why those fixes work , and you're back to square one the next time you are greeted with the same "Fatal error: Unexpectedly found nil" error again. Worse, some of those article are outdated and the Swift syntax is different and you end up with more errors.



And after a while, you just gave up and use the "Fix" button provided by Xcode to make the error go away : 

![autoFix](pitch_img/autoFix.png)





