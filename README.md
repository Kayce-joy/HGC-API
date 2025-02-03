HNG12 Stage 0 API

Description
This API returns my registered email, current datetime (ISO 8601 format), and the GitHub repository URL.



Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Kayce-joy/HGC-API.git
2. Install dependencies:
   pip install flask flask-cors
3. Run the application:
   python app.py



API Documentation
1. Endpoint URL
The endpoint URL for the API is: GET / 
2. Request/Response Format
      Request Method: GET
      Response Format: JSON

      Response Example:
{
  "current_datetime": "2025-02-03T13:16:56.043159Z",
  "email": "wakarijoyce@gmail.com",
  "github_url": "https://github.com/Kayce-joy/HGC-API"
}

3. Example Usage(in Postman or browser)

   GET https://your-api-url.com/

Expected Response:
{
  "current_datetime": "2025-02-03T13:16:56.043159Z",
  "email": "wakarijoyce@gmail.com",
  "github_url": "https://github.com/Kayce-joy/HGC-API"
}


HNG Python Developers: https://hng.tech/hire/python-developers