# Defect Number 1
**Description**

    System allows to do list item to be empty when updating it with a NULL value

**Expected Behavior** - An Error displayed **" Item Can not be empty"**

**Current Behavior** - The field is updated with an empty item 

**Steps**
- Enter New Item in the list
- Click Update button next to the newly added item without inserting any value/text on the field

# Defect Number 2

**Description**

    No pop up message when updating the item to confirm if the user is sure that they wanna update the item to (value123) from (Valueabc)

**Expected Behavior** - Confirmation Pop U Message **" Are you sure you wanna update this item from .... to ....?"**

**Current Behavior** - The field is updated immediately , this may increase a lot of mistakes where user clicked the incorrect item to update

**Steps**
- Enter New Item in the list
- Navigate to the added item , enter changes you wanna make in the field and Click Update button 

# Defect Number 3

**Description**

    No pop up message when deleting an item to confirm if the user is sure that they wanna delete 

**Expected Behavior** - Confirmation Pop U Message **" Are you sure you wanna Delete this item?"**

**Current Behavior** - The field is Deleted immediately , this may increase a lot of mistakes where user clicked the incorrect item to Delete

**Steps**
- Enter New Item in the list
- Navigate to the added item ,  Click X button infront of the item

# Defect Number 4

**Description**

   Delete button not labeled  

**Expected Behavior** - Delete button to be labeled for consistanncy and usability purposes, the update button is a normal button and labeled which makes it easy to find whereas the delete buton is just a sign that might be missed also because of where it is located which is infront of the item.

**Current Behavior** - The delete button should be designed the same as update button and be after the update button not infront of the item , this may cause the users to delete the items unintentionally so.

**Steps**
- Enter New Item in the list
- Navigate to the added item ,  

# Defect Number 5

**Description**

    No field validations  

**Expected Behavior** - Todo Item Field to return an error when invalid data is entered

**Current Behavior** - Currently the system allows user to enter ONLY special charectors and ONLY numbers 

**Steps**
- Enter numbers only or special charectors only in the list
- Check the new item added,  

# Defect Number 6

**Description**

    No Error returned when submitting an empty item  

**Expected Behavior** - Todo Item Field to return an error when empty item is subbmitted ***"Field can not be empty***

**Current Behavior** - Currently the system does nothing when submitting an empty field

**Steps**
-Click Submit button without entering any thing-NULL field 


***For the above mention defects i have attached a screenshot in the following path \qe-todolist\App screenshot_Test Results***