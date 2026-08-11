

 Cybersecurity Fundamentals

# What is Information Security?

Information Security, also called (InfoSec), is about protecting information from people who are not allowed to access it, change it, or destroy it.

The information can be in **digital form or physical form**.

For example:

* A company protects its customer information with passwords.
* A university keeps student files in a locked room.
* A company uses encryption to protect important data.

So, in simple words:

> **Information Security means protecting information from unauthorized access, change, loss, or damage.**

---

### What is Cybersecurity?

Cybersecurity is about protecting **computers, networks, phones, servers, websites, applications, and digital information** from attacks and unauthorized access.

For example:

* Protecting a computer from malware.
* Protecting a website from hackers.
* Using a firewall to protect a network.
* Detecting suspicious activity on a server.

So, in simple words:

> **Cybersecurity means protecting digital systems and data from cyber attacks and unauthorized access.**

### Difference between Information Security and Cybersecurity

The two are very closely related, but they are not exactly the same.

**Information Security** has a wider focus because it protects information whether it is stored on a computer, on paper, or somewhere else.

**Cybersecurity** mainly focuses on protecting digital systems and the information inside them from cyber threats.

For example, locking a confidential paper file in a cabinet is **Information Security**, while protecting a company's computer network from hackers is **Cybersecurity**.

---

# 2. Core Principles of Information Security

While learning Information Security, I came across some important principles that explain what good security should provide.

The main ones I learned are:

* **CIA Triad**
* **AAA**
* **DAD**

---

# 3. CIA Triad

CIA stands for:

* **Confidentiality**
* **Integrity**
* **Availability**

These are three main goals of Information Security.

---

## Confidentiality

Confidentiality means that information should only be accessible to **people who are  allowed or authorized to access it**.

In simple words, we don't want everyone to see private or sensitive information.

For example:

* A person should not be able to read someone else's private messages.
* Only authorized employees should be able to access a company's customer database.
* Important paper documents can be kept in a locked cabinet.

Some ways to protect confidentiality are:

* Passwords
* Access control
* Encryption
* Physical locks



note* : **Confidentiality means Don't let the wrong people see the information**

---

# Integrity

Integrity means that information should remain **correct and trustworthy** and should not be changed by someone who is not authorized.

For example:

* A student should not be able to change their own university grades.
* Someone should not be able to change the amount in a bank account without permission.
* An attacker should not be able to change important files on a server.

We can use things such as **access controls, hashes, and digital signatures** to help protect integrity.

**Simple way to remember:**

> **Integrity = Don't let the wrong people change the information.**

---

## Availability

Availability means that information and systems should be **available to authorized users when they need them**.

It is not enough to protect information. If the authorized user cannot access it when needed, there is also a security problem.

For example:

* Students should be able to access their university portal when they need it.
* Customers should be able to use online banking.
* A company's website should be available to its customers.

Backups, redundant systems, maintenance, and protection against attacks such as **DoS** can help improve availability.

**Simple way to remember:**

> **Availability = Make sure authorized users can access it when they need it.**

---

## CIA Triad in one example

Imagine a university student database.

**Confidentiality:** Only authorized staff can see private student information.

**Integrity:** Students or attackers cannot change grades without permission.

**Availability:** Teachers and students can access the system when they need it.

So I remember CIA as:

> **Confidentiality → Who can see it?**
> **Integrity → Can someone change it?**
> **Availability → Can I access it when I need it?**

---

# 4. AAA

AAA is another important concept related to controlling access to systems.

AAA stands for:

* **Authentication**
* **Authorization**
* **Accounting**

I understand it as three questions:

> **Who are you?**
> **What are you allowed to do?**
> **What did you do?**

---

## Authentication

Authentication is the process of checking **who a person is**.

For example, when I log into my GitHub account, I provide my username/email and password. The system checks whether I am really the person who owns the account.

Other examples include:

* Password
* Fingerprint
* Face recognition
* One-time code
* Multi-factor authentication

**Simple meaning:**

> **Authentication = Proving who you are.**

---

## Authorization

Authorization happens after authentication.

It decides **what an authenticated user is allowed to access or do**.

For example, in a university system:

* A student can view their grades.
* A teacher can add or change grades.
* An administrator may have access to manage student accounts.

All of them may be authenticated, but they don't have the same permissions.

**Simple meaning:**

> **Authorization = What are you allowed to do?**

---

## Accounting

Accounting means keeping track of **what users do on a system**.

The system can record things such as:

* When a user logged in
* When they logged out
* What files they accessed
* What changes they made
* What actions they performed

For example, if someone changes a record in a database, the system may keep a log showing **which account made the change and when it happened**.

This information can be useful when investigating a security incident.

**Simple meaning:**

> **Accounting = Keeping a record of what you did.**

---

# 5. DAD

DAD stands for:

* **Disclosure**
* **Alteration**
* **Denial**

These describe three common ways information or a system can be compromised.

---

## Disclosure

Disclosure happens when information is **shown or given to someone who is not allowed to see it**.

For example:

* Someone steals a company's customer database.
* A private password is exposed.
* Confidential university records are leaked.

This is mainly a problem with **Confidentiality**.

**Simple meaning:**

> **Disclosure = The wrong person sees the information.**

---

## Alteration

Alteration means that information is **changed without permission**.

For example:

* Someone changes a student's grade.
* An attacker changes information in a database.
* Someone changes the amount in a financial record.

This is mainly a problem with **Integrity**.

**simply meaning**
 **Alteration = The wrong person changes the information.**

---

## Denial

Denial happens when authorized users are **prevented from accessing a system or information**.

For example:

* A DoS attack makes a website unavailable.
* A server stops working and users cannot access it.
* An attacker blocks access to important files.

This is mainly a problem with **Availability**.

**Simple meaning:**

> **Denial = The right person cannot access the information or service.**

--- ---- ---- ----

I remember it like this:

> **Disclosure → Someone sees it**
> **Alteration → Someone changes it**
> **Denial → Someone blocks it**

---

