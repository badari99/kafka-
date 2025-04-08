# 🔄 Real-Time CSV Monitoring with Kafka in Python

This project demonstrates a simple data streaming setup using **Apache Kafka** and **Python**, all run inside **Jupyter Notebooks**. It allows you to stream new rows from a CSV file in real-time and process them with Kafka consumers.

---

## 📦 Overview

- **Producer (`kafka prod.ipynb`)**
  - Monitors a CSV file for newly added lines.
  - Sends each new line to a Kafka topic (`test21`) as a message.
  
- **Consumer (`kafka cons.ipynb`)**
  - Listens to the Kafka topic (`test21`).
  - Receives each new message and converts it into a pandas DataFrame.
  - Displays the processed data in the console.

---

## 🛠 Technologies Used

- Python 3.x
- Apache Kafka
- Jupyter Notebook
- Pandas
- kafka-python

---

## 📁 Files

- `kafka prod.ipynb`: Kafka producer notebook that streams new lines from a CSV file.
- `kafka cons.ipynb`: Kafka consumer notebook that processes and displays the incoming data.

---

## 🚀 How to Run

1. Make sure Apache Kafka and Zookeeper are running.
2. Start the Kafka producer using `kafka prod.ipynb`.
3. Add new lines to the CSV file being monitored.
4. Start the Kafka consumer using `kafka cons.ipynb` to see real-time processing.

> ⚠️ The system does not persist data to a database; it displays it in the console only.

---

## 📌 Future Enhancements

- Append the streamed data to a database (like Snowflake or PostgreSQL).
- Add support for JSON or other data formats.
- Include alerting or monitoring tools.

---

## 🧑‍💻 Author

Your Name – [Badari Maddula](https://github.com/badari99/)

