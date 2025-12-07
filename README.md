# Vista Voyages — Basic Travel Agency Demo

This is a small static website built with basic HTML and CSS. JavaScript is used only for login and signup form validation.

Pages:
- `index.html` — Home with hero and featured destinations
- `about.html` — About the agency
- `destinations.html` — Sample destinations with images
- `contact.html` — Contact form
- `login.html` — Login form (client-side validation)
- `signup.html` — Signup form (name, age, email, password; client-side validation)

New destinations added:
- Several Indian destinations were added to `destinations.html`: `Goa`, `Jaipur`, `Kerala (Alleppey)`, and `Agra`.

To view:
```powershell
cd "C:\Users\abhin\Desktop\VISTA VOYAGES\travel-agency"
python -m http.server 8000
# open http://localhost:8000
```

Notes:
- Images are referenced via remote URLs (Unsplash) for demonstration.
- No backend or persistent authentication included — signup/login are front-end demos only.
