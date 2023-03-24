### This app uses Web Speech API to convert speech to text with the click of a button
### Once the button is clicked, the script initializes the SpeechRecognition object from the Web Speech API
### The `interimResults` property is set to true to enable real-time transcription

### Whenever the `result` event is fired, the script retrieves the latest transcription from the event object and
### inserts it into the element with the `convert_text` ID in the HTML document

### If `speech` is set to `true`, the `start()` method is called on the recognition object to begin listening for voice input

### To use the script, simply add the code to your HTML document and add an element with an ID of `click_to_convert`
The script will handle the rest

# CodePen :
https://codepen.io/Mo61n/pen/eYLKKqP
