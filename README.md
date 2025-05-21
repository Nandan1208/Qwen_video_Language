# Qwen2VL Video+Text Explanation Demo

This repository demonstrates how to use the **Qwen2VL** multi-modal model (from Hugging Face) to generate textual explanations for videos with accompanying text prompts.

## Setup

### Install dependencies

Make sure you have Python 3.8+ installed. Then run:

```bash
pip install git+https://github.com/huggingface/transformers
pip install accelerate flash_attn
pip install qwen_vl_utils av

##change the video path in code to analyze the video  
