**Multimedia Application for Stack Up** 

Description about the application features: - 

As we know stack up bounty is something different, here the task is to build two more features continue to the Quest-3 of the campaign 

The features I have added are: - 

a. Share,  
b. Search,  
c. Recycle Bin 



A. **Share feature: -** 

Here I added share feature, when you want to share it in email simply select the file and click share button after login in with your email you can share it through email.  

I only added email option to share not other features because since it is from our local storage, I don’t want to make a vulnerable and I'm still exploring the react js 

And, I added this feature because we always wanted to share this with our close people. 

In code, I created a separate component where when we select a particular file and select share button, we will open the existing email to share it. 

B. **Search Feature:** 

Here, we can search for the file we need. 

What if there is more than 500+ files, and we want to search a particular file we want then search option is the best thing 

I created a component called “search query” by using useState(), where it stores all the file, we uploaded by storing the unique id so that while searching it's easy to find it 

C. **Recycle Bin feature:**

Here, we added this feature because if anyone by mistake deleted an important file then by this recycle bin, they can restore it or delete it permanently. 

In code, I created a component snippet before the functional component where the recycle bin stores the deleted files by files id and when the user deletes it the by file id it will be in recycle bin and later, we can either delete it or restore it. 

