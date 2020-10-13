# RoomDatabaseExample - Part 4

## Tasks
1) Create a simple Input Dialog with DialogFragment

    1.1) Modify the **style.xml**

    1.2) Create layout file - **dialog_input.xml**
    
    1.3) Create DialogFragment() - **DialogInput.kt**
    
    1.4) Save User Input to MainViewModel with fun **insert(voc:Voc)**
 <p align="center">   
<img src="https://github.com/ChrisRoh92/RoomDatabaseExample/blob/Part_4/screenshot/InputDialog.PNG?raw=true" width=400>
</p>

2) Register Observer on the VocList LiveData and Update VocListAdapter
    
    2.1) Create MainViewModel Instance
    
    2.2) Update VocListAdapter with method **fun updateContent(..)** and change ArrayList Type from **String** to **Voc**
    
    2.3) Override ***OnBindViewHolder(...)*** @ **VocListAdapter.kt**
    
    2.4) Implement Observer

## Solution
