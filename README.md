# 1 Welcome!

This document is the specification sheet for your work sample.

The application you have to create is a simple product inquiry web.

Where a customer can make an inquiry regarding a customized design of jewelry.

Therefore, you have to take in account the following points:

1. You can only use the stable version Laravel or Lumen framework
2. The well integration of testing is explicitly desired
3. Strive for good code coverage
3. Quality over quantity

If you have questions, do not hesitate to ask us.

# 2 Backend

Save all the data in the MySQL database or SQLite.

Use background processing for a complex or long-running request.

You have to create the relational data model by yourself with regard to the requirements.

Take care of a structured naming.

*Bonus point for well implemented design pattern.*

# 3 Frontend

Strive to create a testable frontend.

*Bonus point for implementing SPA*

## 3.1 Inquiry page

The root page of the page is the inquiry page.

A customer can submit an inquiry right away without have to log in.

Take care of abusive user, every unique IP address only allowed to submit data once every 10 seconds.

Implement a mechanism to prevent this on server side.

If the inquiry contains reference to a website, that website will be fetched by our system and save as an image.

![Submit page wireframe](./submit_form.png)

## 3.2 Email notification to customer

After an inquiry submitted, an email notification send to customer contains a link to 

a page where they can view their inquiry.

## 3.3 Email notification to admin

After an inquiry submitted, an email notification send to admin.

## 3.4 Login

This page only intended for admin to access all submitted data.

## 3.5 List of inquiries

After logging in, all submitted inquiries will be shown in a table pagination.

When a new inquiry submitted, it will be pushed to the table right away, so admin don't have to refresh the page.


## 3.6 Inquiry detail

That image will be shown at inquiry detail.
