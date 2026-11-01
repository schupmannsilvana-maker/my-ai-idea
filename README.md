# PlantDoctor AI - Mobile Plant Disease Detection

## Summary
PlantDoctor AI is a mobile application designed to help hobby gardeners and farmers identify plant diseases instantly. By taking a photo of a sick plant leaf with a smartphone camera, the AI analyzes the visual symptoms and provides an immediate diagnosis along with eco-friendly treatment recommendations.

## Background
Many people love growing plants or vegetables at home, but struggle when plants get sick from fungi, pests, or nutrient deficiencies. Incorrectly treating the plant or waiting too long often leads to the plant dying. This AI solution makes expert botanical knowledge accessible to everyone, reducing crop failure and preventing the overuse of chemical pesticides.

## How is it used?
The user opens the app and takes a clear photo of the affected plant leaf. 
1. The image is processed by a neural network trained on plant pathology.
2. The app displays the most likely diagnosis (e.g., "Tomato Late Blight") with a confidence score.
3. It suggests actionable, organic remedies and care tips to save the plant.

## Data sources and AI methods
The project relies on computer vision and deep convolutional neural networks (CNNs).
* **Data Sources:** Open-source datasets like "PlantVillage", which contains tens of thousands of labeled images of healthy and diseased plant leaves.
* **Methods:** Supervised learning for image classification, utilizing pre-trained models (like MobileNet) optimized for mobile devices.

## Challenges
* **Image Quality:** Blurry photos, poor lighting, or busy backgrounds can lower prediction accuracy.
* **Lookalikes:** Different nutrient deficiencies can look very similar to fungal infections, which might confuse the model.
* **Scope:** The AI can only diagnose diseases it has seen during training; rare plants might not be supported initially.
