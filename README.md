# angular_interview

https://github.com/delprzemo/angular-cheatsheet

Reactive Forms : key concepts:
1. Form Control : single input field within a form , it manages value and validation state of the input
2. Form Group : Clollection of form controls grouped together, can be used to manage the values and validation of multiple controls as a single unit
3. Form Builder : utility class that simplifies the creation of form controms and form group => it provides a more concise and readable way to define forms
4. Form control properties :
     'value' : the current value of the control
     'valid' & 'invalid' : Boolean check the validity of the control's value according to the defined rules
     'touched' & 'untouched' : Boolean indicating whether the control has been interacted with (touched) or not
     'dirty' & 'pristine' : Boolean indicating whether the control has been interacted with (dirty) or not
5. Validation : validation rules for form controls using built-in validators or custom validation functions
     Build-in validators : 'required' , 'min' , 'max' , 'email', 'pattern'
     Display validation error messages using Angular's error handling mechanisms
6. Asynchronous validation: implement asynchronous validation , which involves making server requests to validate input values
7. FormArray : it's a variation of 'FormGroup' used for managing dynamic lists of form control . it's useful for scenarios like managing a list of ites in a form.
8. Binding to Template : use angular's data binfing to bind form controls to HTML elements | use the  'formCo,trolName','FormGroup',and 'formArrayName' directives to establish the link between form controls and HTML elements
9. Reactive event handling : respond ton user interactiuons with the form in a reactive manner . Use observables like 'valueChanges', 'statusChanges' and 'submit' events to track changes and handle user input.
10. Dynamic forms : create forms with dynamic number if fields based on user actions or data | lean how to dynamically add and rmve form control s or form groups
11. Form Submission : handle form submission by subscribing to the 'ngSubmit' event using observables | prevent default form submission behavior nd perform custom actions , such as making API requests
12. Form reset and Initializations : understand how to share form data and form control instance between components | use Angular services to manage form state and data sharing in a mutlti-component application
13. Testing : write unit tests for reactive forms using Angular's testing utilitues , sush as 'TestBed' and 'FormControlTester' 




Regex : regular expressions are powerfull patterns that allow you to define specific criteria for input validation 
Angular reactive forms empower you to seamlessly integrate regex into your validation strategies
  here's an example of using regex to validate an email input


![image](https://github.com/Firassaad/angular_interview/assets/36532618/90e8b1e6-6864-4b38-a017-5a2d7ca68164)
