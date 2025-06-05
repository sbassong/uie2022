# UIE 2022 Landing

This project is the source code for the UIE 2022 landing page for Jared Spool, a UX expert. The page highlights upcoming events, showcases opportunities to collaborate with Jared, and features an embedded contact form from Airtable. It dynamically displays information for the next upcoming event using data from `calendar.js`. The repository also includes an HTML email template (`email.html`) for the "Leaders of Awesomeness" community.

![uie-page](https://github.com/user-attachments/assets/1a1b0b3a-43c3-4dc0-9048-96770012d2e7)
## Installation

To set up and run this project locally:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/sbassong/agile-intensive-landing.git
    cd uie-2022-landing
    ```

2.  **Navigate to the project directory** 

3.  **Open the landing page:**
    Open the `index.html` file in your web browser to view the landing page.

No special build steps or server-side dependencies are required to run the main landing page. The "Partner with Jared" form is an embedded Airtable form and requires an internet connection to function.

## Usage

* **View Landing Page**: Open `index.html` in any modern web browser.
* **Dynamic Event Display**: The event card on the page automatically populates with the nearest upcoming event from the `calData` array located in `calendar.js`.
* **Update Event Data**: To change or add events, modify the `calData` array in `calendar.js`.
* **Contact Form**: The "Partner with Jared" section contains an embedded Airtable form for users to submit inquiries.
* **Email Template**: `email.html` is a standalone HTML email template. It can be viewed in a browser or used with an email marketing service for community communications.
