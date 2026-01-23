# Investor Tracker

A simple **HTML-based investor tracking tool** to help early-stage founders manage outreach, follow-ups, and notes.  

This tool allows you to **add, remove, update, and export** investor data using a clean, lightweight interface.

---

## Features

- Add new investors with basic details
- Update investor information
- Remove investors from the list
- Export the data as a CSV file
- Import CSV for testing or bulk updates
- Track follow-up actions and key notes

---

## Getting Started

1. **Open `index.html` in your browser**  
   The app is fully client-side — no server or installation needed.

2. **Import a CSV (optional)**  
   - Use the sample CSV `dummy_investors.csv` to test import functionality.  
   - All CSV data is **placeholder for testing only**.  

   ![Import CSV Example](images/import-csv.png)

---

## Using the App

### 1. Adding Investors

- Click the **Add Investor** button:

  ![Add Button](images/add-button.png)

- Fill in the fields (Name, Location, Type, Check Size, Status, etc.):

  ![Add Form](images/add-form.png)

- Click **Save** to add the investor to your list.

---

### 2. Updating Investors

- Click the **Edit** button next to the investor you want to update:

  ![Edit Button](images/edit-button.png)

- Modify the fields as needed.
- Click **Save** to apply changes.

---

### 3. Removing Investors

- Click the **Delete** button next to the investor you want to remove:

  ![Delete Button](images/delete-button.png)

- Confirm the action when prompted.

---

### 4. Exporting Data

- Click the **Export CSV** button to download your current investor list:

  ![Export CSV](images/export-csv.png)

- **Note:** Some browsers may save files automatically to the default **Downloads** folder.

---

## CSV Format

The CSV must include the following columns:


Use `dummy_investors.csv` as an example.

---

## Recommendations

- **Do not commit real investor data** to this repository — use placeholder data for testing.
- For live tracking, keep CSV files locally and import/export as needed.
- This tool is **client-side only** — no backend storage.

---

## License

This project is licensed under the [MIT License](LICENSE).

