🌦️ Smart Weather Alert System using AWS

A cloud-based weather alert system that automatically detects severe weather conditions and sends real-time notifications using AWS services. This project demonstrates how modern cloud technologies can be used to build scalable, event-driven applications.

🚀 Project Overview

The Smart Weather Alert System fetches real-time weather data from a public API and analyzes weather conditions such as rain, storms, or extreme temperature. When dangerous conditions are detected, the system automatically sends alerts via Email/SMS using AWS SNS.

This project follows a serverless architecture, ensuring scalability, reliability, and low operational cost.

🛠️ Technologies Used
Category	Technology
Frontend	HTML, CSS, JavaScript
Weather API	OpenWeather API
Cloud Platform	AWS
Cloud Services	AWS Lambda, SNS, API Gateway
Version Control	Git & GitHub
☁️ System Architecture
User → Web Interface
        ↓
   OpenWeather API
        ↓
    AWS Lambda
        ↓
   Amazon SNS
        ↓
  Email / SMS Alert

✨ Key Features

🌦️ Real-time weather monitoring

⚡ Automatic alert triggering

📩 Email & SMS notification system

☁️ Fully serverless architecture

🔐 Secure and scalable design

📊 Easy to extend and maintain

⚙️ How It Works

User enters a city name on the website

Weather data is fetched using OpenWeather API

Lambda function evaluates weather condition

If weather is dangerous:

SNS sends email/SMS alert

User receives real-time notification

🧪 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/subham1853/weather-alert-system.git
cd weather-alert-system

2️⃣ Configure AWS

Create SNS Topic

Add Email/SMS subscription

Create Lambda function

Add API Gateway trigger

3️⃣ Add Environment Variables
WEATHER_API_KEY=34dd7442ff6fe888f9549ab12377512a
SNS_TOPIC_ARN="arn:aws:sns:ap-south-1:123456789012:WeatherAlertTopic"

4️⃣ Deploy & Test

Open index.html

Enter city name

Receive alert if weather is severe

📸 Screenshots

✔ AWS Console
✔ SNS Topic & Subscription
✔ Lambda Function
✔ API Gateway
✔ Alert Message

(Attached in repository)

🎯 Use Cases

Disaster management systems

Smart city applications

Weather alert platforms

Emergency notification systems

🚀 Future Enhancements

WhatsApp & Telegram notifications

Mobile app version

AI-based weather prediction

Multi-language support

👨‍💻 Author

Subham Bej
Cloud & Full Stack Developer
📧 Email:subhambej29@gmail.com

🌐 GitHub: https://github.com/subham1853
