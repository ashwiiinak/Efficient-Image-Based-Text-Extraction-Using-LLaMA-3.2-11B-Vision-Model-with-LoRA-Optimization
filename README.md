# **Text Extraction from Images using LLaMA 3.2 Vision Model**  

## **Overview**  
This project utilizes the **LLaMA 3.2 11B Vision Model** to extract text from images with high accuracy. The extracted text is evaluated using **Word Error Rate (WER) and Character Error Rate (CER)** to measure performance. Additionally, **LoRA (Low-Rank Adaptation)** is implemented to optimize computational efficiency.  

## **Features**  
✅ **Text Extraction**: Uses LLaMA 3.2 Vision Model to extract text from images.  
✅ **Evaluation Metrics**: Computes WER and CER to assess accuracy.  
✅ **LoRA Fine-Tuning**: Reduces computational costs while maintaining performance.  
✅ **Google Colab Compatible**: Runs efficiently with GPU acceleration.  

## **Technologies Used**  
- Python  
- PyTorch  
- Hugging Face Transformers  
- LoRA (Low-Rank Adaptation)  
- Google Colab  

## **Installation & Usage**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:  
   ```bash
   pip install torch torchvision transformers accelerate huggingface_hub pillow requests peft jiwer
   ```
3. Run the Google Colab notebook or script to extract text and evaluate performance.  

## **Dataset**  
The project works with a dataset of images stored in **Google Drive**, and the script loads them dynamically for processing.  

## **Results**  
- Extracted text is compared against ground truth labels.  
- **WER (Word Error Rate)** and **CER (Character Error Rate)** provide insights into model accuracy.  
- Fine-tuned results using **LoRA** improve efficiency.  

## **Acknowledgments**  
This project leverages **Meta’s LLaMA 3.2 Vision Model** and techniques from Hugging Face’s ecosystem.  
