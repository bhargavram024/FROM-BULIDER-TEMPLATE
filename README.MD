#  Form Template Builder

A **dynamic form template builder** built with React and Tailwind CSS. It allows users to create custom form templates with sections and fields, preview them in real-time, and render them into fillable forms.

---

##  Features

###  Template Builder
- Create up to **5 templates**
- Add **sections** with titles
- Add **fields** with types:
  - Label (H1, H2, H3)
  - Text
  - Number
  - Boolean (checkbox)
  - Enum (dropdown)
- Real-time **preview**
- Drag-and-drop to reorder fields within a section
- Delete sections/fields
- Templates stored in **localStorage**

###  Form Renderer
- Select template to render a fillable form
- Auto validation (based on field type)
- Form submissions saved to localStorage per template

---

## 💻 Tech Stack

| Tech       | Usage                        |
|------------|------------------------------|
| React      | UI Framework                 |
| Tailwind CSS | Styling                     |
| React Beautiful DnD | Drag and Drop Fields |
| uuid       | Unique field/section IDs     |
| LocalStorage | Data persistence            |
| Vite       | Development & build tool     |

---

##  Project Structure

