# Android Templates 

To add template to android studio [link](https://codingwithmitch.com/blog/kotlin-recyclerview-template/) :

File > Settings > Select "File and Code Templates" > Create a new template:

--------------------------------------------
##   RecyclerView Adapter Templates

As Android Developers, we all use RecyclerView's. And the process of setting up any RecyclerView is mostly the same.

    You build a model for the data
    Create a layout for each list item
    Build a RecyclerView.Adapter
    Initialize the RecyclerView in your activity/fragment

I'm going to give you a template you can add to your Android Studio so creating a RecyclerView Adapter can be done in a few clicks.

#### 1- RecyclerAdapter
This template use the powerful of DiffUtil & AsyncListDiffer class to update the list

DiffUtil: is a utility class that can calculate the difference between two lists and output a list of update operations that converts the first list into the second one. DiffUtils is based on Eugene Myers’ algorithm.

Note: Use this template to create adapter with custom submitList() method

This template developed by [CodingWithMitch](https://codingwithmitch.com/blog/kotlin-recyclerview-template/) ,
I'm just add new method addItems

#### 2-RecyclerListAdapter
This template use the powerful of [ListAdapter<T, VH> ](https://developer.android.com/reference/android/support/v7/recyclerview/extensions/ListAdapter) 

------------------------------------------
