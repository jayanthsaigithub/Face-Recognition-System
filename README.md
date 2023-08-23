# User Authentication and Face Recognition System

This project implements a user authentication system using password, passphrase, and face recognition.

## Features

- Secure user authentication using password and passphrase.
- Optional face recognition for enhanced security.

## Setup and Usage

1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Install the required Python packages: pip install -face_recognition
3. Install the required Python packages: pip install -cv2
4. Install the required Python packages: pip install -sqlite3
5. Install the required Python packages: pip install -hashlib
6. Run the program: `python main.py`

## How It Works

1. Users can sign up with a username, password, and passphrase.
2. Password and passphrase are hashed using PBKDF2 with salt.
3. Users can also provide a face encoding for face recognition.
4. Users can log in with their credentials and optionally pass the face recognition check.

## Technologies Used

- Python
- SQLite
- hashlib
- secrets
- OpenCV
- face_recognition

## Contributions

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
