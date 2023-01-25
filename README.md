# AA-DR Portal

A simple portal that allows vendors to sign up to apply, view application progress and status, as well as providing a central location for documents.

### **Running Locally With Docker**

---

_This method will build both front-end and back-end at once with minimal local installation!_

1. Make sure to install Docker for your system first!

2. After doing so simply run `docker compose up -d`

3. To shutdown both the front-end and backend run `docker compose down`

**You will now see the frontend on `localhost:3000` and the backend on `localhost:3001`**

### **Running Locally without Docker**

---

Make sure to have the following installed before proceeding:

- Node.js
- Yarn package manager
- Python 3.10+

**Running the backend**

1. `cd backend`
2. `pip install -r requirements.txt`
3. `python app.py`

**Running the frontend**

1. `cd frontend`
2. `yarn`
3. `yarn run dev`
