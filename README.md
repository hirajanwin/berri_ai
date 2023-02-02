# Berri AI - 1-click deploy for your LLM Apps

Berri AI is a python package that helps developers quickly and easily deploy their LLM App from Google Colab directly to production. With just a few clicks, developers can get their app to the world without having to worry about the hassle of setup and configuration.

Berri AI is built specifically for the Agent class of Langchain framework, a popular Python framework for building LLM Apps.

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

## Benefits

Berri AI allows developers to go from development to production with just a few clicks. Before, developers had to manually configure the environment, making the process time consuming and frustrating. Now, with Berri AI, developers can get their LLM App up and running quickly and easily.
