# Invoice_Extraction
Bussiness Problem:

The client has invoices in PDF format, which contains information like invoice number, client name, client email,due date etc., To extract required data from invoice PDF manually takes much effort, long hours and human errors.

Solution:

I have created a script using Python Programming that can extract data from Invoice PDF in Minutes which not only reduces time but also human errors.

In this Project am using 100 Invoice PDFs with same template.
Here, am using two methods two fetch data from invoice, One is pattern matching and the second is key value matching.
Pattern matching is done using Regex (Regular Expressions), data i used in this project has static patterns such as email, phone number, zipcode.
And the other data like invoice number, subtotal, tax, client name etc is fetched using key value matching that is possible by PyMuPDF library.

datasource: https://www.kaggle.com/datasets/riddhimanghatak/invoice-dataset
