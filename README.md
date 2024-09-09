# AI Image Generator with Stable Diffusion

This project is a web application that generates images from textual prompts using the Stable Diffusion model. The app is designed to run on Google Colab, leveraging GPU support for efficient image generation. It provides an easy-to-use interface for users to input prompts and visualize AI-generated images in real-time.

## Features

- **Text-to-Image Generation:** Converts user-provided text prompts into high-quality images using the Stable Diffusion model.
- **Negative Prompts:** Allows users to specify negative prompts to refine and control the content of the generated images.
- **GPU-Optimized:** Utilizes Google Colab's GPU capabilities to speed up image generation, making it accessible and efficient for users without powerful local hardware.
- **Interactive UI:** Built with Gradio, providing a simple and intuitive interface for seamless interaction.
- **Deployment on Google Colab:** Easily deploy the application on Google Colab with minimal setup, including automatic tunneling with Ngrok for public accessibility.

## How to Use

1. **Setup the Environment:**
   - Clone the repository and open the project in Google Colab.
   - Install the required dependencies:
     ```bash
     !pip install gradio diffusers torch transformers pyngrok
     ```

2. **Run the Application:**
   - Execute the cells in the notebook to start the Gradio interface.
   - Input your text prompt and optional negative prompt to generate an image.
   - Access the app via the provided public URL from Ngrok.

3. **Customize the Prompts:**
   - Modify the prompts directly within the app to experiment with different image outputs.

