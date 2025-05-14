This project is a Python application that converts the text content of a selected PDF file into an audiobook (MP3 format). The application features a simple graphical user interface (GUI) that allows users to choose any PDF file from their computer. Once selected, it extracts the text from all pages of the PDF and uses the Google Text-to-Speech (gTTS) library to generate an audio file that can be played using the default media player.

Libraries Used:
- tkinter (for the GUI and file selection)
- gTTS (Google Text-to-Speech for converting text to audio)
- PyPDF2 (to read and extract text from PDF files)
- os (to handle file paths and play the generated MP3 file)
