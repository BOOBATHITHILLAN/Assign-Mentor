# Assign-Mentor

A) For Local server (ie... Before render deployment)

1.To create Mentor (Post method)
  http://localhost:3001/mentor

2. To create Student (Post method)
   http://localhost:3001/student

3. Assign Student to Mentor (Post method)
   http://localhost:3001/assign/:mentorId/:studentId

4. Re-assign Student to Mentor (Post method)
    http://localhost:3001/reassign/:mentorId/:studentId

5. Get all students for a particular mentor  (Get Method)
   http://localhost:3001/mentor/:mentorId  example=> http://localhost:3001/mentor/64b0c03b5679577bd7c1a39e

6. Get previously assigned mentor for a particular student  (Get Method)
   http://localhost:3001/student/:studentId example=> http://localhost:3001/student/64b0c0585679577bd7c1a3a0

B) After Render Deployment
1.To create Mentor  (Post method)
  https://assignmentor-backend-nodejsexpressjs.onrender.com/mentor

2. To create Student (Post method)
   https://assignmentor-backend-nodejsexpressjs.onrender.com/student

3. Assign Student to Mentor (Post method)
   https://assignmentor-backend-nodejsexpressjs.onrender.com/assign/:mentorId/:studentId

4. Re-assign Student to Mentor (Post method)
   https://assignmentor-backend-nodejsexpressjs.onrender.com/reassign/:mentorId/:studentId

5. Get all students for a particular mentor (Get Method)
   https://assignmentor-backend-nodejsexpressjs.onrender.com/mentor/:mentorId
   Example  https://assignmentor-backend-nodejsexpressjs.onrender.com/mentor/64b0c03b5679577bd7c1a39e

6. Get previously assigned mentor for a particular student (Get Method)
   https://assignmentor-backend-nodejsexpressjs.onrender.com/student/:studentId
   Example  https://assignmentor-backend-nodejsexpressjs.onrender.com/student/64b0c0585679577bd7c1a3a0
