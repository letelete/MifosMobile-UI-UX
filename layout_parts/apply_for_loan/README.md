# Loan Application Screen

![preview](https://i.imgur.com/u87sjYA.png)

## Design flow

### Select loan product, Purpose of loan

It's a select dropdown list. On tap it expands and on select / tap over the dropdown area - collapses.

### Principal amount

It's an EditText, where user enters desired amount for a loan.

#### Empty

If empty, it looks like the Principal amount input on the 1st screen.

#### On focus

Presented on 2nd screen

hint -> header

underline visibility -> visible

text cursor visibility -> visible

header color -> primary blue

underline color -> primary blue

text cursor color -> primary blue

input text color -> bold and black (87% opacity), just like the other input texts

#### On Lost Focus

On lost focus, an input should looks exactly like the Submission date input on the 2nd screen

### Submission date, Expected disbursement date

It's an editable TextView

#### On tap

On tap, the android date picker dialog appears.

![preview](https://i.imgur.com/nC5HDPl.png)

### Currency

Editable TextView, Presents a current currency, On tap the android list picker appears

![preview](https://i.imgur.com/wFfHyUk.png)

#### OnTap

Because of the currencies amount, on tap, the android list select dialog and not select dropdown appears. The user can change currency there.   

### Submit Button

Submits loan application checking for any invalid inputs before.

