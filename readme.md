# Phone Number Recognition

A desktop application built with **Python** and **Flet** that allows users to extract geographical and carrier information from phone numbers. The app features a modern, responsive UI with a gradient background and real-time input validation.

## 🚀 Features

* **Carrier Detection**: Identifies the service provider (carrier) associated with the phone number.
* **Location Tracking**: Determines the country or geographical region of the number.
* **Timezone Identification**: Displays the timezone(s) relevant to the phone number's location.
* **Interactive UI**:
* **Real-time Validation**: The "Search" button is automatically enabled only when a valid length (7+ digits) is entered.
* **Clear Functionality**: Quickly reset input and results with a single click.
* **Visual Feedback**: Results appear with fade-in animations and specific icons.



## 🛠️ Built With

* [Flet](https://flet.dev/) - The framework used for the user interface.
* [phonenumbers](https://pypi.org/project/phonenumbers/) - The Python library used for parsing, formatting, and validating international phone numbers.

## 📦 Prerequisites

To run this application, you need Python installed on your system along with the following libraries:

* `flet`
* `phonenumbers`

## 📥 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/youssef3082004/phonenumber_recognition.git
cd phonenumber_recognition

```


2. **Install the required dependencies:**
```bash
pip install flet phonenumbers

```



## ▶️ Usage

1. Run the application script:
```bash
python "Phone Number.py"

```


2. Enter a phone number in the input field (do not include the `+` sign, as it is pre-filled).
3. Click **Search** to view the Country, Carrier, and Timezone details.

## 📂 Project Structure

* `Phone Number.py`: The main script containing the application logic and UI layout.

## ⚠️ Note

The application attempts to load a window icon from a local path (`C:\Users\Computec\Downloads\Icons\phone.ico`). You may want to update this path in the code or remove the line if the icon file is not present on your machine.

## 📜 License

This project is open-source and available for use and modification.