![image](https://github.com/qzxtu/PDF-Quiz-Exporter-for-Socrative/assets/69091361/df3b33a5-c091-49eb-80a0-447cb073ec49)
---
# PDF Quiz Exporter for Socrative

Welcome to the PDF Quiz Exporter for Socrative, a handy tool that allows you to extract quiz information and questions from Socrative and export them to a PDF format using C# and the iTextSharp library.

## Requirements

- Visual Studio or a compatible C# development environment.
- iTextSharp library (make sure to include it in your project).

## Usage

1. Start the application in your development environment.
2. When prompted, enter the name of the Socrative classroom you'd like to analyze.
3. The application will retrieve information about the quiz and its questions from Socrative.
4. Quiz details will be neatly organized and exported to a PDF file, conveniently named "QuizInfo.pdf," located in your application's directory.

## Sample Output

The resulting PDF file, "QuizInfo.pdf," contains comprehensive information about the quiz, encompassing its title, unique ID, and the individual questions with their respective answers. HTML-encoded entities are seamlessly decoded for enhanced readability.

**Here's a screenshot of the application in action:**

![image](https://github.com/qzxtu/PDF-Quiz-Exporter-for-Socrative/assets/69091361/5874214b-4c0c-4624-9eb1-4fcca9e0060b)

**And here's a screenshot of the generated PDF output:**

![image](https://github.com/qzxtu/PDF-Quiz-Exporter-for-Socrative/assets/69091361/e6fc9651-a901-4f91-9bed-deb98d4f4724)

## Credits

This project leverages the powerful iTextSharp library to create PDF files, ensuring a professional and organized presentation of quiz data.

## Disclaimer

Please note that the use of this application is the sole responsibility of the end user. The creator of this tool, [Your Name], disclaims any liability for its use.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for complete details.
