# Beneficiary Details

## Preview

### GIF

![gif](https://i.imgur.com/LqkCTjH.gif)

### IMG

![gif](https://i.imgur.com/OJCbti8.png)

## Design Flow

### Top app's panel

We have a beneficiary image here and also his name and account number.

#### Editable beneficiary profile image

on tap -> change image

It's great to have a profile image for every beneficiary,
not only because it makes the layout more interesting, 
but also its easier for the user to operate on his beneficaries later in the app.

For example, selecting a beneficiary with his profile image is much easier and faster

![pinterest inspiration](https://i.imgur.com/lnrzIUy.png)

### Details

We have some data form which is consistent by its look and behaviour with the other app forms

#### Name, Account Number, Transfer Limit, Head Office

Editable text views, on focus works as same as the transfer limit input on the 3nd screen.

#### On tap

1. Beneficiary Detials changes its mode to the **Edit Beneficiary** (visible on 3nd screen)
2. Keyboard appears
3. The input transform into edit text.
4. Save button appears
5. Reutrn navigation button in the left top corner transform into the cancel button

### Edit Beneficiary

We should use some coordinator layout here to make the top app's panel collapsed / expanded depending on situation
(3rd screen - view is collapsed, becasue we wanted to make the save button visible, by moving the details cardview relatively to the keyboard)

#### On edit enter

Because the user can enter into the edit mode by tapping on one of the inputs in Beneficiary Details, we would like to
request focus on the tapped field. 

To improve the UX we also need to make the Edit mode scrollable. We could achieve the effect of changing __details__ card view position
depending on requested input (We just want to change the cardview position relatively to the keyboard position, to make save button visible when in request edit mode.

#### Discard changes

He can done that by:

##### Tapping on Cancel button

User can leave edit mode by tapping on the cancel button (X) in the left top corner (3rd screen). It will make the dialog visible (1st screen).

##### Pressing back button (external navigation in the phone)

On Back button press, the dialog will appear (1st screen)

![this one](https://i.imgur.com/dXFwBAY.png)

###### On Dialog Cancel

The user cancel the discard and exit action and stay in the edit beneficiary activity.

###### On Dialog Accept

The user back to the beneficiary details.

#### Save Changes

USer can save changes by tapping on save button

After that he leaves the edit beneficiary activity and back to the beneficiary details





