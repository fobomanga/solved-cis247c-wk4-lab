Download Link: https://assignmentchef.com/product/solved-cis247c-wk4-lab
<br>
STEP 1: Understand the UML Diagram

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/06/518.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/06/518.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

The only change to the Employee class is that there is a new attribute:

+benefit : Benefit

Notice that there is a “+” for this attribute, meaning that it is public. Make sure to examine the multi-arg constructor’s signature!

Also, the dotted directed line between Employee and iEmployee specifies that the Employee class must implement the iEmployee abstract class, and thus provide an implementation for the calculatePay method.










<h2>STEP 2: Create the Project</h2>

You will want to use the Week 3 project as the starting point for the lab. To do this, you will want to create a new project by following these steps:

<ol>

 <li>Create a new project and name it “CIS247C_WK4_Lab_LASTNAME”.</li>

 <li>Copy all the source files from the Week 3 project into the Week 4 project.</li>

 <li>Before you move on to the next step, build and execute the Week 4 project.</li>

</ol>




STEP 3: Modify the Employee Class

<ol>

 <li>Using the UML Diagrams from Step 1, create the Benefit class. To get an idea of how to format displayBenefits, take a look at the output in Step 5.</li>

 <li>Add a Benefit attribute to the Employee class.</li>

 <li>Initialize the new Benefit attribute in both Employee constructors. Again, take note of the multi-arg constructors parameter list!</li>

 <li>Create the iEmployee interface (<strong>abstract class in C++</strong>).</li>

 <li>Modify the Employee class to implement the new interface so that Employee will have to implement the calculatePay method.</li>

 <li>Modify the Employee class to call displayBenefit when displaying Employee information.</li>

</ol>

STEP 4: Modify the Main Method

Notice that the Employee class now has a public benefit object inside it. This means that you can access the set methods of the Benefit object with the following code:

&lt;Employee object&gt;.benefit.&lt;method&gt;

As an example, to set the lifeInsurance attribute inside an Employee object called emp, we could execute the following code:

emp.benefit.setLifeInsurance(lifeInsurance);

The steps required to modify the Main class are below. New steps are in bold.

<ol>

 <li>Create an Employee object using the default constructor.</li>

 <li>Prompt for and then set the first name, last name, and gender. Consider using your getInput method from Week 1 to obtain data from the user for this step as well as Step 3.</li>

 <li>Prompt for and then set the dependents and annual salary using the overloaded setters that accept Strings.</li>

 <li><strong>Prompt for and set healthInsurance, lifeInsurance, and vacation.</strong></li>

 <li>Using your code from Week 1, display a divider that contains the string “Employee Information”.</li>

 <li>Display the Employee Information.</li>

 <li>Display the number of employees created using getNumEmployees(). Remember to access getNumEmployees using the class name, not the Employee object.</li>

 <li><strong>Create a Benefit object called benefit1 using the multi-arg construction. Use any information you want for health insurance, life insurance, and vacation.</strong></li>

 <li>Create another Employee object and use the constructor to fill it with the following:“Mary”, “Noia”, ‘F’, 5, 24000.0, <strong>benefit1</strong></li>

 <li>Using your code from Week 1, display a divider that contains the string “Employee Information”.</li>

 <li>Display the employee information.</li>

 <li>Display the number of employees created using getNumEmployees(). Remember to access getNumEmployees using the class name, not the Employee object.</li>

</ol>




<h2>STEP 5: Screen Prints</h2>

Capture the Console output window and paste it into a Word document. The following is a sample screen print.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/06/508.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/06/508.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

STEP 7: Submit Deliverables

<ul>

 <li>Capture the Console output window and paste it into a Word document</li>

 <li>Archive the files and screen shots (Project folder files Word document that contains programming code and screen shots of program output)</li>

</ul>


