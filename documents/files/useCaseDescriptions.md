# WZC De Witte Meren: Use Case Descriptions

## Use Case 1: View contents
### Functionality
As a user I can view the contents of the website.
### Normal flow
The system displays the "De Witte Meren" website home page. The Actor can view the contents of the home page. The Actor selects another page from the Navbar on the home page. The system redirects the Actor to the selected page and displays the contents of the selected page. 

## Use Case 2: Register for admission
### Functionality
As a user I can register for admission.
### Preconditions
The Actor is on the admission page
### Normal flow
The system displays an admission form with data the Actor has to fill in (name, surname, medical information, ...). The Actor fills in the required data and submits the form. The system archives the document, converts the document to PDF and via an external mail service the document is send to the correct mailbox.
### Alternatives
**Forgotten input field**: The Actor forgot to fill in an input fields but wants to submit the form. The system displays a message stating the Actor for a certain input field that is required. The Actor fills in the required field and sumbits the form.
**Wrong format**: The Actor didn't follow the format that an input field requires but wants to submit the form. The system displays a message saying the Actor filled in a certain input field in the wrong format. The Actor fixes his mistake and submits the form.

## Use Case 3: Register for event
### Functionality
As a user I can register for an event
### Preconditions
The Actor is on the event page
### Normal flow
The system displays an register for event form with data the Actor has to fill in (name, surname, ...). The Actor fills in the required data and submits the form. The system archives the document, converts the document to PDF and via an external mail service the document is send to the correct mailbox.
### Alternatives
**Forgotten input field**: The Actor forgot to fill in an input fields but wants to submit the form. The system displays a message stating the Actor for a certain input field that is required. The Actor fills in the required field and sumbits the form.
**Wrong format**: The Actor didn't follow the format that an input field requires but wants to submit the form. The system displays a message saying the Actor filled in a certain input field in the wrong format. The Actor fixes his mistake and submits the form.

## Use Case 4: Manage website contents
### Functionality
As a admin I can manage the website contents
### Preconditions
The actor has administrative rights to the website
### Normal flow
The Actor makes changes to the website contents (texts, pictures, etc.). The system updates with the contents updates.

## Use Case 5: Manage website structure
### Functionality
As a admin I can manage the website structure
### Preconditions
The actor has administrative rights to the website
### Normal flow
The Actor makes structure changes to the website (layout, color, orientation, branding, ...). The website updates with the structure changes.
















