**Contact Book**

We come across lots of people daily. We make acquaintances and friends. We get their contacts to keep in touch later on. Sadly, keeping the received contact details can be hard. One way to do this is to write the contact details down. But this is not secure as the physical book can easily be lost.
This is where the Contact Book project comes in. A contact book is a tool for saving a contact�s details, such as name, address, phone number, and email address. With this contact book project, you can build a software tool that people can use to save and find contact details.
With the contact book project idea, users can save their contacts with less risk of losing the saved contact details. It�ll always be accessible from their computer, through the command-line.

*Technical Details*
The main objective of this project is to save contact details. It�s important that you set up the commands users can use to enter the contact details. You can use the argparse or click command-line frameworks. They abstract a lot of complex stuff, so you only have to focus on the logic to be run when executing commands.
Some features you should implement include the commands to delete contacts, update contact information, and list saved contacts. You can also allow users to list contacts using different parameters, such as alphabetical order or contact creation date.
Since it�s a command-line project, the SQLite database will be fine for saving contacts. SQLite is user-friendly to set up. You may save the contact details in a file, but a file will not offer the benefits you can gain from using SQLite, such as performance and security.
To use the SQLite database in this project, the Python sqlite3 module will be very useful.