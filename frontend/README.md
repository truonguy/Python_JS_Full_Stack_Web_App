# Deployment Instructions

1. Navigate to the backend directory:
    ```bash
    cd backend
    ```

2. Create a virtual environment:
    - On macOS and Linux:
        ```bash
        python3 -m venv venv
        ```
    - On Windows:
        ```bash
        python -m venv venv
        ```

3. Activate the virtual environment:
    - On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```

4. Install the dependencies:
    - On macOS and Linux:
        ```bash
        pip3 install -r requirements.txt
        ```
    - On Windows:
        ```bash
        pip install -r requirements.txt
        ```

5. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

6. Install the dependencies:
    ```bash
    npm install
    ```

7. Build the frontend:
    ```bash
    npm run build
    ```

8. Navigate to the backend directory:
    ```bash
    cd ../backend
    ```

9. Run the Flask app:
    ```bash
    flask run
    ```

10. Open your browser and go to `http://localhost:5000/` to view the app.