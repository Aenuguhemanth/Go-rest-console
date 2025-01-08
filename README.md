🌟 Go-Rest-Console 🌟
Go-Rest-Console is a sleek and efficient web console application designed for developers to test APIs quickly and easily. With an intuitive interface, you can provide a request URL, specify the HTTP method, add a request body, and instantly view the response status and body.

✨ Features
🖇️ Customizable API Requests

Input a Request URL.
Choose from various HTTP Methods (GET, POST, PUT, DELETE, etc.).
Add an optional Request Body for POST, PUT, or PATCH methods.
📡 Real-Time Feedback

Get the Response Status and Response Body instantly.
💻 User-Friendly Interface

Designed for seamless and hassle-free API testing.
⚙️ How It Works
📝 Provide API Details:

Enter the API endpoint (e.g., https://gorest.co.in/public-api/users).
Select the HTTP method (e.g., POST).
Add a request body if needed (JSON format).
🚀 Submit the Request:

Click the "Send" button to execute the API call.
👀 View Results:

Instantly see the response status and body in the console.
🛠️ Example Use Case
🧪 Testing a User Creation API
🔗 Request URL: https://gorest.co.in/public-api/users
📤 Request Method: POST
🗂️ Request Body:
json
Copy code
{
    "name": "John Doe",
    "email": "john.doe@example.com",
    "gender": "male",
    "status": "active"
}
✅ Response Status: 201 Created
📥 Response Body:
json
Copy code
{
    "id": 1234,
    "name": "John Doe",
    "email": "john.doe@example.com",
    "gender": "male",
    "status": "active"
}
🚀 Installation
📦 Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/go-rest-console.git
📂 Navigate to the Project Directory:

bash
Copy code
cd go-rest-console
📥 Install Dependencies (if applicable):

bash
Copy code
npm install  
▶️ Run the Application:

bash
Copy code
npm start  
Open your browser and start testing APIs!

🔧 Technologies Used
🌐 Frontend: HTML, CSS, JavaScript
🖥️ Backend: (Add your backend technology, e.g., Node.js, Go, etc.)
🔌 API Testing: RESTful services
