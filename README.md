# Berri AI: ⚡️ 1-click deploy for your LLM Apps

Berri AI is a python package that helps developers quickly and easily deploy their LLM App from Google Colab directly to production. Just install the package, import the function, and run deploy. At the end of the deploy (~10-15mins), you will get: 

1. 🎉 A web app to interact with your agent
2. 😱 An endpoint you can query (<endpoint_url>/langchain_agent?query=<user_query>)

Berri AI is built specifically for the Agent class of [Langchain](https://github.com/hwchase17/langchain) framework, a popular Python framework for building LLM Apps.

## Usage

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
   `    deploy(user_email=<your email>)
   `
   Note: Today, berri will look for the initialize_agent() function in your code. If you're using another way of initializing your agent, let us know and we'll update the package to account for that.

Once deployment is complete, you will receive an email notification. The entire process usually takes 10-15 minutes.

## Support

If you have any questions or need help using Berri AI, join the [Discord](https://discord.gg/KvG3azf39U) or text/WhatsApp us @ +17708783106.
