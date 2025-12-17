# Mini Drone Landing Simulator 🛬

This is a Flask-based application designed for the YoloNeuroLand: A YOLO & LLM-Driven Autonomous Drone Landing System.


---

## 📁 Get the Benchmark Dataset

To test the Drone Landing System, **please get the `Drone Landing Benchmark Dataset` files** from `../Drone Landing Benchmark Dataset`. After you run the web app locally, upload the images one-by-one through the demo interface. 

> Note: The fine-tuned YOLO model weights are already included in this repo as `best.pt`.

---

## 🔑 Set up your Gemini API key (required for landing selection)

The **landing spot selection** module uses Gemini and will **not work** unless you provide a Gemini API key.

Create a key here: [https://ai.google.dev/gemini-api/docs/api-key](https://ai.google.dev/gemini-api/docs/api-key)

Then paste it into `app.py` (see **line 17**).


---

## 🚀 Running the Flask App Locally

```bash
pip install -r requirements.txt
# Set your Gemini API key in app.py (see line 17), then run:
python app.py

```


