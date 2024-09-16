#Virtual Threaded Sentiment Analyser Project
(application Incomplete)

The Runner class serves as the entry point for the sentiment analysis application. It provides a console-based user interface for interacting with the application and selecting various sentiment analysis options.


Description
The Runner class displays a menu of options to the user, allowing them to specify input sources, configure lexicons, and execute sentiment analysis. It also includes a progress meter to visualize the progress of tasks.



File Structure

-Runner.java: The main Java class containing the entry point for the sentiment analysis application.

-ConsoleColour.java: A utility class defining console colors for text output.

-LexiconLoader.java: A class responsible for loading lexicons used in sentiment analysis.

-TweetAnalyzer.java: A class for analyzing tweets using loaded lexicons.

-TweetReader.java: A class for reading tweets from different sources.

-ReportGenerator.java: A class for generating reports based on sentiment analysis results.



Usage

Compile and run the Runner class.

Follow the on-screen menu options to specify input sources, configure lexicons, and execute sentiment analysis.

Monitor the progress meter to visualize the progress of tasks.

Review the generated reports for sentiment analysis results.



Dependencies

This application requires the following dependencies:

Java Development Kit (JDK) 8 or higher

Scanner class for user input

Thread class for progress meter animation
