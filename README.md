# Monthly Timesheet Validator
This tool helps you **validate your work hours for a month** while also displaying **leave days** or **work-offs** (such as Saturdays or Sundays).

**Features:**
* **Accurately calculates** the total number of hours worked in a month, ensuring error-free tracking.
* Highlights **leaves** and designated **work-off days** for better clarity.
* Simplifies the process of tracking hours, ensuring **accurate billing** and **avoiding manual mistakes**.
* Whether you're a freelancer, employee, or business owner, this tool ensures hassle-free time tracking and transparent reporting.

Feel free to contribute, suggest improvements, or report any issues!

**Let's make time tracking efficient and accurate!**

**Declared Holidays**

**In order to have declared holidays as master, and to populate automatically,  use the following script so that it could be executed in console**

let holidays = {
  "25-12-2025":  "Christmas  - Thursday"
}

localStorage.setItem("holidays", JSON.stringify(holidays));

if holidays text box isEmpty, process from local Storage otherwise it would be taken from textbox.






