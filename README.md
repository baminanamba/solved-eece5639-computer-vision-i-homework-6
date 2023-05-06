Download Link: https://assignmentchef.com/product/solved-eece5639-computer-vision-i-homework-6
<br>
<span style="font-size: 2.61792em; letter-spacing: -1px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Homographies, Stereo and Motion</span>

<ol>

 <li>Explain the differences between a planar homography between two images, the Essential and theFundamental matrices in stereo.</li>

 <li>Where are the epipoles in the case when the two cameras have parallel optical axes (the “canonical”configuration)?</li>

 <li>Show how the projection of a point in a planar scene at world coordinates (<em>X,Y </em>) to pixel coordinates (<em>u,v</em>) in an image plane can be represented using a <em>planar affine camera model</em>. Under what conditions is the use of an affine transformations appropriate when viewing a planar scene? How many degrees of freedom are there in the model and what is the minimum number of calibration points needed to estimate the transformation? What effects can a planar affine transformation have on parallel lines?</li>

 <li>Consider the convergent binocular imaging system shown below. The cameras and all the points arein the <em>y </em>= 0 plane. The image planes are perpendicular to their respective camera axes. Find the disparity corresponding to the point <em>P</em>. <em>Hint</em>: The perpendicular distance between any point√ (<em>x<sub>o</sub>,y<sub>o</sub></em>)</li>

</ol>

an a line given by <em>ax </em>+ <em>by </em>+ <em>c </em>= 0 is (<em>ax<sub>o </sub></em>+ <em>by<sub>o </sub></em>+ <em>c</em>)<em>/ a</em><sup>2 </sup>+ <em>b</em><sup>2</sup>.

<em>x</em>

<ol start="5">

 <li>Determine the matrices <em>H<sub>l </sub></em>and <em>H<sub>r </sub></em>needed to normalize the entries of the fundamental matrix before estimating the Fundamental matrix using the Eight Point Algorithm. Hint: given a set of points</li>

</ol>

1

<strong>p</strong><em><sub>i </sub></em>= [<em>x<sub>i</sub>,y<sub>i</sub>,</em>1]<em><sup>T </sup></em>with <em>i </em>= 1<em>,…,n </em>define ¯<em>x </em>= 1<em>/n</em><sup>P</sup><em><sub>i </sub>x<sub>i</sub></em>, ¯<em>y </em>= 1<em>/n</em><sup>P</sup><em><sub>i </sub>y<sub>i </sub></em>and

Then find a 3 × 3 matrix <em>H </em>such that

<em>H</em><strong>p</strong><em><sub>i </sub></em>= <strong>p</strong>ˆ<em><sub>i </sub></em>with <strong>p</strong>ˆ<em><sub>i </sub></em>= [(<em>x<sub>i </sub></em>− <em>x</em>¯<em><sub>i</sub></em>)<em>/d,</em>(<em>y<sub>i </sub></em>− <em>y</em>¯<em><sub>i</sub></em>)<em>/d,</em>1]<em><sup>T </sup></em>with <em>i </em>= 1<em>,…,n</em>

<ol start="6">

 <li>Use the method of least squares to derive a linear system of equations to estimate the affine transformation that maps a set of points (<em>x<sub>i</sub>,y<sub>i</sub></em>) into new points (<em>x</em><sup>0</sup><em><sub>i</sub>,y<sub>i</sub></em><sup>0</sup>). Show that it is not necessary to solve a 6 × 6 system all at once, since the problem can be decomposed into two smaller sets of equations.</li>

 <li>(Old Exam) Two identical security cameras are mounted in a room as shown in the figure below. The world coordinate system W is at one corner of the room, and each camera has its own coordinate system C<sub>1 </sub>and C<sub>2</sub>. In the following, <em>P<sup>w</sup></em>, <em>P</em><sup>1 </sup>and <em>P</em><sup>2 </sup>represent the coordinates of a point <em>P </em>with respect to the world coordinate system W, the camera 1 coordinate system C<sub>1 </sub>and the camera 2 coordinate system C<sub>2</sub>, respectively. The <em>world coordinates </em>of the centers of projectionand are (2<em>,</em>2<em>,</em>4) and (4<em>,</em>3<em>,</em>3), respectively. The focal length of the cameras is 1 and their image planes are located at <em>z<sup>i </sup></em>= 1, <em>i </em>= 1<em>,</em>2, respectively.

  <ul>

   <li>Let <em>E</em><sub>1 </sub>and <em>E</em><sub>2 </sub>be the epipoles in camera 1 and 2 respectively. Find the camera coordinates and of the epipoles expressed in their respective camera systems.</li>

   <li>The cameras capture images of a fly in the room. Let <em>f</em><sub>1 </sub>and <em>f</em><sub>2 </sub>be the images of the fly in the first and second camera, respectively. The camera 1 coordinates of the image in the first camera are 1). Find the equation of the epipolar plane containing the fly, expressed in the camera 2 coordinate system. <strong>Hint: </strong>find</li>

   <li>The fly flies following a straight line with constant velocity <em>with respect to the world coordinate system</em>(−3<em>,</em>−2<em>,</em>−1). Find the <em>camera coordinates </em>of the FOE <strong>in camera 1</strong>.</li>

  </ul></li>

 <li>(Old Exam) Consider the Hankel matrix:

  <ul>

   <li>What is the complexity of the underlying dynamics?</li>

   <li>Find a regressor of the formexplaining the data in the given matrix.</li>

   <li>Find the values of <em>x </em>and <em>y</em>.</li>

  </ul></li>

</ol>

2