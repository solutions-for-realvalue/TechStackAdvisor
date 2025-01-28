# Tech Stack Advisor

Tech Stack Advisor is your personal AI-powered consultant, designed to provide technology stack recommendations tailored to your software projects. Simply describe your project needs, and receive insightful, AI-driven advice on the most suitable technologies to use.

<br/>
<p align="center">
    <a href="https://www.openai.com/">
        <img alt="OpenAI GPT-4" src="https://img.shields.io/static/v1.svg?label=OpenAI&message=GPT-4&color=brightgreen" />
    </a>
    <a href="https://nodejs.org/">
        <img alt="Node.js" src="https://img.shields.io/static/v1.svg?label=Node.js&message=JavaScript runtime&color=lightyellow" />
    </a>
    <a href="https://www.npmjs.com/">
        <img alt="npm" src="https://img.shields.io/static/v1.svg?label=npm&message=packages&color=lightblue" />
    </a>
    <a href="https://reactjs.org/">
        <img alt="React" src="https://img.shields.io/static/v1.svg?label=React&message=UI library&color=blue" />
    </a>
    <a href="https://expressjs.com/">
        <img alt="Express.js" src="https://img.shields.io/static/v1.svg?label=Express.js&message=Web framework&color=green" />
    </a>
    <a href="https://github.com/">
        <img alt="GitHub" src="https://img.shields.io/static/v1.svg?label=GitHub&message=hosting&color=lightgrey" />
    </a>
    <a href="https://opensource.org/license/mit/">
        <img alt="License" src="https://img.shields.io/static/v1.svg?label=License&message=MIT&color=lightgreen" />
    </a>
</p>
<br/>

## 🚀 Features

- **AI-Powered Recommendations**: Leverages OpenAI's GPT-4 for generating detailed technology stack recommendations.
- **Full-Stack Application**: React frontend paired with an Express backend for seamless user interaction and server-side logic.
- **Customizable Input**: Tailor project descriptions for more specific advice.

---

## 🛠 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/solutions-for-realvalue/TechStackAdvisor.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd TechStackAdvisor
   ```

3. **Install Dependencies**:
   - For the server:
     ```bash
     cd server && npm install
     ```
   - For the client:
     ```bash
     cd ../client && npm install
     ```

---

## 🔑 OpenAI API Key

To use Tech Stack Advisor, you need an OpenAI API key:

1. Sign up at [OpenAI](https://www.openai.com/) and generate an API key.
2. Create an `.env` file in the `server` directory and add your API key:
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```

---

## ▶️ Usage

1. **Build the Application**:
   ```bash
   npm run build
   ```

2. **Start the Server**:
   ```bash
   cd server
   npm start
   ```

3. **Launch the Client** (in a new terminal):
   ```bash
   cd client
   npm run preview
   ```

4. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

5. **Describe Your Project**:
   Enter your project details to receive AI-powered technology stack recommendations.

![Tech Stack Advisor Input](https://github.com/user-attachments/assets/85a19bce-f40d-4c86-9b5f-ba7d7e302d13)
![Tech Stack Advisor Output](https://github.com/user-attachments/assets/563de454-ea27-4faf-85a7-4914ea050cf4)

---

## 🤝 Contributing

Contributions are welcome! Here’s how you can contribute:

1. Fork the repository and create a branch for your feature or bug fix.
2. Commit your changes and push the branch.
3. Open a pull request with a detailed description of your changes.

### Ideas for Contribution:
- Add support for more project types.
- Improve the recommendation algorithms.
- Build advanced data visualization dashboards.

---

## 📜 License

This project is licensed under the [MIT License](https://github.com/solutions-for-realvalue/TechStackAdvisor/blob/main/LICENSE). See the `LICENSE` file for more details.

---

## 🌟 Fun Fact

Tech Stack Advisor is inspired by the vision of empowering developers with smarter, AI-driven tools for better decision-making. Join us in revolutionizing how we plan and implement technology stacks!
