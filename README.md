# XSpellCheck-App

The XSpellCheck is a React-based application designed for real-time spell-checking and auto-correction. It uses a custom dictionary to identify and suggest corrections for common typos and misspellings in user-entered text. The app focuses on improving user-written content by flagging the first detected misspelling and offering a correction.

## Getting Started

To run the XSpellCheck React application, follow the steps below:

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd xspellcheck-react
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000/`.

## Usage

The XSpellCheck application provides a textarea where users can enter text. The application will perform real-time spell-checking based on a custom dictionary and suggest corrections for misspelled words.

## Custom Dictionary

The custom dictionary used for spell-checking is defined in the `customDictionary` constant within the `SpellCheckApp.js` file. You can modify or extend this dictionary as needed.

```javascript
const customDictionary = {
  teh: "the",
  wrok: "work",
  fot: "for",
  exampl: "example"
};
```

