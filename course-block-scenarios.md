# 💥 Course Block Scenarios

## Your Basic Course Block

In this scenario, we want to block a course based on completion of another course.

{% embed url="https://www.loom.com/share/dcd18a1b77114ddf95372fad795dc1dd" %}

**Setup Steps**

* [ ] Add a Course Block section to the Student Dashboard
* [ ] In the Type of Block settings group, choose&#x20;
  * [ ] **What should be blocked**: _Course or Bundle_
  * [ ] **Course/Bundle to Block**: _The course that you want to block. example: "Lie Down"_
* [ ] Add an unlock condition
  * [ ] **When to unlock this?**: _Course/Bundle Completed_
  * [ ] **Course/Bundle to Complete**: _The course that you are requiring to be completed example: "Basic Obedience"_&#x20;
* [ ] Setup your individual course pages for the courses that are to be block so that the student cannot access the course from the course landing page

## Everything "But"...

This is great when you may have a foundational course that you want everyone to take before they move into to another course.

{% embed url="https://www.loom.com/share/62fe0e027c1944d5ae73b1c6f9da521a" %}

**Setup Steps**

* [ ] Add a Course Block section to the Student Dashboard
* [ ] In the Type of Block settings group, choose&#x20;
  * [ ] **What should be blocked**: _Everything but... (below)_
  * [ ] **Everything But... Course/Bundle**: _The course/bundle that you want to NOT block. example: "Basic Obedience"_
* [ ] Add an unlock condition
  * [ ] **When to unlock this?**: _Course/Bundle Completed_
  * [ ] **Course/Bundle to Complete**: _The course that you are requiring to be completed example: "Basic Obedience"_&#x20;
* [ ] Setup your individual course pages for the courses that are to be block so that the student cannot access the course from the course landing page

## Blocking "Levels" of courses

In this scenario, you may want to block a set of courses until another set of courses is completed.

{% embed url="https://www.loom.com/share/7bb8471b116c4c978e6a5d3604915edf" %}

**Setup Steps**

* [ ] Add a Course Block section to the Student Dashboard
* [ ] Create a draft bundle _"Level 1"_ (if you do not have one already) that includes that will define what is required to be completed
* [ ] Create a second draft bundle: _"Level 2"_ that will define what courses will be blocked until all courses in Level 1 will be completed
* [ ] In the Type of Block settings group, choose&#x20;
  * [ ] **What should be blocked**: _Course or Bundle_
  * [ ] **Course/Bundle to Block**: _The bundle that you want to block. example: "Level 2"_
* [ ] Add an unlock condition
  * [ ] **When to unlock this?**: _Course/Bundle Completed_
  * [ ] **Course/Bundle to Complete**: _The bundle that you are requiring to be completed example: "Level 1"_&#x20;
* [ ] Setup your individual course pages for the courses that are to be block so that the student cannot access the course from the course landing page

{% hint style="info" %}
If you do not have "Bundles" on your Thinkific plan, then you can use multiple individual Course Blocks to accomplish the same thing.
{% endhint %}
