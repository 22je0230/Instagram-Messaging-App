# Instagram-Messaging-App- Firebase | Kotlin Coroutines | MVVM
Firebase Firestore Structure
    ```
 `     Collection: Users
           documentid: userid // the user who is loggedin
 
      Collection: Posts
           documentid: postid // a random id generated with the help of UUID
       
        each post has a field that contains the list as value, this list contains 
        the usersids of users who have liked the post. 
 
      Collection: Follow
             documentid: userid // the user who is loggedin
                   followingid: List of users I follow
      
      ```
I have used the following tech:
1)Navigation components
2)Kotlin coroutines
3)MVVM
4)Recyclerview
5)Firebase,Firestore, Firebasestorage

