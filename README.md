Download Link: https://assignmentchef.com/product/solved-cosc2452-week6-independent-investigative-effort-5
<br>
<table width="748">

 <tbody>

  <tr>

   <td width="748">5. This week’s programming task will cover concepts required by Assignment 2. You should aim to get the help of your tutors and make further revisions.<strong>Coding exercise steps (Hint: Need help? Ask your tutor via Canvas→Discussions→”IIE06″):</strong>Complete the 04/Jan/2021 solution first as this extends upon that work. Next follow Canvas→<a href="https://rmit.instructure.com/courses/70691/modules">Modules→Week 6</a> where the topics of creating non-static methods is explained. <strong>Your tutors will provide further explanations on these general topics and how they relate to this IIE during their weekly “tutor chats”</strong>.<strong>a) </strong>Your IIE05 solution as developed during 4/Jan/2020 is given at the end of this document for ease of reference. It takes the following overall layout:<strong>public</strong> <strong>class</strong> PleaseRenameMe { <strong>public</strong> <strong>static</strong> <strong>void</strong> main(String[] args) {GTerm gt = <strong>new</strong> GTerm(600, 400);// Rest of code}}Make a copy of the IIE05 solution that uses GTerm and rename it to IIE06 and refactor your code to fit the following structure:// The instructions in the comments must be followed when for all programs in <u>Intro</u> To Programming assessments from now on.<strong>public</strong> <strong>class</strong> PleaseRenameMe {// The following are “object member variable” declarations.// All declarations at this level must be explicitly private and must not mention ‘static’.// There should be no = (equals) signs here here. <strong>private</strong> GTerm <u>gt</u>;// The following is the “constructor” method <strong>public</strong> PleaseRenameMe() {// Object member variable declarations must be <u>initialised</u> before doing anything else.// Any reference to an object member variable must always start with “this.” <strong>this</strong>.gt = <strong>new</strong> GTerm(600, 400);// Rest of code (remember to start with “this.” when referring to object member variables)}<strong>public</strong> <strong>static</strong> <strong>void</strong> main(String[] args) {PleaseRenameMe <u>prmObj</u>=<strong>new</strong> PleaseRenameMe();}}</td>

  </tr>

  <tr>

   <td width="748">Run the code and test it. It should look as it did in IIE05. i.e. there should be no difference to the end-user. Are you stuck? Please ask your</td>

  </tr>

 </tbody>

</table>

<strong>Access issues:</strong> For non-programming technical issues (relating to infrastructure, passwords, etc.) please call the <a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/service-and-support-centre">RMIT IT Service and </a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/service-and-support-centre">Support Centre</a> for quick help on 03-9925 8888 and remember to ask for a reference number and pass it on to your instructor.

<strong>Extensions: </strong>For all new extensions,  <a href="https://specon.rmit.edu.au/specon/"> </a><a href="https://specon.rmit.edu.au/specon/">a</a><a href="https://specon.rmit.edu.au/specon/">  </a><a href="https://specon.rmit.edu.au/specon/">pply for special consideration online</a> .  Contacting your tutors, instructors first will lead to delays.

<strong>Please follow/complete all steps below in the given sequence:</strong>

<ol>

 <li>Check your <a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">official</a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">  </a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">@student.rmit.edu.au e</a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">  </a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">mail account</a>  for announcements and other communication from the university. If getting in touch with your instructors, please only use this account (not Canvas inbox, messages, personal email, phone, Microsoft Teams, etc.)</li>

 <li><a href="https://rmit.instructure.com/courses/70691/pages/how-to-watch-recordings-of-live-lessons?module_item_id=2768983">Watch any unwatched recordings</a> of the <strong>Weekly Live Lecture</strong> and complete all missed tutorials <strong>before going further</strong>. For your convenience, the time stamps of recordings are sent via student email/Canvas→Announcements.</li>

 <li>Is there something that you have not fully grasped from what has been covered so far? Please have your doubts clarified via one of the relevant forums under <a href="https://rmit.instructure.com/courses/70691/discussion_topics">Canvas→Discussions</a>. Leaving gaps has shown to be severely detrimental to learning.</li>

 <li>Did you want to make any additions to the previous IIE? Please do by replying to your original post. i.e. do not edit, change the images of existing posts as it affects submission timing.</li>

</ol>




<table width="748">

 <tbody>

  <tr>

   <td width="748">friendly tutor by creating a post in the relevant IIE forum.<strong>b.                   </strong>Move all of your array declarations (you need to include all of them) and variable declarations that correspond with ‘currentNumStudents’ and ‘maxNumStudents’ (refer to IIE05 solution) to the object member variable level (ensure that they are named to suit your program). Also ensure that they follow the guidelines given in the 5a’s comments. The array creation and variable initialisations should still be inside the constructor. Ensure that, when a method refers to an object member variable (or array), it starts with <strong><sub>this</sub></strong><sub>.</sub> (“this dot”) at all times. Run the program and ensure that it works. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.<strong>c.                    </strong>Create the following method (it must be at the same level as the other methods, not inside any other methods):<strong>public</strong> <strong>void</strong> refreshTable() {// 1. Clear the rows of the table.// 2. Loop through the arrays and add each record to the table}Implement the steps in the above method’s comments. You will need to make the loop (step 2) repeat from 0 to currentNumStudents. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.<strong>d.                   </strong>Next, modify your old code (which should still be in the constructor) so that it does not invoke/use the .addRowToTable method. Instead, it calls the refreshTable method when it needs to display values in the table. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.<strong>e.                    </strong>After the statement that adds the table, add the following statement:<strong>this</strong>.gt.addButton(“Add”, <strong>this</strong>, “addRecord”);Run the program and verify that there is a button named “Add”.Now implement the following method (it must be at the same level as the other methods, not inside any other methods):<strong>public</strong> <strong>void</strong> addRecord() {// 1. Take comma separated inputs of a record// 2. Split the input// 3. Add the split input in to the array, increment currentNumRecords// 4. Call refreshTable}After implementing the above (and its comments), you may want to remove the loop-based record adding code from the IIE05 solution.i.e. now, when the user wants to add one record, they will select the “add” button. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.<strong>f.                    </strong>Investigative exercise: With the help of your tutor, investigate in the <a href="https://img1.wsimg.com/blobby/go/d666d560-b60b-4b59-9db3-e2778fabc10a/downloads/GTerm-Documentation-2020.08.25.pdf?ver=1609742780215">GTerm documentation</a> (Javadoc) for a suitable method to add a text field (or several). Modify your addRecord code so that it takes what is in the text field, instead of using .getInputString. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.<strong>g.                   </strong>Create a copy of the above IIE06 project and name it IIE06C. Make this version use Scanner’s .nextLine + System.in for inputs and System.out for outputs (GTerm, JoptionPane, etc. should not be mentioned). It should provide all of the functionality that the GTerm version allowed. </td>

  </tr>

 </tbody>

</table>