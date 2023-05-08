Download Link: https://assignmentchef.com/product/solved-programming-project-6-pizza-palace
<br>
<strong>Project Outcomes:</strong>

Develop a Java program that uses:

<ul>

 <li>Graphical User Interfaces</li>

 <li>Java Components such as JFrames, JPanels, check boxes, radio buttons and spinners</li>

 <li>Event handlers such as ActionListeners.</li>

</ul>

<strong>Preparatory Readings:</strong>

Java ZyBook Chapters 1 – 14

<strong>Background Information:</strong>

<strong>Project overview:</strong>

Create a java graphical program that displays an order menu and bill from a pizza shop. In this program the design is left up to the programmer however good object oriented design is required. Below are two images that should be used to assist in development of your program. Items are selected on the Order Calculator and the message window that displays the subtotal, tax and total is displayed when the Calculate button is pressed. You can also combine the two functions in the same panel if you wish.




<strong>Project Requirements:</strong>

<ol>

 <li>Develop a project that provides the functionality shown in the images above.</li>

 <li>The type of shop, items offered and cost is up to the designer. However each item must have a different cost and the final calculation must be correct.</li>

 <li>The images display the minimum requirements, however the following is a list of those minimum requirements.

  <ol>

   <li>Welcome panel with the shop name and three item panels with panel labels.</li>

   <li>At least one set of checkboxes that allows multiple selection and one set of radio buttons that are mutually exclusive.</li>

   <li>A panel that holds the calculate and exit buttons.</li>

   <li>A popup box or separate panel that displays the cost of the selections and the tax. Note the tax must be calculated after the items are selected.</li>

  </ol></li>

</ol>

<strong>Implementation Notes:</strong>

<ol>

 <li>Create a project that is object oriented, therefore there should be several classes.</li>

 <li>Create a UML class diagram that shows all the classes in your project.

  <ol>

   <li>The class diagrams should be created in at multiple iterations.

    <ol>

     <li>The first iteration should be done before you code and should provide a design that the code follows.</li>

     <li>The second iteration should be completed after the code is complete and should reflex the <em>exact</em> class structure of you final program.</li>

     <li>The class diagrams should include

      <ol>

       <li>Access specifier (- or +).</li>

       <li>All instance fields with types.</li>

       <li>All methods with return type and parameter types.</li>

       <li>Associations, generalization (inheritance), aggregation and multiplicity .</li>

       <li>Stereotyping – interface or abstract classes.</li>

      </ol></li>

     <li>Create a word document explaining the differences and the rational behind the differences between the final result of the two series of iterations. A difference is expected as it is extremely difficult to anticipate every design characteristic prior to coding.</li>

    </ol></li>

  </ol></li>

 <li>Below is an outline of possible structure of the program. This is a basic outline and does not address all the required details. You may want to think about your design first before reading the suggested structure below.

  <ol>

   <li>Create a separate class for each Panel except the button panel.</li>

   <li>Create an Order Calculation class.

    <ol>

     <li>Extends JFrame.</li>

     <li>Instance fields are objects of the JPanel type.</li>

     <li>Adds the JPanels to the JFrame using a BorderLayout</li>

     <li>A method to create the button panel (Calculate and Exit)</li>

     <li>Two inner ActionListener classes that handle the button actions.</li>

    </ol></li>

   <li>A class that contains the main method and simply creates the Order Calculation object.</li>

  </ol></li>

</ol>


