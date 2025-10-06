#Creative Prompt Lab: Custom Modifiers
​
This is a single-file, fully responsive web application designed to help AI artists build sophisticated, hyper-detailed prompts for large image generation models (like Imagen 3.0 and Midjourney). It functions as a personalized laboratory for refining creative language and is ideal for quick deployment via services like GitHub Pages.

​Developed by Diana Modica
​
Core Features
​
The application is built using HTML, JavaScript, and Tailwind CSS, ensuring a fast, clean, and mobile-friendly user experience. It leverages secure, persistent storage via Google Firestore to save your personalized data.

​Dynamic, User-Expandable Modifiers: Offers a comprehensive taxonomy of 8 modifier categories (e.g., Style, Lighting, Composition). Users can easily add their own artistic keywords, which are saved instantly and persistently to their private Firestore database.

​Prompt Expander (Gemini-Powered): An integrated feature that invokes the Gemini 2.5 Flash model to transform a simple core concept into a technically perfect, verbose, and professional-grade master prompt for cinematic results.

​Persistent Storage (Firestore): All custom modifier additions are instantly secured and recalled from your private Firestore path, ensuring your personalized language database grows over time.

​Direct Generation: Utilizes the Imagen 3.0 API for high-quality, watermark-free image generation, complete with flexible aspect ratio controls.

​Image-to-Prompt Analysis: Allows users to upload an image and use Gemini to analyze its structure, style, and mood, generating a refined, professional prompt based on the visual input.

#​Installation & Deployment

​This application requires no local build process. It is a single, self-contained file optimized for easy hosting.

​Obtain the Artifact: Download the index.html file (the main application).

​Deployment: Upload the index.html file to the root of your GitHub repository.

​Access: Enable GitHub Pages for the repository. The application will then be live at the URL, such as Creative-Prompt-Lab.github.io.

​Secure Initialization: The application automatically initializes the secure Firebase connection and authenticates the user via the environment's provided token to manage your personalized modifier data.
​
Technology Stack (API Dependencies)

Imagen 3.0 High-fidelity image generation.

Gemini 2.5 Flash Prompt expansion and Image-to-Prompt analysis.

Google Firestore Secure

#License

This project is protected under The Covenant of Gnosis License (CGL). Please review the included LICENSE.md file for details.
