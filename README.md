# Runs a demo for a classification model on MNIST


```
import gradio as gr
import numpy as np

def predict(img):
  
#   model = MLP()
#   output = model.predict(img)                   
  return f'hello {len(img)}'

iface = gr.Interface(predict, gr.inputs.Image(shape=(200, 200)), "text")
iface.launch(share=True)
```
