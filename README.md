# OpenAI-Image-Generation-useing-MERN

This is a web app that generates images using OpenAI's GPT-3 text-to-image generation model. It is built using Vite (React), MongoDB, Express, Node.js, Cloudinary, and OpenAI.

# Technologies Used
1. Vite (React) - A build tool and development server that improves the frontend development experience.
2. MongoDB - A NoSQL database used for storing image data.
3. Express - A Node.js framework used for building the server-side API.
4. Node.js - A JavaScript runtime used for building the server-side API.
5. Cloudinary - A cloud-based image and video management service used for storing generated images.
6. OpenAI - A research organization focused on creating artificial intelligence in a safe and beneficial manner. The DALL-E model is used for generating images in this app.

![Screenshot (848)](https://user-images.githubusercontent.com/72490093/223148038-7715ef64-aa2b-4516-8b3f-2f9b67e1868f.png)
![Screenshot (850)](https://user-images.githubusercontent.com/72490093/223148052-7b4b07bb-2e39-4590-afa4-0aa14f7595b0.png)

# Requirements
To run this web app, you need to have the following:

1. Node.js v14 or higher
2. MongoDB instance
3. OpenAI API key
4. Cloudinary API key

# Installation
1. Clone the repository: 

        git clone https://github.com/SaifSunny/OpenAI-Image-Generation-useing-MERN.git
        
4. Install the dependencies: 

        cd client
        npm install

        cd ../server
        npm install
  
3. Set up environment variables: In server/.env, set the following environment variables:

       MONGODB_URL: the URI of your MongoDB instance
       OPENAI_API_KEY: your OpenAI API key
       CLOUDINARY_CLOUD_NAME: your Cloudinary cloud name
       CLOUDINARY_API_KEY: your Cloudinary API key
       CLOUDINARY_API_SECRET: your Cloudinary API secret

4. Start the server: 

       cd server
       npm start
  
This will start the server at http://localhost:8080.

5. Start the client:

        cd ../client
        npm start
  
This will start the client at http://127.0.0.1:5173/.

# Usage
To use the web app, go to http://127.0.0.1:5173/. You can then enter a prompt in the input field and click the "Generate Image" button to generate an image based on the prompt.

The generated image will be displayed on the page. You can also save the image to Cloudinary by clicking the "Save to Cloudinary" button. The image URL will be displayed on the page.

# Contributing
Feel free to contribute to this project by creating issues or submitting pull requests.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
