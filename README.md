## Flask Application Design

### HTML Files

**1. flashcards.html**
- The main page displaying the flashcards.
- Contains the Bootstrap-styled layout, including the navigation bar and flashcard content.
- Uses JavaScript to handle flashcard flipping and translation.

**2. base.html**
- The base HTML template for all pages.
- Includes the common elements such as the header, footer, and navigation bar.

### Routes

**1. /flashcards**
- Endpoint to display the main flashcards page (flashcards.html).

**2. /translate**
- Endpoint to handle the translation request for a flashcard.
- Receives the flashcard text in English and returns the translation in Dutch.

**3. /static/js/flashcards.js**
- Endpoint to serve the JavaScript file used for handling flashcard flipping and translation.

**Note:** The Flask application does not refer to any local files and relies solely on the above HTML files and routes for its functionality.