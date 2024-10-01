<div align="center">
  <h1>Create Sling App</h1>
</div>

<div align="center">
  <img src="https://sling.biz/assets/images/sling_biz_sling_image.jpg"/>
</div>

<p align="center">
  <strong>
    <a href="https://studio.sling.biz">🚀 Live Demo</a>
  </strong>
</p>

Open-source drag-and-drop frontend CMS in Next.js. Completely customizable Pages, Templates & Widgets written in Next.js. Sling is an open-source alternative to Builder.io.

---

## ✨ Features :fire:

- **It’s just React & Node.js**: Built using modern frameworks, making customization easy and straightforward.
- **Control how your components are edited**: With Sling.biz, you can control the React widgets and their props directly from the Studio.
- **Drag-and-Drop Functionality**: Easily add, remove, and rearrange components within the visual editor.
- **Page Templates and Routes**: Create routes and attach fully customizable page templates.

---

## 🛠️ Prerequisites

To properly set up Sling, you need the following:

- **MongoDB URI**: Make sure you have a MongoDB instance running and obtain its URI.
- **Node.js**: Ensure you have Node.js version 18 or greater installed.

---

## 🚀 Setting up Sling - Hosted Studio

To set up a Sling project locally using [Hosted Studio](https://studio.sling.biz/), follow these steps:

### Frontend App Setup

1. **Use the Installer**:
   - Create the Sling Frontend app by running the following command:
     ```sh
     yarn create sling-app my-project
     ```
   - Follow the prompts to configure your Sling app.

2. **Obtain Sling Studio Keys**:
   - Visit [Sling Studio](https://studio.sling.biz/) to sign up and create an account.
   - Complete the company setup.
   - Navigate to your account settings or profile section.
   - Locate the section for accessing or generating Sling Studio Keys.
   - Copy the keys provided and update them in the `.env` file for the frontend app.

3. **Start and Play Around**:
   - Run your app and navigate to [http://localhost:4087](http://localhost:4087).
   - Explore the Sling Studio interface, create custom widgets, and see real-time updates on your pages.

---

## 🌐 Setting up Sling - Self-Hosted Studio

If you prefer to host Sling Studio locally, follow these instructions. Sling consists of three main parts: Sling Studio, Sling API, and Sling FE.

1. **Run the Installer**:
   - Use the installer to set up the Sling project by running the following command:
     ```sh
     yarn create sling-app my-project
     ```

2. **Configure for Self-Hosting**:
   - Follow the prompts to configure your Sling app and select the **Self-Hosted** option.
   - The starter script will start the necessary services in the background, or you can manage them manually.

3. **Navigate to the Services**:
   - Frontend: [http://localhost:4087](http://localhost:4087)
   - Studio: [http://localhost:2021](http://localhost:2021)
   - API: [http://localhost:10001](http://localhost:10001)

---

## 📚 Documentation and Resources

- [Official Website](https://sling.biz)
- [Documentation](https://sling.biz/documentation/)
- [Live Demo](https://studio.sling.biz)
- [YouTube Channel](https://www.youtube.com/@wearesling1441): Watch tutorials and demos.

---

## 🙋 Getting Help :wave:

If you have any questions, need assistance, or want to contribute, feel free to:

- Join our [Slack](https://slingbiz.slack.com/archives/C06KE4ZMSQP) community.
- Raise a [GitHub issue](https://github.com/slingbiz/sling-fe/issues) to report bugs or request features.
- Reach out via [Email](mailto:ankur@sling.biz) or connect on [LinkedIn](https://www.linkedin.com/in/ankurpata/).

---

## ✨ Contributions

Contributions are welcome! Whether you’re improving documentation, building new features, or fixing bugs, feel free to open a pull request.

---

<div align="center">
  <strong>Thank you for checking out Sling! 🚀</strong>
</div>
