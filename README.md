
<h1>Computer Vision (CS 763) - Spring 2018 </h1>

<h2>Course Information</h2>
<ul>
<li><b>Instructor:</b> <a href="http://www.cse.iitb.ac.in/~ajain/">Arjun Jain</a>
<li><b>Office:</b> 216, CSE New Building
<li><b>Email:</b> <i>ajain@cse DOT iitb DOT ac DOT in</i>
<li><b>Teaching Assistants:</b> Rishabh Dabral, Safeer Afaque
<li><b>Instructor Office Hours (in room 216 CSE New Building):</b> Arjun is on campus only on Thursdays and Fridays. Meet him after class or fix an appointment over email.
</ul>

<h3> Please note that CS663 is a hard prerequisite for this course.</h3> 

<h2>Topics to be covered (tentative)</h2>
<ul>

<li> Camera geometry, camera calibration, vanishing points, important
transformations, homographies
<li> Deep Learning in computer vision: the data-driven paradigm, feed
forwards networks, back-propagation and chain rule; CNNs and their
building blocks, generative adverserial networks (GANs)
<li> Deep Learning applications including face detection, CNN
compression, siamese and triplet networks and applications to face
recognition
<li> Image registration: RANSAC for point-matching, SIFT overview
<li> Algorithms for: shape from shading, optical flow,
Kanade-Lucas-Tomasi algorithm, applications of optical flow
<li> Photometric stereo - deriving shape from multiple images of an
object taken under different lighting conditions; applications to
illumination invariant face recognition, face relighting
<li> Stereo (geometric binocular): epipolar geometry and fundamental
matrix, the correspondence problem and shape from stereo; structure
from motion
</ul>

<h2>Learning materials and textbooks</h2>
<ul>
<li> Lecture slides that will be regularly posted
<li><a href="http://szeliski.org/Book/">Computer Vision: Algorithms and Applications</a>, by Richard Szeliski</li>
<li><a href="http://crcv.ucf.edu/gauss/BOOK.PDF">Fundamentals of Computer Vision</a>, by Mubarak Shah</li>
<li> <a href = "http://www.deeplearningbook.org/">Deep Learning</a>, by Ian Goodfellow and Yoshua Bengio and Aaron Courville (freely downloadable!)
<li> All <a href="https://github.com/facebook/iTorch">iTorch</a> notebooks for topics covered in class can be found <a href="https://github.com/cs763-dl/2017Spring/tree/master/Notebooks">here</a>
</ul>

<h2>Grading Policy</h2>
<ul>
	<li> Mid-sem exam: 20%
	<li>Final exam (cumulative): 20%
	<li>Assignments (five or six): 35% (all to be done in groups of 2-3 students)
	<li>Course project: 20% (to be done in the same group of 2-3 students)
	<li>Class participation: 5%
	<li>Course project work will be presented by the student group during a viva at the end of the course. During this viva, each student in the group will be separately questioned, not only on the project work, but also the assignments. Each student is expected to contribute to each and every assignment and the course project. 
	<li>Audit requirements: You must write both exams, submit all assignments and the project, and score at least 40% to get an AU.
</ul>

<h2>Other Policies</h2>
<ul>
	<li> Assignments will be given out (typically) once every two or three weeks. They must be submitted on or before the deadline. No late assignments will be accepted. The programming components of the assignments will typically involve MATLAB and lua, so you must be willing to learn it quickly.
	<li><b>We will adopt a zero-tolerance policy against any forms of plagiarism or any other form of cheating. Just don't do it! In cases of plagiarism, givers and takers will both be considered equally responsible.</b>
	<li>This course is (inherently) cumulative. The syllabus for the final exam will include everything taught during the semester.
</ul>

<h2>Course Projects</h2>

Read this <a href="projects">link</a> for a list of project topics, and various instructions regarding course project submissions and expectations. You can also refer to "extra interesting readings" in the lecture schedule or Stanford <a href="http://cs231n.stanford.edu/reports.html">course CS231n</a> projects for ideas.
	
<h2>Assignments</h2>
TBD

<h2>Lecture Schedule: </h2>

<table>
  <tbody>  
    <tr>
      <th>Date</th>
      <th>Topics</th>
      <th>Slides</th>
      <th>iTorch Notebooks</th>
      <th>Extra Reading</th>
    </tr>  
    <tr>
      <td>4th Jan. 2018</td>
      <td><ul><li>Introduction to computer vision, applications and course overview <ul></td>
      <td><a href="https://www.dropbox.com/s/6w02e2w4w75xckm/L1.pdf?dl=0">Slides</a></td>
      <td align="center"> --
      </td>
      <td align="center">--</td>
    </tr>  
  
   <tr>
      <td>5th Jan. 2018</td>
      <td><ul>
	<li>Homogeneous coordinates and projective geometry
        <li>Vanishing points, ideal line, point line duality in P2
        <li>Important 2D and 3D transformations using homogeneous coordinates
        <li>Introduction to the pin-hole camera model
      </ul></td>
      <td><a href="https://www.dropbox.com/s/k70kt7x4ybd2o5b/L1.pdf?dl=0">Slides</a></td>
      <td align="center"> --
      </td>
      <td ><a href="http://www.ipb.uni-bonn.de/book-pcv/pdfs/PCV-A-sample-page.pdf">Homogeneous Representations of Points, Lines and Planes</a></td>
  </tr>
  </tbody>
</table>


