## Face App

Face App for ERPNext 15

### Requirements

- ERPNext v15.x
- Frappe v15.x
- Python 3.10+

### Installation

Before installing the app:

```bash
bench get-app https://github.com/chumam2050/face_app
bench --site [your-site-name] install-app face_app
```

The app will automatically install required dependencies including cmake, qrcode, opencv-contrib-python, and face_recognition during migration.

#### License

MIT

