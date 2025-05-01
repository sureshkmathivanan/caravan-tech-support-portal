## Manufacturer Admin Portal – Design & Flow
# Overview
The Manufacturer Admin Portal allows caravan manufacturers to upload, manage, and update caravan information in the system. It supports legacy data import, real-time updates, and image uploads, and provides edit/delete capabilities for data accuracy and lifecycle tracking.

# 🔑 Key Features
1. Upload Caravan Data
Legacy Upload (CSV):

Upload caravan records in bulk using a structured CSV template.

Future Integration (API):

Enter API credentials or endpoints to enable automatic syncing of new models.

Photo Upload:

Upload a photo of each caravan model (PNG/JPG).

Optional, but recommended for technician identification.

2. Manage Caravan Entries
A table showing:

VIN

Model Name

Year

Status (Active, Scrapped)

Photo (Thumbnail or placeholder)

Each row includes:

Edit button (opens a form to update model name, parts, repair info, etc.)

Delete button (with confirmation modal for irreversible removal)

Upload/Replace Photo option

3. Search & Filter
Search bar: Search by VIN, model name, or manufacturer.

Filters: Dropdowns for Year, Manufacturer, and Status.

4. Navigation & UI
Sidebar navigation or tabs for:

Upload Caravan

Manage Caravans

API Integration

Clean, minimalist design with inline editing or modal forms.

✅ Flow Summary
Manufacturer logs into their portal.

Uploads new caravan data (via CSV or API).

Can view all caravan entries and update any incorrect information.

Can delete records if a caravan is scrapped or irrelevant.

Uploads photos for better technician support.

# 🖼 Screenshots 
Figma Design 1: Upload Caravan
![Manufacturer Admin Page 1](https://github.com/user-attachments/assets/e0134d27-d924-49ac-8acf-9acd51f760ed)


Figma Design 2: Caravan Management Table with Edit/Delete actions
![Manufacturer Admin Page 2](https://github.com/user-attachments/assets/83ac6f9f-8882-4084-90cf-0b24b03e6a76)


Figma Design 3: API settings and Navigation bar
![Manufacturer Admin Page 3](https://github.com/user-attachments/assets/abd9e457-736c-4a77-91f3-7e6c741b4239)
