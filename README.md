# Design-Thinking-Website-code
Group-3(201-A)
1. HTML Structure:
The page is a form that allows users to place an order for printing a PDF document, with options for number of copies, print type, binding, and pickup time.
2. Head Section:
It includes the metadata (<meta>) for proper character encoding and responsive design, a title for the page, and a link to an external CSS stylesheet (style1.css) for styling.
3. Header:
A header section contains the site name (PrintEz) and navigation links (Home, Orders, Contact).
4. Main Content - Form:
The form allows users to submit their order information via the POST method to page2.html. It contains:
File Upload: Allows the user to upload a PDF file.
Number of Copies: A number input to specify how many copies to print.
Print Type: A dropdown to choose between black-and-white or color printing.
Printer Shop: A dropdown to choose which printer shop will handle the order.
Binding Options: A dropdown to select binding options (none or spiral binding).
Pickup Time: A time input to select when they want to pick up the order.
Submit Button: A button to submit the form when ready.
5. Improvements for Accessibility:
Each form input is paired with a <label> for better accessibility, helping screen readers and improving form usability.
The form includes a required attribute for mandatory fields to ensure they are filled before submission.
6. Form Action and Method:
The form will send data to page2.html when submitted, using the POST method (for secure data transfer).
The enctype="multipart/form-data" is specified for file uploads to ensure the PDF can be uploaded correctly.
7. CSS:
The external style1.css file is linked for styling, which would control the appearance of the page (though it’s not shown in this code snippet).
Summary:
This code builds a simple and functional print order page where users can upload a PDF, choose print settings (number of copies, print type, printer shop, binding), and specify a pickup time. The form is styled with an external CSS file, and includes basic form validation.
