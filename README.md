# **Challenge Pool Title**<br/>by **Instructor**

README and outline deadline: YYYY-MM-DD 

As part of the 'outline' process, you will need to complete the following tasks:

- [ ] Edit this README by filling in the information for step 1.
- [ ] Update the requirements.sh file in your practice pool repository on GitHub. Check with your contact as needed.


## Challenge development resources

* Authoring documentation: https://authoring.datacamp.com/
* Practice admin page: https://www.datacamp.com/teach/content/challenges
* Technical documentation on challenge types: (in development)


## Step 1: Write practice pool outline

### How to create the practice pool outline
* Make the outline of concepts in the template below; the outline lists all concepts that are taught in the corresponding course.
* For each concept, specify the concept parts: the important things to understand about this concept (e.g. nuances, syntax, arguments, data types of arguments / return types, differences with other functions, …)
* For each concept part, what is the exercise that is going to test exactly this?
* Add a challenge type to each exercise, ensuring a mix of various challenge types in each chapter.
* A typical challenge pool contains 10 exercises per course chapter.

### Your outline
> Example from a practice pool on Introduction to Databases in Python

> Chapter 1 - Basics of Relational Databases
>   * MultipleChoiceChallenge: does the student know the different steps of getting data out of a database and the order they go in
>     * make connection
>     * execute
>     * get results
>   * BlanksChallenge: does the student know the parts of a `create_engine` function call, and the format of it (in quotations, `engine = create_engine(‘sqlite:///census_nyc.sqlite’`)
>   * OutputChallenge: does the student understand that `repr` output has a particular format, can s/he get the needed information out of it
>     * `print(repr({{var1}})`
>     * Var1 → different tables


## Step 2: Build exercises for ONE chapter on the Teach Editor

### Content vision
it is the goal of practice exercises to
* check if the student has a correct understanding of the course
* check whether the student remembers the most important things taught in the course
* allow the student to exercise until s/he can apply what s/he's learned in the course without having to look things up

### Content guidlines
* each pool should have
   * ~ 40 exercises, equally distributed over the different chapters of a course
   * a good mix of the different exercise types
   * a good mix of conceptual and general questions (e.g. why use this package over that package), and detailed questions (e.g. what is the name of the function of package x to do y?)
* each pool should test
  * the most important misunderstandings of a course
  * whether the student remembers the most important concepts and their meaning

### Content checklist
- [ ] is it clear from the outline which concepts will be tested?
- [ ] are the most important things tested?
- [ ] is it clear what exactly is going to be tested?
- [ ] is there a good mix of exercise types?
- [ ] does each exercise check exactly what you want to test?
- [ ] are all distractors distracting? Is it realistic someone might think they are the correct answer?
- [ ] will the student spend most time answering the question, instead of understanding what is being asked?
- [ ] do the different versions of an exercise test the same concept?
- [ ] do all sentences start with a capital letter?
- [ ] is the code is formatted nicely, using newlines where necessary?
- [ ] does the output not contain more than 5 lines?
- [ ] do tables contain no more than 3 columns?
- [ ] are all exercise keys unique?
