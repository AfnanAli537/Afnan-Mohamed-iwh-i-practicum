# Integrating With HubSpot I: Foundations Practicum — Afnan Mohamed

This project was created for the **Integrating With HubSpot I: Foundations Practicum** as part of the HubSpot Academy Developer certification.  
It demonstrates how to build a simple **Node.js integration** with the HubSpot CRM API using **Contacts** and custom properties.

---

## 🌿 Contacts Custom Properties: "Pet"

This project uses the HubSpot **Contacts object** to store records representing pets.  
Each Contact record has the following custom properties (all **Single-line text**):

- **Name Pet**  
- **Pet Age**  
- **Pet Gender**  
- **Pet Type**

Each record can be created, viewed, and listed through this Node.js app.

---

## 🔗 Contacts List View (required link)

**Contacts List URL:**  
[View Pet Records in HubSpot](https://app-eu1.hubspot.com/contacts/147127607/objects/0-1/views/all/list)

---

## 🧠 Tech Stack
- **Node.js**  
- **Express.js**  
- **Axios**  
- **Pug** (for server-side templates)  
- **CSS** (for styling)  
- **HubSpot CRM v3 API**

---

## 🧩 Functionality

### Homepage (`/`)
- Displays all Pet records (Contacts) in a clean HTML table, showing:  
  - Name Pet  
  - Pet Age  
  - Pet Gender  
  - Pet Type  

### Add Record (`/update-cobj`)
- Form to create a new Pet record in HubSpot.  
- After submission, redirects back to the homepage to display the updated list.

---

## ⚙️ Setup Instructions

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-github-username>/<repo-name>.git
   cd <repo-name>
