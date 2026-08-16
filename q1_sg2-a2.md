# Annex C <br> Code Quality Assessment Worksheet

Section: 9 - Arayat 

25 / Louise Cassidy D. Panganiban
<br> 26 / Desiree L. Pasawa
<br> 27 / Caitlin Mariel T. Pineda

Score:____________
<br> Date: August 16, 2026


<br> **Instructions:**

The problem: Finding the highest (Maximum) number from a given list of numbers.

<img width="824" height="511" alt="Screenshot 3226-08-06 115556" src="https://github.com/user-attachments/assets/3f4861a3-9871-4aaf-b89d-5a43620e1665" />

<br> **Questions with Checklists**
<br> **1. Efficiency**
<br> Which algorithm is faster when the list of numbers is very large? Why?

Algorithm one is faster when dealing with a list of larger numbers because it only uses one loop, while algorithm two uses two nested loops. The first algorithm avoids unnecessary repetitions and therefore also finishes in fewer steps. 

<img width="824" height="120" alt="Screenshot 3226-08-06 115934" src="https://github.com/user-attachments/assets/d61233c3-735b-445d-93e0-8af9454b8f44" />


<br> **2. Readability**
<br> Which algorithm is easier to understand at first glance? What makes it clearer?

Algorithm one is easier to understand at first glance because the logic and naming conventions used are simple yet still meaningful. For example, it uses "max" as a clear name for one variable, compared to algorithm two's "bigger." It also has fewer lines of code which makes it easier for the user to revise. 

<img width="824" height="160" alt="Screenshot 3226-08-06 120138" src="https://github.com/user-attachments/assets/1b67f6a2-67c4-4466-b92d-5b98f9dd5a75" />

<br> **3. Maintainability**
<br> If you had to add a new feature (like finding both max and min), which algorithm would be easier to update? Why?

 It would be easier to update the second algorithm since it tests every number individually, instead of looking for just the maximum. In this case, we can adjust the code so that it not only tests each number for the maximum value, but also for the minimum.

<img width="823" height="162" alt="Screenshot 3226-08-06 120435" src="https://github.com/user-attachments/assets/954a576b-24ea-478a-a600-79aad23a406c" />

<br> **4. Testability**
<br> Which algorithm is easier to test with different inputs? Why?

Algorithm one is easier/simpler because it does a one-to-one comparison with the number after itâ€”unlike algorithm two, which tests all numbers individuallyâ€”making the current number the maximum until it finds a higher value.

<img width="824" height="163" alt="Screenshot 3226-08-06 120644" src="https://github.com/user-attachments/assets/f0646e12-056d-4d45-9fe3-94a1ccf4f2a2" />

<br> **5. Security**
<br> Imagine the input list comes from a user. What should the algorithm check to avoid errors or misuse?

The algorithm should first check if the list contains any numbers before trying to find the highest value. It should also check whether the inputs are valid numbers and reject or handle inputs such as letters or other invalid characters. This helps prevent errors and keeps the algorithm from crashing when the user enters unexpected or unusual data. Adding these checks would make the algorithm safer and more reliable when handling different types of user input.

<img width="824" height="184" alt="Screenshot 3226-08-06 120812" src="https://github.com/user-attachments/assets/b8c56102-2334-4065-a925-9e4bad71119f" />

<br> **6. Final Answer**
<br> Based on your answers from 1 to 5, which one is the better algorithm that you will use to solve the problem of finding the highest number? Why? Summarize your answer

Algorithm one is the better choice for finding the highest number because it is faster, simpler, and easier to understand. It uses fewer comparisons and does not repeat the same work unnecessarily, which makes it more efficient when working with a large list of numbers. Its straightforward logic also makes the code easier to read, modify, and maintain. Although algorithm one is already more efficient, adding checks for empty lists and invalid inputs would make it more reliable and safer to use.
