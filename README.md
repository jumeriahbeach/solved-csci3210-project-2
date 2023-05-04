Download Link: https://assignmentchef.com/product/solved-csci3210-project-2
<br>
<strong>Goal:</strong><strong> To be familiar with the language you are going to present . </strong>

<strong>Problem</strong> : Suppose at the end of the semester, there is a file “scores.dat” recording scores each student has earned so far from closed lab assignments (CLA), open lab assignments (OLA), quizzes, exams, and final exam score. You can assume there are no more than 30 students. The final letter grade is decided according to the following table based on the total points they have earned:

<table width="619">

 <tbody>

  <tr>

   <td width="152"><strong>Total Points</strong></td>

   <td width="153"><strong>Final Letter Grade</strong></td>

   <td width="153"><strong>Total Points</strong></td>

   <td width="152"><strong>Final Letter Grade</strong></td>

  </tr>

  <tr>

   <td width="152">&gt;=90</td>

   <td width="153">A</td>

   <td width="153">&gt;=70, but &lt;73</td>

   <td width="152">C-</td>

  </tr>

  <tr>

   <td width="152">&gt;=87, but &lt;90</td>

   <td width="153">B+</td>

   <td width="153">&gt;=67, but &lt;70</td>

   <td width="152">D+</td>

  </tr>

  <tr>

   <td width="152">&gt;=83, but &lt;87</td>

   <td width="153">B</td>

   <td width="153">&gt;=63, but &lt;67</td>

   <td width="152">D</td>

  </tr>

  <tr>

   <td width="152">&gt;=80, but &lt;83</td>

   <td width="153">B-</td>

   <td width="153">&gt;=60, but &lt;63</td>

   <td width="152">D-</td>

  </tr>

  <tr>

   <td width="152">&gt;=77, but &lt;80</td>

   <td width="153">C+</td>

   <td width="153">&lt;60</td>

   <td width="152">F</td>

  </tr>

  <tr>

   <td width="152">&gt;=73, but &lt;77</td>

   <td width="153">C</td>

   <td width="153"> </td>

   <td width="152"> </td>

  </tr>

 </tbody>

</table>

In this assignment, you are asked to write a program to calculate student final letter grades as well as the average and highest scores of CLA, OLA, quizzes, exams, and final exam scores. The final result should be printed to the screen (standard output).

<strong>Requirements:</strong>

<ul>

 <li>At the beginning of the program, your program should give the user a prompt for the name of the data file which contains the records of student grades.</li>

 <li>Define a class Student, which includes student id, scores for CLA, OLA, quizzes, exams, final scores, total points, and letter grade. All member data must be private. The class must provide a function to calculate the final letter grade.</li>

 <li>Store all <em>Student</em> objects in an associative array (other similar data structures like map, hash map are also fine) so that we can lookup student final letter grade by C#.</li>

 <li>Your program should allow users to perform two queries. For each query, the user inputs C#, and your program should print all information (including his/her final letter grade) of the student with the given C#. After two queries, your program print information of all students on the screen.</li>

 <li>If the language doesn’t support object-oriented programming or associative array, then use appropriate data structures.</li>

 <li>If the language doesn’t support file input, you can store them in your program.</li>

</ul>




Make sure that your program has the proper documentation (program heading, variable explanation, description/input/output for each user defined function, explanation for logically related statements, etc), and style for good program readability and modifiability. Refer to the back page for more details on program requirements your program should follow.




<strong>What to be submit?</strong>

Besides Rubric2.doc and your source program, please submit the following:

<ul>

 <li>A document, which must specifies how you set up your development environment, including but not the least,

  <ul>

   <li>Where to download the IDE or compiler</li>

   <li>How to install the IDE or compiler</li>

   <li>How to compile your program</li>

   <li>How to execute your program</li>

  </ul></li>

 <li>A short video showing the execution of your program, including the following steps

  <ul>

   <li>Display your program</li>

   <li>Compile your program</li>

   <li>Execute your program</li>

  </ul></li>

</ul>




<strong>How to make Video:</strong>

Never using cell phone or camera to record video from your screen. Instead, please use a screen recording software to produce the video with better quality. The following are some tools recommended from other students in previous semesters:

<ul>

 <li>ffmpeg https://www.ffmpeg.org/</li>

 <li>VLC http://www.videolan.org/vlc/index.html</li>

 <li>OBS https://obsproject.com/</li>

 <li>Active Presenter: http://atomisystems.com/activepresenter/free-edition/</li>

</ul>





