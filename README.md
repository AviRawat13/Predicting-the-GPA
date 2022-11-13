<h1>Predicting the GPA</h1>
 Predicting the GPA of University Students with Supervised Regression Machine Learning Model.
<br>
<h2>Introduction</h2>
  The abilities and knowledge of each student are evaluated during his studies with grades
  or percentages that tell us how good the student is in the study. This evaluation gives us the
  GPA and according to it we consider students to be good, bad, talented or lazy. Students’
  learning outcomes and achievements during their university studies can be influenced by
  many factors, such as learning patterns, talents, interpersonal relationships, motivation and
  many others. The student’s results can subsequently affect life after graduation and can even
  help with finding a job. However, it is not always important what academic results the student
  has achieved during their studies, and for many employers, the experience and what they can
  do is much more important. Not surprisingly, many people with a worse academic result or
  without a university degree are very successful in their lives.
<br>
<h2>Problem</h2>
  The SAT is a test widely used for college admission in USA. People think that students that achieve high score in SAT, have also the highest GPA during college. In     this competition we want to predict the average GPA cumulated by a student in the college, based only on the scores that he/she achieved in SAT.
<br>
<h2>Dataset</h2>
  You are given a training dataset, in which each row contain the student ID, SAT score and average GPA cumulated during college. Use this dataset for training your     model and then test your model using test dataset. Each row of test dataset contain student ID and SAT score. Finally you should submit a CSV file, that contains the   student ID , and predicted GPA score for each row of the test dataset.
  
<h2>Regression Used</h2>
  The formula for a simple linear regression is:

  y = {\beta_0} + {\beta_1{X}} + {\epsilon}
  y is the predicted value of the dependent variable (y) for any given value of the independent variable (x).
  B0 is the intercept, the predicted value of y when the x is 0.
  B1 is the regression coefficient – how much we expect y to change as x increases.
  x is the independent variable ( the variable we expect is influencing y).
  e is the error of the estimate, or how much variation there is in our estimate of the regression coefficient.
  Linear regression finds the line of best fit line through your data by searching for the regression coefficient (B1) that minimizes the total error (e) of the model.

While you can perform a linear regression by hand, this is a tedious process, so most people use statistical programs to help them quickly analyze the data.
<br>
<h2>Python Libraries Used:-</h2>
  <ul>
    <li>Numpy</li>
    <li>Pandas</li>
    <li>Matplotlib</li>
    <li>Sklearn</li>
  </ul>
 <h2>Authors</h2>
  <li><a href="www.linkedin.com/in/avi-rawat">AviRawat</a>
 <h2>License</h2>
This project is licensed under the MIT License.
  
Copyright (c) 2022 Avi Rawat
  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:    
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
