# Python 2.7 Teaching Scenario Generator (AI-Assisted)
# Δημιουργός Διδακτικών Σεναρίων Python 2.7 (Υποβοηθούμενος από AI)

## Description
## Περιγραφή

This project contains a Python 3 script that uses the Google Gemini API to automatically generate a draft for a part of a teaching scenario. The generated scenario is designed for teaching a specific topic in **Python 2.7** to **novice students**. The structure of the generated scenario follows a standard template with 9 key sections, including objectives, activities, and worksheet ideas, specifically tailored for the Python 2.7 context.

---

Αυτό το έργο περιέχει ένα script σε Python 3 που χρησιμοποιεί το Google Gemini API για την αυτόματη παραγωγή ενός προσχεδίου για ένα τμήμα διδακτικού σεναρίου. Το παραγόμενο σενάριο έχει σχεδιαστεί για τη διδασκαλία ενός συγκεκριμένου θέματος στην **Python 2.7** σε **αρχάριους μαθητές**. Η δομή του παραγόμενου σεναρίου ακολουθεί ένα τυπικό πρότυπο με 9 βασικές ενότητες, συμπεριλαμβανομένων στόχων, δραστηριοτήτων και ιδεών για φύλλα εργασίας, προσαρμοσμένες ειδικά για το πλαίσιο της Python 2.7.

## Features
## Χαρακτηριστικά

* **AI-Powered Content Generation:** Uses the Google Gemini API to create textual content for scenario sections based on your input.
* **Structured Output:** Generates content for the 9 defined sections of a teaching scenario part.
* **Python 2.7 Focus:** Prompts the AI to generate content relevant to teaching Python 2.7 syntax and concepts to beginners.
* **Customizable Input:** Allows you to specify the topic, student level, and desired duration.

---

* **Παραγωγή Περιεχομένου με AI:** Χρησιμοποιεί το Google Gemini API για τη δημιουργία κειμένου για τις ενότητες του σεναρίου με βάση την εισαγωγή σας.
* **Δομημένη Έξοδος:** Παράγει περιεχόμενο για τις 9 καθορισμένες ενότητες ενός τμήματος διδακτικού σεναρίου.
* **Εστίαση στην Python 2.7:** Ζητά από την AI να δημιουργήσει περιεχόμενο σχετικό με τη διδασκαλία της σύνταξης και των εννοιών της Python 2.7 σε αρχάριους.
* **Προσαρμόσιμη Είσοδος:** Σας επιτρέπει να καθορίσετε το θέμα, το επίπεδο των μαθητών και την επιθυμητή διάρκεια.

## Prerequisites
## Προαπαιτούμενα

* **Python 3:** Make sure you have Python 3 installed on your system.
* **Google Gemini API Key:** You need to obtain an API key from Google AI Studio or Google Cloud Platform.
* **`google-generativeai` library:** This Python library is required to interact with the Gemini API.

---

* **Python 3:** Βεβαιωθείτε ότι έχετε εγκατεστημένη την Python 3 στο σύστημά σας.
* **Google Gemini API Key:** Πρέπει να αποκτήσετε ένα κλειδί API από το Google AI Studio ή την Google Cloud Platform.
* **Βιβλιοθήκη `google-generativeai`:** Αυτή η βιβλιοθήκη Python απαιτείται για την επικοινωνία με το Gemini API.

## Installation
## Εγκατάσταση

1.  Clone this repository (if applicable) or save the script `pythonlessonplanning.py` to your local machine.
2.  Install the required library:
    ```bash
    pip install google-generativeai
    ```

---

1.  Κάντε κλώνο αυτό το αποθετήριο (αν υπάρχει) ή αποθηκεύστε το script `pythonlessonplanning.py` στον υπολογιστή σας.
2.  Εγκαταστήστε την απαραίτητη βιβλιοθήκη:
    ```bash
    pip install google-generativeai
    ```

## Usage
## Οδηγίες Χρήσης

1.  Run the script from your terminal:
    ```bash
    python pythonlessonplanning.py
    ```
    or
    ```bash
    python3 pythonlessonplanning.py
    ```
2.  When prompted, enter your Google Gemini API Key.
3.  Follow the prompts to provide the specific topic within Python 2.7, the student level, and the desired duration for the lesson.
4.  The script will then call the AI and print the generated teaching scenario part to your console.

---

1.  Εκτελέστε το script από το τερματικό σας:
    ```bash
    python pythonlessonplanning.py
    ```
    ή
    ```bash
    python3 pythonlessonplanning.py
    ```
2.  Όταν σας ζητηθεί, εισάγετε το Google Gemini API Key σας.
3.  Ακολουθήστε τις οδηγίες για να εισάγετε το συγκεκριμένο θέμα στην Python 2.7, το επίπεδο των μαθητών και την επιθυμητή διάρκεια του μαθήματος.
4.  Το script θα επικοινωνήσει με την AI και θα εκτυπώσει το παραγόμενο τμήμα του διδακτικού σεναρίου στην κονσόλα σας.

## Important Notes & Disclaimer
## Σημαντικές Σημειώσεις & Αποποίηση Ευθύνης

* **API Key Security:** Your API key provides access to Google Cloud services. **Keep it confidential and do not share it publicly.**
* **Potential Costs:** Using the Gemini API may incur costs depending on usage. Refer to Google Cloud pricing.
* **AI-Generated Content:** The output is a *draft*. While AI aims to provide relevant information, it is crucial for an educator to **review, verify, and adapt** the content for pedagogical accuracy, suitability for students, and specific needs of the lesson, especially given the focus on Python 2.7 (as the AI is primarily trained on more recent data).
* **Focus on Python 2.7:** The generated content is specifically prompted for teaching Python 2.7. Ensure it aligns with the specific syntax and behaviors of that version.

---

* **Ασφάλεια API Key:** Το κλειδί API παρέχει πρόσβαση σε υπηρεσίες της Google Cloud. **Διατηρήστε το εμπιστευτικό και μην το μοιράζεστε δημόσια.**
* **Πιθανό Κόστος:** Η χρήση του Gemini API ενδέχεται να επιφέρει χρεώσεις ανάλογα με τη χρήση. Ανατρέξτε στην τιμολογιακή πολιτική της Google Cloud.
* **Περιεχόμενο Παραγόμενο από AI:** Η έξοδος είναι ένα **προσχέδιο**. Ενώ η AI στοχεύει να παρέχει σχετικές πληροφορίες, είναι κρίσιμο για έναν εκπαιδευτικό να **ελέγξει, να επαληθεύσει και να προσαρμόσει** το περιεχόμενο για παιδαγωγική ακρίβεια, καταλληλότητα για τους μαθητές και συγκεκριμένες ανάγκες του μαθήματος, ειδικά δεδομένης της εστίασης στην Python 2.7 (καθώς η AI είναι κυρίως εκπαιδευμένη σε πιο πρόσφατα δεδομένα).
* **Εστίαση στην Python 2.7:** Το παραγόμενο περιεχόμενο ζητείται συγκεκριμένα για τη διδασκαλία της Python 2.7. Βεβαιωθείτε ότι ευθυγραμμίζεται με τη συγκεκριμένη σύνταξη και συμπεριφορές αυτής της έκδοσης.

## File Included
## Περιεχόμενο Αρχείου

* `pythonlessonplanning.py`: The Python script for generating the teaching scenario part.
