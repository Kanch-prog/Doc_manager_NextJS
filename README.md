# Document Management System using Next.js

## Introduction
The Document Management System is a web application developed using Next.js, allowing users to efficiently manage their documents. This system provides features for uploading, organizing, and retrieving documents. Users can upload documents through the web interface, which are then stored in local storage.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Next.js](https://nextjs.org/)
- React Hooks
- Next.js Routing

## Output Preview
[Insert a brief description or screenshot of the final output]

## Approach to Create Document Management System
1. **Setup the Project:** Create a new Next.js project and install necessary libraries.
2. **Design the Layout:** Design the layout of the Document Management System, including components like Navbar, Documents, AddDocument, SearchBar, etc.
3. **Create Components:** 
   - Create `Documents` component: Display the list of documents with functionality to view, delete, and search specific documents. Create a modal to view a document in detail.
   - Create `AddDocument` component: Contains the form to add document details such as name, description, and image.
4. **Manage State:** Use `useState` hook to manage the form state.
5. **Data Storage:** Utilize `localStorage` to store document metadata.
6. **Styling:** Use Bootstrap to style the components.

## Steps to Create Document Management System
### Step 1: Create a Next.js Application
```bash
npx create-next-app doc-management
cd doc-management
npm install bootstrap
npm install react-toastify

## Contributors: [Kanchana Karunarathna]
Feel free to customize it according to your project's specific details and requirements!
