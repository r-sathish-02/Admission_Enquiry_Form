# Admission_Enquiry_Form
## Date:

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Saveetha Engineering College - Admission Enquiry</title>
    </head>
    <body>
        <h1 align="center">Admission Enquiry Form</h1>
        <form method="post">
            <label>Full Name:</label><br>
            <input type="text" id="fullName" name="fullName" required><br><br>
            <label>Email Address:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label>Mobile Number:</label><br>
            <input type="tel" id="mobileNumber" name="mobileNumber" required><br><br>
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label>Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label>Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label>Other</label><br><br>
            <label>Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>
            <label>Department Interested:</label><br>
            <select id="department" name="department" required>
                <option value="">Please select</option>
                <option value="CSE">Computer Science and Engineering</option>
                <option value="ECE">Electronics and Communication Engineering</option>
                <option value="EEE">Electrical and Electronics Engineering</option>
                <option value="MECH">Mechanical Engineering</option>
                <option value="CIVIL">Civil Engineering</option>
                <option value="IT">Information Technology</option>
                <option value="AI_DS">Artificial Intelligence and Data Science</option>
            </select><br><br>
            <label>Academic Qualification:</label><br>
            <textarea id="academicQualification" name="academicQualification" rows="5" cols="50" required></textarea><br><br>
            <label>Address:</label><br>
            <textarea id="address" name="address" rows="5" cols="50" required></textarea><br><br>
            <label>Preferred Mode of Contact:</label><br>
            <input type="checkbox" id="contactEmail" name="contactMode" value="email">
            <label>Email</label><br>
            <input type="checkbox" id="contactPhone" name="contactMode" value="phone">
            <label for="contactPhone">Phone</label><br><br>
            <input type="submit" value="Submit Enquiry">
        </form>
    </body>
</html>
## Output:
![image](https://github.com/user-attachments/assets/65afccf0-763a-4909-a6fd-721069a204f8)

## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
