# TeamCity VS Jenkins


### TeamCity and Jenkins are two of the most used CI’s out there, and having used both of them I have a pretty solid idea of the pros and cons of each one and I’ll list some of them in this post according to my experience using both products.

- Jenkins:

```
Jenkins was the first CI I’ve used and I must admit is a really good product, even more when you think that is an open source project and you don’t have to pay anything to use it.

Pros:

Very easy to use.
Backed up by a huge community.
Lots of plugins to choose from.
Open source.

Cons:

Some server instability (at least when installed in a windows machine).
Outdated interface.
Node js plugin doesn’t work on windows machine installations yet (This was the main reason for me to start using TeamCity 🙂 )
So if your an opensource enthusiast this might be the right tool for you. It’s a very mature product with lots of plugins providing all the heavy lifting for you and an enormous community to help you as well.

```
 

- TeamCity:

``` 
tc

TeamCity developed by JetBrains is the CI I now use the most. Although the reason for me to start using TeamCity wasn’t at first related to its features, I’m glad I choose to use TeamCity. The simplicity and ease of usage caught my attention from the first day.

Although being a commercial product, meaning you have to pay for it, you have 20 builds and 3 free agent installations, which should be enough for you to start using it and show the business guys how awesome it is, so you can ask for the license purchase :). Also, if you work on a startup you get 50% discount, and if you’re working on an open source project the license is free.

Pros:

Very easy to install and maintain.
Lots of plugins to choose from.
Multi-platform builds.
Excellent backup functionality.
Excellent source control support.

Cons:

Free edition limited to 20 builds.
Built in Java, meaning that if you want to create your own plugin you have to know java.
 
``` 

Having used both of them, and still use them both in my current company, I tend to prefer TeamCity over Jenkins mainly because TeamCity is so easy to use and it behaves better under node js deployments, which gives it a bit of an edge over Jenkins, not to mention the ancient Jenkins interface :).

But don’t understand me wrong, Jenkins is an awesome CI and should be always considered as a viable option.
