# letz-eight-be
- Please move to the api project to run this app by using the command:
```cd ./src/Presentation/LetzEight.Api```
- Then run with command:
```dotnet run -lp https```
The "-lp" (launch profile) option is specificed what profile you prefer to launch: http or https (recommended https).
🧩 Letz-Eight Backend
🚀 Getting Started

Follow the steps below to run the Letz-Eight API locally.

1️⃣ Navigate to the API Project

Open your terminal and move to the API project directory:

cd ./src/Presentation/LetzEight.Api

2️⃣ Run the Application

You can launch the API using either HTTP or HTTPS (recommended):

# Run with HTTPS (recommended)
dotnet run -lp https

# Or run with HTTP
dotnet run -lp http

ℹ️ What is -lp?

The -lp flag stands for launch profile.
It specifies which profile from your launchSettings.json file to use when starting the application.

https → runs the app using the HTTPS profile (recommended for secure local testing)

http → runs the app using the HTTP profile

✅ Example
dotnet run -lp https


This command starts the Letz-Eight API using the HTTPS launch profile.
