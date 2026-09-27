# Jump Game Auto Player

An auto player for **「此时欢宴」**, a mini-game from the **Arknights: Endfield × Arknights Anniversary Event 「共贺庆典」** on Skland (森空岛).

Built with **Python, OpenCV, and ADB**.

![Demo](./image.png)

## Features

- Automatic game state detection
- Jump detection with OpenCV
- Automatic screen tapping through ADB
- Automatic restart after game over

## Requirements

- Python 3
- OpenCV
- NumPy
- ADB
- Android device or emulator

```bash id="5g5j7q"
pip install opencv-python numpy
```

## Usage

Configure the ADB path and device ID in `adb_tool.py`:

```python id="z9zj6g"
ADB_PATH = r"path\to\adb.exe"
DEVICE_ID = "your-device-id"
```

Run:

```bash id="9c48mr"
python main.py
```
