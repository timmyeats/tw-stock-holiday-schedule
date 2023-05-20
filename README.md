# Taiwan Stock Exchange Holiday Schedule 2023

This JSON file contains the holiday schedule for the Taiwan Stock Exchange in the year 2023. It includes information on the dates of holidays, the names of the holidays, and any relevant descriptions or notes.

## Usage

This file can be used by developers who are building applications that interact with the Taiwan Stock Exchange. It can be used to determine when the exchange is closed and when trading is not available.

## Format

The file is formatted as a JSON object with a single key, "data", which contains an array of holiday objects. Each holiday object contains the following keys:


<!-- Color for vscode darkblue readiable -->
<!-- <span style='color: #007acc'>date</span> -->

- <span style="color: #007acc">date</span>: The date of the holiday in YYYY/MM/DD format.
- <span style="color: #007acc">name</span>: The name of the holiday.
- <span style="color: #007acc">description</span>: A description of the holiday, including any relevant notes or information.


## Example

Here's an example of a holiday object from the file:

```
{
    "date": "2023/01/01",
    "name": "Founding Day of the Taiwan",
    "description": "According to regulations, one day off.<br>January 1st falls on Sunday, and one day off is made up on January 2nd (Monday)."
}
```

## License

This file is provided under the MIT License.
