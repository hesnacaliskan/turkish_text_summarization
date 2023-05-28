# Turkish Text Summarization and Categorization App 

<p align="justify">This application is a Flask application that performs text summarization and classification tasks. Frequency-based summarization method is used for text summarization, while a TF Vector ML model is used for classification. </p>
<p align="justify">The home page contains a text input field and two buttons. Enter the text you want to analyze in the text input field. By clicking the "Özetle" button, you can get a summary of the text, which will consist of important sentences from the original text. By clicking the "Sınıflandır" button, you can perform classification on the text, indicating which category the text belongs to.</p>

![sayfagörünümü](https://github.com/hesnacaliskan/turkish_text_summarization/assets/56639245/5bda4e15-2cb5-4901-b2b3-e625e0f2e402)

### Technologies Used:

- Python
- Flask
- Frequency-based summarization
- TF Vector ML model (classification)

### Usage
1. Clone the repository to your local machine:
```bash
git clone https://github.com/rumeysaakbas/Turkish_text_summarization.git
```

2. Create and activate the virtual environment:
```bash
cd text_summarization
python -m venv venv
venv\Scripts\activate
```
3. install the required packages:
```bash
pip install pandas
pip install nltk
pip install scikit-learn
```

4. Run the application:
```bash
python app.py
```

5. View in browser:
```bash
http://localhost:5000
```

### Contributing

Pull requests are accepted. For major changes, please open a thread to discuss what you want to change first.

### License

[MIT](https://choosealicense.com/licenses/mit/)

</br>
*This project was developed by Hatice Hesna Çalışkan and Rümeysa Akbaş as a Computer Engineering Graduation project of Çanakkale Onsekiz Mart University.*
