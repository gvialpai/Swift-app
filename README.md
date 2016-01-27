# Swift-app Step By Step Process

1. Creating a Multi Page App and seeing the pros and cons. The reason is that the first page is a multi-page one -> Deleting it

2. Deciding to go with a Single Page app as most tutorials advise it and following the Apple tutorial (ttps://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson2.html#//apple_ref/doc/uid/TP40015214-CH5-SW1). After completion, I am submitting my first commit.

3. After some Google Search, I found a good tutorial for scrollable pages for first landing page. https://www.youtube.com/watch?v=8bltsDG2ENQ

4. I faced a compatibility issue based on the previous tutorial as Swift has evolved since then. After some Google search, I found a way to correct it: http://stackoverflow.com/questions/33443549/how-to-properly-advance-a-pageviewcontroller-in-swift. Once Found I submit my second commit

5. Page Up and Running: Third Commit

6. Creation of the first page of tutorial: Fourth Commit

7. I realized that I forgot to add the interface to prompt the user to disclose if a carer is around. After creation, fifth commit.

8. Once the page is created, I link it to the previous page and do my sixth commit.

9. I check if the page is working and then I create a new page to redirect the users if they are not meant to use the app

10. I link the tutorial page if the user has dementia and a carer.

11. I create the page in which I prompt the carer to disclose his/her first name.

12. I create a new view with an age picker.

13. I implement the code found with this tutorial (http://codewithchris.com/uipickerview-example/). There is a conflict on 
```
//        self.picker.delegate = self
//        self.picker.dataSource = self
```

as self has been previously used for defining the multi-view page on page 1 and is rejected at the end of the function. I comment this expression out to resolve conflicts, the feature is therefore not up and running.