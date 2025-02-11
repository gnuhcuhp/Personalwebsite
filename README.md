# Academic Personal Website

A modern, responsive academic personal website built with Flask and Bootstrap.

## Features

- Responsive design that works on all devices
- Clean and professional layout
- Sections for research, teaching, and contact information
- Interactive contact form
- Social media integration
- Easy to customize and maintain

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- On Windows:
```bash
venv\Scripts\activate
```
- On macOS/Linux:
```bash
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

The website will be available at `http://localhost:5000`

## Customization Guide

### 1. Personal Information
- Edit your name, title, and contact information in the templates
- Update social media links in `base.html`
- Replace profile image in `static/images/profile.jpg`

### 2. Content Sections

#### Home Page (`templates/index.html`)
- Update hero section with your introduction
- Modify news items
- Add/edit featured research projects

#### Research Page (`templates/research.html`)
- Add your research projects
- Update publications list
- Modify research interests

#### Teaching Page (`templates/teaching.html`)
- Update teaching philosophy
- Add current and past courses
- Modify student resources

#### Contact Page (`templates/contact.html`)
- Update contact information
- Customize contact form
- Edit office hours and location

### 3. Styling
- Modify colors and styles in `static/css/style.css`
- Update images in `static/images/`

### 4. Adding New Pages
1. Create new template in `templates/`
2. Add route in `app.py`
3. Update navigation in `base.html`

## File Structure
```
personal_website/
├── app.py
├── requirements.txt
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── research.html
│   ├── teaching.html
│   └── contact.html
└── README.md
```

## Dependencies
- Flask
- Bootstrap 5
- Font Awesome
- Other dependencies listed in requirements.txt

## License
MIT License 