# Integrating Pre-Trained Language Models and Embeddings for Enhanced Search and Retrieval

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+Take+a+look+into+our+project!;" />
</h1>

# Contributors


<table>
  <tr>
    <td width="50%">
      <h3>Yassine Squalli Houssaini</h3>
    </td>
    <td width="50%"> 
      <a href="mailto:squayassine@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
      </a>
      <a href="https://www.linkedin.com/in/yassine-squalli-houssaini-2abb1a255/" target="_blank"> 
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
      </a>
      <a href="https://sites.google.com/view/yassinesqualli/accueil?pli=1" target="_blank">
         <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <h3>Kaoutar Lakdim</h3>
    </td>
    <td>
      <a href="mailto:kaoutarlakdim2001r@gmail.com">
        <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
      </a>
      <a href="https://www.linkedin.com/in/kaoutar-lakdim-6b335720a/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
      </a>
      <a href="https://sites.google.com/d/16hx83iZG4SG6yTcSR9ZiAAfmGMnbDqar/p/1Mfwcay3qYgpCDfxNlZcuYlTnHvE4w68F/edit" target="_blank">
         <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" />
      </a>
    </td>
  </tr>
</table>


# 🚀Tools

<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/aec684f0-f726-46d8-89ad-e596dbb91619" alt="aws" width="300" height="200"/> </a>  <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/4f06647f-d7d8-4d95-8cc7-9f28d109b2ee" alt="azure" width="323" height="200"/></a> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/14069fa6-24f4-4b48-b4f5-789ae2c1ff7d" alt="azure" width="300" height="200"/></a> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/f1fd56b5-89c3-40e5-84fb-6c2792bb2d8c" alt="azure" width="200" height="150"/></a><a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/95eb4dc6-3762-4ea2-b9f3-5218d62e6078" alt="azure" width="300" height="150"/>











---

# 🤔 Explaining the project

This project focuses on developing multiple systems for efficient search and retrieval using pre-trained language and vision models. The architecture integrates these models to enable seamless cross-modal understanding and advanced information retrieval.

## 🛠️System Components

| System                                   | Focus                                      | Model                           | Workflow                                                                                                        |
|------------------------------------------|--------------------------------------------|---------------------------------|-----------------------------------------------------------------------------------------------------------------|
| Image Retrieval System                   | Search images with text inputs             | CLIP (ViT-B/32 variant)         | Real-time webcam images are processed and encoded by CLIP; Replicate API generates captions for similarity.     |
| Video Frame Retrieval and Captioning System | Analyze video frames with text inputs    | CLIP, Replicate                 | User-uploaded videos analyzed using CLIP and Replicate captions to identify frames matching user queries.     |
| PDFs Retrieval System                    | Answer questions about PDFs                | LLAMA-2, Transformers           | LLAMA-2 indexes PDFs; Transformers provide contextually relevant responses based on user queries.             |

## 💻 User-Friendly Interface

The project features a user-friendly interface that accommodates both real-time image capturing through a camera and video file uploads. Users can seamlessly interact with the systems, facilitating intuitive exploration of visual and textual information.

![Copie de Management Org Chart Team Whiteboard in Black Red Green Trendy Sticker Style](https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/bf57a1ab-ae6b-45bc-9a9e-6012f87d79a3)

# 🎥💬 Chat with your own Videos

<img width="943" alt="Screenshot 2023-08-30 at 19 26 45" src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/0a40dc99-9698-4ddd-94d7-d29b419b0065">


# 🦙💬 Llama 2 Chat with your own pdfs

This chatbot is created using the open-source Llama 2 LLM model from Meta.

Particularly, we're using the [**Llama2-7B**]
To use this app, you'll need to get your own API token.

## Other Llama 2 models to try

As mentioned above, this chatbot implementation uses the [**Llama2-7B**](https://replicate.com/a16z-infra/llama7b-v2-chat) model that was trained on 7 billion parameters.

You can also try out the larger models:
- [Llama2-13B](https://replicate.com/a16z-infra/llama13b-v2-chat)
- [Llama2-70B](https://replicate.com/replicate/llama70b-v2-chat)

## Further Reading
- [Llama 2 website](https://ai.meta.com/llama/)
- [Llama 2 technical overview](https://ai.meta.com/resources/models-and-libraries/llama/)
- [Llama 2 blog](https://ai.meta.com/blog/llama-2/)
- [Llama 2 research article](https://ai.meta.com/research/publications/llama-2-open-foundation-and-fine-tuned-chat-models/)
- [Llama 2 GitHub repo](https://github.com/facebookresearch/llama/tree/main)


---
#  How it works:




https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/41c49024-6dd2-4a45-9fbb-58920494f9fd



---

https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/bb6d26ad-a680-49c3-aa1d-dc703e920fa5

---


https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/d57eab5e-f48b-4922-abda-55b79c0cf475













# Special thanks to:
<img width="294" alt="Screenshot_2023-08-31_at_19 23 25-removebg-preview" src="https://github.com/kaoutar-lakdim/LM-Enhanced-Search/assets/127676452/f32be6c5-fb0e-419e-bb37-8e145cea02eb">




<br/><br/>
<hr/>

<h3 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=40&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Thank+you+for+your+time+:);" />
</h3>

<br/>


---


