# Admission_Enquiry_Form
## Date: 7/7/25

### NAME : HARISH RAGAV S 

### LIVE PAGE - https://harishragav-s.github.io/Admission_Enquiry_Form/
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
```
<!DOCTYPE html>
<html>
<head>
    <title>Admission Enquiry Form</title>
</head>
<body>

    <h1>Admission Enquiry</h1>

    <form>
        Full Name:<br>
        <input type="text" name="fullname" placeholder="Enter your full name" required><br><br>

        Email Address:<br>
        <input type="email" name="email" placeholder="Enter your email" required><br><br>

        Phone Number:<br>
        <input type="tel" name="phone" placeholder="Enter your phone number" required><br><br>

        Program of Interest:<br>
        <input type="text" name="program" placeholder="Enter program name" required><br><br>

        Message:<br>
        <textarea name="message" rows="5" cols="40" placeholder="Write your message here" required></textarea><br><br>

        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
    </form>

</body>
</html>
```

## Output:
![image](https://github.com/user-attachments/assets/cdb485c7-e16d-4df6-b933-ea0f24ff2d0a)


## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
