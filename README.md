# Vision to Tabla Sound

## Overview
An AI-driven application that analyzes image features to generate rhythmic tabla compositions. This innovative system bridges computer vision and music generation by transforming visual characteristics into dynamic tabla patterns with multiple taals.

## Features
- **Image Feature Extraction**: Analyzes color, texture, brightness, and sharpness from input images
- **Dynamic Tabla Generation**: Converts extracted features into rhythmic tabla compositions
- **Multiple Taals**: Supports various traditional Indian rhythmic cycles (3-taal, 5-taal, 7-taal, etc.)
- **Real-time Processing**: Fast audio output with high-quality synthesis
- **Interactive UI**: User-friendly Streamlit interface for easy interaction

## Technologies Used
- **Python**: Core programming language
- **Streamlit**: Web-based interactive user interface
- **OpenCV**: Image processing and feature extraction
- **librosa**: Audio synthesis and processing
- **NumPy & Pandas**: Data manipulation and numerical computing

## Installation

```bash
git clone https://github.com/SagarRawada9/vision-to-tabla-sound.git
cd vision-to-tabla-sound
pip install -r requirements.txt
```

## Usage

```bash
streamlit run app.py
```

Then:
1. Upload or select an image
2. Choose your preferred taal
3. Click "Generate Tabla" to create the composition
4. Listen to and download the generated audio

## Project Structure
```
├── app.py              # Main Streamlit application
├── image_processor.py  # Image feature extraction
├── tabla_generator.py  # Tabla rhythm generation
├── audio_synthesis.py  # Audio output creation
├── requirements.txt    # Dependencies
└── README.md          # Documentation
```

## Results & Performance
The application successfully maps visual characteristics to musical patterns, creating unique and consistent tabla compositions from any input image.

## Future Enhancements
- Support for additional Indian classical instruments
- Machine learning model for improved feature-to-rhythm mapping
- Real-time visualization of rhythm patterns
- Export to MIDI format

## License
MIT License

## Author
Sagar Rawada

## Contact
For questions or collaboration, feel free to reach out!
