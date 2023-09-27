# CodeClauseInternship_Time-Conversion-by-Country

# TimeConversionByCountry
This Java program allows you to input a country name and then displays the current time in the specified time zone for that country. It uses the Java java.time package to handle date and time operations and allows you to convert the current time to various time zones.

# Prerequisites
Java Development Kit (JDK) installed on your system.
A basic understanding of Java programming concepts.

# Usage

Clone or download the repository to your local machine.

Open your terminal or command prompt and navigate to the directory where the program files are located.

Compile the Java source code:


javac TimeConversionByCountry.java
Run the program:


java TimeConversionByCountry
Follow the on-screen instructions to enter a country name when prompted.

The program will display the current time in the specified time zone for the entered country.

# Supported Countries

The program supports time zone conversions for the following countries:

India
Germany
United States
China
Japan
Russia
Italy
Spain
United Kingdom
If you enter a country name not listed above, the program will display a message indicating that the country name is not listed.

# Customization

You can easily add more countries and their corresponding time zones by modifying the getZoneIdFromCountryName method in the code. Simply add a new case with the country name and its corresponding time zone using the ZoneId format.

java

case "New Country":
    return "ZoneId/For/NewCountry";

# Example Output

Here is an example of how the program's output will look:

yaml

Enter the Country name: United States
United States time now: 27:Sep:2023 10:15:30

# License

This program is open-source and distributed under the MIT License.

# Author
[Vinay Singh]

Feel free to reach out with any questions or feedback!







