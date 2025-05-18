Emotion_Classifier is a web model that recognizes four emotions—Happy, Angry, Sad, and Neutral—from audio files and also detects abusive content. It extracts key audio features such as MFCC, MelSpectrogram, chroma_stft, and chroma_cqt using libraries like Librosa, NumPy, pandas, and scikit-learn.

The models were trained on VS code, and their weights were saved using the Pickle library. In the backend, these pickle files are loaded for real-time inference in the app. Users can upload audio files to get instant emotion and abuse detection results.

