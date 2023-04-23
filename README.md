Download Link: https://assignmentchef.com/product/solved-assignment-1-book-inventory-shell-program-solved
<br>
<u>Aim</u>

The objectives of this assignment includes:

<ul>

 <li>Learning about shell filters, commands and shell scripting language</li>

 <li>Apply the concepts learnt by developing a simple (book) inventory shell program</li>

</ul>

<u>Background</u>

This assignment requires you to write a standalone Book Inventory (Shell) program. The Inventory program is normally used by the Book Store owner to keep track of book information and available quantity.  It should be an interactive menu-based program allowing the owner to:

<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

The system allows book details to be individually entered/updated and then stored in a text file (called “BookDB.txt”) in the following format:

[ Title ]:[ Author ]:[ Price ]:[ Qty Available ]:[ Qty Sold ]

eg:       <strong><em>Windows Vista in 21 days:John Goodman:33.68:100:48</em></strong>

<strong><em>MacOS X for dummies:Mary Abraham:53.48:88:38</em></strong>

etc…

The colon (:) character is used to separate each piece of information.

<u>Task Requirements</u>

<ol>

 <li>Instead of specifying exactly what each function (in the above menu) is supposed to do, the bookstore owner has painstakingly documented his desired output in the following <strong>Appendices A – F</strong>.</li>

 <li>Before you start developing your program, you should take some time to review the output, and analyze the requirements of the inventory application.</li>

 <li>It is recommended that you come up with some basic table of technical requirements to document what you interpret to be desired functionalities of the program, before you proceed with program development.</li>

 <li>Once the program is completed and tested to be working successfully, you are highly encouraged to add on “new features” to the program that you feel are relevant to the tasks of book inventory tracking. Additional marks may be awarded subject to the relevancy and correctness of the new functionalities.</li>

 <li>You are not allowed to use Java, C++ or any other languages to form the whole, or even part of your book inventory application. You have to use Shell syntax and commands for your entire program.</li>

 <li>However, you are <u>not limited</u> to using the <u>shell commands that you have been taught</u>. In fact, you are highly encouraged to do additional research and learn in depth about any other commands necessary to do the task efficiently and effectively.</li>

</ol>

<u>Deliverables</u>

<ul>

 <li>The deliverables include the following:</li>

</ul>

<ol>

 <li>The actual working shell program (hard+soft copies), <strong><em><u>with comments on each file, function or block of code</u></em></strong> to help the tutor understand its purpose.</li>

 <li>A word document (hard+soft copies) that elaborates on:

  <ul>

   <li>(Interpreted) requirements of the inventory program</li>

   <li>Diagram / Illustrations of program design</li>

   <li>Summary of implementation of each module in your program</li>

   <li>Reflections on program development (e.g. assumptions made, difficulties faced, what could have been done better, possible enhancements in future, <strong><em>what have you learnt</em></strong>, etc)</li>

   <li>A program demo/evaluation during lab session. You must be prepared to perform certain tasks / answer any questions posed by the tutor.</li>

  </ul></li>

</ol>

<ul>

 <li>IMPT: Please <strong>follow closely</strong>, to the submission instructions in <strong>Appendix G</strong>, which contains details about what to submit, file naming conventions, when to submit, where to submit, etc.</li>

</ul>

<ul>

 <li>The evaluation will be held during lab session where you are supposed to submit your assignment. Some time will be allocated for you to present / demonstrate your program during the session.</li>

</ul>

<u>Grading</u>

Student’s deliverable will be graded according to the following criteria:

<ul>

 <li>Program fulfills all the basic requirements stipulated by the assignment</li>

</ul>

<ul>

 <li>Successful demonstration of a working program, clarity of presentation and satisfactory answers provided during Q &amp; A session.</li>

</ul>

<ul>

 <li>Additional effort (e.g. enhancing the program with <em><u>relevant</u></em> features over and above task requirements, impressive, ‘killer’ presentation)</li>

</ul>

<ul>

 <li>After the submission of deliverables, students will be required undergo an evaluation process (to determine fulfillment of task requirements.) Further instructions will be given by the Tutor during the subsequent respective labs. Please pay attention as failure to adhere to instructions may result in deduction of marks.</li>

</ul>

Tutor’s note:

In the real working world, satisfactory completion of your tasks is no longer enough. The ability to <u>add value</u>, <u>communicate</u> and/or <u>demonstrate</u> your ideas with clarity is just as important as correct functioning of your program. The grading criteria is set to imitate such requirements on a ‘smaller scale’.

<u>APPENDIX A</u>

<u> </u>(Sample output for function : Add New Book)

Note : User’s input is underlined, to differentiate it against program’s output (e.g. prompt for info)

<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>1</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Windows Vista in 21 days</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>John Goodman</u></em></strong>

<strong><em>Error! Book already exists!</em></strong>

<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>1</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>C++ for dummies</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Edward Scissorhands</u></em></strong>

<strong><em>Price : <u>15.01</u></em></strong>

<strong><em>Qty Available : <u>10</u></em></strong>

<strong><em>Qty Sold : <u>5</u></em></strong>

<strong><em>New book title ‘C++ for dummies’ added successfully!</em></strong>

<strong><em> </em></strong><strong><em>&lt;Displays main menu again …&gt;</em></strong>

<u>APPENDIX B</u>

<u> </u>(Sample output for function : Remove Existing Book Info)

Note : User’s input is underlined, to differentiate it against program’s output (e.g. prompt for info)

<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>2</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Biography of Crocodile Dundee</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Crox Swamplund</u></em></strong>

<strong><em>Error! Book does not exists!</em></strong>

<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>2</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>C++ for dummies</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Edward Scissorhands</u></em></strong>

<strong><em>Book Title ‘C++ for dummies’ removed successfully!</em></strong>

<strong><em> </em></strong><strong><em>&lt;Displays main menu again …&gt;</em></strong>

<u>APPENDIX C</u>

<u> </u>(Sample output for function : Update Existing Book Info)

Note : User’s input is underlined, to differentiate it against program’s output (e.g. prompt for info)

<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>3</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Star Wars VI – Return of the Jedi</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Obi-Wan Kenobi</u></em></strong>

<strong><em>Error! Book does not exists!</em></strong>







<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>3</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>C++ for dummies</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Edward Scissorhands</u></em></strong>

<strong><em>Book found!</em></strong>

<ol>

 <li><strong><em>Update Title</em></strong></li>

 <li><strong><em>Update Author</em></strong></li>

 <li><strong><em>Update Price</em></strong></li>

 <li><strong><em>Update Qty Available</em></strong></li>

 <li><strong><em>Update Qty Sold</em></strong></li>

 <li><strong><em>Back to main menu</em></strong></li>

</ol>

<strong><em>Please enter your choice: <u>a</u></em></strong>

<strong><em> </em></strong>

<strong><em> </em></strong>

<strong><em>NewTitle : <u>C++ for Experts</u></em></strong>

<strong><em>Book’s Title has been updated successfully!</em></strong>




<ol>

 <li><strong><em>Update Title</em></strong></li>

 <li><strong><em>Update Author</em></strong></li>

 <li><strong><em>Update Price</em></strong></li>

 <li><strong><em>Update Qty Available</em></strong></li>

 <li><strong><em>Update Qty Sold</em></strong></li>

 <li><strong><em>Back to main menu</em></strong></li>

</ol>

<strong><em>Please enter your choice: <u>e</u></em></strong>

<strong><em>New Qty Sold : <u>38</u></em></strong>

<strong><em>Book’s Qty Sold  has been updated successfully!</em></strong>

<strong><em> </em></strong>

<ol>

 <li><strong><em>Update Title</em></strong></li>

 <li><strong><em>Update Author</em></strong></li>

 <li><strong><em>Update Price</em></strong></li>

 <li><strong><em>Update Qty Available</em></strong></li>

 <li><strong><em>Update Qty Sold</em></strong></li>

 <li><strong><em>Back to main menu</em></strong></li>

</ol>

<strong><em>Please enter your choice: <u>f</u></em></strong>

<strong><em> </em></strong>




<strong><em>&lt;Displays main menu again …&gt;</em></strong>










<u>APPENDIX D</u>

<u> </u>

(Sample output for function : Search for Book by title/author)




Note : User’s input is underlined, to differentiate it against program’s output (e.g. prompt for info)




<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>4</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Star Wars VI</u></em></strong>

<strong><em>Author : </em></strong><strong><em>&lt;enter&gt;</em></strong>

<strong><em>Found 2 records :</em></strong>

<strong><em>                </em></strong><strong><em>Star Wars VI – Return of the Jedi, Obi-Wan Kenobi, $15.98, 20, 15</em></strong>

<strong><em>                </em></strong><strong><em>Star Wars VI – Return of the Jedi, Darth Vader, $8.05, 30, 20 </em></strong>







<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>4</u></em></strong>

<strong><em>Title : &lt;enter&gt;</em></strong>

<strong><em>Author : </em></strong><strong><em><u>Scissorhands</u></em></strong>

<strong><em>Found 3 records : </em></strong>

<strong><em>C++ for dummies, John Scissorhands, $15.01, 10, 5</em></strong>

<strong><em>Java for dummies, Mary Scissorhands, $16.02, 20, 15</em></strong>

<strong><em>VB.NET  for dummies, Edward Scissorhands, $17.03, 30, 25</em></strong>






















<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>4</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Java for dummies</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Edward Scissorhands</u></em></strong>

<strong><em>Found 1 record :</em></strong>

<strong><em>Java for dummies, Edward Scissorhands, $16.02, 20, 15</em></strong>







<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>4</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>The Never-ending story</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Kelly Longbreath</u></em></strong>

<strong><em>Book not found!</em></strong>







<strong><em>&lt;Displays main menu again …&gt;</em></strong>










<u>APPENDIX E</u>

<u> </u>

(Sample output for function : Process a book sold)




Note : User’s input is underlined, to differentiate it against program’s output (e.g. prompt for info)




<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>5</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Star Wars VI – Return of the Jedi</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Darth Vader</u></em></strong>

<strong><em>No. of copies sold  : <u>3</u></em></strong>

<strong><em>Current book  info :           </em></strong>

<strong><em>Star Wars VI – Return of the Jedi, Darth Vader, $8.05,  30, 20 </em></strong>

<strong><em> </em></strong>

<strong><em>New book info :   </em></strong>

<strong><em>Star Wars VI – Return of the Jedi, Darth Vader, $8.05,  27, 23 </em></strong>







<ul>

 <li><strong><em>Add new book</em></strong></li>

 <li><strong><em>Remove existing book info</em></strong></li>

 <li><strong><em>Update book info and quantity</em></strong></li>

 <li><strong><em>Search for book by title/author</em></strong></li>

 <li><strong><em>Process a book sold</em></strong></li>

 <li><strong><em>Inventory summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ul>

<strong><em>Please enter your option: <u>5</u></em></strong>

<strong><em>Title : </em></strong><strong><em><u>Star Wars VII – Return of the Frodo</u></em></strong>

<strong><em>Author : </em></strong><strong><em><u>Bilbo Baggins</u></em></strong>

<strong><em>Error! Book does not exists!</em></strong>

<strong><em> </em></strong>

<strong><em>&lt;Displays main menu again …&gt;</em></strong>




<u>APPENDIX F</u>




<table>

 <tbody>

  <tr>

   <td width="706">

    <table width="100%">

     <tbody>

      <tr>

       <td></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<u>APPENDIX G</u>

Submission Instructions  (V. IMPT!!)

<ul>

 <li><strong>Deliverables</strong></li>

</ul>

<ol>

 <li>All submissions should be in <strong>softcopy</strong>, unless otherwise instructed</li>

</ol>

<ol>

 <li>For the actual files to be submitted, you typically need to include the following:</li>

</ol>

<ul>

 <li>word document report (e.g. <strong>*.doc</strong>), save as <u>MS Word 97-2003</u> format</li>

</ul>

<ul>

 <li>the source file(s), (e.g. *<strong>.sh</strong>, *<strong>.c</strong>, *<strong>.h</strong>, *<strong>.o</strong>, or *<strong>.cpp</strong> files)</li>

</ul>

<ul>

 <li>the executable file, compile into an executable file with <strong>*.exe</strong></li>

</ul>

(e.g. Assn1.<strong>exe</strong>).  Note: this only applies to <strong><em><u>non-shell script</u></em></strong> assignments!

<ul>

 <li><strong>How to package</strong></li>

</ul>

Compress all your assignment files into a <u>single zip file</u>. Please use the following naming             format :

<strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong>_Assn<strong>1</strong>_<strong>&lt;Stud. No.&gt;_&lt;Name&gt;.zip</strong>

<em>Example : </em> <strong>FT</strong>_Assn<strong>1</strong>_<strong>1234567_JohnDoeAnderson. zip</strong>

<ul>

 <li><strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong> Use “<strong>FT</strong>” for <strong>F</strong>ull-<strong>T</strong>ime student, “<strong>PT</strong>” if you are <strong>P</strong>art-<strong>T</strong>ime student</li>

</ul>

<ul>

 <li>Assn<strong>1</strong> if you are submitting assignment <strong>1</strong>, Assn<strong>2</strong> if submitting assignment <strong>2</strong></li>

</ul>

<ul>

 <li><strong>&lt;Stud. No.&gt;</strong> refers to your UOW student number (e.g. 1234567)</li>

</ul>

<ul>

 <li><strong>&lt;Name&gt;</strong> refers to your UOW registered name (e.g. JohnDoeAnderson)</li>

</ul>

<ul>

 <li><strong>Where to submit </strong></li>

</ul>

Please submit your assignment via Moodle eLearning site.

<strong>In the event of UNFORSEEN SITUATIONS : </strong>

( E.g.  Student’s moodle account not ready, cannot login to moodle, eLearning site down on submission day, unable to upload assignment, etc )




Please email your single zip file to your tutor at :

<a href="/cdn-cgi/l/email-protection#c8abbbaba1faf8fcbda7bf88b1a9a0a7a7e6aba7a5"><span class="__cf_email__" data-cfemail="c6a5b5a5aff4f7f486bfa7aea9a9e8a5a9ab">[email protected]</span></a>             for<em> <strong>FULL</strong></em> TIME students

<table>

 <tbody>

  <tr>

   <td width="498"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

(To be announced)                      for <strong><em>PART</em></strong> TIME students

In your email <strong>subject</strong> line, type in the following information :

<strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong> &lt;assignment info&gt; &lt;<strong>student number</strong>&gt; and &lt;<strong>name</strong>&gt;

<table>

 <tbody>

  <tr>

   <td width="155"></td>

   <td width="41"></td>

   <td width="40"></td>

   <td width="14"></td>

   <td width="57"></td>

   <td width="47"></td>

   <td width="33"></td>

   <td width="47"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td rowspan="3"></td>

   <td></td>

   <td rowspan="4"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="2"></td>

   <td></td>

   <td></td>

   <td rowspan="4"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="4"></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>




Example:

<strong>            To</strong>                   :           <strong><a href="/cdn-cgi/l/email-protection#d5b6a6b6bce7e5e1a0baa295acb4bdbabafbb6bab8">tutor’s</a> email</strong> (see above)

<strong>            Subject</strong>          :           <strong>FT</strong> Assn<strong>1</strong> <strong>1234567</strong> <strong>JohnDoeAnderson</strong>

<strong><em>Note 1 : </em></strong>        The timestamp shown on tutor’s email Inbox will be used to determine if the                               assignment is late or not.

<strong><em>Note 2 : </em></strong>        After email submission, your mailbox’s  <strong><em>sent folder</em></strong>  would have a                                         copy (record) of your sent email, please <strong><u>do not delete</u></strong> that copy !!  It could                                     be used to prove your timely submission, in case the Tutor did not receive                                     your email!

<ul>

 <li><strong>When to submit</strong></li>

</ul>

<ol>

 <li>Depending on the time-table, a <u>demo / evaluation for your assignment</u> may be scheduled during the 3<sup>rd</sup> – 5<sup>th</sup> lab session for the semester (i.e. lab 3 – 5).</li>

</ol>

Please consult your tutor for further details. Some time may be allocated for each student to present / explain your system design during the session.

Please submit your files <u>1 day before</u> the start of your demo / evaluation lab session.

<ol>

 <li>To illustrate, please refer to the following table on the different submission events and deadlines</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="93"><strong>Assignment</strong></td>

   <td width="221"><strong>Submission Deadline</strong></td>

   <td width="145"><strong>Assignment Evaluation (Tasks)</strong></td>

   <td width="194"><strong>Email Evaluation files by :</strong></td>

  </tr>

  <tr>

   <td width="93">1</td>

   <td width="221">Night before Lab – 2(PT), 3(FT)</td>

   <td width="145">Lab 2(PT), 3(FT)</td>

   <td width="194">End of Lab 2(PT), 3(FT)</td>

  </tr>

  <tr>

   <td width="93">2</td>

   <td width="221">Night before Lab – 3(PT), 4(FT)</td>

   <td width="145">Lab 3(PT), 4(FT)</td>

   <td width="194">End of Lab 3(PT), 4(FT)</td>

  </tr>

  <tr>

   <td width="93">3</td>

   <td width="221">Night before Lab – 4(PT), 5(FT)</td>

   <td width="145">Lab 4(PT), 5(FT)</td>

   <td width="194">End of Lab 4(PT), 5(FT)</td>

  </tr>

 </tbody>

</table>


