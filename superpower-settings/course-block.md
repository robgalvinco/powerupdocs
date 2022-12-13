# Course Block

{% embed url="https://www.loom.com/share/ab62392763894cb399f3bfc4a9b36312" %}

## Type of Block

This determines how this specific Course Block restriction will be applied.

<figure><img src="../.gitbook/assets/Screen Shot 2022-09-24 at 2.29.03 PM.png" alt=""><figcaption></figcaption></figure>

### Block Enrolling

This blocks all links for free, paid, free trial and is valid on the course page only. You still have to select the product and conditions below.

### Block Resuming

When enabled, this will block all resume links based on the conditions specified. This works on both the Student Dashboard and Course Page

### What should be locked?

* Course or Bundle - this will use the [Course/Bundle to Block](course-block.md#course-bundle-to-lock) setting to determine what should be blocked
* Everything but... (below) - this will use the Everything But... Course/Bundle setting to determine what should be blocked

### Course/Bundle to Block

* Choose a course of bundle of courses to block.

### Everything But... Course/Bundle

* When you select a course for this option - everything except this course will be blocked
* When you select a bundle for this option - everything except all of the courses in the bundle will be blocked

## Popup Settings

<figure><img src="../.gitbook/assets/Screen Shot 2022-09-19 at 3.53.59 PM.png" alt=""><figcaption></figcaption></figure>

### Heading

This will be used in the block popup message as the heading. `[NAME]` will be replaced with the students first name.

### Summary

This will be used in the block popup message as the subheading.

* `[COURSE CONDITION]` will be replaced by the course name in the condition list that fails the condition
* `[COURSE LOCKED]` will be replaced by the name of the course that is locked

### Prompt

This will be used in the block popup message as the text above the prompt buttons.

* `[COURSE CONDITION]` will be replaced by the course name in the condition list that fails the condition

### Prompt (yes)

This is the text for the "yes" option which is typically to resume the course that has failed the condition.

### Prompt (no)

This is the text for the "no" option which will close the popup.

<figure><img src="../.gitbook/assets/Screen Shot 2022-09-19 at 4.01.14 PM.png" alt=""><figcaption></figcaption></figure>

## Activation Settings

<figure><img src="../.gitbook/assets/Screen Shot 2022-12-07 at 10.54.48 AM.png" alt=""><figcaption></figcaption></figure>

The settings in this group allows you to control when this specific course block is active.

* When to activate this block? (When to Not Activate setting over-rides this)
  * Always: This Course Block will always be active&#x20;
  * Enrolled In:  This Course Block will be active when the student is enrolled in the selected course or bundle
  * Not Enrolled In: This Course Block will be active when the student is not enrolled in the selected course or bundle
* When to not activate this block?&#x20;
  * Never: The activate block settings apply
  * Enrolled In:  This Course Block will not be active when the student is enrolled in the selected course or bundle
  * Not Enrolled In: This Course Block will not be active when the student is not enrolled in the selected course or bundle

## Excluded Users

<figure><img src="../.gitbook/assets/Screen Shot 2022-09-19 at 4.02.32 PM.png" alt=""><figcaption></figcaption></figure>

This allows you to exclude certain users from this course block. Enter the exact email address of the users that will not have this specific course block restriction.

## Lock Condition Settings

<figure><img src="../.gitbook/assets/Screen Shot 2022-09-19 at 4.03.56 PM.png" alt=""><figcaption></figcaption></figure>

### When to unlock this course?

* All conditions must be met - when all conditions from the list of conditions have been satisfied, the this specific course block will lifted
* Any condition must be met - when any of the conditions from the list of conditions has been satisfied, then the specific course block will be lifted.

## Unlock Conditions

Add one or more conditions that will be reviewed in order to lift the course block.

### When to unlock this?

* Course/Bundle Completed - when the specific course or courses in the associated bundle has been completed, then this course block will be lifted
* _More condition types coming soon_

### Course/Bundle to Complete

* When choosing a course, if this course is completed, then the course block will be lifted
* When choosing a bundle, then all courses in that bundle must be completed for the course block to be lifted
