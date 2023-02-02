# 🍇 Berri AI: 1-click deploy for your LLM Apps ⚡️

Berri AI is a python package that helps developers quickly and easily deploy their LLM App from Google Colab directly to production. Just install the package, import the function, and run deploy. At the end of the deploy (~10-15mins), you will get: 

1. 🎉 A web app to interact with your agent 👉 [example](https://agent-repo-35aa2cf3-a0a1-4cf8-834f-302e5b7fe07e-45247-8aqi.zeet-team-ishaan-jaff.zeet.app/)
2. 😱 An endpoint you can query 👉 `https://agent-repo-35aa2cf3-a0a1-4cf8-834f-302e5b7fe07e-45247-8aqi.zeet-team-ishaan-jaff.zeet.app/langchain_agent?query="who is obama?"`

Berri AI is built specifically for the Agent class of [Langchain](https://github.com/hwchase17/langchain) framework, a popular Python framework for building LLM Apps.

![ezgif com-gif-maker(1)](https://user-images.githubusercontent.com/17561003/216242793-a5cc6887-3f02-4421-ae2d-1cd0df11c342.gif)

### [Demo Video / Walkthrough](https://www.loom.com/share/fd4375b4a77f4ea7802369cb06a16d43)

## 🤓 Usage

To use Berri AI, follow these steps:

1. Install the package:

   ```
   pip install berri-ai
   ```

2. Import the deploy method:

   ```
   from berri_ai import deploy
   ```

3. Initiate the deployment by providing your email address:
   ```
   deploy(user_email=<your email>)
   # example deploy(user_email="ishaan@berri.com")
   ```
   Note: Today, berri will look for the initialize_agent() function in your code. If you're using another way of initializing your agent, let us know and we'll update the package to account for that.

Once deployment is complete, you will receive an email notification. The entire process usually takes 10-15 minutes.

## 📚 Examples 

1. [Berri LangChain Youtube Agent Example](https://colab.research.google.com/drive/1Do4Utp4crMSpPngDlZOXx30HFmKhtxIF?usp=sharing)
2. [Berri LangChain Search Agent Example](https://colab.research.google.com/drive/1cB-QfCaKBs2Npe58R60qf-II0wcsT6VQ?usp=sharing)

## 🚨 Support

If you have any questions or need help using Berri AI, join the [Discord](https://discord.gg/KvG3azf39U) or Text/WhatsApp us @ +17708783106 📱.
