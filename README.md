  # **BwETA-IID-100M**  
  **BwETA** (*Boring's Experimental Transformer for Autoregression*) is a small but feisty autoregressive model trained to predict the next token in a sequence. It might not be the best, but hey, it works!  
  
  **Trained on determination, fueled by suffering, powered by free TPUs.** 🔥  
  
  ## **🛠️ Model Details:**  
  - **Size**: 100M parameters  
  - **Training Data**: 8M sentence (token length: 512)  
  - **Max Window Size**: 512 tokens (It can handle bigger sequence but trained on 512 length)
  - **Architecture**: Transformer-based  
  - **Tokenizer**: GPT-2 Tokenizer  
  - **Trainer**: Custom-built because why not?  

  ## **⚡ How to Use:**  

  ```python
  import BwETA #use v0.12

  # Load the model from Hugging Face  
  BwETA.load_hf("WICKED4950/BwETA-IID-100M")

  # Load the model locally  
  BwETA.load_local(path)

  # Save the model locally  
  model.save_pretrained(path)

  # Generate text  
  model.custom_generate()  # (Will be changed to model.generate() in future updates)
  ```

  ## **📌 Notes:**  
  - This model is **experimental** and has **basic** functionalities.  
  - If it breaks, don’t cry—fix it (or let me know).  
  - You can extend its functionalities in your own code.  

  ## **📩 Contact Me**  
  If something doesn’t work or you just wanna chat about AI, hit me up on Instagram: [Instagram](https://www.instagram.com/boring._.wicked)  

  ## **What's Next?**  
  🚀 **The future is uncertain... but it's going to be wild!**  
  
  - **Possibly a 400M model**—same architecture, but with more functionality.  
  - **Exploring new architectures & designing custom layers** (because why not?).  
  - **Losing my sanity along the way?** Most likely. But that’s the fun part. 😆
