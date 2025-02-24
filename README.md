# AI Image Generator

This project is a simple AI-powered image generator that takes user input and generates an image using OpenAI's DALL·E API. The project consists of a frontend built with HTML, Tailwind CSS, and JavaScript, and a backend using Node.js and Express.
sssefr4252hshsh
## Features
- User can enter a text prompt to generate an image
- Displays a loading message during API requests
- Prevents multiple clicks on the "Generate Image" button while processing
- Provides a downloadable link for the generated image

## Requirements
- Node.js (>=14)
- An OpenAI API Key

## Installation and Setup
### 1. Clone the Repository
```sh
git clone https://github.com/your-repo/ai-image-generator.git
cd ai-image-generator
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the project root and add your OpenAI API Key:
```sh
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the Backend Server
```sh
node server.js
```
If you want to run with auto-restart on changes, install `nodemon` and use:
```sh
npm install -g nodemon
nodemon server.js
```

### 5. Open the Frontend
Simply open `public/index.html` in a web browser, or use an HTTP server:
```sh
npx http-server public -p 8080
```
Then visit `http://localhost:8080` in your browser.

## Usage
1. Enter a description of the image you want to generate.
2. Click **"Generate Image"**.
3. Wait for the image to be processed and displayed.
4. Click the **Download** button to save the image.

## Troubleshooting
- If you get a `billing_hard_limit_reached` error, check your OpenAI account billing.
- If the server does not start, verify that `node` and `npm` are installed.
- Ensure your API key is correctly set in the `.env` file.

## Future Enhancements
- Add different image size options
- Allow users to select different AI models
- Improve UI with better styling

## License
This project is open-source under the MIT License.
