# Library-Management-System---Zoho-creator

1.	Books Module :
  Create a form with the following fields: 
      Book ID (Auto-generated)
      Title (Text - Mandatory)
      Author (Text - Mandatory)
      Genre (Dropdown - Predefined values: Fiction, Non-Fiction, Sci-Fi, Biography)
      Publication Year (Number - Only valid years between 1900 and the current year)
      Available Copies (Number - Mandatory, minimum value = 0)
      ISBN Number (Text - Unique validation)
      Rating (Number - Accept values between 1 to 5)



2.  Members Module  :
   Create a form with the following fields: 
      Member ID (Auto-generated)
      Name (Text - Mandatory)
      Email (Email - Validate for proper email format)
      Phone Number (Number - Mandatory, validate for 10 digits)
      Membership Start Date (Date - Default to the current date)
      Membership Type (Dropdown - Values: Basic, Premium, Elite)
      Max Books Allowed (Number - Auto-filled based on Membership Type: Basic=2, Premium=5, Elite=10)



3.	Transactions Module  :
	Create a form with the following fields: 
      Transaction ID (Auto-generated)
      Member (Lookup to Members)
      Book (Lookup to Books)
      Issue Date (Date - Default to the current date)
      Return Date (Date - Must be greater than Issue Date)
      Status (Dropdown - Values: Issued, Returned, Overdue)
      Fine Amount (Currency - Auto-calculated for overdue books)

   
4.	Staff Members Module  :
  Create a form with the following fields: 
      Staff ID (Auto-generated)
      Name (Text - Mandatory)
      Email (Email - Validate for proper email format)
      Role (Dropdown - Values: Librarian, Assistant)
      Phone Number (Number - Mandatory, validate for 10 digits)

   
role-based permissions: 
	Librarians can issue and return books.
	Assistants can only view books and members but cannot make changes.

https://youtu.be/jThwZGQcojI
