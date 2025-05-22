# Custom JSP Tag Library

This repository contains a **custom JSP tag library** implemented in Java, designed to help developers and designers work more effectively by separating business logic from presentation in JSP-based web applications.

## 📌 Overview

JSP (JavaServer Pages) allows for dynamic web page generation, but mixing Java code directly within HTML can reduce readability and maintainability. This project addresses that by introducing **custom tags** that encapsulate logic in Java while keeping JSP pages clean and designer-friendly.

This tag library was created to deeply understand the underlying mechanics of JSP and Java EE, and to build a reusable, extensible set of components for use in JSP pages.

## 🚀 Features

- Custom tags for common UI and logic operations
- Clean separation of concerns (logic in handlers, layout in JSP)
- Tag Library Descriptor (TLD) file for easy integration
- Reusable across JSP-based projects
- Helpful for both developers and front-end designers

## 🧩 Tags Implemented

The library includes the following custom tags:

- `PopulateClass`
- `EntityList`
- `ValidateUser`
- `FormId`
- `FormResubmission`
- `Module`
- `Designations`
- `IfTagHandler` – allows using conditional logic in a tag-based way (e.g., `<my:if condition="...">...</my:if>`)

## 🛠️ Technologies Used

- Java (JDK 8+)
- JSP / Servlet API
- Apache Tomcat 9
- Tag Library Descriptor (TLD)
- Maven (optional for build and dependency management)
