
# GUVI LLM GPT-2 Text Generator

## Objective:

To deploy a pre-trained or Fine tuned GPT model using HUGGING FACE SPACES, making it accessible through a web application built with Streamlit or Gradio.

## Skills Takeaway

- Python
- My SQL
- Deep Learning
- Transformers
- Hugging face models
- LLM
- Streamlit

## Technology and Tools
- Python 3.12.2
- My SQL
- Transformers
- Hugging Face
- Streamlit
  

## Packages and Libraries
```
import streamlit as st
import mysql.connector
import bcrypt
import datetime
import re
import json
import torch
import pytz
from transformers import GPT2LMHeadModel, GPT2Tokenizer
```

## Overview

- Collecting the data or Extracting the GUVI Company based Data from various Sources like, GUVI webpage, Linkedin, Wikipedia, GitHub, FB, Instagram etc.
- After Collecting the data, the data preparation is done by eliminating some special charaters, unwanted spaces etc.
- Taking a Pre Trained GPT-2 Text Generator Model.
- Using GPT-2 Tokenizer to convert the text data into tokens.
- Ensuring the data is tokenized consistently to match the pre-trained model’s requirements.
- Use the Hugging Face Transformers library or similar tools to fine-tune the GPT-2 model on the prepared dataset.
- Using My SQL to collect and store the Entry Data of Users.
- Deploying the Fine Tuned model in Hugging Face Platform.
- Creating a scalable and secure web application using Streamlit &  making the model accessible to users over the internet.


