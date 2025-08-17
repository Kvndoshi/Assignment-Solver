## Assignment Solver

This tool lets you snip any region of your screen, extract the text (OCR), and feed it to an AI model to generate an answer. I originally built it using the Davinci-002 API back when ChatGPT didn’t exist, to quickly solve/accelerate college assignments with minimal effort. A sample assignment is included to show how this tool helps complete work easily.

Today, you don’t even need a paid GPT API: you can connect this to any open-source LLM for answer generation.

### How it works
- Snip a region of the screen to capture the question
- OCR the image to extract text
- Send the extracted text to an LLM endpoint and display the answer

### Screenshots

![Screenshot](<Screenshot 2025-08-16 221004.png>)

Gives you the option to take text via the screen snipper or enter it manually.

![Screenshot](<Screenshot (8).png>)

This is the screen-snipping interface.

![Screenshot](<Screenshot (9).png>)

You can tweak parameters (originally built for Davinci‑002). There’s also a multiple-questions mode: if the assignment has multiple questions in one block of text, it splits them and feeds them to the AI one by one, showing answers on the right side of the page.

![Screenshot](<Screenshot 2025-08-16 215406.png>)

This is a sample assignment I used to get.



