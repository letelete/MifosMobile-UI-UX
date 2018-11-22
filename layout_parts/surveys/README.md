# Surveys layout

![preview](https://i.imgur.com/awcbAbQ.gif)

## Design Flow

I created very clean and minimalist proposal with elegantly separated questions by using rounded rectangles.

I moved a progress bar above the bottom navigation bar to make it bigger, better, faster and stronger (Actually to avoid progress bar being crushed between these two navigation buttons).

I got rid of the blue background for each question and replace it with this small, lovely rounded rectangle which contains information about the current question and the total amount of them. Furthermore, the blue, rounded rectangle refers to the progress bar.

I've also created some simple confirmation dialog to replace this ugly, default one.

### Buttons logic:

- Back button:
Is available if any previous question exists,
- Next button:
Is available if the user answered the question. It also changes its text from 'Next' to 'Submit' if currently opened question is the last one,
- Answer radio buttons:
Obviously, if user back to the previous question it should be marked accordingly to what his answer was. The same thing happens when user back from already answered question B to question A and then press 'Next' - question B should contain the answer,
- Cancel(Dialog):
Dismiss dialog and show current question screen,
- Yes(Dialog):
Dismiss dialog, submit the survey and open app menu from where the user starts a survey.
