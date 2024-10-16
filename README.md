C:\Users\TG\Desktop\Multimodel for image and audio processing\multimodel.png
# Interactive-Media-Analysis-Using-Whisper-and-LLaVA-for-Image-and-Audio-Processing
## Overview
This project showcases a cutting-edge integration of audio transcription and image processing using state-of-the-art machine learning models from OpenAI. It combines the capabilities of the **LLaVA 1.5** model, which generates detailed textual descriptions from images, with the **Whisper** model, designed for high-quality automatic speech recognition.

The system allows users to interact seamlessly by converting spoken language into written text and generating insightful descriptions of uploaded images. This multimodal approach enhances accessibility and usability, enabling users to engage with both audio and visual content in an intuitive manner.

### Key Features:
- **Voice Input:** Users can record or upload audio, which the system converts into accurate text. This feature is particularly useful for those who prefer speaking over typing, enhancing productivity and ease of use.
- **Image Processing:** Users can upload images, and the system will analyze them to provide rich, descriptive outputs in both text and speech formats. This capability is valuable in various applications, from educational tools to creative content generation.

By leveraging advanced AI technologies, this project aims to provide a user-friendly interface that promotes interaction and understanding across different modalities.


## Requirements
To run this project, ensure you have the following packages installed:
- `transformers==4.41.0`
- `bitsandbytes==0.41.3`
- `accelerate==0.26.0`
- `gradio`
- `gTTS`
- `whisper` (installed via GitHub)

You can install the dependencies using the following command:
pip install -q -U \
    transformers==4.41.0 \
    bitsandbytes==0.41.3 \
    accelerate==0.26.0 \
    gradio \
    gTTS \
    git+https://github.com/openai/whisper.git



## Contributions
Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- OpenAI for providing the Whisper and LLaVA models.
- Gradio for making user interaction simple and intuitive.

