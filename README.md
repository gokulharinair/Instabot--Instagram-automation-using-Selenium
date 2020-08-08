# Instabot--Instagram-automation-using-Selenium

## This project has been created using Python and Selenium. 
## All the functions used for this project have been defined under the class named my_bot. 
## A sample working of the code has been showed in the provided notebook.

## The functions which are defined and used are:

### 1) __init__ (also called constructor in oops terminology): 
#### This gets called when an object is created from class my_bot and allows my_bot to initialise its attributes. Here you can pass in your user name and password ( as shown in the code file) so as to open your instagram account.

### 2) searchword: 
#### This function searches for instagram ids related to the name asked by it which gets searched for in the search bar and returns the related ids that appear in the dialog box.

### 3) openingprofile_andfollow:
#### This function asks for the instagram id of the person to be followed and works with the help of a helper function, followed_or_not. After the required action has beeen taken, the user will be returned back to home page.

### 3.1) followed_or_not:
#### After the required insta id has been provided to the above function, this helper function first checks if the account has already been followed or not. If not followed, the account gets followed and a message regarding the same is generated. If already followed, a suitable message is generated.

### 4) openingprofile_andunfollow:
#### This function asks for the instagram id of the person to be unfollowed and works with the help of a helper function, unfollowed_or_not. After the required action has beeen taken, the user will be returned back to home page.

### 4.1) unfollowed_or_not:
#### After the required insta id has been provided to the above function, this helper function first checks if the account has already been unfollowed or not. If not unfollowed, the account gets unfollowed and a message regarding the same is generated. If already unfollowed, a suitable message is generated.

### 5) openingprofile:
#### This function simply opens the profile of the instagram id that has been asked by it.

### 6) likeposts:
#### This function should be performed only after carrying out function 5). This function askes how many of the top photos are to be liked. While performing the task, it checks if the photo has already been liked or not. If it is already liked, it won't carry out the task and move to the next image.

### 7) unlikeposts:
#### This function should be performed only after carrying out function 5). This function askes how many of the top photos are to be disliked. While performing the task, it checks if the photo has already been disliked or not. If it is already disliked, it won't carry out the task and move to the next image.

### 8) story_status:
#### This function should be performed only after carrying out function 5). This function checks if the story has been viewed already or not, or if a story exists at all. If a story exists and has not been viewed already, the story gets viewed. According the the scenario, a message is also generated.

### 9) recentfollowers:
#### Returns the instagram ids of the followers who have followed a particular account recently. Should be performed only after funstion 5).

### 10) public_or_not:
#### Checks if an account is public or not (Note: USE THIS FUNCTION TO CHECK FOR THOSE PROFILES THAT YOU DO NOT FOLLOW)

### 11) followed_account_public_or_not:
#### Works in the same way as above function, except that this works only on profiles that you follow.

### 12) backtohomepage:
#### Returns back to home page.

### The above functions have been constructed according to my knowleadge regarding selenium and the internet connectivity in my area. If any modifications can be done in the above functions, please let me. Your feedback will be valuable to me. Thank You!
