🚀 IdiomMaster AI: ESL Tutor

IdiomMaster AI is a single-file, serverless web application designed to help English as a Second Language (ESL) learners master American English idioms through interactive speech and AI-powered feedback.

Built entirely with HTML, CSS, and JavaScript, this application uses the Google Gemini API to function as a supportive, virtual language coach.

✨ Features

Speech-to-Text (STT): Uses the browser's native speech recognition (requires Chrome/Edge on desktop/mobile) to capture the user's spoken attempts.

AI-Powered Tutoring: Leverages the Gemini 2.5 Flash model to provide structured linguistic feedback, including:

Fluency and Confidence scores.

CEFR Band assessment.

IPA Pronunciation and Syllable breakdown.

Tips on context and usage.

Dynamic UI: Uses the HTML <canvas> element to visualize conversation history, lesson progress, and phoneme-level analysis.

Zero-Dependency: Runs entirely locally in a browser without any build steps or external dependencies.

Customizable Content: Includes a built-in list of idioms sourced from "Idiomania" and supports importing new lessons via CSV file upload.

🛠️ Setup and Installation

Since this is a single-file application, setup is incredibly easy.

Download: Save the provided index.html file to your computer.

Open: Double-click the index.html file to open it in any modern web browser (Chrome, Edge, or Safari are recommended for full Speech-to-Text support).

Configure API Key:

Click the Settings button in the top right.

Paste your Gemini API Key into the input field (see the section below on how to get one).

Click Save Settings.

The application is now ready to use!

🗣️ How to Use

Read the Idiom: The current idiom, its meaning, and an example sentence are displayed at the top.

Click to Speak: Click the large "Tap to Speak" microphone button. The button will turn red and change to "Stop Listening."

Practice: Say the idiom in a full, coherent sentence (e.g., "I decided to think outside the box to solve the problem.").

Get Feedback: Once you stop speaking, the application sends your transcript to the Gemini AI tutor, and the feedback, scores, and linguistic analysis will appear on the canvas.

Next Lesson: Click "Next Idiom" to advance once you've reviewed the feedback.

⚙️ Customization

Idiom List Import

The application supports loading new idiom sets from a standard CSV file.

The required columns for the CSV file must include:
| Header | Description | Required | Example |
| :--- | :--- | :--- | :--- |
| phrase | The idiom phrase itself. | Yes | Go with the flow |
| meaning | The definition of the idiom. | Yes | Relax and accept a situation... |
| example | A sample sentence using the idiom. | Yes | Just go with the flow. |
| register | Contextual usage (e.g., Informal, Business). | Yes | Informal |
| confusables| (Optional) Words or phrases learners might confuse it with (comma-separated list). | No | Go with the water |

Upload your CSV via the file input in the Settings modal.

Dark Mode

A dark mode toggle is available in the Settings modal for comfortable viewing in low-light environments.
