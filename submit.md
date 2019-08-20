# How to submit questions
You may submit questions in one of three ways:
## 1. By submitting an issue with your question

The requirements for the question are as follows:

* It should be a multiple choice question 
  * with four possible answers and 
  * only one correct answer.  
* It should be written in [GIFT format](https://docs.moodle.org/37/en/GIFT_format#Multiple_choice).  Please use the [GIFT Question Editor](https://fuhrmanator.github.io/GIFT-grammar-PEG.js/docs/editor/editor.html) to validate that your question can be parsed correctly before submitting.
* It should not include a title

Precede your questions with comments that include:
* The numbered _"study task"_ listed in the [Certified Professional in Accessibility Core Competencies Body of Knowledge](https://iaap.membershipsoftware.org/files/IAAP%20CPACC%20BOK%202017_062317.docx) that your question relates to.  
* A reference to any source materials you are basing the question on

***

An example submission would be something like this:

### Question
```
// Study Task: I:A.1 Characterize and differentiate between theoretical models of disability, including the strengths and weaknesses of their underlying assumptions

// Sources: 
//   The [Certified Professional in Accessibility Core Competencies Body of Knowledge](https://iaap.membershipsoftware.org/files/IAAP%20CPACC%20BOK%202017_062317.docx)

What is a strength of the medical model of disability?
{
  =It defines disability in a way that facilitates treatment of the individual by the medical profession. # right;
  ~It emphasizes the responsibility of society for creating enabling conditions for all people.
  ~It encourages individuals to view themselves as a class with common interests, so they can more effectively advocate for their rights.
  ~It encourages empathy for those with disabilities.
}
```