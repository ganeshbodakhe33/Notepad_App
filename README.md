# GB Text Editor
GB Text Editor is a simple text editing application built using Python's Tkinter library for the graphical user interface and ReportLab for generating PDF files. This application allows users to write and save notes either as plain text files or PDF documents.

Features
Text Editing: Provides a user-friendly interface for entering and editing text.
Save as Text: Allows users to save the entered text as a plain text file (.txt).
Save as PDF: Enables users to save the entered text as a PDF document with proper formatting.
Functionality
Save as Text
The Save as Text function prompts the user to specify a location and filename to save the text entered in the editor. It utilizes the filedialog.asksaveasfilename method from Tkinter to facilitate file saving.

Save as PDF
The Save as PDF function generates a PDF document from the text entered in the editor. It uses ReportLab's canvas.Canvas to create a PDF canvas with the text content. Each line of text is drawn on the canvas, ensuring proper line breaks and spacing.

Usage
Text Editing:

Enter or edit text in the provided text area.
Save as Text:

Click the Save as Text button to save the entered text as a plain text file (.txt).
A file dialog prompts for the file location and name.
Save as PDF:

Click the Save as PDF button to save the entered text as a PDF document.
A file dialog prompts for the PDF file location and name.
Getting Started
