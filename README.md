# GearShare

GearShare is a web platform that enables users to share, borrow, and manage items within a community. Whether you want to lend your gear, borrow something for a project, or manage collections, GearShare provides a secure and user-friendly environment for item sharing.

---

## Features

- **User Registration & Authentication:**  
  Secure sign-up, login, and profile management.

- **Item Sharing:**  
  Users can list items for others to borrow, including images, descriptions, and categories.

- **Borrow Requests:**  
  Request to borrow items, specify dates, and communicate with item owners.

- **Collections:**  
  Organize items into public or private collections for easier management and sharing.

- **Borrower Agreement:**  
  Users must accept a digital agreement before borrowing, outlining responsibilities and consequences for late returns or damage.

- **Return & Condition Tracking:**  
  Return items, report condition, and leave notes for owners.

- **Admin & Librarian Roles:**  
  Special permissions for managing users, items, and resolving disputes.

- **AWS S3 Integration:**  
  Images and media files are stored securely in Amazon S3.

---

## Getting Started

### Prerequisites

- Python 3.12+
- Django 4.2+
- PostgreSQL or SQLite
- AWS account (for S3 storage)
- Node.js & npm (for frontend assets, optional)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/GearShare.git
   cd GearShare
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure environment variables:  
   Create a `.env` file and set your AWS credentials and other secrets.

4. Set up the database:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (admin):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

---

## Usage

1. **Add Items:**  
   List items with images, descriptions, and categories.

2. **Browse & Search:**  
   Find items by category, keyword, or collection.

3. **Borrow Items:**  
   Submit a borrow request and accept the borrower agreement.

4. **Return Items:**  
   Mark items as returned, report condition, and leave notes.

5. **Manage Collections:**  
   Create, edit, and share collections (public or private).

---

## Technologies

- **Backend:** Django, Django REST Framework  
- **Frontend:** Bootstrap, HTML/CSS, JavaScript  
- **Storage:** AWS S3 (via django-storages)  
- **Database:** PostgreSQL or SQLite

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## License

MIT License

---

## Acknowledgements

- Django  
- Bootstrap  
- AWS S3  
- All contributors
