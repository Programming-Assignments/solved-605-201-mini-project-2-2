Download Link: https://assignmentchef.com/product/solved-605-201-mini-project-2-2
<br>
Please do the following to complete this assignment.

<strong>Purpose:</strong>

The purpose of this project is to provide non-trivial practice in the use of Java object-oriented programming features to implement an object-oriented design and have a bit of fun doing it.

<strong>Resources Needed:</strong>

You will need a computer system with Java 8 or greater SE edition run-time and Java Development Kit (JDK).  You may optionally use a Java IDE for example NetBeans, Eclipse, etc.  However application builders are not allowed.

<strong>Submitted Files:</strong>

Design and Analysis:

This is an informal essay-style single-spaced word-processed document.   The file formats accepted will be announced at project assignment. The length of the document should be between 1 and 1.5 pages.  The following subjects should be discussed in this order:

<ol>

 <li>General program design. How is the program organized?  What major data structures were used?  How did you divide the functionality among your classes? How are commands processed?</li>

 <li>What alternative approaches were considered and why were they rejected?</li>

 <li>What did you learn from doing this project and what would you do differently?</li>

</ol>

Source files:

Each public class <em>must</em> be contained in a separate Java source file.  Only one source file will have a main() method and this source will be named <strong>VendingMachineSimulator.java</strong>.  Other source/class names are up to you following the guidelines specified so far in the course.

The format of the Java source must meet the general Java coding style guidelines discussed so far during the course.  Pay special attention to naming guidelines, use of appropriate variable names and types, variable scope (public, private, protected, etc.), indentation, and comments.  Classes and methods should be commented with JavaDoc-style comments (see below).  Please use course office hours or contact the instructor directly if there are any coding style questions.

JavaDocs:

Sources should be commented using JavaDoc-style comments for classes and methods.  Each class should have a short comment on what it represents and use the @author annotation.  Methods should have a short (usually 1 short sentence) description of what the results are of calling it.  Parameters and returns should be documented with the @param and @return annotations respectively with a short comment on each.

JavaDocs must be generated against every project Java source file.  They should be generated with a –<strong>private</strong> option (to document all protection-level classes) and a <strong>–</strong>d [dir] option to place the resulting files in a <strong>javadocs</strong> directory/folder at the same level as your source files.  See the JavaDocs demonstration for more details.

Submit file:

The submit file is to be a Zip file containing your design and analysis document, your Java sources, and your javadocs directory/folder.  Any appropriate file name for this Zip file is acceptable.

If you know how to create a standard Java JAR file, this is also acceptable for your source code.  However, make sure you include the source code in your JAR file.

<strong>Collaboration:</strong>

It is encouraged to discuss technical or small design parts of this project with your fellow students.  However the resulting design and implementation must be your own.  For example, it is acceptable to discuss different ways of maintaining the vending machine state but not detailed design or implementation information on processing the purchase command.  When in doubt, ask during office hours or contact your instructor.

<strong>Program Specification:</strong>

<ol>

 <li>Create a new multi-class Java program which implements a vending machine simulator which contains the following functionality:

  <ol>

   <li>At program startup, the vending machine is loaded with a variety of products in a variety of packaging for example soda/tonic/Coke in bottles, peanuts in bags, juice in cartons, etc. Also included is the cost of each item. The program should be designed to <em>easily</em> load a different set of products easily (for example, from a file).</li>

  </ol></li>

</ol>

Also at program startup, money should be loaded into the vending machine.  Money should consist of different monetary objects for the specified currency for example in USD $1 bills, $5 bills, quarters, dimes, etc.  Your program should be designed to use different national currencies easily (for example the Euro) <em>without changing source code</em>.  Money should be maintained as paper bills and coins, not just amounts.

<ol>

 <li>A menu of commands must be provided. The menu should consists of the following commands using the command numbers indicated:

  <ol>

   <li>Display the list of commands</li>

   <li>Display the vending machine inventory. For each item, this command should result in displaying a description and current quantity.</li>

   <li>Display the money currently held in the vending machine.</li>

   <li>Purchase an item. The result of this selection should be the following actions:

    <ol>

     <li>Prompt the user to indicate what item to purchase</li>

     <li>Prompt the user to specify what monetary items are being used for payment (the actual items for example quarters, dimes, etc.), not a money amount</li>

     <li>If the user specified enough money to purchase the selected item, the item is purchased (deducted from inventory), supplied money is added to the vending machine, and any change is returned in the form of monetary items (quarters, dimes, etc.).</li>

     <li>If the user did not specify enough money for the selected item, the transaction is aborted with the supplied money not added to the machine (not accepted) and the product not purchased (i.e. the state of the vending machine is unchanged).</li>

    </ol></li>

   <li>Exit – exits the program displaying a departing message.</li>

  </ol></li>

 <li>Additional points to consider:

  <ol>

   <li>You can use the Java Standard Edition (SE) API library as supplied by Oracle (AKA Sun) <em>except the collection classes</em> (i.e. not ArrayList, Map, Vector, etc.).  These other collections will be covered later in the course.</li>

   <li>When developing complex classes, consider creating a main() method to test them out. Once tested successfully, delete the main() method.</li>

   <li>You should generate error messages when appropriate, for example on invalid input values or not enough money supplied for the selected item to purchase. Exceptions will be covered later in the course so for this program displaying appropriate messages on the console is fine.</li>

  </ol></li>

</ol>

<strong>Other Activates:</strong>

<ol>

 <li>Observe the presentation on JavaDocs.</li>

 <li>Observe the Vending Machine Simulator demonstration for an example of one implementation.</li>

 <li>Create a compressed zipped folder containing your Design and Analysis document, your Java source code files, and your javadocs folder.</li>

 <li>Submit your compressed zipped folder as directed by your instructor.</li>

</ol>

<strong>Assignment Rubric:</strong>

<strong>Part                      70%                          80%                         90%                               100%                           % of </strong>

<strong>Grade</strong>

<strong>Design and           </strong>All but one                All assigned             All assigned subjects    All assigned              15%

<strong>Analysis               </strong>subject addressed    subjects address     address with                 subjects address

<strong>Document           </strong>with relevant,           with mostly            accurate and                 with accurate,

information.   relevant relevant.  Nicely relevant, and Few minor information.  formatted document. insightful typographical Nicely formatted Document is within information.  Very issues. Document document.  assigned length nicely formatted.

is close to                 Document is                                                 Document is

assigned length        close to assigned                                          within assigned

length                                                           length

<strong>Functionality      </strong>Majority of Most required             Nearly all required      All required     60% required function      function parts function parts work    function parts

Note: parts work as work as indicted as indicted in the work as indicted Compilation indicted in the in the assignment text in the assignment errors and assignment text.  assignment text above and submitted text above and warnings are One major or 3 above and documentation.  One submitted part of this minor defects.  submitted to two minor documentation.

evaluation.           All major                  documentation.      defects.

functionality at        One major or 3




least partially

working (example change provided but not correct).  Design document does not fully reflect functionality.

<strong>Code                    </strong>Majority of the

code conforms to coding standards as explained and demonstrated so far in the course (ex. method design, naming, formatting, etc.).  Five to six minor coding standard violations.  Some useful comments. Some JavaDocs commenting. Code compiles with multiple warnings or fails to compile with difficult to diagnose error. minor defects.  All major functionality at least partially working ((example change provided but not correct). Most of the code conforms to coding standards as explained and demonstrated so far in the course (ex. method design, naming, formatting, etc.). Three to four minor coding standard violations.  Mostly useful comments. Public class JavaDocs complete.  Code compiles with one to two warnings.

Almost all code conforms to coding standards as explained and demonstrated so far in the course (ex. method design, naming, formatting, etc.).  One to two minor coding standard violations.  Appropriate level of useful comments.  Public class

JavaDocs complete. Code compiles.  Code compiles with no errors or warnings.

All code                     25%

conforms to coding standards as explained and demonstrated so far in the course (ex. method design, naming, formatting, etc.).  Appropriate level of useful comments.  Complete JavaDocs as specified.  Code compiles with no errors or warnings.